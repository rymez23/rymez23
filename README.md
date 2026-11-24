# Phillipe Janvier

**Logistics Specialist at Amazon → Software Engineer | CS Student at WGU | Python Developer**

I'm a CS student at Western Governors University and an Amazon operations professional moving into software engineering. I like building tools that solve real problems: automating the busywork, running AI locally, and writing clean, tested code that someone else could pick up and maintain.

## Current Focus
- **Logistics Specialist at Amazon** (Tempe, AZ), building automation for day-to-day operations
- **BS Computer Science**, Western Governors University (expected 2027)
- **Certifications:** CompTIA ITF+ (certified) · CompTIA A+ (Core 1 passed)

## Featured Projects

### 🎙️ [Jarvis](https://github.com/rymez23/jarvis): offline voice assistant
A "Hey Jarvis" voice assistant that runs **entirely offline** on a 2017 laptop CPU, with no GPU and no cloud.
- **Brain:** local LLM (Gemma 4 E2B) through Ollama, with **tool calling** (time, opening apps from an allow-list, reading my morning brief aloud)
- **Ears:** faster-whisper speech-to-text with my own energy-based end-of-speech detection
- **Voice:** Piper neural text-to-speech · **Wake word:** openWakeWord (~4% of one CPU core)
- Hybrid routing: regex fast-path for common requests, LLM tool calls for everything else
- 44 unit tests using fake audio, a fake model server, and dependency injection

`Python` `Ollama` `faster-whisper` `Piper` `openWakeWord` `pytest`

### ☀️ [Morning Brief](https://github.com/rymez23/morningbrief): daily briefing, built for me and used every day
Every morning at 5:30 it gathers what I need before my shift and emails it to my phone:
- Today's **Google Calendar** and unread **Gmail** (OAuth 2.0, read-only plus send-to-self)
- **PC health:** Chrome version, pending Windows updates, app updates via winget
- New **tech, politics and science** headlines from RSS, de-duplicated across days
- Every section fails independently; structured JSON run logs; HTML output with escaping for untrusted feed text
- Windows Task Scheduler automation, 14 unit tests · [project site](https://rymez23.github.io/morningbrief/)

`Python` `Gmail API` `Google Calendar API` `OAuth 2.0` `GitHub Pages`

## Other Work
- **FPS game** in C# and C++ (Visual Studio): game loop, collision detection, debugging
- **KPI dashboards** in Excel and Power BI for high-volume operations metrics

## Technical Skills
- **Languages:** Python, C#, C++, SQL
- **Tools:** Git, VS Code, Visual Studio, pytest, Ollama, Power BI, Excel
- **Interests:** automation, local/offline AI, data systems, trust & safety

## Background
Before software I ran a professional kitchen as head chef and spent nine years as a quality auditor and performance facilitator. That's where I learned to own a process end to end, measure it, and keep improving it. I bring the same approach to code.

## Let's Connect
- **LinkedIn:** [linkedin.com/in/phillipe-janvier-137a98168](https://linkedin.com/in/phillipe-janvier-137a98168)
- **Location:** Tempe, AZ

---
*Last updated: November 2026*
