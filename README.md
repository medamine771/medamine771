<div align="center">

<img src="assets/header.svg" alt="Terminal animé : whoami, Mohamed Amine BAICH, Développeur Full-Stack, ouvert aux opportunités" width="100%"/>

</div>

```text
 █████╗ ███╗   ███╗██╗███╗   ██╗███████╗
██╔══██╗████╗ ████║██║████╗  ██║██╔════╝
███████║██╔████╔██║██║██╔██╗ ██║█████╗
██╔══██║██║╚██╔╝██║██║██║╚██╗██║██╔══╝
██║  ██║██║ ╚═╝ ██║██║██║ ╚████║███████╗
╚═╝  ╚═╝╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝╚══════╝
        Du backend au frontend
```

---

## ⚙️ `systemctl start amine.service`

<div align="center">

<img src="assets/boot.svg" alt="Journal de démarrage animé : Java, microservices, Docker, FastAPI, React, puis prêt à collaborer" width="100%"/>

</div>

```bash
amine@dev:~$ cat about.txt
Je conçois et livre des applications web full-stack, de l'API à l'interface :
services REST, microservices, interfaces React / TypeScript et déploiement
avec Docker. Je m'intéresse aussi à l'intégration d'IA (LLM, NLP).

amine@dev:~$ neofetch
  ┌──────────────────────────────────────────────┐
  │  OS        : Linux / Windows                 │
  │  Base      : Tantan, Maroc 🇲🇦                 │
  │  Formation : Ingénierie Logicielle · ENSIASD │
  │  Langues   : Arabe · Français · English      │
  │  Éditeur   : VS Code / IntelliJ              │
  │  Focus     : Spring Boot · FastAPI · React   │
  │  Statut    : Ouvert aux opportunités         │
  └──────────────────────────────────────────────┘
```

---

## 📊 `htop`

<div align="center">

<img src="assets/skills-htop.svg" alt="Panneau façon htop : niveau de focus auto-évalué en Backend, Frontend, DevOps, IA et Data, et liste des technologies utilisées" width="100%"/>

</div>

---

## 📦 `ls ~/stack`

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</div>

<details>
<summary><code>$ cat stack.md</code> · voir le détail</summary>
<br/>

**Langages :** Java · Python · JavaScript · TypeScript · PHP · C / C++

**Backend :** Spring Boot (Security, Cloud Gateway) · FastAPI · Laravel · API REST · JWT · Microservices

**Frontend & Mobile :** React · TypeScript · Tailwind CSS · Flutter

**Bases de données :** PostgreSQL · MySQL · MongoDB · Redis

**DevOps & Outils :** Docker · Docker Compose · Git / GitHub · CI/CD · Maven · Linux · Pytest · Postman

**IA & Data :** Intégration de LLM · NLP · Machine Learning · OpenCV · Power BI

</details>

---

## 🐳 `docker ps`

```text
CONTAINER      IMAGE                  STATUS         PORTS / ROLE
a1f3c9d2e801   flowbill               Up 2026        microservices · gateway · PostgreSQL
b7e20c44d9a3   smart-cv-analyzer      Up 2026        FastAPI → LLM → score
c93d1a7f5b62   mobile-groupes         Up             Flutter · chat · Docker
d04e8b21c7f9   opportunites           Up (healthy)   ouvert aux collaborations
```

---

## 🗂️ `cd ~/projets`

<details open>
<summary><code>$ cd flowbill</code> · <b>Flowbill</b>, plateforme SaaS multi-tenant (B2B)</summary>
<br/>

<div align="center">

<img src="assets/flowbill-architecture.svg" alt="Architecture de Flowbill : React, Spring Cloud Gateway, microservices auth, tenants, projets, temps, facturation, puis PostgreSQL" width="100%"/>

</div>

```yaml
# docker-compose.yml (aperçu)
services:
  gateway:    # Spring Cloud API Gateway · JWT + rôles (Spring Security)
  auth:       # authentification
  tenants:    # gestion des clients
  projets:    # projets
  temps:      # suivi du temps
  facturation:# facturation
  postgres:   # un schéma par client · migrations Flyway
  frontend:   # React / TypeScript / Tailwind CSS
```

`Java 17` `Spring Boot 3` `React` `TypeScript` `PostgreSQL` `Docker`

👉 [Ouvrir le dépôt](https://github.com/medamine771/NOM_DU_DEPOT) <!-- TODO: remplacer NOM_DU_DEPOT -->

</details>

<details>
<summary><code>$ cd smart-cv-analyzer</code> · <b>Smart CV Analyzer</b>, scoring automatique de CV</summary>
<br/>

```json
{
  "name": "smart-cv-analyzer",
  "pipeline": ["API FastAPI", "LLM (extraction)", "calcul du score"],
  "input": "un CV",
  "output": ["compétences", "expériences", "formation", "score"],
  "tests": ["Pytest", "Postman"],
  "frontend": "React / Tailwind CSS"
}
```

`Python` `FastAPI` `LLM` `React` `Tailwind CSS`

👉 [Ouvrir le dépôt](https://github.com/medamine771/NOM_DU_DEPOT) <!-- TODO: remplacer NOM_DU_DEPOT -->

</details>

<details>
<summary><code>$ cd mobile-groupes</code> · <b>Application mobile de gestion de groupes avec chat</b></summary>
<br/>

```text
Fonctions : gestion des membres et des groupes, messagerie intégrée
Backend   : containerisé avec Docker
```

`Flutter` `Docker`

👉 [Ouvrir le dépôt](https://github.com/medamine771/NOM_DU_DEPOT) <!-- TODO: remplacer NOM_DU_DEPOT -->

</details>

---

## 🚀 `cat .github/workflows/ci.yml`

<div align="center">

<img src="assets/pipeline.svg" alt="Pipeline CI/CD illustré : lint, test, build, docker, deploy" width="100%"/>

</div>

---

## 🧭 `git log --oneline`

```mermaid
timeline
    title Mon parcours de développeur
    2023 : Application web de gestion de clubs scolaires (Laravel, MySQL)
    2024 : Modèle NLP d'analyse de sentiments + tableaux de bord Power BI
    2025 : Application de gestion des actifs informatiques chez OCP (Laravel)
    2026 : Smart CV Analyzer chez INITIA SOLUTIONS (FastAPI, LLM, React)
         : Flowbill, plateforme SaaS en microservices
```

---

## 🐍 `./snake.sh`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/medamine771/medamine771/output/github-snake-dark.svg"/>
  <img alt="Serpent animé qui mange mes contributions GitHub" src="https://raw.githubusercontent.com/medamine771/medamine771/output/github-snake.svg" width="100%"/>
</picture>

</div>

---

## 📊 `./stats.sh`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=medamine771&show_icons=true&theme=github_dark&hide_border=true&count_private=true&title_color=3fb950&icon_color=3fb950" alt="Statistiques GitHub"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=medamine771&layout=compact&theme=github_dark&hide_border=true&title_color=3fb950" alt="Langages principaux"/>

</div>

---

## ⏰ `crontab -l`

```cron
# m h  dom mon dow   commande
0  *  *   *   *     apprendre quelque chose de nouveau
0  9  *   *   1-5   docker compose up -d && git pull
30 18 *   *   1-5   git commit -m "feat: ship it"
@reboot              echo "Du backend au frontend"
```

---

## 📖 `man amine`

<details>
<summary><code>$ man amine</code> · ouvrir la page de manuel</summary>

```text
AMINE(1)                  Manuel du développeur                  AMINE(1)

NOM
       amine - développeur full-stack, du backend au frontend

SYNOPSIS
       amine [--backend] [--frontend] [--docker] [--ia]

DESCRIPTION
       Conçoit et livre des applications web full-stack : API REST,
       microservices, interfaces React / TypeScript, déploiement Docker.
       S'intéresse à l'intégration d'IA (LLM, NLP).

OPTIONS
       --backend    Spring Boot, FastAPI, Laravel
       --frontend   React, TypeScript, Tailwind CSS, Flutter
       --docker     Docker, Docker Compose, CI/CD
       --ia         LLM, NLP, OpenCV, Power BI

VOIR AUSSI
       flowbill(1), smart-cv-analyzer(1), mobile-groupes(1)

AUTEUR
       Mohamed Amine BAICH · Tantan, Maroc

                               2026                              AMINE(1)
```

</details>

---

## 📡 `./contact.sh`

```bash
amine@dev:~$ ./contact.sh
> Ouvert aux opportunités professionnelles et aux collaborations.
```

<details>
<summary><code>$ sudo hire amine</code></summary>

```bash
[sudo] mot de passe pour recruteur : ********
Vérification des compétences ......... [  OK  ]
Vérification de la motivation ........ [  OK  ]
Envoi de la proposition .............. [  OK  ]

✔ Excellente décision. Contactez-moi via LinkedIn ou par email ci-dessous.
```

</details>

<div align="center">

<a href="https://www.linkedin.com/in/mohamed-amine-baich-7bab5b258"><img src="https://img.shields.io/badge/LinkedIn-mohamed--amine--baich-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Profil LinkedIn"/></a>
<a href="mailto:mohamedaminebaichh@gmail.com"><img src="https://img.shields.io/badge/Gmail-mohamedaminebaichh@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Envoyer un email"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=medamine771&label=Visites%20du%20profil&color=238636&style=flat-square" alt="Compteur de visites"/>

</div>
