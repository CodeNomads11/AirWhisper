# AirWhisper

**Silent GPT-Powered Wearable Communication Device**

---

> “Built for the bros. Whispered by tech. Engineered in silence."

AirWhisper is a next-gen wearable project by **Code Nomads**, a team of high schoolers pushing the boundaries of AI and stealth communication. This device allows users to whisper privately to a wearable microphone, which then connects to GPT and replies discreetly through a bone-conduction speaker — all without making a sound.

---

## 🎯 Project Goal

To build a discreet, hands-free, AI-powered communication system that enables:

* Silent question asking in class or public environments
* Private GPT responses through a wearable ear receiver
* Stealthy design (no visible wires, no bulky hardware)

---

## 🧠 Key Features

* ESP32-based processing unit
* MEMS microphone for near-field whisper detection
* Ring-based push-to-talk activation system
* GPT voice query + reply via WiFi
* Bone conduction ear speaker (hidden in ear)
* Discreet wearable PCB on the nape
* Optional vibration feedback

---

## 📦 Components

* ESP32-S3 microcontroller
* MEMS mic (e.g. INMP441)
* Li-ion Battery + TP4056 charging module
* Bone conduction speaker
* Vibration motor (optional feedback)
* Bluetooth receiver for audio output
* Ring-based button trigger
* 3D printed housing (ear + neck units)

---

## ⚙️ Architecture Overview

1. Whisper -> Mic captures input
2. ESP32 sends audio to mobile/Pi -> GPT
3. GPT response returned as audio
4. Audio delivered via bone conduction
5. Ring button used to trigger or end query

---

## 📅 Timeline

| Phase | Description                     | Status         |
| ----- | ------------------------------- | -------------- |
| 1     | Voice input + GPT text test     | ✅ Done         |
| 2     | Add ring trigger system         | ὐ1 In progress |
| 3     | Bone conduction speaker testing | ὐ1             |
| 4     | Compact PCB + housing design    | ⏳              |
| 5     | Final wearable integration      | ⏳              |

---

## 🚀 What's Next

* Build MVP using recycled/borrowed parts
* Reach out to tech communities for hardware support
* Share updates, test in real-life scenarios

---

## 👨‍💻 Built by

**Code Nomads**:

* Frontman (Vision, Dev)
* Mulleti (Co-Dev, AI)
* 456 (Hardware Learn Dev)

---

## 🤝 We’re Looking For

* ESP32 / MEMS mic / speaker donations
* Mentors for wearable hardware & AI
* Collaborators who vibe with the mission

If you want to support, help, or just talk tech:

> 📩 Contact: \[Wadoodabdul150@Gmail.com]
---

## 🌟 License

This project is licensed under the **MIT License**.

> You are free to use, modify, distribute, and build upon this project, provided you include attribution to the Code Nomads team and do not use it for unethical or illegal purposes (including academic dishonesty).

> “Built not to cheat. Built to communicate like never before.”
