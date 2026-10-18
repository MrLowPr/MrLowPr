<img src="assets/profile-header-v2.svg" alt="Mr. Lowprofile" width="100%">

<h1 align="center">Mr. Lowprofile</h1>
<p align="center">
  <strong>Java &amp; Python Backend Engineer</strong> · Reverse Engineering · Full-stack<br>
  <sub>I build reliable backend systems — and take closed software apart until it is readable again.</sub>
</p>

<p align="center">
  <a href="#expertise"><img src="https://img.shields.io/badge/Core-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"></a>
  <a href="#expertise"><img src="https://img.shields.io/badge/Core-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Open%20to%20Work-brightgreen?style=for-the-badge&logo=githubactions&logoColor=white" alt="Open to work">
</p>

<p align="center">
  <a href="mailto:mrlowpr@protonmail.com"><img src="https://img.shields.io/badge/Email-MrLowProtonMail-c79111?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/MrLowPr?tab=repositories"><img src="https://img.shields.io/badge/Projects-43%20repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"></a>
</p>

---

## 🎯 Expertise

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>☕ Java — Primary</h3>
      <sub><b>Production backend, data-heavy services, Android.</b></sub>
      <br><br>
      <b>Core &amp; language</b><br>
      <code>Java 8–21</code> · OOP · Generics · Streams · Concurrency · <code>CompletableFuture</code> · <code>java.*</code> module system
      <br><br>
      <b>Frameworks &amp; stack</b><br>
      Spring Boot · Spring MVC · Spring Data JPA · Hibernate · Jakarta EE · Maven · Gradle
      <br><br>
      <b>Data &amp; infrastructure</b><br>
      PostgreSQL · MySQL · JDBC · JUnit 5 · Mockito · Maven/Gradle CI · Docker multi-stage builds
      <br><br>
      <b>Also</b><br>
      Android (Kotlin/Java) · REST API design · clean architecture · design patterns
    </td>
    <td width="50%" valign="top">
      <h3>🐍 Python — Primary</h3>
      <sub><b>Automation, tooling, data pipelines, analysis.</b></sub>
      <br><br>
      <b>Core &amp; language</b><br>
      <code>Python 3.10+</code> · Typing &amp; type hints · Generators · Decorators · Context managers · <code>asyncio</code>
      <br><br>
      <b>Libraries &amp; stack</b><br>
      FastAPI · Flask · Requests · httpx · Pydantic · SQLAlchemy · Pandas · NumPy
      <br><br>
      <b>Data &amp; tooling</b><br>
      pytest · Logging · Config management · CLI tooling · JSON/HTTP clients · Web scraping · Data cleaning
      <br><br>
      <b>Also</b><br>
      Code analysis &amp; static analysis tools · Reverse-engineering scripts · Shell automation
    </td>
  </tr>
</table>

**Supporting:** JavaScript/TypeScript · React · C/C++ · HTML/CSS · Bash · Go · CMake

```text
Java    ████████████████░░░░  80%
Python  ██████████████████░░  90%
JS/TS   ████████████░░░░░░░░  60%
C / C++ ██████████░░░░░░░░░░  50%
SQL     ██████████░░░░░░░░░░  50%
```

---

## 💼 What I build

<table>
  <tr>
    <td width="33%" valign="top"><b>⚙️ Backend systems</b><br><sub>REST and service APIs in Java/Spring Boot and Python/FastAPI — clean layers, typed contracts, real tests, containerised builds.</sub></td>
    <td width="33%" valign="top"><b>🤖 Automation &amp; tooling</b><br><sub>Python CLIs, data pipelines, parsers and analysis scripts that remove manual steps and give deterministic results.</sub></td>
    <td width="33%" valign="top"><b>🔬 Reverse engineering</b><br><sub>Recovering source from shipped binaries, reading bundles, static and dynamic analysis, rebuilding an app so it can be modified again.</sub></td>
  </tr>
</table>

---

## 📌 Featured project — Overdrive (fork)

### 🎮 A PS5 homebrew game store — **1,800+ titles** — rebuilt from its own compiled bundle

[![Overdrive banner](assets/banner.svg)](https://github.com/MrLowPr/overdrive)

**This is my strongest engineering case study.** The application existed only as an opaque,
compiled bundle with no readable source. I recovered the source from that binary, then rewrote the
front end as React + esbuild so it could be read, changed, debugged and built again — and turned it
into a maintained fork of the original project.

<table>
  <tr>
    <td width="150" valign="top"><b>Problem</b></td>
    <td valign="top">A working PS5 store front shipping 1,800+ games — shipped only as compiled output. Unmaintainable, unreadable, impossible to fix or extend.</td>
  </tr>
  <tr>
    <td valign="top"><b>Approach</b></td>
    <td valign="top">Bundle analysis and source recovery → static analysis of the compiled app → functional reimplementation in a maintainable stack → upstream fork with documented deltas.</td>
  </tr>
  <tr>
    <td valign="top"><b>What it does</b></td>
    <td valign="top">Browse, search, queue downloads, install and update games directly from the console UI — no browser round-trip, no PC required.</td>
  </tr>
  <tr>
    <td valign="top"><b>Engineering</b></td>
    <td valign="top">Focus-driven controller navigation · 15 interface languages · RTL-aware layout · resumable download queue across multiple providers.</td>
  </tr>
  <tr>
    <td valign="top"><b>Stack</b></td>
    <td valign="top">C++ · React · JavaScript · Python (tooling) · esbuild · CMake · ICU / i18n</td>
  </tr>
  <tr>
    <td valign="top"><b>My role</b></td>
    <td valign="top">Fork owner and maintainer — source recovery, UI rewrite, localisation, queue system, upstream sync.</td>
  </tr>
  <tr>
    <td valign="top"><b>License</b></td>
    <td valign="top">MIT</td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/MrLowPr/overdrive"><b>Source code</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/MrLowPr/overdrive/releases/tag/v1.1.0"><b>Latest release v1.1.0</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/MrLowPr/overdrive/blob/main/FORK-NOTES.md"><b>Fork notes</b></a>
</p>

Maintained as a fork of [MyLuxy/overdrive](https://github.com/MyLuxy/overdrive). Every fork-specific
change is listed in [FORK-NOTES.md](https://github.com/MrLowPr/overdrive/blob/main/FORK-NOTES.md)
and released through [CHANGELOG.md](https://github.com/MrLowPr/overdrive/blob/main/CHANGELOG.md).

---

## 🛠️ Other work

- **[SandiGenerate](https://github.com/MrLowPr/SandiGenerate)** — password generator and strength tester running entirely on `crypto.getRandomValues` (CSPRNG) instead of `Math.random`, so output is not guessable.
- **[MrLowPr/overdrive](https://github.com/MrLowPr/overdrive)** — the Overdrive fork: full source recovered, UI rewritten, kept in sync with upstream and documented at every fork-specific delta.
- **43 repositories** spanning backend services, automation tooling, web apps, image/convert utilities and reverse-engineering work.

---

## 📍 Currently

- Deepening **Java** (concurrency, JVM internals) and **Python** (asyncio, typing, data engineering).
- Shipping production-grade backend code and tooling.
- **Open to work** — Java / Python backend, platform engineering, or anything touching reverse engineering. Remote-friendly, available for contract or full-time.

## 📫 Contact

- GitHub — [@MrLowPr](https://github.com/MrLowPr) (issues, discussions, or just say hello)
- Email — **mrlowpr@protonmail.com**

<p align="center">
  <sub>Hand-written Markdown, no trackers, no build step.</sub>
</p>