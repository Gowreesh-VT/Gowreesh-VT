<div align="center">

<!-- Animated header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Gowreesh%20V%20T&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20WebOps%20%7C%20CS%20%40%20VIT%20Chennai%20%2B%20IITM&descAlignY=58&descSize=17&animation=fadeIn" />

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Building+production-grade+full-stack+apps;Next.js+%7C+Node.js+%7C+PostgreSQL+%7C+Redis+%7C+Docker;CI%2FCD+%7C+AWS+%7C+GCP+%7C+Vercel+%7C+GitHub+Actions;Blockchain+%7C+Cybersecurity+%7C+AI-ML;CS+%40+VIT+Chennai+%2B+IITM+Data+Science)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-gowreesh.me-7C3AED?style=for-the-badge&logoColor=white)](https://gowreesh.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gowreesh)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vt.gowreesh43@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/gowreesh_2007)

</div>

---

## `> whoami`

```ts
const gowreesh = {
  name        : "Gowreesh V T",
  education   : ["VIT Chennai — B.Tech CSE Core", "IIT Madras — BS Data Science"],
  role        : "Full-Stack Developer Intern",
  location    : "Erode, Tamil Nadu 🇮🇳",
  focus       : ["Production Web Apps", "WebOps & Cloud Infra", "CI/CD Pipelines", "System Design"],
  currentWork : ["VehicleTrack Pro — B2C Fleet PWA", "Custom Email Client GUI"],
  cloudStack  : ["AWS", "GCP", "Azure", "Vercel", "Docker"],
  community   : "Microsoft Innovation Club — 10-Workshop Series Host",
  funFact     : "Debugging at midnight hits different 🌙",
};
```

---

## 🚀 Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### 🚛 VehicleTrack Pro
> **B2C Fleet Compliance PWA** — Production Intern Project

Real-world PWA targeting low-literacy truck drivers & fleet operators in Tier 2/3 Indian cities. Built and deployed with enterprise-grade seriousness.

**Highlights:**
- 🔍 VAHAN RTO scraper + Tesseract.js OCR captcha solving
- 📸 Client-side OCR certificate scanner
- 💳 Razorpay payment integration
- 📲 SMS/push notification reminders
- 🌐 Tamil i18n with `next-intl`
- 📍 PIN/pattern login for low-literacy UX
- 👨‍✈️ Captain-vehicle many-to-many management
- 🚀 Deployed on Vercel with GitHub Actions CI/CD

**Stack:** `Next.js 14` `PostgreSQL` `Prisma` `NextAuth.js` `Razorpay` `Serwist PWA` `Playwright` `Tesseract.js`

</td>
<td width="50%" valign="top">

### 📧 Custom Email Client GUI
> **Full-Stack Email Platform** — Production Intern Project

Fully-featured email client with advanced SMTP pooling, bulk workflows, real-time tracking, and automated cron jobs via GitHub Actions.

**Highlights:**
- 🔀 4-level SMTP priority chain (Global → Admin → User → Legacy)
- 📊 Bulk send with CSV import
- 📝 HTML template editor (CodeMirror 6)
- 📡 Email open/click tracking pixel
- 🔔 Push notifications + audit logging
- 📄 Certificate PDF generation
- ⏰ GitHub Actions cron for scheduled sends
- 📷 QR code scan/generate (mobile PWA)

**Stack:** `Next.js 14` `PostgreSQL/Neon` `Prisma` `Redis` `Shadcn/ui` `GitHub Actions` `Vercel`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 Smartlinxliving
> **Smart Home Automation Platform**

Web platform for smart home integration, automation workflows, and IoT device management.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Gowreesh-VT/Smartlinxliving)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔬 qbbit-explorer & Data-Rhythm-Academy
> **Exploration Projects**

TypeScript-based explorations into data science tooling and interactive learning platforms.

[![qbbit](https://img.shields.io/badge/qbbit--explorer-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Gowreesh-VT/qbbit-explorer)
[![DRA](https://img.shields.io/badge/Data--Rhythm--Academy-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Gowreesh-VT/Data-Rhythm-Academy)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
</tr>
</table>

---

## ☁️ WebOps & Cloud

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                        DEPLOYMENT PIPELINE                          │
│                                                                     │
│  Code Push  →  GitHub Actions CI/CD  →  Build & Test  →  Deploy    │
│                        ↓                                            │
│            ┌───────────┴────────────┐                               │
│            ▼                        ▼                               │
│         Vercel                   Docker                             │
│      (Next.js Apps)           (Containerised)                       │
│            ↓                        ↓                               │
│    ┌───────┴───────┐        ┌───────┴───────┐                       │
│    ▼               ▼        ▼               ▼                       │
│   AWS             GCP     Azure           Neon DB                   │
│  (S3/EC2)   (Cloud Run) (VM/Functions)  (Postgres)                  │
└─────────────────────────────────────────────────────────────────────┘
```

</div>

| Layer | Tools & Services |
|---|---|
| 🔄 **CI/CD** | GitHub Actions · Vercel Preview Deploys · Automated cron jobs |
| 🐳 **Containers** | Docker · Docker Compose |
| ☁️ **Cloud** | AWS (S3, EC2) · GCP (Cloud Run, Firebase) · Azure (VMs, Functions) |
| 🗄️ **Managed DB** | Neon (Serverless Postgres) · Supabase · Firebase Realtime |
| ⚡ **Caching** | Redis · Edge caching on Vercel |
| 📊 **Monitoring** | GitHub Actions logs · Vercel Analytics |

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Shadcn/ui](https://img.shields.io/badge/Shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**Databases & ORMs**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**WebOps, Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Blockchain & Security**

![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![MetaMask](https://img.shields.io/badge/MetaMask-F6851B?style=for-the-badge&logo=metamask&logoColor=white)
![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white)

</div>

---

## 🎙️ Community & Leadership

<div align="center">

### 🏢 Microsoft Innovation Club — Workshop Series Host

</div>

Organized and hosted a **10-session technical workshop series** with hackathons, covering full-stack development, cybersecurity, blockchain, and AI — making complex topics accessible to mixed-skill audiences with an energetic, hands-on style.

| Session | Topic |
|---|---|
| 🔗 Final Session | **Build Your Own Cryptocurrency** — Solidity, Remix IDE, MetaMask, Sepolia Testnet, ERC-20/OpenZeppelin |
| ⚙️ Series Topics | Full-stack dev · DSA · Cloud & WebOps · Cybersecurity · AI/ML · Hackathon sprints |

> *Making complex tech accessible to everyone — that's the mission.*

---

## 🎓 Certifications

<div align="center">

| 🏅 Certificate | 🏢 Issuer | 🔖 Domain |
|---|---|---|
| Meta Full-Stack Developer | Meta / Coursera | Full-Stack Engineering |
| Meta Python Professional | Meta / Coursera | Backend & Scripting |
| MongoDB Developer | MongoDB University | NoSQL & Database Design |
| Redis Certified Developer | Redis University | Caching & Data Structures |
| SQL Associate | DataCamp | Relational Databases |
| Responsive Web Design | freeCodeCamp | Frontend / CSS |
| Introduction To AWS | AWS | DevOps |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Gowreesh-VT&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gowreesh-VT&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false&layout=compact"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=Gowreesh-VT&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-trophies.vercel.app/?username=Gowreesh-VT&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Gowreesh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Gowreesh-VT&theme=tokyo-night&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

### 💬 Dev Philosophy

*"Ship fast, learn faster. Real products teach you what no tutorial ever will."*

---

**Open to collaborations, internships, and building things that actually matter.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

</div>
