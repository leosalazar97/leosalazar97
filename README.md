<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=90&section=header&text=Leonardo%20Salazar%20Cassano&fontColor=e6edf3&fontSize=30&fontAlignY=55" width="100%" alt="header" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3000&pause=1200&color=8B949E&center=true&vCenter=true&width=520&height=24&lines=Full-Stack+Software+Developer;Java+%C2%B7+Spring+Boot+%C2%B7+React+%C2%B7+Angular+%C2%B7+TypeScript;Python+%26+AI+%C2%B7+Linux+%C2%B7+Cloud" alt="Typing SVG" /></a>

</div>

## Chi sono

Full-Stack Software Developer passionate about building practical software solutions, from intuitive user interfaces to backend logic, database management, and deployment. Experienced in enterprise ERP systems, international Agile teams, web and mobile development, automation, and AI-powered applications. Combining technical skills with a strong interest in UX, design, and problem-solving. Italian, Spanish, and English.

<br>

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

## Why Me?

<details>
<summary><b>Why should you choose me?</b></summary>
<br>

I'm a versatile Full-Stack Developer with hands-on experience across different technologies, projects, and development environments. I've worked on a production ERP system, contributed to web applications in different tech stacks, collaborated with an international team, and built personal projects involving mobile development, Python automation, and cloud deployment.

I adapt to new tools by focusing on the fundamentals that matter: clean code, separation of concerns, problem-solving, and maintainable solutions. I'm looking for a team where I can contribute, take on real challenges, and keep growing as a developer.

</details>

<details>
<summary><b>What value can I bring to your company?</b></summary>
<br>

I can contribute across the development lifecycle, from building user interfaces and implementing business logic to working with databases, integrating APIs, and deploying applications on Linux.

My experience across different stacks helps me understand how the different parts of an application fit together, collaborate effectively with frontend and backend developers, and investigate issues beyond a single layer. Combined with my adaptability, attention to usability, and ability to work in Italian, Spanish, and English, I bring a flexible, collaborative mindset to a development team.

</details>

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

<br>

## Perché scegliere me?

<details>
<summary><b>Perché non mi sono specializzato in una sola tecnologia?</b></summary>
<br>

Perché le tecnologie cambiano e il vantaggio sta nell'adattarsi, più che nel conoscerne una sola a fondo. Ho scelto di toccare stack anche molto diversi tra loro (Java, React, Angular, Python, Supabase, Linux) per imparare cosa resta uguale sotto: modellare i dati, separare le responsabilità, gestire gli errori. Quando arriva uno strumento nuovo, parto da quelle basi.
</details>

<details>
<summary><b>Come lo dimostro, oltre a dirlo?</b></summary>
<br>

Con i fatti: in tre esperienze consecutive ho lavorato con tre stack diversi (Java/JSP/jQuery in un ERP, Angular + Spring Boot in un'app web, React + Supabase a Malta) e dopo la formazione ho aggiunto Python e API OpenAI. In più ho portato un progetto personale fino al deploy su Linux.
</details>

<details>
<summary><b>Che valore porta un profilo che vede tutta la filiera?</b></summary>
<br>

`[DA CONFERMARE CON TE]` Bozza: so cosa succede dall'interfaccia al database fino al server su cui gira il codice. Questo mi aiuta a parlare con colleghi di front-end e back-end, a capire dove nasce un problema e a non fermarmi al mio pezzo.
</details>

<br>

## Contatti

[LinkedIn](#) · [Email](#) · [Portfolio](#)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:30363d,100:0d1117&height=60&section=footer" width="100%" alt="footer" />
