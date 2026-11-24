<div align="center">
  <p><code>amine@dev:~$ whoami</code></p>
  <h1>Mohamed Amine BAICH</h1>
  <p><strong>Développeur full-stack</strong></p>
  <p>Étudiant en ingénierie logicielle à l’ENSIASD · Tantan, Maroc</p>
  <p>
    <a href="#projets">Projets</a> ·
    <a href="#stack">Stack</a> ·
    <a href="#parcours">Parcours</a> ·
    <a href="#contact">Contact</a>
  </p>
</div>

## `$ cat profil.txt`

Je développe des applications de l’API à l’interface. Mes projets couvrent les microservices sécurisés, les interfaces web et mobiles et l’intégration de LLM dans des applications.

**Langues** · Arabe, français et anglais

```diff
+ Ouvert aux opportunités
+ Ouvert aux collaborations
```

<a name="projets"></a>

## `$ ls ~/projets`

### Flowbill · SaaS de facturation B2B

Une plateforme multi-tenant pour suivre les projets, le temps et la facturation. PostgreSQL isole les données dans un schéma par client, avec Flyway pour les migrations. Spring Security contrôle les accès avec JWT et des rôles.

```text
gateway  Spring Cloud Gateway
web      React · TypeScript
styles   Tailwind CSS
runtime  Docker Compose
```

<details>
<summary><strong>Voir l’architecture de Flowbill</strong></summary>

L’interface React appelle l’API Gateway. La passerelle achemine les requêtes vers les cinq microservices, qui utilisent PostgreSQL.

```mermaid
flowchart TD
    accTitle: Architecture de Flowbill
    accDescr: L’interface React passe par Spring Cloud Gateway pour appeler cinq microservices reliés à PostgreSQL.
    UI["React / TypeScript / Tailwind CSS"] --> GW["Spring Cloud Gateway"]
    GW --> S["Microservices<br/>Auth · Tenants · Projets<br/>Temps · Facturation"]
    S --> DB[("PostgreSQL<br/>Un schéma par client · Flyway")]
```

</details>

<!-- TODO Flowbill: remplacer https://github.com/medamine771/NOM_DU_DEPOT par l’URL du dépôt. -->

### Smart CV Analyzer · Extraction et scoring de CV

L’API FastAPI utilise un LLM pour extraire les compétences, les expériences et la formation, puis calcule un score selon des critères définis.

```text
entrée   CV → FastAPI
calcul   Extraction LLM → score
tests    Pytest · Postman
web      React · Tailwind CSS
```

<!-- TODO Smart CV Analyzer: remplacer https://github.com/medamine771/NOM_DU_DEPOT par l’URL du dépôt. -->

### Application mobile · Groupes et messagerie

Une application Flutter pour gérer les groupes et leurs membres et échanger dans une messagerie intégrée. Le backend est conteneurisé avec Docker.

<!-- TODO Application mobile: remplacer https://github.com/medamine771/NOM_DU_DEPOT par l’URL du dépôt. -->

<a name="stack"></a>

## `$ tree ~/stack`

```text
Full-stack
├── Backend
├── Frontend et mobile
├── Données et IA
└── DevOps et qualité
```

- **Backend** · Java, Spring Boot, Spring Security, Spring Cloud Gateway, Python, FastAPI et Laravel.
- **Frontend et mobile** · React, TypeScript, Tailwind CSS et Flutter.
- **Données et IA** · PostgreSQL, MySQL, MongoDB, Redis, intégration de LLM et NLP, OpenCV et Power BI.
- **DevOps et qualité** · Docker, Docker Compose, Git, CI/CD, Maven, Linux, Pytest et Postman.

<a name="parcours"></a>

## `$ git log --oneline`

- **2026** · Smart CV Analyzer chez INITIA SOLUTIONS et plateforme Flowbill.
- **2025** · Application de gestion des actifs informatiques chez OCP avec Laravel.
- **2024** · Modèle NLP d’analyse de sentiments et tableaux de bord Power BI.
- **2023** · Application web de gestion de clubs scolaires avec Laravel et MySQL.

<a name="contact"></a>

## `$ ./contact.sh`

[LinkedIn](https://www.linkedin.com/in/mohamed-amine-baich-7bab5b258) · [E-mail](mailto:mohamedaminebaichh@gmail.com)

<details>
<summary><code>sudo hire amine</code></summary>

```text
Accès accordé.
```

Si tu as un projet en tête, raconte-moi ce que tu construis et le problème que tu veux résoudre.

</details>
