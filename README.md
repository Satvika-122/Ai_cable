## AI-Driven Cable Design Validator

This project is an AI-powered web application that validates low-voltage cable designs against **IEC 60502-1** and **IEC 60228** standards. It demonstrates how AI reasoning can assist engineers in reviewing cable designs efficiently.

## 🚀 Live Demo
- **Application:** https://aicable-echghg4ip3a6vsmsae3alh.streamlit.app/
- **Demo Video:** https://drive.google.com/file/d/1-RXB48KqxZckKul6XNiuPrER3mA5YLqe/view

## 📌 Features
- Accepts free-text or JSON cable design inputs  
- AI-based interpretation and validation  
- Clear **PASS / WARN / FAIL** results  
- Engineering explanations with confidence scores  
- Safe fallback logic if AI output is invalid  

## 🧠 Tech Stack
- Python  
- Streamlit  
- Hugging Face Transformers  
- Qwen 2.5 Instruct Model  

## ⚙️ How It Works
1. User enters cable design details  
2. AI extracts key parameters  
3. Design is evaluated against IEC standards  
4. Results are shown with explanations and confidence  

## 🛠️ Run Locally
```bash
git clone https://github.com/Satvika-122/Ai_cable.git
cd Ai_cable
pip install -r requirements.txt
streamlit run app.py
