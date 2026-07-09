<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0A0005,30:1C0035,70:FFE81A,100:0D0D0D&text=SUHAILI%20FARUQ&fontSize=55&fontColor=FFE81A&animation=fadeIn&fontAlignY=38&desc=Offline-First%20Mobile%20Engineer%20•%20Flutter%20•%20Kotlin%20•%20React%20Native%20•%20Go%20Backend&descAlignY=58&descSize=18&descColor=FF003C"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=26&pause=1000&color=FFE81A&center=true&vCenter=true&width=1000&height=100&lines=Offline-First+Mobile+%2F%2F+That+Is+The+Job.;Flutter+%7C+Kotlin+%7C+React+Native.;7+Apps+Shipped+%2F%2F+Play+Store+%2B+App+Store.;Realm+%7C+Room+%7C+SQLite+%2F%2F+Sync+That+Survives.;Go+Fiber+%2F%2F+Backend+Services.)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-FFE81A?style=for-the-badge&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/suhaili-faruq-8475a0189/)
[![Gmail](https://img.shields.io/badge/EMAIL-FF003C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suhaili.faruq01@gmail.com)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logo=firefoxbrowser&logoColor=black)](https://portfolioweb-55f91.web.app/)

</div>

---

# 🧬 ABOUT_ME.dart

```dart
class Developer {
  final String name = "Suhaili Faruq";
  final String role = "Mobile Engineer";
  final String location = "Jakarta, Indonesia";
  final int yearsOfExperience = 4;

  // Three stacks, all shipped to production. No favourites on the CV.
  final List<String> mobile = [
    "Flutter (Riverpod, BLoC)",
    "Kotlin (Native Android, Compose, KMP)",
    "React Native (Expo, New Architecture, Re.Pack)",
  ];

  // Side projects and one freelance deploy. Not a job title. Yet.
  final List<String> backend = [
    "Go (Fiber v3)",
    "Kotlin (Ktor)",
    "PostgreSQL",
    "Redis",
    "Docker, Nginx, VPS",
  ];

  final String focus =
      "Offline-first mobile apps with sync that survives a dead connection, "
      "backed by REST services I can build and deploy myself.";

  final int appsPublished = 7; // Play Store + App Store

  bool canOwnTheApiContract() => true; // both ends of it

  String mindset() => "Build clean. Build scalable. Keep learning.";
}
```

Four years of shipping mobile apps for mall loyalty programs, city government tax
services, network operations tooling, batik e-commerce, and heavy equipment field
inspection.

The through line is offline-first. Every app I care about had to keep working when the
signal died, so I have written the same queued-sync problem three times over in Realm,
Room, and SQLite. Flutter, Kotlin, and React Native are all in production under my name.
Which one a project uses matters less to me than whether the data survives the tunnel.

I also write the service the app talks to. Go Fiber and Ktor, PostgreSQL, Redis, deployed
to a VPS I keep alive myself. That is not a second career, it is the reason I stopped
arguing with backend engineers about pagination.

---

# 📱 SHIPPED.APPS

Seven apps published to the Play Store and App Store, plus the enterprise app I build today.
Ordered by recency, not by stack.

| App | Platform | Stack | Source |
|---|---|---|---|
| **COIP Mobile** (United Tractors) \* | Android, iOS | React Native 0.74, Realm, TanStack Query, Zustand | [repo](https://github.com/FaaStatic/project_coip) |
| **ForYou** (Sinarmas Land) | Android, iOS | Flutter, Riverpod, Clean Architecture | [repo](https://github.com/FaaStatic/foryou-sinarmasland-source) |
| **MyKekancan** | Android, iOS | Flutter, Riverpod, Google Maps | [repo](https://github.com/FaaStatic/myKekancan-app-source) |
| **NMSxPro Mobile** | Android, iOS | Flutter, BLoC, on-device SSH client | [repo](https://github.com/FaaStatic/nmsmobile-source) |
| **Nexa Ticket Scanner** | Android | Flutter, barcode / QR scanning | — |
| **Hebat!** (Semarang City Gov) | Android, iOS | React Native, Redux Toolkit | [repo](https://github.com/FaaStatic/hebat-apps-source) |
| **Kla Computer** (Infokom) | Android, iOS | React Native, Redux Toolkit, FCM | [repo](https://github.com/FaaStatic/infokom-mobile-source) |
| **Naratik** (Batik e-commerce) | Android | Kotlin, Hilt, Room, WorkManager, CNN model | [repo](https://github.com/FaaStatic/naratik-mobile-source) |

<sub>\* COIP Mobile is an enterprise app distributed to United Tractors customers. The seven store-published apps are the rest.</sub>

---

# ⚡ MOBILE.EXE

### 🐦 Flutter

<sub>4 published apps, 2022 to 2024</sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=flutter,dart"/>
<br/><br/>
<img src="https://img.shields.io/badge/Flutter-Production-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Riverpod-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/BLoC-1C0035?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Clean_Architecture-FFE81A?style=for-the-badge&labelColor=0D0D0D"/>
</div>

Four of the seven published apps are Flutter, across loyalty, maps, and network operations.
NMSxPro ships an on-device SSH client so field technicians can run commands against network
equipment straight from the phone. Riverpod 2 and Clean Architecture on ForYou and
MyKekancan, BLoC on NMSxPro.

### 🤖 Kotlin

<sub>Native Android since 2021, plus Kotlin Multiplatform</sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,java"/>
<br/><br/>
<img src="https://img.shields.io/badge/Kotlin-Native_Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/Hilt_+_Room-3DDC84?style=for-the-badge&logo=android&logoColor=black"/>
<img src="https://img.shields.io/badge/Kotlin_Multiplatform-FFE81A?style=for-the-badge&logo=kotlin&logoColor=black"/>
</div>

Where I started, and where I still go when a problem wants the platform directly. Naratik is
native Kotlin with Hilt, Room, DataStore, and WorkManager background sync, plus a CNN
authenticity checker from a paper I co-authored. KMP Todo shares domain models between an
Android and iOS Compose client and a Ktor backend, so the whole thing is one language end
to end.

### ⚛️ React Native

<sub>2 published apps, plus the enterprise app I build today</sub>

<div align="center">
<img src="https://skillicons.dev/icons?i=react,ts"/>
<br/><br/>
<img src="https://img.shields.io/badge/React_Native-Production-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"/>
<img src="https://img.shields.io/badge/Zustand-FFE81A?style=for-the-badge&labelColor=0D0D0D&logoColor=black"/>
<img src="https://img.shields.io/badge/Re.Pack_+_Rspack-FF003C?style=for-the-badge&labelColor=0D0D0D"/>
<img src="https://img.shields.io/badge/NativeWind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Redux_Toolkit-6441AA?style=for-the-badge&logo=redux&logoColor=white"/>
</div>

Hebat! for the Semarang city government and Kla Computer for Infokom, both Redux Toolkit.
Currently building COIP Mobile at PT United Tractors Tbk: typed API layer generated from the
backend OpenAPI spec with Kubb, so there is no hand-written client code and no schema drift.
Conditional validation across 100+ fields in multi-tab checksheets. Around 100 unit and UI
tests with Jest and RNTL.

### 📴 Offline-first

The part I would actually put on a business card. Realm on COIP, Room plus WorkManager on
Naratik, SQLite elsewhere. Jobs get created with no signal, photo evidence queues up, and
everything reconciles when the technician walks back out of the basement. Nothing is lost in
between, which sounds obvious until you have shipped it.

---

# ⚙️ BACKEND.PROTOCOL

<div align="center">
<img src="https://skillicons.dev/icons?i=go,kotlin,postgres,redis,docker,firebase"/>
<br/><br/>
<img src="https://img.shields.io/badge/Go_Fiber_v3-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/Kotlin_Ktor-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-FF003C?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker_+_Nginx-0D0D0D?style=for-the-badge&logo=docker&logoColor=00FFFF"/>
</div>

| Project | What it is | Stack |
|---|---|---|
| [**Shop POS Backend**](https://github.com/FaaStatic/Shop_project_be) | POS API: products, transactions, debt tracking, Excel and PDF report export. Deployed to a Linux VPS with Docker Compose and Nginx. | Go Fiber v3, GORM, PostgreSQL, Redis, Cobra CLI migrations |
| [**KMP Todo**](https://github.com/FaaStatic/kmp_todo_app) | Full-stack Kotlin. Compose Multiplatform client sharing domain models with a Ktor backend. JWT with refresh tokens, BCrypt, Swagger. | Kotlin Multiplatform, Ktor, Exposed, PostgreSQL |
| [**Local CDN**](https://github.com/FaaStatic/local_cdn_go) | Small self-hosted static asset server. | Go |
| [**LMS Inkaedu**](https://github.com/FaaStatic/web-lms-inkaedu-source) | Learning platform for AMDAL certification training. I deployed both frontend and backend to production; 100 active users at launch. | React 18, Redux Toolkit |

This is side-project and freelance work, not a job title I have held. What it buys me is the
other end of the API contract. On COIP the typed client is generated straight from the
OpenAPI spec, so the schema is the contract. On KMP Todo the client and the server share the
same domain models in the same language. And the POS service is one I actually run, which is
how I ended up learning Certbot, Nginx, and Docker Compose the hard way.

Hire me for mobile. The backend means you will not spend a sprint explaining why the endpoint
is shaped that way.

---

# 🔬 PUBLICATION

**Classification of Batik Authenticity Using Convolutional Neural Network Algorithm with Transfer Learning Method**
2021 Sixth International Conference on Informatics and Computing (ICIC), IEEE, Nov 2021, pp. 1 to 6.
[DOI: 10.1109/ICIC54025.2021.9632937](https://doi.org/10.1109/ICIC54025.2021.9632937)

The model from this paper became the authenticity checker inside the Naratik Android app.

---

# 🧠 CURRENT.FOCUS

```yaml
Mobile:
  - Flutter: Riverpod, BLoC, Clean Architecture
  - Kotlin: Compose, KMP, Hilt
  - React Native: New Architecture, Re.Pack + Rspack, Module Federation

Architecture:
  - Clean Architecture
  - MVVM
  - Offline-first sync (Realm, Room, SQLite)

Backend:
  - Go Fiber v3
  - PostgreSQL, Redis
  - Docker, Nginx, CI/CD
```

---

<details>
<summary><b>🗄️ ARCHIVE</b> (older and smaller work)</summary>

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

# 📊 DATA.ANALYTICS

<div align="center">
<img src="https://streak-stats.demolab.com?user=FaaStatic&theme=transparent&hide_border=true&ring=FFE81A&fire=FF003C&currStreakLabel=FFE81A&sideNums=FFFFFF&currStreakNum=FFE81A&dates=AAAAAA"/>
</div>

---

# 🐍 NETRUNNER.TRACE

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile/snake-light.svg" />
    <img alt="Contribution snake" src="./profile/snake-dark.svg" width="100%"/>
  </picture>
</div>

---

# 📡 JACK.IN

<div align="center">

<a href="https://www.linkedin.com/in/suhaili-faruq-8475a0189/">
  <img src="https://img.shields.io/badge/LINKEDIN-FFE81A?style=for-the-badge&logo=linkedin&logoColor=black"/>
</a>
<a href="mailto:suhaili.faruq01@gmail.com">
  <img src="https://img.shields.io/badge/GMAIL-FF003C?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://portfolioweb-55f91.web.app/">
  <img src="https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logo=firefoxbrowser&logoColor=black"/>
</a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:FFE81A,50:1C0035,100:0A0005"/>

</div>
