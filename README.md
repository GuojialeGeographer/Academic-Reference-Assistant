# Academic Reference Assistant 📝 (学术文献助理)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A bilingual, "no-code" solution that uses Large Language Models to transform messy publication lists into structured, insightful tables. This repository provides two powerful prompts (Chinese and English) to accelerate your literature review.

---

## 🇬🇧 For English-Speaking Users

A smart assistant to turn unstructured publication lists into perfectly formatted tables, ready for Excel or Notion.

### ✨ Key Features

- **Intelligent Parsing**: Automatically extracts titles, authors, journals, and citation data from unstructured text.
- **Deep Analysis**: Generates high-quality **Chinese summaries (中文摘要)**, **keywords (关键词)**, and **citation advice (引用建议)** for each paper.
- **Structured Output**: Creates a clean, ready-to-use table in TSV format that pastes perfectly into any spreadsheet software.
- **Bilingual & Versatile**: Easily analyze any scholar's publication list by simply changing the target author's name in our English or Chinese prompts.

### 🔧 How to Use

1. **Get the Prompt**:

   * Navigate to the `prompts/` folder.
   * Open the `ultimate_prompt_en.md` file.
2. **Configure Your Target**:

   * Copy the entire prompt text.
   * Find the line: `The target author I am interested in is: 【Please enter the target author's name here...】`
   * **Replace the placeholder** with the name of the scholar you are analyzing (e.g., `Yan Zhang`).
3. **Run in Your Favorite LLM**:

   * Go to your preferred LLM chat interface (e.g., ChatGPT, Gemini, Claude).
   * **Paste your configured prompt** into the chat box.
   * Immediately after the prompt, **paste the raw text** of the paper list.
   * Send the message.
4. **Export to Your Tool**:

   * The AI will generate a table in TSV (Tab-Separated Values) format.
   * **Copy the entire generated table** and paste it into Excel, Notion, or your preferred research tool.

---

## 🇨🇳 为中文用户

一款由大语言模型驱动的智能助理，能将格式混乱的出版物列表，转化为结构清晰、富有洞见的表格。是您构建参考文献、追踪引用、加速文献综述的完美工具。

### ✨ 核心功能

- **智能解析**：从非结构化文本中自动提取标题、作者、期刊和引用数据。
- **深度分析**：为每篇论文生成高质量的**中文摘要**、**中文关键词**和**可引用点**。
- **结构化输出**：创建纯净、即用型的TSV格式表格，可完美粘贴到 **Excel、Notion** 或任何电子表格软件中。
- **双语支持与高通用性**：通过我们提供的中/英文Prompt，只需修改目标作者姓名，即可轻松分析任何学者的论文列表。

### 🔧 使用方法

1. **获取Prompt**：

   * 进入 `prompts/` 文件夹。
   * 打开 `ultimate_prompt_zh.md` 文件。
2. **配置目标作者**：

   * 复制完整的Prompt文本。
   * 找到 `我关心的目标作者是：【请在此处输入目标作者的姓名...】` 这一行。
   * **将占位符替换**为您要分析的学者姓名（例如 `张岩`）。
3. **在LLM中运行**：

   打开您常用的大语言模型聊天工具（如 ChatGPT、Google AI：https://aistudio.google.com/app/prompts/new_chat 等）。

   * **将配置好的Prompt粘贴**到聊天框中。
   * 紧接着，**粘贴您从网页或PDF复制的原始论文列表文本**。
   * 发送消息。
4. **导出到您的工具**：

   * AI将生成一个TSV（制表符分隔）格式的表格。
   * **复制整个表格**，然后粘贴到Excel或您使用的研究工具中。

---

## 🤝 Contributing

This project thrives on community input. If you have ideas for improving the prompt, adding features, or developing a scripted version (e.g., Python), please feel free to open an issue or submit a pull request.

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
