<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&amp;color=0:0D1117,100:087F5B&amp;height=144&amp;section=header&amp;text=amine%40dev%3A~%24&amp;fontSize=50&amp;fontColor=F0FDF4&amp;fontAlignY=52" width="100%" alt="Invite de commande amine@dev" />

  <h1>Mohamed Amine BAICH</h1>
  <p><strong>Développeur full-stack · Ingénierie logicielle</strong></p>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=600&amp;size=19&amp;duration=2600&amp;pause=1000&amp;repeat=false&amp;color=56D98F&amp;center=true&amp;vCenter=true&amp;width=650&amp;height=44&amp;lines=%24+whoami;%24+ls+~%2Fprojets;%24+git+log+--oneline" />
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=600&amp;size=19&amp;duration=2600&amp;pause=1000&amp;repeat=false&amp;color=067647&amp;center=true&amp;vCenter=true&amp;width=650&amp;height=44&amp;lines=%24+whoami;%24+ls+~%2Fprojets;%24+git+log+--oneline" alt="Commandes du portfolio : whoami, ls et git log" width="650" height="44" />
  </picture>

  <p>
    <a href="#projets">Projets</a> ·
    <a href="#stack">Stack</a> ·
    <a href="#parcours">Parcours</a> ·
    <a href="https://www.linkedin.com/in/mohamed-amine-baich-7bab5b258">LinkedIn</a>
  </p>
</div>

## `whoami`

Je conçois et livre des applications web de l’API à l’interface. Je travaille sur des services REST et des microservices, des interfaces React / TypeScript et leur déploiement avec Docker. J’explore aussi l’intégration de LLM et le traitement de données avec PySpark.

```text
amine@dev:~$ cat profil.txt
Base       TanTan, Maroc
Formation  Ingénierie logicielle · ENSIASD
Langues    Arabe · Français · Anglais
Éditeurs   VS Code · IntelliJ IDEA
```

## Projets

### `$ cd ~/projets/movielens-pyspark`

**Quel film recommander ensuite ?** Un pipeline PySpark exploite **100 836 notes** MovieLens pour proposer à chacun des **610 utilisateurs** dix films qu’il n’a pas encore notés.

```text
amine@dev:~/projets/movielens-pyspark$ python recommend.py --user 1
```

| Sur les notes les plus récentes | ALS | Popularité |
| --- | ---: | ---: |
| Précision@10 | 0,74 % | **5,62 %** |
| Utilisateurs avec au moins un film pertinent dans le top 10 | 6,43 % | **31,13 %** |

Sur ce test, le classement par popularité retrouve plus souvent un film pertinent que le modèle ALS. Les deux méthodes utilisent le même historique d’entraînement.

[Voir le dépôt MovieLens →](https://github.com/medamine771/movielens-pyspark)

<details>
<summary><code>cd flowbill</code> · <strong>Facturation SaaS multi-tenant</strong></summary>

Flowbill réunit l’authentification, les clients, les projets, le suivi du temps et la facturation derrière une passerelle Spring Cloud. Chaque client possède son propre schéma PostgreSQL, géré avec Flyway. Les accès sont contrôlés par rôles avec Spring Security et JWT.

`Java 17` · `Spring Boot 3` · `React / TypeScript` · `Tailwind CSS` · `Docker Compose`

</details>

<details>
<summary><code>cd smart-cv-analyzer</code> · <strong>Extraction et évaluation de CV</strong></summary>

Un LLM extrait les compétences, les expériences et la formation. L’application calcule ensuite un score selon des critères définis. L’API est testée avec Pytest et Postman.

`Python` · `FastAPI` · `LLM` · `React` · `Tailwind CSS`

</details>

<details>
<summary><code>cd mobile-groupes</code> · <strong>Gestion de groupes et messagerie</strong></summary>

Une application Flutter pour gérer les groupes et leurs membres, avec une messagerie intégrée et un backend conteneurisé avec Docker.

`Flutter` · `Docker`

</details>

**Autres dépôts publics** · [E-commerce en microservices](https://github.com/medamine771/ecommerce-microservices) · [Projet ETL](https://github.com/medamine771/etl_project) · [Gestion des actifs](https://github.com/medamine771/asset-management)

## Stack

<p>
  <img src="https://img.shields.io/badge/Java-1F2937?style=flat-square&amp;logo=openjdk&amp;logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-1F2937?style=flat-square&amp;logo=springboot&amp;logoColor=6DB33F" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Python-1F2937?style=flat-square&amp;logo=python&amp;logoColor=FFD54F" alt="Python" />
  <img src="https://img.shields.io/badge/React-1F2937?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/PySpark-1F2937?style=flat-square&amp;logo=apachespark&amp;logoColor=FF8A65" alt="PySpark" />
  <img src="https://img.shields.io/badge/Docker-1F2937?style=flat-square&amp;logo=docker&amp;logoColor=60A5FA" alt="Docker" />
</p>

<details>
<summary><code>ls ~/stack</code> · Technologies par domaine</summary>

| Domaine | Technologies |
| --- | --- |
| Langages | Java, Python, JavaScript, TypeScript, PHP, C, C++ |
| Backend | Spring Boot, Spring Security, Spring Cloud Gateway, FastAPI, Laravel, REST, JWT |
| Interfaces | React, TypeScript, Tailwind CSS, Flutter |
| Données et IA | PostgreSQL, MySQL, MongoDB, Redis, PySpark, LLM, NLP, OpenCV, Power BI |
| Tests et déploiement | Pytest, Postman, Docker, Docker Compose, Git, GitHub, CI/CD, Maven, Linux |

</details>

## Parcours

```text
amine@dev:~$ git log --oneline
```

- **2026** · Smart CV Analyzer chez INITIA SOLUTIONS et Flowbill en microservices.
- **2025** · Application de gestion des actifs informatiques chez OCP avec Laravel.
- **2024** · Analyse de sentiments avec NLP et tableaux de bord Power BI.
- **2023** · Application de gestion de clubs scolaires avec Laravel et MySQL.

## Contact

Ouvert aux opportunités professionnelles et aux collaborations.

[LinkedIn](https://www.linkedin.com/in/mohamed-amine-baich-7bab5b258) · [E-mail](mailto:mohamedaminebaichh@gmail.com)
