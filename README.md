<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0E27,50:0F3460,100:16213E&height=220&section=header&text=RAM%2FOS&fontSize=58&fontColor=E8F4F8&animation=fadeIn&fontAlignY=32&desc=Random%20Access%20Maker&descAlignY=52&descSize=16&descColor=00D9FF" alt="RAM/OS header banner" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&width=650&height=50&lines=RAM%2FOS+--+booting...;Identity%3A+Vishnu+Sai+Ram+Chennamsetty;Role%3A+Full-Stack+%2B+Applied+AI+Engineer;Status%3A+building%2C+breaking%2C+debugging%2C+shipping" alt="Typing animation"/>

</div>

<br>

## `[ 00 ]` BOOT

<div align="center">

```
$ whoami
vishnu_sai_ram_chennamsetty

$ ram-os --status
[ OK   ]  frontend_engine ......... loaded
[ OK   ]  backend_services ........ loaded
[ OK   ]  ai_lab .................. loaded
[ OK   ]  curiosity.mount ......... /dev/sda1
[ WARN ]  sleep_schedule.sys ...... not found — running on caffeine_fallback
[ RAM/OS ]  boot sequence complete. identity verified.
```

</div>

Full-Stack + Applied AI Engineer. B.Tech CSE (AI & ML) from CMR University, Bengaluru — Class of 2026.

I build the whole thing — interface, API, database, the AI layer that occasionally hallucinates, and the CSS that makes it all look intentional.

<br>

## `[ 01 ]` CURRENT_MISSION

Right now I'm sharpening two things at once: **backend depth** and **AI application architecture**, while keeping the frontend instincts I already trust.

The loop I keep running:

<div align="center">

**`BUILD`** → **`BREAK`** → **`DEBUG`** → **`UNDERSTAND`** → **`SHIP`** → **`REPEAT`**

</div>

Active focus: Data Structures & Algorithms, system design fundamentals, RAG pipelines, and getting comfortable in the parts of the stack that don't come with a UI.

<br>

## `[ 02 ]` BOSS_PROCESS // WanderWay

> Most travel apps ask where you're going. This one tries to actually answer what happens next.

WanderWay takes a destination and a set of trip preferences and turns them into a structured itinerary — then puts it on an interactive map instead of a wall of text.

**Running under the hood:**

`React` `Next.js` `Python` `FastAPI` `PostgreSQL` `Redis` `Mapbox GL JS` `Groq SDK` `Docker`

**The actual engineering problem:** external travel APIs are slow and rate-limited, LLM calls aren't free, and nobody wants to stare at a spinner. Redis sits in front of the repeated external calls — cutting them by roughly **60%**. That's the one number in this README I can actually back up.

| STATE | WHAT |
|:---|:---|
| ✅ **Live** | itinerary generation, route/destination maps, Redis caching layer |
| 🛠 **Improving** | external service failure handling, itinerary quality |
| 🧪 **Exploring next** | multi-day trip logic, collaborative planning |

<div align="center">

[![Repository](https://img.shields.io/badge/Repository-0A0E27?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/vishnusairam654/WanderWay)
[![Live Demo](https://img.shields.io/badge/Live_Demo-0F3460?style=for-the-badge&logo=vercel&logoColor=00D9FF)](https://wander-way-weld.vercel.app/)

</div>

<br>

## `[ 03 ]` VITALS

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=vishnusairam654&show_icons=true&theme=transparent&hide_border=true&title_color=00D9FF&icon_color=8B5CF6&text_color=C9D1D9&ring_color=00D9FF" alt="GitHub stats"/>
<img height="165em" src="https://github-readme-streak-stats.herokuapp.com/?user=vishnusairam654&theme=transparent&hide_border=true&stroke=00D9FF&ring=8B5CF6&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=C9D1D9&currStreakNum=E8F4F8&sideNums=E8F4F8&dates=6E7681" alt="GitHub streak"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishnusairam654&layout=compact&theme=transparent&hide_border=true&title_color=00D9FF&text_color=C9D1D9&langs_count=8" alt="Top languages" width="48%"/>

</div>

<br>

## `[ 04 ]` MEMORY_MAP

<div align="center">

| LAYER | STACK |
|:---|:---|
| 🖥️ **BUILD LAYER** | React · Next.js · Tailwind CSS |
| 🧠 **LOGIC LAYER** | Python · JavaScript (ES6+) · TypeScript · C++ |
| ⚙️ **SERVER ROOM** | FastAPI · Node.js · Express |
| 🗄️ **DATA VAULT** | PostgreSQL · MongoDB · Redis |
| 🧪 **AI LAB** | RAG · LangChain · LLM APIs (Groq / Llama) · Prompt Engineering |
| 🎛️ **INTERACTION ENGINE** | GSAP · Framer Motion · React Three Fiber · Mapbox GL JS |
| 🧰 **TOOLBOX** | Git · Docker · Postman · Vercel · Linux |

</div>

<br>

## `[ 05 ]` UPGRADE_QUEUE

<div align="center">

```
backend depth      ██████░░░░
DSA consistency     ███████░░░
AI systems           ████████░░
sleep schedule        ██░░░░░░░░  known issue, patch pending
```

*(not scientifically measured. mostly vibes. peer-reviewed by nobody.)*

</div>

<br>

## `[ 06 ]` ACTIVE_PROCESSES

**Voice Of Words** — documents usually sit quietly in a folder. This one talks back.

Upload a PDF, DOCX, or TXT and hold a real conversation with it — by text or by voice. The interesting part isn't the chat window, it's what happens before it: large documents were creating slow, timeout-prone backend jobs, so extraction moved client-side (`pdfjs-dist`, `Mammoth`) instead of choking a server. MongoDB backs the retrieval layer that keeps responses grounded in what was actually uploaded — not a perfect hallucination shield, just a better-anchored one.

`React` `Next.js` `Node.js` `MongoDB` `WebRTC` `Vapi AI` `LangChain / RAG`

[![Repository](https://img.shields.io/badge/Repository-0A0E27?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/vishnusairam654/voiceOfWords)
[![Live Demo](https://img.shields.io/badge/Live_Demo-0F3460?style=flat-square&logo=vercel&logoColor=00D9FF)](https://voice-of-words.vercel.app/)

---

**StoreIT** — cloud file storage that still cares about how it looks.

Upload, organize, share, and track storage usage — with ownership rules and access checks doing the boring-but-critical work underneath, and Redux Toolkit holding the app state together. The dashboard leans on React Three Fiber and GSAP, because a storage app doesn't have to look like a spreadsheet.

`React` `Next.js` `Redux Toolkit` `Appwrite` `React Three Fiber` `GSAP`

[![Repository](https://img.shields.io/badge/Repository-0A0E27?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/vishnusairam654/storeIt)
[![Live Demo](https://img.shields.io/badge/Live_Demo-0F3460?style=flat-square&logo=vercel&logoColor=00D9FF)](https://store-it-navy-mu.vercel.app/)

---

**Side quest — CineMetrics**: a real-time analytics build, running quieter than the others but still very much alive.

[![Repository](https://img.shields.io/badge/Repository-0A0E27?style=flat-square&logo=github&logoColor=00D9FF)](https://github.com/vishnusairam654/cinemetrics)
[![Live Demo](https://img.shields.io/badge/Live_Demo-0F3460?style=flat-square&logo=vercel&logoColor=00D9FF)](https://cinemetrics-flax.vercel.app/)

<br>

## `[ 07 ]` EXTERNAL_MODULE

`CircuitVerse` (open source) — fixed a responsive layout bug in the CSS Grid behavior, went through maintainer review, shipped the change. Small patch, real codebase, real feedback loop — the kind of contribution that teaches you more about reading other people's code than writing your own.

<br>

<details>
<summary>⚡ you found a hidden process (click to expand)</summary>
<br>

If you're reading this in the raw `.md` file instead of the rendered page — respect. That's exactly the kind of curiosity that makes a good engineer.

```
$ ps aux | grep curiosity
vishnu    1     0.4  2.1   curiosity_process   [running, will not terminate]
```

</details>

<br>

## `[ 08 ]` ACTIVITY_LOG

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=vishnusairam654&theme=react-dark&hide_border=true&bg_color=00000000&color=00D9FF&line=8B5CF6&point=E8F4F8" alt="Contribution activity graph" width="100%"/>

<img src="https://komarev.com/ghpvc/?username=vishnusairam654&label=CONNECTIONS%20LOGGED&color=0F3460&style=flat-square" alt="Profile views"/>

</div>

<br>

## `[ 09 ]` TRANSMISSION_CHANNEL

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-0A0E27?style=for-the-badge&logo=vercel&logoColor=00D9FF)](http://ram654.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0E27?style=for-the-badge&logo=linkedin&logoColor=00D9FF)](https://www.linkedin.com/in/vishnu654/)
[![GitHub](https://img.shields.io/badge/GitHub-0F3460?style=for-the-badge&logo=github&logoColor=00D9FF)](https://github.com/vishnusairam654)
[![Email](https://img.shields.io/badge/Email-YOUR_EMAIL-0A0E27?style=for-the-badge&logo=gmail&logoColor=00D9FF)](mailto:chennamvishnu123@gmail.com)

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213E,50:0F3460,100:0A0E27&height=120&section=footer&animation=fadeIn" alt="footer" width="100%"/>

*`RAM/OS` will keep running background processes. check back after the next commit.*

</div>
