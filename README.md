# Beautify - Beauty and Skincare Assistant 🤖💅

Beautify is an intelligent beauty and skincare assistant designed to provide personalized beauty tips, skincare advice, and product recommendations. Built with Natural Language Processing (NLP) and machine learning models, Beautify can classify user intents, suggest beauty routines, and engage in real-time conversations to guide users toward their beauty goals.

---

🚀 **Features**

- **Intent Recognition:** Classifies user input into beauty-related categories using **Logistic Regression** and **TF-IDF vectorization**.
- **Personalized Responses:** Generates beauty-related advice based on the user’s input, including skincare routines, product suggestions, and beauty tips.
- **Interactive Interface:** Built using **Streamlit** for an interactive, user-friendly experience.
- **Conversation Logging:** Saves interactions to a log file for monitoring and future improvement.
- **Beauty Awareness:** Helps users maintain a healthy and personalized beauty routine by offering valuable suggestions.

---

🛠️ **Tools and Technologies**

- **Programming Language:** Python
- **NLP Libraries:**
  - NLTK
  - Scikit-learn (TF-IDF Vectorizer and Logistic Regression)
- **Frontend Framework:** Streamlit
- **Machine Learning:** Logistic Regression for intent classification
- **Utilities:**
  - `csv` for logging conversations
  - `datetime` for timestamps
  - `os` and `json` for file handling

---

🧠 **Methodology**

### **Data Preparation**

- The intent data is stored in a structured **JSON** format with beauty-related queries and corresponding responses.
- The chatbot is trained on different beauty topics, such as skincare routines, beauty trends, and makeup tips.

### **Model Development**

- **TF-IDF Vectorizer** converts user input into numerical features.
- **Logistic Regression** model classifies user input into predefined beauty-related intents.

### **Response Mechanism**

- Depending on the classified intent, specific responses related to beauty and skincare are returned.
- The fallback mechanism ensures the chatbot engages with users, even for unrecognized queries.

### **Interface and Deployment**

- The chatbot is deployed on **Streamlit**, which provides a sleek and interactive web interface for users to ask questions.
- Conversations are logged to a **CSV** file for analysis and improvement.

---

### **Screenshots**

- Screenshots of the chatbot in action (to be added later).

---

🤖 **Try Now:**
- [Beautify: Link](#) (This can be the link to the hosted application)

---

### **Prerequisites**

- Python 3.8 or above
- Required Python libraries: **nltk**, **streamlit**, **scikit-learn**

---

### **Description of Key Files**

- **chatbot.py**
  - Contains the core logic of the chatbot, including intent classification, response generation, and Streamlit interface.
  
- **intents.json**
  - A structured dataset defining user intents, patterns, and corresponding beauty-related responses.

- **requirements.txt**
  - A list of dependencies and libraries required to run the chatbot.

- **chat_log.csv**
  - Logs user inputs, chatbot responses, and timestamps during interactions for analysis and improvement. This file is dynamically created during runtime.

---

### **assets/**

- A directory for storing additional resources like pre-downloaded datasets or NLTK data files.

---

### **📬 Contact**

If you have any questions, feedback, or suggestions, feel free to reach out:

- **Author:** Eswari Marthurthi
- **Email:** eswarimarthurthi@gmail.com
- **GitHub:** [https://github.com/Aanshies]
- **LinkedIn:** [www.linkedin.com/in/eswari-marthurthi-74a8a9286]

We appreciate your interest in Beautify, and we look forward to hearing from you!

