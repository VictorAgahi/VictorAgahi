<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Backend+%26+Systems+Engineer;NestJS+%2F+Fastify+%2F+Rust+%2F+Go;Building+secure%2C+scalable+platforms;Kubernetes+%2B+GitOps+enthusiast" alt="Typing SVG" />
</a>

### Victor Agahi

Backend engineer building distributed, event-driven platforms and polyglot systems — from encrypted data vaults to real-time market intelligence pipelines, self-hosted on Kubernetes.

<p>
  <a href="mailto:victor@agahi.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/VictorAgahi"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/victor-agahi-49b97b292/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## Stack Technique

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**DevOps & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## Projets en Vedette

### [VaultedMind](https://github.com/VictorAgahi/VaultedMind) — Coffre-fort santé mentale, zero-trust

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Application full-stack pour journaliser humeur et réflexions personnelles sans jamais exposer la donnée brute, même en interne.

- **Chiffrement au repos** : chaque champ sensible est chiffré en AES-256-GCM avant persistance ; les emails sont protégés par blind indexing pour permettre une recherche sans exposer le PII.
- **Isolation réseau stricte** : NetworkPolicies Kubernetes garantissant que seul le frontend parle au backend, et seul le backend parle à la base de données.
- **Module IA d'insights** (`ai-insights`) en architecture hexagonale (`domain` / `application` / `infrastructure`) : un `data-sanitizer.service` anonymise les journaux avant tout appel LLM, un `prompt.service` construit les prompts, et un cron génère périodiquement des insights personnalisés.
- **CI/CD & sécurité** : pipelines GitHub Actions avec scan de secrets, déploiement GitOps via ArgoCD/Kustomize.

---

### [SentiGraph Finance](https://github.com/VictorAgahi/sentigraph-finance) — Market intelligence crypto temps réel

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

Architecture microservices polyglotte pensée pour la faible latence, composée de quatre services indépendants reliés par un backbone Redis (DragonflyDB) :

- **Harvester (Rust)** : ingestion haute fréquence des flux WebSocket Binance Futures (ticker, profondeur de marché, liquidations), avec reconnexion automatique à backoff exponentiel.
- **Analyst (Go)** : pool de workers pour l'analyse de sentiment via Ollama, persistance batch dans TimescaleDB, diffusion temps réel par WebSocket.
- **Scout (Go)** : veille RSS multi-sources et Nitter, redirigée vers l'Analyst pour scoring de sentiment.
- **Dashboard (Next.js)** : terminal de monitoring avec `lightweight-charts`, mise à jour sub-seconde pilotée par WebSocket.

---

### [NightQuizz](https://github.com/MasterNIghtQuizz/head) — Plateforme de quiz live, microservices DDD

![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Valkey](https://img.shields.io/badge/Valkey-A41E11?style=flat-square&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

Monorepo Yarn (Fastify + Domain-Driven Design) découpé en cinq services : `api-gateway`, `ms-user`, `ms-quiz-management`, `ms-session`, `ms-response`, plus un `ws-service` dédié au temps réel.

- **Auth zero-trust en cascade** : le gateway vérifie le JWT externe puis mint un token interne signé (RSA) par requête ; chaque microservice le revalide via des hooks Fastify (`hookAccessToken`/`hookInternalToken`) sans jamais faire confiance à un appel direct.
- **Kafka avec idempotence garantie** : chaque événement (`USER_CREATED`, etc.) porte un `eventId` UUID ; les consommateurs le confrontent à une table `processed_events` dans la même transaction TypeORM, assurant un traitement *exactly-once* malgré la sémantique *at-least-once* de Kafka.
- **Valkey** comme cache/broker (fork open-source de Redis) partagé entre les services, déployé via des manifests Kubernetes dédiés (`k8s/services/cache`).
- **Observabilité complète** : OpenTelemetry pour le traçage distribué, Jaeger pour la visualisation des traces, OpenSearch + Dashboards pour la centralisation des logs, et des dashboards Grafana/Prometheus custom.
- **Déploiement** : Docker Compose multi-profils (`infra`/`app`) en local, manifests K8s + overlays ArgoCD pour la prod.

---

### [Volontariapp](https://github.com/Volontariapp/meta) — Écosystème bénévolat, event-driven à l'échelle

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

Méta-repo ("umbrella") orchestrant une douzaine de dépôts indépendants (microservices, workers, app mobile, packages partagés), documentés selon le **modèle C4** (contexte, containers, flux async, déploiement).

- **Transactional Outbox Pattern** : chaque microservice insère sa donnée métier et un job "pending" dans la même transaction ACID Postgres, éliminant le "dual write problem" entre la base et le bus d'événements.
- **Pipeline job → audit → stream** : un `outbox-runner` pousse les jobs vers BullMQ (Redis) ; un `worker` les exécute et journalise le résultat, ce qui déclenche un **trigger SQL automatique** republiant l'événement vers un Redis Stream, consommé à son tour par des `post-processors`.
- **Scatter-Gather orchestré par WebSocket** : à la création d'un événement, plusieurs post-processors indépendants (géocodage, écriture dans le graphe Neo4j `ms-social`) travaillent en parallèle ; le `ws-service` agrège leurs accusés de réception par `correlation_id` et ne notifie le client qu'une fois toutes les étapes confirmées — avec Saga compensatoire (rollback Neo4j) en cas d'échec partiel.
- **gRPC synchrone + Redis asynchrone** : l'API Gateway route les requêtes rapides en gRPC vers les microservices isolés (chacun avec sa propre base Postgres), tandis que tout traitement lourd est délégué à la tuyauterie événementielle.
- **Sécurité GitOps** : cluster K3s en Pod Security Admissions "Restricted" (non-root, read-only filesystem, seccomp), secrets chiffrés via Bitnami Sealed Secrets, Network Policies en default-deny entre domaines.
- **Mobile** : application React Native (Expo 54) consommant ce même écosystème via l'API Gateway.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## Historique de Commits & Activité

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=VictorAgahi&theme=tokyo-night&hide_border=true&area=true" alt="Commit activity graph" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=VictorAgahi&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">

## Statistiques GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=VictorAgahi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VictorAgahi&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=VictorAgahi&color=38BDF8&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%">
