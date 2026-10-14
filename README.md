<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f172a,50:1e293b,100:334155&height=180&section=header&text=Muhammad%20Rafi%20Irfansyah&fontSize=36&fontColor=f8fafc&animation=fadeIn&fontAlignY=42&desc=Backend%20Software%20Engineer%20%E2%80%A2%20Enterprise%20Microservices%20%E2%80%A2%20Multiplatform%20Mobile&descAlignY=65&descSize=16" alt="Header" width="100%" />

<div align="center">
  <a href="https://www.linkedin.com/in/irfnsyhh/">
    <img src="https://img.shields.io/badge/LinkedIn-irfnsyhh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=181717" alt="LinkedIn" />
  </a>
  <a href="mailto:mrafiirfansyah16@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=181717" alt="Email" />
  </a>
  <a href="https://muhammad-rafi-irfansyah.my.canva.site/">
    <img src="https://img.shields.io/badge/Portfolio-Visit_Site-00C4CC?style=for-the-badge&logo=canva&logoColor=white&labelColor=181717" alt="Portfolio" />
  </a>
  <a href="https://github.com/krafime?tab=followers">
    <img src="https://img.shields.io/github/followers/krafime?label=Followers&style=for-the-badge&color=2F81F7&logo=github&logoColor=white&labelColor=181717" alt="GitHub Followers" />
  </a>
</div>

</div>

---

<table>
<tr>
<td width="58%" valign="top">

### ⚡ Engineering Profile

I'm a **Backend Software Engineer at PT DAnS Multi Pro**, building and maintaining enterprise microservices for telecommunication platforms. My work spans the full software lifecycle: designing RESTful APIs, implementing core business logic, integrating enterprise systems, remediating security findings, and supporting production deployments.

Before focusing on backend systems, I built cross-platform and native mobile applications with **Kotlin** and **Flutter**—a background that continues to shape how I design clean API contracts and seamless end-to-end user experiences.

- 🎓 **Education:** B.Sc. in Informatics, **Telkom University** *(Cum Laude, GPA 3.71/4.00)*
- 📍 **Base:** Karawang, West Java, Indonesia
- 🗣️ **Languages:** Indonesian *(Native)* • English *(Intermediate)*

</td>
<td width="42%" valign="top">

### 🎯 Current Telemetry

~~~yaml
engineer: Muhammad Rafi Irfansyah
pronouns: He/Him
role: Backend Software Engineer
organization: PT DAnS Multi Pro

core_focus:
  - Java (Java 8 -> 21 Migration)
  - Spring Boot & RESTful APIs
  - Microservices & RabbitMQ
  - Enterprise System Integration

also_builds_with:
  - Kotlin & Compose Multiplatform
  - Flutter (Android, iOS, Web)
  - Python (Data & Applied ML)

mission: >
  Build systems that are reliable,
  secure, and pleasant to use.
~~~

</td>
</tr>
</table>

---

## 🏗️ System Architecture & Tech Stack

~~~mermaid
flowchart LR
    subgraph Client["📱 Client Layer (Mobile & Web)"]
        KMP["Kotlin / Compose Multiplatform"]
        FLT["Flutter / Dart"]
    end

    subgraph Core["⚙️ Backend & Microservices"]
        API["RESTful APIs"]
        SB["Spring Boot (Java 21)"]
        SEC["Pentest Remediation & SonarQube"]
    end

    subgraph Infra["🗄️ Data, Messaging & Infra"]
        RMQ[["RabbitMQ Broker"]]
        DB[("PostgreSQL / Oracle")]
        K8S("Kubernetes / Linux")
    end

    KMP & FLT -->|HTTPS / JSON| API
    API --> SB
    SB --> SEC
    SB -->|Async Events| RMQ
    SB -->|Persistence| DB
    SB -.->|Orchestrated on| K8S
~~~

## 🛠️ Technologies & Tools

<div align="center">
  <p align="center">
    <strong>Backend, Data &amp; DevOps</strong><br/><br/>
    <img src="https://skillicons.dev/icons?i=java,spring,rabbitmq,postgres,kubernetes,linux,gitlab,git,postman,idea&perline=10" alt="Backend skills" /><br/>
    <sub>SQL with PostgreSQL &amp; Oracle</sub>
  </p>
  <br/>
  <p align="center">
    <strong>Mobile &amp; Others</strong><br/><br/>
    <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,flutter,dart,firebase,python,js&perline=10" alt="Mobile skills" /><br/>
    <sub>Android (Jetpack Compose), KMP &amp; Cross-Platform</sub>
  </p>
</div>

---

## 💼 Experience & Key Impact

<table>
<tr>
<td width="34%" valign="top">

#### 🟢 PT DAnS Multi Pro
**Backend Software Engineer**  
*Nov 2025 – Present*

- Delivered enhancements across **20+ REST APIs** and **6 enterprise microservices** for multi-channel prepaid SIM registration workflows.
- Migrated legacy microservices from **Java 8 to Java 21**, resolving dependency conflicts and validating with regression testing.
- Built event-driven services with **Spring Boot & RabbitMQ**, resolved internal/external pentest findings, and improved SonarQube quality gates.

</td>
<td width="33%" valign="top">

#### 🔵 Duluin (PT Rasa Aksata)
**Flutter Mobile Intern (HRMS)**  
*Apr 2025 – Jul 2025*

- Built a cross-platform **HR Management System** for Android, iOS, and Web using Flutter.
- Integrated REST APIs via **Dio** and engineered key security/utility modules: **Face Detection**, **Fake GPS Detection**, PDF Viewer, and infinite pagination.
- Collaborated in an **Agile Scrum** product team.

</td>
<td width="33%" valign="top">

#### 🟣 PDAM (City Water Utility)
**System Integration Intern**  
*Aug 2023 – Nov 2023*

- Engineered an Android field-reporting application with **GPS attendance validation** for field officers.
- Integrated field data streams with a centralized **Looker Dashboard** for management visibility.
- Analyzed business requirements and designed end-to-end reporting workflows.

</td>
</tr>
</table>

---

## 🚀 Featured Projects (Bento Showcase)

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Backend Engineering (Java)
- 🔗 **[ops — Online Payment System API](https://github.com/krafime/ops)**  
  RESTful API mini-project demonstrating payment transaction flows and service modularity in Java.
- 📦 **[ims — Inventory Management System](https://github.com/krafime/ims)**  
  Java-based inventory tracking and management project built during PT DAnS Multi Pro training.
- 🏢 **[ams (Asset Management)](https://github.com/krafime/ams)** & **[tms (Task Management)](https://github.com/krafime/tms)**  
  Core Java backend repositories focusing on structured domain modeling and CRUD operations.

</td>
<td width="50%" valign="top">

### 📱 Mobile & Multiplatform
- 🛍️ **[KMP-ECommerce](https://github.com/krafime/KMP-ECommerce)**  
  Shared-UI e-commerce application targeting Android, iOS, Desktop, and Web with **Kotlin & Compose Multiplatform**.
- 🎬 **[CineNook_Flutter](https://github.com/krafime/CineNook_Flutter)**  
  Movie discovery app featuring search, category filtering, and REST API integration (**Flutter & Dart**).
- 📚 **[BukuKu-MobileDevelopment](https://github.com/krafime/BukuKu-MobileDevelopment)**  
  Bangkit 2023 Capstone book recommendation mobile client built with **Kotlin, Firebase, and REST APIs**.
- 💧 **[dashboard_pdam](https://github.com/krafime/dashboard_pdam)** & 🥫 **[easy_pantry](https://github.com/krafime/easy_pantry)**  
  Field reporting Android app (Kotlin) & household pantry tracker (Flutter).

</td>
</tr>
</table>

<details>
<summary><b>🔬 Click to expand: Data Science, Machine Learning & Publications</b></summary>
<br/>

| Type | Title / Repository | Stack & Details |
| :--- | :--- | :--- |
| 📄 **Journal Publication** | **Music Recommendation System Using Alternating Least Squares Method** | Published in *Indonesia Journal on Computing (Indo-JC)* • May 2024 |
| 🤖 **Machine Learning** | **[BukuKu-Capstone](https://github.com/krafime/BukuKu-Capstone)** | Machine learning modeling side of the BukuKu Bangkit Capstone (`Python`, `Jupyter`) |
| 📊 **Ensemble Learning** | **[ML_Project-Base](https://github.com/krafime/ML_Project-Base)** | Implementation and comparative analysis of ensemble learning algorithms (`Python`) |
| 📡 **IoT & Signal** | **[IOT-Signal-and-Data-Filering](https://github.com/krafime/IOT-Signal-and-Data-Filering)** | IoT sensor signal processing and noise filtering pipelines (`Python`, `Jupyter`) |

</details>

<details>
<summary><b>🏅 Click to expand: Certifications & Programs</b></summary>
<br/>

- **Belajar Membuat Aplikasi Flutter untuk Pemula** — *Dicoding Indonesia (09/2024)*
- **IT Support Specialist** — *Google (07/2024)*
- **Bangkit Academy 2023 Graduate (Mobile Development Path)** — *Google, GoTo, Traveloka (07/2023)*

</details>

---

## 📈 GitHub Telemetry

<div align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=krafime&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=krafime&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=krafime&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p><i>"Code is like humor. When you have to explain it, it's bad."</i> — Cory House</p>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:334155,50:1e293b,100:0f172a&height=100&section=footer" alt="Footer" width="100%" />
</div>
