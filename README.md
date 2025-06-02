# 🤖 Jarvis - Virtual Assistant using Python  

Jarvis is a **voice-activated virtual assistant** built using Python. It performs various daily tasks like fetching information from Wikipedia, sending emails, reporting system status, playing music, and more — all through simple voice commands.  

## 🚀 Features  

- 🎤 **Voice Command Recognition** using Speech Recognition.  
- 📢 **Text-to-Speech Response** with pyttsx3.  
- 🌐 **Wikipedia Search & Summarization**.  
- ✉️ **Automated Email Sending** via SMTP.  
- 🕑 **Time & Date Information**.  
- 💻 **System Monitoring** (CPU usage, battery percentage).  
- 📷 **Screenshot Capturing**.  
- 🎶 **Play Music** from a specified directory.   
- 🔌 **System Control** (shutdown, restart, logout).  
- 🃏 **Fun Commands** like jokes and small talk.  

## 🛠️ Technologies & Libraries  

- **Python 3.x**  
- **pyttsx3** — Text-to-speech conversion.  
- **speech_recognition** — Speech-to-text conversion.  
- **wikipedia** — Fetching Wikipedia data.  
- **smtplib** — Sending emails.  
- **psutil** — System status monitoring.  
- **pyjokes** — For generating jokes.  
- **datetime** — For date and time functions.  
- **os & subprocess** — For system operations.  

## 🔧 Installation & Setup  

### 1. Clone the Repository  

```bash
git clone https://github.com/Rachana-Hegde/jarvis-virtual-assistant.git
```  

### 2. Navigate to the Project Directory  

```bash
cd jarvis-virtual-assistant
```  

### 3. Install Required Libraries  

```bash
pip install pyttsx3 speechrecognition wikipedia pyjokes psutil
```  

### 4. Run Jarvis  

```bash
python jarvis.py
```  

## 💻 How It Works  

1. **Voice Command Listener**: Listens for user commands using the microphone.  
2. **Speech Recognition**: Converts voice input to text.  
3. **Command Processing**: Matches recognized commands to predefined functions.  
4. **Voice Response**: Responds through system audio using text-to-speech.  

## 🎮 Example Commands  

| Command                                | Action                                  |  
|----------------------------------------|-----------------------------------------|  
| "Jarvis, what time is it?"              | Tells current time                      |  
| "Search Wikipedia for Python"          | Returns a summary from Wikipedia        |  
| "Send email to [recipient]"             | Sends an email                          |  
| "Play music"                           | Plays a random song from your directory |  
| "What's the CPU usage?"                 | Reports CPU and battery status          |  
| "Take a screenshot"                    | Captures and saves a screenshot         |  
| "Tell me a joke"                       | Tells a random joke                     |  
| "Shutdown the system"                  | Shuts down the computer                 |  

## 📂 Project Structure  

```
jarvis-virtual-assistant/
│── jarvis.py               # Main Python script
│── python-3.13.2-amd64     # Install this software for PyAudio 
│── README.md               # Project documentation
│── /music                  # (Optional) Folder to store music files
│── /screenshots            # (Optional) Folder where screenshots will be saved
```  

## 📝 Notes  

- Ensure your microphone and speaker are enabled and working properly.  
- You can customize the music directory path in the script.  
- Email feature requires SMTP setup and login credentials — handle securely.  

## 🌟 Contributing  

Contributions, suggestions, and improvements are welcome!  

1. Fork the repository.  
2. Create your feature branch: `git checkout -b feature-name`.  
3. Commit your changes: `git commit -m 'Add some feature'`.  
4. Push to the branch: `git push origin feature-name`.  
5. Open a pull request.  

## 📬 Contact  

For queries or feedback:  
🔗 **GitHub:** [Rachana-Hegde](https://github.com/your-username)  
