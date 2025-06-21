# Academic-Reference-Assistant 📝

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A smart assistant powered by Large Language Models to transform messy publication lists into structured, insightful tables. Perfect for building bibliographies, tracking citations, and accelerating your literature review.

Are you spending hours manually formatting reference lists or trying to make sense of a long list of papers? **Academic-Reference-Assistant** provides a powerful, "copy-and-paste" prompt that does the heavy lifting for you.

---

## ✨ Key Features

-   **Intelligent Parsing**: Automatically extracts titles, authors, journals, and citation data from unstructured text.
-   **Deep Analysis**: Generates high-quality **中文摘要 (Chinese summaries)**, **关键词 (keywords)**, and **引用建议 (citation advice)** for each paper.
-   **Structured Output**: Creates a clean, ready-to-use table in TSV format, which pastes perfectly into **Excel, Notion, or any spreadsheet software**.
-   **Highly Versatile**: Easily analyze any scholar's publication list by simply changing the target author's name.
-   **"No-Code" Solution**: No programming skills required. All you need is access to a modern LLM (like ChatGPT, Gemini, Claude, etc.).

---

## 🔧 How to Use (The "No-Code" Method)

Get your beautifully formatted reference table in just four simple steps.

### **Step 1: Get the Prompt**

-   Navigate to the `prompts/` folder in this repository.
-   Open the `ultimate_prompt.md` file, which contains the core logic for the AI.

### **Step 2: Configure Your Target**

-   Copy the entire prompt text.
-   In the copied text, find the line: `我关心的目标作者是：【请在此处输入目标作者的姓名...】`
-   **Replace the placeholder** with the name of the scholar you are analyzing (e.g., `Cui, Q` or `Yan Zhang`). This tells the AI who to focus on.

### **Step 3: Run in Your Favorite LLM**

-   Go to your preferred LLM chat interface.
-   **Paste your configured prompt** into the chat box.
-   Immediately after the prompt, **paste the raw text** of the paper list you copied from a website (like Google Scholar) or a PDF.
-   Send the message.

### **Step 4: Export to Your Tool**

-   The AI will generate a table in TSV (Tab-Separated Values) format.
-   **Copy the entire generated table.**
-   Open a blank Excel sheet, click on cell **A1**, and paste. The data will be perfectly organized into columns, ready for your research.

---

## 🤝 Contributing

This project thrives on community input. If you have ideas for improving the prompt or developing a scripted version (e.g., Python), please feel free to open an issue or submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
