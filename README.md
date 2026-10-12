<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=90&section=header&text=Leonardo%20Salazar%20Cassano&fontColor=e6edf3&fontSize=30&fontAlignY=55" width="100%" alt="header" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3000&pause=1200&color=8B949E&center=true&vCenter=true&width=520&height=24&lines=Full-Stack+Software+Developer;Java+%C2%B7+Spring+Boot+%C2%B7+React+%C2%B7+Angular+%C2%B7+TypeScript;Python+%26+AI+%C2%B7+Linux+%C2%B7+Cloud" alt="Typing SVG" /></a>

</div>

## Who I am

Full-Stack Software Developer passionate about building practical software solutions, from intuitive user interfaces to backend logic, database management, and deployment. Experienced in enterprise ERP systems, international Agile teams, web and mobile development, automation, and AI-powered applications. Combining technical skills with a strong interest in UX, design, and problem-solving. Italian, Spanish, and English.

<br>

## Why Me?

<details>
<summary><b>Why did I choose to work across different technologies instead of specializing in just one?</b></summary>
<br>

I believe the direction technology is taking is pushing us to become more versatile developers: people who can work across different technologies, understand different areas of software development, and adapt to new challenges.

The tech world moves incredibly fast. The way we build software today may look very different a year from now. In my opinion, adaptability is essential at every level of seniority. That's why I chose not to limit myself to a single programming language or framework. I want to understand different technologies, recognize the principles they share, and be ready to learn and adapt as the industry evolves.

</details>

<details>
<summary><b>What value can I bring to a company?</b></summary>
<br>

I see a Full-Stack Developer as more than someone who works on both frontend and backend. Especially in small and medium-sized businesses, I believe this role can bring value by understanding and contributing to a wide range of technological needs: from building websites and business management systems to creating digital content, integrating services, and maintaining or debugging legacy software.

I bring experience with modern technologies used in professional software development, together with a broad set of complementary skills. My goal is to understand the bigger picture, identify what a project needs, and contribute wherever my skills can make a difference, while continuing to learn and grow with the team.

</details>

## Tech Stack

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/Angular-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/TypeScript-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/JavaScript-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/Material_UI-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/Zustand-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/Bootstrap-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/HTML5-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/CSS3-2563EB?style=flat" />
  <img src="https://img.shields.io/badge/jQuery-2563EB?style=flat" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/Java-16A34A?style=flat" />
  <img src="https://img.shields.io/badge/Spring_Boot-16A34A?style=flat" />
  <img src="https://img.shields.io/badge/REST_API-16A34A?style=flat" />
  <img src="https://img.shields.io/badge/Python-16A34A?style=flat" />
</p>

**Database & Data**

<p>
  <img src="https://img.shields.io/badge/SQL-9333EA?style=flat" />
  <img src="https://img.shields.io/badge/MySQL-9333EA?style=flat" />
  <img src="https://img.shields.io/badge/Supabase-9333EA?style=flat" />
  <img src="https://img.shields.io/badge/Row_Level_Security-9333EA?style=flat" />
  <img src="https://img.shields.io/badge/Realtime-9333EA?style=flat" />
</p>

**Mobile Development**

<p>
  <img src="https://img.shields.io/badge/React_Native-F97316?style=flat" />
  <img src="https://img.shields.io/badge/Expo-F97316?style=flat" />
</p>

**Cloud, Tools & Methodologies**

<p>
  <img src="https://img.shields.io/badge/Linux-475569?style=flat" />
  <img src="https://img.shields.io/badge/Ubuntu-475569?style=flat" />
  <img src="https://img.shields.io/badge/Oracle_Cloud-475569?style=flat" />
  <img src="https://img.shields.io/badge/Git-475569?style=flat" />
  <img src="https://img.shields.io/badge/GitHub-475569?style=flat" />
  <img src="https://img.shields.io/badge/Agile-475569?style=flat" />
  <img src="https://img.shields.io/badge/Scrum-475569?style=flat" />
</p>

## Come sviluppo

Gli schemi che uso per ragionare quando parto da zero con una tecnologia. Cambiano gli strumenti, non l'idea: ogni livello ha una responsabilità sola.

### Frontend Development

```mermaid
flowchart TD
    A[Componenti UI] --> B[State Management]
    B --> C[Layer API]
    C -->|HTTP Request| D[Backend / REST API]
    D -->|HTTP Response| C
    C --> B
    B -->|Aggiornamento UI| A

    classDef frontend fill:#2563eb,color:#fff,stroke:#1d4ed8
    classDef state fill:#7c3aed,color:#fff,stroke:#6d28d9
    classDef api fill:#0891b2,color:#fff,stroke:#0e7490
    class A frontend
    class B state
    class C,D api
```
### Backend Development

```mermaid
flowchart TD
    A[Client] -->|HTTP Request| B[Controller / REST API]
    B --> C[Service / Business Logic]
    C --> D[Repository / Data Access]
    D --> E[(Database)]
    E --> D
    D --> C
    C --> B
    B -->|HTTP Response| A

    classDef api fill:#2563eb,color:#fff,stroke:#1d4ed8
    classDef logic fill:#16a34a,color:#fff,stroke:#15803d
    classDef data fill:#9333ea,color:#fff,stroke:#7e22ce
    class A,B api
    class C logic
    class D,E data
```

### Mobile Development

```mermaid
flowchart TD
    A[Screen / UI] <--> B[State & App Logic]
    B <--> C[(Local Storage)]
    B <--> D[Backend / REST API]
    D <--> E[Remote Services]
    E --> F[Push Notifications]
    F --> A

    classDef ui fill:#2563eb,color:#fff,stroke:#1d4ed8
    classDef logic fill:#16a34a,color:#fff,stroke:#15803d
    classDef data fill:#9333ea,color:#fff,stroke:#7e22ce
    classDef service fill:#ea580c,color:#fff,stroke:#c2410c
    class A ui
    class B logic
    class C,D data
    class E,F service
```

### AI & Automation

```mermaid
flowchart TD
    A[Event / User Input] --> B[Async Handler]
    B --> C[Business Logic]
    C --> D{Task Type}
    D -->|AI Processing| E[AI API / LLM]
    D -->|Automation| F[Automation Workflow]
    E --> G[Response / Action]
    F --> G
    G --> H[(Storage / Logs)]

    I[Python / asyncio] -. Orchestration .-> B

    classDef input fill:#2563eb,color:#fff,stroke:#1d4ed8
    classDef logic fill:#16a34a,color:#fff,stroke:#15803d
    classDef ai fill:#9333ea,color:#fff,stroke:#7e22ce
    classDef output fill:#ea580c,color:#fff,stroke:#c2410c
    class A input
    class B,C,I logic
    class D,E,F ai
    class G,H output
```
    
### Deployment & Infrastructure

```mermaid
flowchart LR
    A[Git / Repository] --> B[Build & Tests]
    B --> C[Deployment]
    C --> D[Linux / Ubuntu]
    D --> E[Running Application]
    E --> F[Logs & Monitoring]

    G[Oracle Cloud Infrastructure] --- D

    classDef code fill:#2563eb,color:#fff,stroke:#1d4ed8
    classDef process fill:#16a34a,color:#fff,stroke:#15803d
    classDef infra fill:#475569,color:#fff,stroke:#334155
    class A code
    class B,C process
    class D,E,F,G infra
```

<br>aving&color=0:30363d,100:0d1117&height=60&section=footer" width="100%" alt="footer" />
