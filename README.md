<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=shark&height=260&color=0:000000,40:1A0B2E,75:FCEE0A,100:FF003C&text=SUHAILI%20FARUQ&fontSize=58&fontColor=FCEE0A&animation=fadeIn&fontAlignY=36&desc=Offline-First%20Mobile%20Engineer%20//%20Flutter%20•%20Kotlin%20•%20React%20Native%20•%20Go&descAlignY=56&descSize=18&descColor=00F0FF"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Rajdhani&weight=700&size=28&pause=1000&color=FCEE0A&center=true&vCenter=true&width=1000&height=100&lines=WAKE+UP%2C+SAMURAI.+THE+SYNC+QUEUE+IS+FULL.;Offline-First+Mobile+%2F%2F+That+Is+The+Job.;Now+at+Reddog+%2F%2F+React+Native+0.87+%2B+Go+gRPC.;7+Apps+Shipped+%2F%2F+Play+Store+%2B+App+Store.;Claude+Code+%2F%2F+Plan.+Build.+Test.+Debug.)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-FCEE0A?style=for-the-badge&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/suhaili-faruq-8475a0189/)
[![Gmail](https://img.shields.io/badge/EMAIL-FF003C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suhaili.faruq01@gmail.com)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00F0FF?style=for-the-badge&logo=firefoxbrowser&logoColor=black)](https://portfolioweb-55f91.web.app/)

<sub><code>[ NODE: JAKARTA, ID ]  [ CURRENT GIG: REDDOG ]  [ CLASS: NETRUNNER / MOBILE ]  [ STATUS: SHIPPING ]</code></sub>

</div>

---

# // 01 :: ABOUT_ME.dart

```dart
class Developer {
  final String name = "Suhaili Faruq";
  final String role = "Mobile Engineer @ Reddog";
  final String location = "Jakarta, Indonesia";
  final int yearsOfExperience = 4;

  // Three stacks, all shipped to production. No favourites on the CV.
  final List<String> mobile = [
    "Flutter (Riverpod, BLoC)",
    "Kotlin (Native Android, Compose, KMP)",
    "React Native (bare 0.87, Nitro modules, Re.Pack)",
  ];

  // Side projects, one freelance deploy, and the Go services at Reddog.
  final List<String> backend = [
    "Go (Fiber v3, Gin, gRPC)",
    "Kotlin (Ktor)",
    "PostgreSQL",
    "Redis",
    "Docker, Nginx, VPS",
  ];

  // The agent in my terminal: plans, code, tests, and bug hunts.
  final String cyberdeck = "Claude Code";

  final String focus =
      "Offline-first mobile apps with sync that survives a dead connection, "
      "backed by REST services I can build and deploy myself.";

  final int appsPublished = 7; // Play Store + App Store

  bool canOwnTheApiContract() => true; // both ends of it

  String mindset() => "Build clean. Build scalable. Keep learning.";
}
```

Four years of shipping mobile apps for mall loyalty programs, city government tax
services, network operations tooling, batik e-commerce, heavy equipment field
inspection, and now food ordering.

The through line is offline-first. Every app I care about had to keep working when the
signal died, so I have written the same queued-sync problem three times over in Realm,
Room, and SQLite. Flutter, Kotlin, and React Native are all in production under my name.
Which one a project uses matters less to me than whether the data survives the tunnel.

I also write the service the app talks to. Go Fiber and Ktor, PostgreSQL, Redis, deployed
to a VPS I keep alive myself. That is not a second career, it is the reason I stopped
arguing with backend engineers about pagination.

---

# // 02 :: CURRENT.GIG // REDDOG

<sub><code>[ ACTIVE CONTRACT // MOBILE ENGINEER // PRIVATE REPOS // APPS IN INTERNAL TESTING ]</code></sub>

<div align="center">
<img src="https://img.shields.io/badge/React_Native-0.87_Bare-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Nx_+_pnpm-Monorepo-FCEE0A?style=for-the-badge&logo=nx&logoColor=black&labelColor=000000"/>
<img src="https://img.shields.io/badge/Go-gRPC_Services-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka_+_Elasticsearch-000000?style=for-the-badge&logo=apachekafka&logoColor=FF003C"/>
</div>

<br/>

Reddog is a food ordering platform. Customers order from outlets in one app, outlet staff
take the orders in another, and admins run the menu, vouchers, payments, and staff from a
web backoffice. I work on the product team across all three apps and the Go backend
behind them.

| Repo | What it is | Stack | Source |
|---|---|---|---|
| **reddog-application** | Nx monorepo: customer app, outlet staff app, and admin backoffice on one shared API and auth layer | React Native 0.87 (bare), React 19, Vite, TanStack Router + Query, zod, Nitro native modules | [repo](https://github.com/Reddog-Technology-Team/reddog-application) `private` |
| **reddog-backend** | Seven gRPC services behind one REST gateway. Writes go through an outbox to Kafka; reads come from Elasticsearch projections | Go 1.27, gRPC + buf, Gin, PostgreSQL, Kafka, Elasticsearch, Redis, OpenTelemetry | [repo](https://github.com/Reddog-Technology-Team/reddog-backend) `private` |

What I have shipped there so far:

- **Force update** for the customer and outlet apps, driven by a version config endpoint I added to the gateway.
- **Voucher rules end to end**: re-checked at checkout and charge, minimum spend measured before tax, expired voucher sends blocked, zero-total checkouts settled.
- **Role-based access**: role and admin writes limited to superadmin in the gateway and the backoffice, with actions shown by permission.
- **Safe deletes**: staff and outlets can't be retired while orders are in flight; permanent outlet delete and soft-deleted staff.
- **Live order state**: order status and outlet hours resync on focus, off-screen queries pause, and outlet stats roll over at WIB midnight.
- **Device polish**: iOS deep links on a running app, edge-to-edge safe areas, keyboard overlap in sheets, and Rupiah decimals.

The client and outlet apps are in internal testing ahead of their store release.

---

# // 03 :: SHIPPED.APPS

<sub><code>[ GIG LOG // ORDERED BY RECENCY, NOT BY STACK ]</code></sub>

Seven apps published to the Play Store and App Store, plus COIP, an enterprise app for
United Tractors. Reddog's two apps join this list when they leave internal testing.

| App | Platform | Stack | Source |
|---|---|---|---|
| **COIP Mobile** (United Tractors) \* | Android, iOS | React Native 0.74, Realm, TanStack Query, Zustand | [repo](https://github.com/FaaStatic/project_coip) `private` |
| **ForYou** (Sinarmas Land) | Android, iOS | Flutter, Riverpod, Clean Architecture | [repo](https://github.com/FaaStatic/foryou-sinarmasland-source) |
| **MyKekancan** | Android, iOS | Flutter, Riverpod, Google Maps | [repo](https://github.com/FaaStatic/myKekancan-app-source) |
| **NMSxPro Mobile** | Android, iOS | Flutter, BLoC, on-device SSH client | [repo](https://github.com/FaaStatic/nmsmobile-source) |
| **Nexa Ticket Scanner** | Android | Flutter, barcode / QR scanning | `private` |
| **Hebat!** (Semarang City Gov) | Android, iOS | React Native, Redux Toolkit | [repo](https://github.com/FaaStatic/hebat-apps-source) |
| **Kla Computer** (Infokom) | Android, iOS | React Native, Redux Toolkit, FCM | [repo](https://github.com/FaaStatic/infokom-mobile-source) |
| **Naratik** (Batik e-commerce) | Android | Kotlin, Hilt, Room, WorkManager, CNN model | [repo](https://github.com/FaaStatic/naratik-mobile-source) |

<sub>\* COIP Mobile is an enterprise app distributed to United Tractors customers. The seven store-published apps are the rest. <code>private</code> marks client source that stays closed; the link works for people with access.</sub>

---

# // 04 :: MOBILE.EXE

### ▚ Flutter

<sub><code>[ 4 PUBLISHED APPS // 2022 TO 2024 ]</code></sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=flutter,dart"/>
<br/><br/>
<img src="https://img.shields.io/badge/Flutter-Production-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Riverpod-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/BLoC-1A0B2E?style=for-the-badge&logo=flutter&logoColor=FCEE0A"/>
<img src="https://img.shields.io/badge/Clean_Architecture-FCEE0A?style=for-the-badge&labelColor=000000"/>
</div>

Four of the seven published apps are Flutter, across loyalty, maps, and network operations.
NMSxPro ships an on-device SSH client so field technicians can run commands against network
equipment straight from the phone. Riverpod 2 and Clean Architecture on ForYou and
MyKekancan, BLoC on NMSxPro.

My current Flutter side project is [**Shop POS**](https://github.com/FaaStatic/POS_project_FE),
a Melos monorepo with two apps on one shared core: a web CMS for the shop owner and an
offline-first cashier app for Android and iOS. Cashiers keep several sale tabs open at once,
take QRIS and VA payments, and print receipts to a Bluetooth thermal printer. BLoC and Clean
Architecture throughout, with an 80% coverage gate on the domain, data, and bloc layers.

### ▚ Kotlin

<sub><code>[ NATIVE ANDROID SINCE 2021 // PLUS KOTLIN MULTIPLATFORM ]</code></sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,java"/>
<br/><br/>
<img src="https://img.shields.io/badge/Kotlin-Native_Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/Hilt_+_Room-3DDC84?style=for-the-badge&logo=android&logoColor=black"/>
<img src="https://img.shields.io/badge/Kotlin_Multiplatform-FCEE0A?style=for-the-badge&logo=kotlin&logoColor=black"/>
</div>

Where I started, and where I still go when a problem wants the platform directly. Naratik is
native Kotlin with Hilt, Room, DataStore, and WorkManager background sync, plus a CNN
authenticity checker from a paper I co-authored. KMP Todo shares domain models between an
Android and iOS Compose client and a Ktor backend, so the whole thing is one language end
to end.

### ▚ React Native

<sub><code>[ 2 PUBLISHED APPS // COIP // REDDOG IN TESTING ]</code></sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=react,ts"/>
<br/><br/>
<img src="https://img.shields.io/badge/React_Native-Production-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
<img src="https://img.shields.io/badge/Zustand-FCEE0A?style=for-the-badge&labelColor=000000&logoColor=black"/>
<img src="https://img.shields.io/badge/Re.Pack_+_Rspack-FF003C?style=for-the-badge&labelColor=000000"/>
<img src="https://img.shields.io/badge/NativeWind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Redux_Toolkit-6441AA?style=for-the-badge&logo=redux&logoColor=white"/>
</div>

Hebat! for the Semarang city government and Kla Computer for Infokom, both Redux Toolkit.
At PT United Tractors Tbk I built COIP Mobile: a typed API layer generated from the backend
OpenAPI spec with Kubb, so there was no hand-written client code and no schema drift.
Conditional validation across 100+ fields in multi-tab checksheets, and around 100 unit and
UI tests with Jest and RNTL. At Reddog I work on bare React Native 0.87 with Nitro native
modules, two apps sharing one UI library inside an Nx monorepo.

### ▚ Offline-first

The part I would actually put on a business card. Realm on COIP, Room plus WorkManager on
Naratik, drift on the Shop POS cashier, SQLite elsewhere. Jobs get created with no signal,
photo evidence queues up, and everything reconciles when the technician walks back out of the
basement. On the POS, cash and credit sales keep going through an outage under an offline
receipt number, then sync in batches when the connection returns or at noon and midnight.
Nothing is lost in between, which sounds obvious until you have shipped it.

---

# // 05 :: BACKEND.PROTOCOL

<div align="center">
<img src="https://skillicons.dev/icons?i=go,kotlin,postgres,redis,docker,firebase"/>
<br/><br/>
<img src="https://img.shields.io/badge/Go_Fiber_v3-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/Kotlin_Ktor-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-FF003C?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker_+_Nginx-000000?style=for-the-badge&logo=docker&logoColor=00F0FF"/>
</div>

| Project | What it is | Stack |
|---|---|---|
| [**Shop POS Backend**](https://github.com/FaaStatic/POS_System_Project_BE) | POS API: products, transactions, debt tracking, Excel and PDF report export. Deployed to a Linux VPS with Docker Compose and Nginx. | Go Fiber v3, GORM, PostgreSQL, Redis, Cobra CLI migrations |
| [**KMP Todo**](https://github.com/FaaStatic/kmp_todo_app) | Full-stack Kotlin. Compose Multiplatform client sharing domain models with a Ktor backend. JWT with refresh tokens, BCrypt, Swagger. | Kotlin Multiplatform, Ktor, Exposed, PostgreSQL |
| [**Local CDN**](https://github.com/FaaStatic/local_cdn_go) | Small self-hosted static asset server. | Go |
| [**LMS Inkaedu**](https://github.com/FaaStatic/web-lms-inkaedu-source) | Learning platform for AMDAL certification training. I deployed both frontend and backend to production; 100 active users at launch. | React 18, Redux Toolkit |

Most of this is side-project and freelance work. At Reddog I also ship changes in the Go
gateway and services (see // 02). What it buys me is the other end of the API contract. On
COIP the typed client came straight from the OpenAPI spec, so the schema was the contract.
On KMP Todo the client and the server share the same domain models in the same language.
And the POS service is one I actually run, with both
[client apps](https://github.com/FaaStatic/POS_project_FE) built against it, which is how I
ended up learning Certbot, Nginx, and Docker Compose the hard way.

Hire me for mobile. The backend means you will not spend a sprint explaining why the endpoint
is shaped that way.

---

# // 06 :: AI.CYBERDECK

<div align="center">
<img src="https://img.shields.io/badge/Claude_Code-Agent-D97757?style=for-the-badge&logo=claude&logoColor=white"/>
<img src="https://img.shields.io/badge/CLAUDE.md-Project_Rules-FCEE0A?style=for-the-badge&labelColor=000000"/>
<img src="https://img.shields.io/badge/MCP-Context7_Docs-00F0FF?style=for-the-badge&labelColor=000000"/>
<img src="https://img.shields.io/badge/Hooks-Command_Gates-FF003C?style=for-the-badge&labelColor=000000"/>
</div>

<br/>

I run Claude Code as an agent in my terminal, as an assistant for the whole loop: it plans
the change with me, writes code against tests, runs the checks, and traces bugs to their
cause. Shop POS went through it end to end, from the plan for each feature to the fixes
after device testing. At Reddog my bug tickets go through the same loop.

```text
> BREACH_PROTOCOL :: daily loop
──────────────────────────────────────────────────────────────────────
[01] PLAN    read the repo, draft the change, list every file it touches
[02] BUILD   failing test first, then the minimum code, then refactor
[03] TEST    analyze, unit and widget tests, coverage gate before commit
[04] DEBUG   reproduce, trace the root cause, fix it once at the source
──────────────────────────────────────────────────────────────────────
```

Each repo carries a `CLAUDE.md` with its architecture rules, folder map, and commands, so
the agent layers code the way the project expects. Context7 feeds it docs for the exact
library version in the lockfile, not the version the model remembers. Hooks make it state
what a shell command or a new file is for before it runs.

---

# // 07 :: PUBLICATION

**Classification of Batik Authenticity Using Convolutional Neural Network Algorithm with Transfer Learning Method**
2021 Sixth International Conference on Informatics and Computing (ICIC), IEEE, Nov 2021, pp. 1 to 6.
[DOI: 10.1109/ICIC54025.2021.9632937](https://doi.org/10.1109/ICIC54025.2021.9632937)

The model from this paper became the authenticity checker inside the Naratik Android app.

---

# // 08 :: CURRENT.FOCUS

```yaml
Mobile:
  - Flutter: Riverpod, BLoC, Clean Architecture
  - Kotlin: Compose, KMP, Hilt
  - React Native: bare 0.87, Nitro modules, Re.Pack + Rspack

Architecture:
  - Clean Architecture
  - MVVM
  - Offline-first sync (Realm, Room, SQLite, drift)
  - Nx and Melos monorepos

Backend:
  - Go: Fiber v3, Gin, gRPC
  - PostgreSQL, Redis, Kafka, Elasticsearch
  - Docker, Nginx, CI/CD

AI Workflow:
  - Claude Code: plan, build, test, debug
  - CLAUDE.md project rules, MCP (Context7), hooks
```

---

<details>
<summary><b>// ARCHIVE</b> (older and smaller work)</summary>

<br/>

- [Survey Apps](https://github.com/FaaStatic/project-survey-app-source) - Flutter
- [Semargress 2022](https://github.com/FaaStatic/semargress2022-source) - React Native
- [Money Expense Tracker](https://github.com/FaaStatic/moneyexpensetracker) - Flutter
- [Portfolio Web](https://github.com/FaaStatic/portfolioapps) - Flutter Web
- [Github Apps](https://github.com/FaaStatic/GithubApp) - Kotlin
- [Cashier Bookstore](https://github.com/FaaStatic/project-cashier-book-source) - Java Swing
- [Village Admin System](https://github.com/FaaStatic/proyek-sistem-desa-source) - CodeIgniter 4

</details>

---

# // 09 :: DATA.ANALYTICS

<div align="center">
<img src="https://streak-stats.demolab.com?user=FaaStatic&theme=transparent&hide_border=true&ring=FCEE0A&fire=FF003C&currStreakLabel=FCEE0A&sideNums=FFFFFF&currStreakNum=00F0FF&dates=AAAAAA"/>
</div>

---

# // 10 :: NETRUNNER.TRACE

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile/snake-light.svg" />
    <img alt="Contribution snake" src="./profile/snake-dark.svg" width="100%"/>
  </picture>
</div>

---

# // 11 :: JACK.IN

<div align="center">

<a href="https://www.linkedin.com/in/suhaili-faruq-8475a0189/">
  <img src="https://img.shields.io/badge/LINKEDIN-FCEE0A?style=for-the-badge&logo=linkedin&logoColor=black"/>
</a>
<a href="mailto:suhaili.faruq01@gmail.com">
  <img src="https://img.shields.io/badge/GMAIL-FF003C?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://portfolioweb-55f91.web.app/">
  <img src="https://img.shields.io/badge/PORTFOLIO-00F0FF?style=for-the-badge&logo=firefoxbrowser&logoColor=black"/>
</a>

<br/><br/>

<sub><code>[ CONNECTION CLOSED // SEE YOU IN NIGHT CITY ]</code></sub>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=shark&height=140&section=footer&color=0:FF003C,40:FCEE0A,100:000000"/>

</div>
