<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=160&section=header&text=Leonardo%20Salazar%20Cassano&fontColor=e6edf3&fontSize=38&fontAlignY=38" width="100%" alt="header" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1200&color=8B949E&center=true&vCenter=true&width=620&lines=Full-Stack+Software+Developer;Java+%C2%B7+Spring+Boot+%C2%B7+React+%C2%B7+Angular+%C2%B7+TypeScript;Python+%26+AI+%C2%B7+Linux+%C2%B7+Cloud" alt="Typing SVG" /></a>

</div>

<br>

## Chi sono

Sviluppatore full-stack, nato a Bergamo, trilingue (spagnolo madrelingua, italiano C2, inglese B2).
Ho lavorato su un ERP in produzione per clienti aziendali, in un team internazionale a Malta e su progetti personali che arrivano fino al deploy su Linux.
Cerco un team in cui crescere su progetti reali.

<br>

## Stack

**Frontend** &nbsp; `React` `Angular` `TypeScript` `JavaScript` `Material UI` `Zustand` `Bootstrap`
**Backend** &nbsp; `Java` `Spring Boot` `REST API` `Python`
**Dati** &nbsp; `MySQL` `SQL` `Supabase (RLS, trigger, realtime)`
**Mobile** &nbsp; `React Native (Expo)`
**Infrastruttura e metodo** &nbsp; `Linux (Ubuntu)` `Oracle Cloud` `Git` `Agile/Scrum`

<p>
  <img src="https://skillicons.dev/icons?i=react,angular,ts,js,java,spring,python,mysql,supabase,linux,git&theme=dark" alt="skills" />
</p>

<br>

## Come penso e come costruisco

### Automation System: automazione per community Telegram

Sistema in Python per gestire in autonomia una community Telegram ad accesso a pagamento: ingresso degli iscritti, controllo della scadenza dell'abbonamento, rimozione automatica alla fine del periodo e invio di messaggi programmati e personalizzati. Gira su un'istanza Oracle Cloud (Ubuntu) che ho configurato e gestisco io.

```mermaid
flowchart LR
    A[Telegram] <--> B[Userbot Python<br/>asyncio]
    B --> C[Gestione iscritti<br/>e scadenze]
    B --> D[Invio messaggi<br/>programmati e personalizzati]
    C --> E[(Persistenza dati)]
    D --> E
    B -. deploy .-> F[Oracle Cloud<br/>Ubuntu / Linux]
```

> `[DA VERIFICARE]` il blocco "Persistenza dati": se usi file, SQLite o altro, lo scrivo con il nome giusto.

### Mobile Reminder & Personal Finance App

App cross-platform in React Native (Expo) per scadenze ricorrenti e contabilità personale (entrate e uscite), con notifiche push e dati salvati in locale.

```mermaid
flowchart LR
    A[UI<br/>React Native + Expo] --> B[Gestione dello stato]
    B --> C[(Local storage)]
    B --> D[Notifiche push<br/>scadenze ricorrenti]
```

### Dove ho usato cosa

```mermaid
flowchart TB
    subgraph SIT[SIT Informatica · ERP in produzione]
        S1[Java · SQL · JSP] --- S2[JavaScript · jQuery · low-code]
    end
    subgraph ROMA[Progetto Roma · app web]
        R1[Angular · Bootstrap] --- R2[Java · Spring Boot · MySQL]
    end
    subgraph MALTA[Born Digital Studios · Malta]
        M1[React · Material UI · Zustand] --- M2[Supabase · RLS · realtime]
    end
    SIT --> ROMA --> MALTA
```

Tre contesti, tre stack diversi, un filo comune: partire dal problema e adattare gli strumenti.

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:30363d,100:0d1117&height=100&section=footer" width="100%" alt="footer" />
