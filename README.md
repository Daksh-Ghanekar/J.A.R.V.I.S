# MARK L (50)

### The Ultimate Cross-Platform Personal AI Assistant — By Daksh Ghanekar

A real-time voice AI that can hear, see, understand, and control your computer — on Windows, macOS, and Linux. Built on the Gemini Live API for native audio streaming.

---

## ✨ Overview

MARK L is a JARVIS-style personal AI assistant designed to provide real-time voice interaction, computer control, visual awareness, persistent memory, and proactive assistance.

It combines voice AI, system automation, computer vision, web search, memory, and desktop control into a single cross-platform assistant.

---

## 🚀 Capabilities

### Core Features

| Feature                       | Description                                                                |
| ----------------------------- | -------------------------------------------------------------------------- |
| 🎙️ Real-time Voice           | Low-latency voice conversation using the Gemini Live API                   |
| 🖥️ System Control            | Launch apps, adjust volume/brightness, WiFi, shortcuts, and power controls |
| 🧩 Autonomous Tasks           | Planning and execution of complex multi-step tasks                         |
| 👁️ Visual Awareness          | Screen capture and webcam vision                                           |
| 🧠 Persistent Memory          | Remembers projects, preferences, and context across sessions               |
| ⌨️ Hybrid Input               | Switch between keyboard and voice commands                                 |
| 🌅 Morning Briefing           | Time, previous-session summary, and relevant information                   |
| 🔔 Proactive Assistant        | Context-aware check-ins based on time and activity                         |
| 🗓️ Session Memory            | Summarizes conversations for future context                                |
| 👁️‍🗨️ Background Monitoring | Monitors user-configured topics for new developments                       |
| 📊 Hardware Monitoring        | CPU, RAM, GPU, and temperature telemetry                                   |
| 🌤️ Weather Report            | Live weather information                                                   |
| 🗺️ Dynamic Content Panel     | Displays web results, news, and search information                         |
| 🔍 Multi-Mode Web Search      | News, research, price, compare, and general search                         |
| ⏰ Smart Reminders             | OS-native scheduled notifications                                          |
| ✈️ Flight Finder              | Flight price and availability lookup                                       |
| 🎮 Game Updater               | Checks and manages game updates                                            |
| 📂 File Processor             | Reads, summarizes, and answers questions about files                       |
| 💻 Code Helper                | Code review, debugging, and generation                                     |
| 🌐 Browser Control            | Open URLs and interact with browser tabs                                   |
| 📨 Send Message               | Messaging integration                                                      |
| 🎬 YouTube Control            | Search and control YouTube playback                                        |
| 🖱️ Desktop Control           | Window, taskbar, and desktop operations                                    |
| 📱 Remote Dashboard           | Control the assistant from a phone                                         |
| ⚡ Auto-Start                  | Launches automatically with the operating system                           |
| 📋 Clipboard Intelligence     | Translate, summarize, explain, and fix copied text                         |
| 🎨 Assistant Customization    | Customize assistant and user names                                         |

---

## 🆕 What's New in Mark L

### 🗓️ Session Memory

At the end of each session, MARK generates a short summary of the conversation and stores it for future context.

The next session can naturally reference previous work without repeatedly displaying the same information.

### 👁️‍🗨️ Background Monitoring

Users can configure MARK to monitor specific topics and check for new developments.

The monitoring system is fully opt-in and only watches topics explicitly configured by the user.

### 🔔 Proactive System 2.0

The proactive engine uses:

* Time of day
* Active projects
* Monitored topics
* Recent conversation context
* Conversation rotation
* Cooldown periods

This makes proactive interactions more contextual and less repetitive.

### 👁️ Instant Vision Acknowledgment

When asked to analyze the screen or camera, MARK immediately acknowledges the request before processing the visual input.

### 📰 Parallel News Search

News searches can use multiple search sources simultaneously, allowing the first valid result to be returned without unnecessarily waiting for another source.

---

## 🗺️ Mark Roadmap

| Version    | Focus                                                                                      |
| ---------- | ------------------------------------------------------------------------------------------ |
| **XLVIII** | Instant interrupt, parallel news, two-phase briefing, exponential backoff, vision cooldown |
| **XLIX**   | Auto-start, clipboard intelligence, assistant customization                                |
| **L**      | Session memory, background monitoring, proactive system, instant vision, parallel news     |
| **LI+**    | Plugin system, email, quiz mode, calorie counter, calendar                                 |

---

## ⚡ Quick Start

```bash
git clone YOUR_REPOSITORY_URL
cd Mark-L
pip install -r requirements.txt
python main.py
```

> ⚠️ Some operating-system-specific dependencies may need to be installed separately. If you encounter a `ModuleNotFoundError`, install the required package using `pip install <module_name>`.

---

## 📋 Requirements

| Requirement    | Details                        |
| -------------- | ------------------------------ |
| **OS**         | Windows 10/11, macOS, or Linux |
| **Python**     | 3.11 or 3.12                   |
| **Microphone** | Required for voice interaction |
| **API Key**    | Gemini API key                 |

---

## 🗂️ Project Structure

```text
Mark L/
├── main.py
├── ui.py
├── setup.py
├── actions/
│   ├── web_search.py
│   ├── screen_processor.py
│   ├── background_monitor.py
│   ├── proactive.py
│   ├── reminder.py
│   ├── system_monitor.py
│   ├── computer_settings.py
│   ├── computer_control.py
│   ├── open_app.py
│   ├── browser_control.py
│   ├── file_controller.py
│   ├── file_processor.py
│   ├── send_message.py
│   ├── weather_report.py
│   ├── flight_finder.py
│   ├── youtube_video.py
│   ├── game_updater.py
│   ├── code_helper.py
│   ├── dev_agent.py
│   └── desktop.py
├── memory/
│   ├── memory_manager.py
│   └── long_term.json
├── core/
│   └── prompt.txt
└── config/
    └── api_keys.json
```

---

## ⚠️ License

Personal and non-commercial use only.

See the repository license file for the complete licensing terms.

---

## 👤 Creator

### Daksh Ghanekar

A student developer building AI-powered applications, automation tools, and JARVIS-style assistants.

⭐ Star the repository if you find the project useful.

---

## 🔗 Connect

* **GitHub:** Daksh Ghanekar
* **Project:** MARK L
