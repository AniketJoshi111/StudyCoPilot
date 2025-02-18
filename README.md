# StudyCoPilot

**StudyCoPilot** is a Chrome extension designed to make academic research faster and smarter! With the power of Gemini AI and a Spring Boot backend, this tool allows users to use AI features like Summarization on the go leading to fast researching tasks.
---

## 🚀 Features

- **Smart Summarization:** Extract and summarize abstracts, introductions, conclusions, and more with one click.
- **Gemini AI Integration:** Uses the latest Gemini AI model for fast, accurate, and insightful summaries.
- **Spring Boot Backend:** Efficient and scalable API for handling summarization requests.
- **Browser Integration:** Seamlessly works within Chrome to provide contextual summaries without leaving the page.

---

## 🛠️ Tech Stack

- **Frontend:** Chrome Extension (HTML, CSS, JavaScript)
- **Backend:** Spring Boot (Java/Kotlin)
- **AI Model:** Gemini AI (via API integration)

---

## 📦 Installation

1. **Clone the repository:**

```bash
 git clone https://github.com/AniketJoshi111/StudyCoPilot.git
```

2. **Backend Setup:**

- Open the Spring Boot backend in your preferred IDE.
- Configure the Gemini AI API key in `application.properties`.
- Run the backend:

```bash
 mvn spring-boot:run
```

3. **Frontend Setup:**

- Open Chrome and go to `chrome://extensions/`.
- Enable Developer Mode.
- Click "Load unpacked" and select the `/chrome-extension` folder.

4. **Start Summarizing!**

---

## ⚙️ Usage

1. Open any research paper in your Chrome browser.
2. Click on the StudyCopilot extension icon.
3. Select the sections you want to summarize (Abstract, Introduction, Conclusion, etc.).
4. View the summary instantly generated using Gemini AI.
---

## 🐞 Troubleshooting
- **Chrome Extension Errors:** Make sure you’ve loaded the correct `/frontend` folder and enabled Developer Mode.
