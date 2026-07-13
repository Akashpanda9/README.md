# 🏠 Smart Home Automation Using WhatsApp

A Raspberry Pi-based IoT home automation system that allows users to control household appliances remotely through WhatsApp using the Twilio API. The project demonstrates the integration of embedded systems, cloud communication, and Python-based automation to provide a simple and efficient smart home solution.

---

## 👨‍💻 Developer

**Akash Kumar Panda**

B.Tech Computer Science & Engineering (IoT)

Institute of Technical Education and Research (ITER), SOA University

📍 Bhubaneswar, Odisha, India

📧 akashkumarpanda2005@gmail.com

🔗 LinkedIn: https://linkedin.com/in/akash-kumar-panda-296478329

💻 GitHub: https://github.com/Akashpanda9

---

## 📌 Project Overview

This project enables users to control electrical appliances such as LEDs and DC motors through WhatsApp messages. A Raspberry Pi receives commands from the Twilio WhatsApp API, processes them using a Flask application, and controls connected devices through GPIO pins.

The system demonstrates practical implementation of IoT-based automation using cloud messaging services.

---

## ✨ Features

- 📱 WhatsApp-based appliance control
- 💡 LED ON/OFF operation
- 🌪️ DC Motor/Fan Control
- 🔌 Raspberry Pi GPIO Interface
- 🌐 Flask Webhook Integration
- ☁️ Twilio WhatsApp API Communication
- ⚡ Real-time Device Control
- 🛡️ Lightweight and Easy to Deploy

---

## 🛠️ Technologies Used

- Python
- Flask
- Raspberry Pi
- Twilio WhatsApp API
- GPIOZero
- HTML
- CSS
- Git & GitHub

---

## 🔧 Hardware Components

- Raspberry Pi Zero 2W
- L298N Motor Driver
- LED
- DC Motor / Fan
- Breadboard
- Jumper Wires
- Power Supply

---

## 📂 Project Structure

```
Smart-Home-Automation-Using-WhatsApp
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── docs/
├── images/
├── led_test.py
├── motor_test.py
└── Testing Code of fan and LED.py
```

---

## ⚙️ Working Principle

1. User sends a command through WhatsApp.
2. Twilio forwards the message to the Flask Webhook.
3. Flask processes the received command.
4. Raspberry Pi activates the corresponding GPIO pins.
5. LED or DC Motor responds according to the received command.

---

## 📲 Supported Commands

| WhatsApp Command | Action |
|------------------|--------|
| LED ON | Turns LED ON |
| LED OFF | Turns LED OFF |
| FAN ON | Starts the DC Motor/Fan |
| FAN OFF | Stops the DC Motor/Fan |

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Akashpanda9/Smart-Home-Automation-Using-WhatsApp.git
```

### Navigate to Project

```bash
cd Smart-Home-Automation-Using-WhatsApp
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

## 📷 Demonstration

Add screenshots of:

- WhatsApp Chat Commands
- Flask Webhook Running
- Raspberry Pi Setup
- LED ON/OFF Operation
- Motor/Fan Control

---

## 📚 Learning Outcomes

- IoT System Development
- Raspberry Pi GPIO Programming
- Python Automation
- Flask Web Development
- API Integration
- Twilio WhatsApp Messaging
- Embedded Systems Programming
- Git Version Control

---

## 🎯 Future Enhancements

- Mobile Application
- Voice Assistant Integration
- MQTT Support
- Firebase Database
- Multiple Appliance Management
- Live Device Status Dashboard

---

## 📄 License

This project is intended for educational and learning purposes.

---

## ⭐ Acknowledgements

Special thanks to **ITER, SOA University** for providing the academic environment that encouraged practical IoT and embedded systems development.

If you found this project useful, consider giving it a ⭐ on GitHub.
