# 🌐 Language Translation Tool

A simple **Language Translation Tool** built with **Python, Streamlit, and Googletrans**.  
This tool allows you to translate text from one language to another through a simple web interface.

---

## ✨ Features
- Translate text between multiple languages  
- User-friendly **Streamlit** interface  
- Hosted online using **Ngrok** for sharing your project demo  

---

## 📦 Requirements
Make sure you have Python installed. Then install the required packages:

```bash
pip install googletrans==4.0.0-rc1
pip install streamlit
pip install pyngrok
```

---

## 🚀 How to Run
1. Open the project in **Google Colab** or **VS Code**  
2. Save the Streamlit code as `app.py`  
3. Run the Streamlit app:

```bash
streamlit run app.py
```

4. Use **Ngrok** to create a public link:

```python
from pyngrok import ngrok
ngrok.set_auth_token("YOUR_AUTH_TOKEN_HERE")
public_url = ngrok.connect(8501)
print("Your Public URL:", public_url)
```

5. Open the public URL in your browser to use the tool.

---

## 📸 Demo
![Demo Screenshot](screenshot.png)

---

## 📂 Project Files
- `Language_Translation_Tool.ipynb` – Jupyter Notebook with full code  
- `app.py` – Streamlit app file  
- `README.md` – Project documentation  

---

## 👨‍💻 Author
Created by **Bavadharani**
