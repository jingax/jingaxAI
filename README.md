# 🧠 JingaxAI: Personal AI Chatbot

JingaxAI is an interactive AI chatbot designed to answer questions about you, providing insights into your background, skills, projects, and more. Hosted within an iframe on your portfolio site, it offers visitors a personalized conversational experience.
---
I have it currently hosted on portfolio [here](https://jingax.github.io/). Do check check out!

## ⚙️ Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/jingax/jingaxAI.git
   cd jingaxAI
   ```

2. **Create and Activate a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the App**:
   ```bash
   streamlit run main.py
   ```

---

## 🌐 Deployment

Deploy the chatbot on [Streamlit Cloud](https://streamlit.io/cloud), [Render](https://render.com/), or any other hosting provider.

To embed it in your personal website:

```html
<iframe src="https://your-deployed-app-url" width="100%" height="600px"></iframe>
```

Replace `https://your-deployed-app-url` with your actual app URL.

---

## ✍️ Customizing the Chatbot (for Another Person)

To personalize JingaxAI for someone else:

1. Open the `about_me.txt` file.
2. Replace the content with the new individual's information, such as:
   - Full name
   - Education
   - Skills
   - Work experience
   - Projects
   - Hobbies, interests, and achievements

   Example:
   ```
   My name is John Doe. I graduated from MIT in Computer Science...
   ```

3. Save the file. The chatbot will automatically use the new content — no other changes are necessary.

---

## 🧠 How It Works

JingaxAI reads the profile information from `about_me.txt`, embeds the text, and uses a language model (e.g., OpenAI GPT) to answer user questions conversationally and accurately.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **OpenAI GPT (via API)**
- **Local context from `about_me.txt`**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
