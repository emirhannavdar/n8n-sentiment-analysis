# 🧠 Sentiment Analysis Agent – n8n Workflow

> A fully automated sentiment analysis workflow built with [n8n](https://n8n.io), [OpenAI GPT](https://platform.openai.com/), and [Google Sheets](https://www.google.com/sheets/about/).

---

## 📌 Summary

This workflow collects user feedback through a form, analyzes the sentiment using GPT-4o-mini, and stores the name, comment, and sentiment result into a connected Google Sheet.

---

## ⚙️ Features

✅ Collects user feedback via an embedded form  
✅ Analyzes input with OpenAI’s GPT-4o-mini model  
✅ Uses LangChain’s LLM Chain for prompt formatting  
✅ Automatically appends results to Google Sheets  
✅ 100% no-code setup via n8n

---

## 🧰 Tech Stack

| Tool | Role |
|------|------|
| **n8n** | Workflow engine |
| **OpenAI GPT-4o-mini** | Sentiment classification |
| **LangChain** | LLM Chain node for prompt logic |
| **Google Sheets** | Stores structured results |
| **JSON** | Workflow format |

---

## 📥 Input Example

**Form Fields:**
- Full Name
- Please share your experience

**Sample Input:**  
> "The hotel was beautiful but the staff were very rude."

**LLM Output:**  
> `negative`

---

## 📤 Output Example (Google Sheets)

| Name        | Experience                                       | Review    |
|-------------|--------------------------------------------------|-----------|
| Jane Smith  | The hotel was beautiful but the staff were rude. | negative  |
| John Doe    | I had a wonderful time, everything was perfect.  | positive  |

---

## 📁 Files

- `sentiment_analysis_agent.json`  
  Exportable workflow for import into any n8n instance.

---

## 🚀 How to Use

1. Import `sentiment_analysis_agent.json` into your n8n instance.
2. Configure your **OpenAI** and **Google Sheets** credentials.
3. Deploy and activate the workflow.
4. Share the form link with users or embed it on your website.
5. Monitor results in your Google Sheet.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Feel free to fork the repo and submit a pull request. Feedback and contributions are always welcome!

---

> Built with ❤️ using n8n + OpenAI + LangChain


