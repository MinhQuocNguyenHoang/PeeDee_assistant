# PeeDee Assistant

## Overview
PeeDee Assistant is a simple voice assistant that listens to user commands and responds with appropriate answers.
It is designed for easy experimentation with voice recognition and speech synthesis.


---

## Key Features
- **Voice recognition:** Listens to user speech commands via microphone
- **Speech response:** Replies with appropriate answers using text-to-speech
- **Lightweight:** Easy to run on any mini PC with Python
- **Simple interaction:** No complex setup, minimal dependencies

## Hardware Used
- Mini pc: Rasberry Pi Model B+
- Oled 0.96 inch via I2C
- Loa and Mạch khuếch đại âm thanh PAM8403 6W Hifi 2.0 Class D (không volume)
- Micro rasberry pi 

## Software & Tools
- Programming Language: Python 3.11
- Libraries: SpeechRecognition, pyttsx3 (or gTTS), API Germini flash 2.5 pro
- IDE: VS Code
- Platform: Linux

## Project Structure
```
PeeDee_assistant/
├─ PeeDee # Source code files
├─ PeeDee_3D # Source 3D cover of assistant
├─ demo_PeeDee # Demo
└─ README.md # This file
```

## Getting Started

### Prerequisites
- Python 3.x installed
- Required libraries: `SpeechRecognition`, `pyttsx3`, `pyaudio`

### Installation
```bash
git clone https://github.com/MinhQuocNguyenHoang/PeeDee_assistant.git
cd PeeDee
python main.py
#peak a command into your microphone
#PeeDee Assistant will process your speech and respond accordingly
```

## Demo
- [Demo](./demo_PeeDee/)

## Future Improvements
- Add more natural language understanding for complex commands
- Connect to APIs (e.g., weather, calendar)
- Develop mobile or web interface for interaction
- Multi-language support

## Author
Nguyễn Hoàng Minh Quốc<br>
Phạm Mai Diệu Thảo<br>
Phan Nguyễn Thanh Tùng<br>
Phạm Quốc Trung<br>
Lê Bùi Xuân Quang<br>
Nguyễn Trí Thức<br>