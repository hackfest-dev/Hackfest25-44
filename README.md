# 🚨 Guardian AI – Real-Time Harassment Detection from Calls & Messages  
### Team Name: Compiling Pandas  
### Hackathon: Hackfest 2025  
### Track: Open Innovation  
### College: B.M.S Institute Of Technology And Management, Karnataka  

---

## 🔍 Problem Statement  
*AI-powered harassment detection for calls & messages*

Harassment via phone calls and messages is a rising concern. Victims receive threats, abuse, and emotional manipulation, often from unknown or masked numbers. Existing tools like spam filters rely on crowd-sourced reports and fail to catch real-time abuse — especially verbal harassment during calls.

---

## 💡 Our Solution: Guardian AI  

*Guardian AI* is an intelligent system designed to detect harassment and scam attempts in real time, without needing prior reports or user actions.

### Key Highlights:
- 🧠 AI-based detection from live phone calls and messages  
- 📞 Automatically records unknown number calls  
- 🎧 Uses Whisper to transcribe calls  
- 🔍 Uses a BERT-based NLP model to detect scam or harassment type  
- 🔐 Offers options to block, report, or save the call/message as legal evidence  

---

## 🧠 How It Works  

1. 📞 *Incoming call from an unknown number*  
   - Just like Google Dialer's auto-recording, our system starts recording unknown calls if enabled.
2. 🎧 *Audio is recorded in real-time*
3. 🧾 *Speech-to-text processing using OpenAI Whisper*
4. 📊 *Text is fed into a fine-tuned BERT model*  
   - Model classifies into categories like Extortion, Romance Scam, Tech Support, etc.
5. 🔔 *User receives real-time alerts*  
6. 🛡 *User chooses action*: Block, Report, or Save for future reference  

---

## 🌐 Gradio Interface (Demo for Hackathon)

In this demo version:
- Users simulate a recorded call by uploading an .mp3 file.
- The system transcribes and analyzes the audio instantly.
- Output includes both the *transcript* and *predicted harassment/scam category*.

<p align="center">
  <img src="https://i.imgur.com/your_demo_screenshot.png" alt="Guardian AI Gradio Demo" width="600"/>
</p>

---

## 🛠 Tech Stack  

| Component | Technology |
|----------|------------|
| *Speech-to-Text* | OpenAI Whisper, Google Speech-to-Text API |
| *NLP Classification* | BERT, Hugging Face Transformers, PyTorch |
| *Frontend* | Gradio |
| *Backend/API* | FastAPI / Node.js (future scope) |
| *Database* | Firebase Firestore / MongoDB (future scope) |
| *Cloud* | Google Colab, Google Cloud, AWS Lambda |

---

## 📂 Dataset  

Trained using a custom-labeled dataset containing messages and their scam categories such as:
- 📞 Tech Support Scam  
- 💰 Extortion / Sextortion  
- ❤ Romance Scam  
- 👮‍♂ Fake Law Enforcement  
- 💼 Workplace Harassment  
- 📩 Debt Collection Threats  

---

## 🔐 Features  

- ✅ Automatically starts when an unknown number calls  
- ✅ Real-time speech-to-text & harassment detection  
- ✅ Classifies into multiple scam/harassment categories  
- ✅ Supports legal evidence storage  
- ✅ Designed to scale with telecom integration  

---

## 🚀 Future Scope  

- 🌎 *Multi-language model support* for regional detection  
- 📶 *Integration with telecom providers* to block threats at the source  
- 🗂 *Secure cloud storage* for flagged evidence  
- 🔁 *Model improvement via continuous training*

---

## 🧑‍💻 Team – Compiling Pandas  
- sandeep bhajantri 
- tarun m 
- tejas k m 
- samartha s 

---

## 📸 Screenshots & Demo  

Add screenshots or screen recordings of your Colab notebook, Gradio UI, or prediction examples here.  

---

## 📜 License  
This project was developed as part of Hackfest 2025 – Open Innovation Track. Intended for educational and research purposes only.

---

> Guardian AI – Because your phone should be a safe space.
