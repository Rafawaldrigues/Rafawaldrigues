# Rafael Guerra Waldrigues

Software developer from Brazil, studying Computer Science at **UEL** (graduating July 2027). I build mobile apps, websites and backends, run the servers they live on, and work with data and machine learning. Security is where I go deepest: I reverse engineer Android apps and write up what I find.

Currently **Full Stack Intern at ORV**.

[LinkedIn](https://www.linkedin.com/in/rafael-guerra-05b042248/) · [waldriguesrafa@gmail.com](mailto:waldriguesrafa@gmail.com) · Portuguese (native) · English (advanced)

## Tech

<table>
  <tr>
    <td valign="top" width="340">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Rafawaldrigues&layout=compact&langs_count=6&hide=makefile&theme=github_dark">
        <img alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rafawaldrigues&layout=compact&langs_count=6&hide=makefile&theme=default" width="320">
      </picture>
    </td>
    <td valign="top">
    <img src="https://img.shields.io/badge/JAVA-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="JAVA">
    <img src="https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="PYTHON">
    <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JAVASCRIPT">
    <br>
    <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TYPESCRIPT">
    <img src="https://img.shields.io/badge/KOTLIN-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="KOTLIN">
    <br>
    <img src="https://img.shields.io/badge/SWIFT-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="SWIFT">
    <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/ASSEMBLY-1F2937?style=for-the-badge" alt="Assembly">
    <img src="https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FASTAPI">
    <br>
    <img src="https://img.shields.io/badge/POSTGRESQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="POSTGRESQL">
    <img src="https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="DOCKER">
    <br>
    <img src="https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="LINUX">
    <img src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white" alt="GIT">
    <img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GITHUB">
    <img src="https://img.shields.io/badge/FIGMA-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="FIGMA">
    <img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge" alt="POWER BI">
    <br>
    <img src="https://img.shields.io/badge/FRIDA-1F2937?style=for-the-badge" alt="FRIDA">
    <img src="https://img.shields.io/badge/JADX-1F2937?style=for-the-badge" alt="JADX">
    <img src="https://img.shields.io/badge/GHIDRA-1F2937?style=for-the-badge" alt="GHIDRA">
    <img src="https://img.shields.io/badge/BURP%20SUITE-FF6633?style=for-the-badge" alt="BURP SUITE">
    <br>
    </td>
  </tr>
</table>

## What I work with

- **Mobile:** native iOS in Swift, Android in Kotlin and Java.
- **Web:** websites and web apps with HTML, CSS, JavaScript and TypeScript, backed by Python (FastAPI).
- **Backend and servers:** REST APIs, PostgreSQL, JWT authentication, Docker, deployment, VPS administration, logs and CI.
- **Data and AI:** data pipelines, Power BI dashboards, and machine learning such as Bayesian preference optimization.
- **Security:** Android app analysis with JADX and Frida, static analysis tooling, CTF write-ups and x86-64 reverse engineering.

## Featured projects

- **[JADX Atlas](https://github.com/Rafawaldrigues/jadx-atlas)** — attack-surface map for Android apps, built on JADX output. It shows which components are exposed, what each class is even when the name is `a.b.c`, where sensitive APIs are used, and possible paths from an exposed entry point to the code worth reviewing. Runs locally, and every result carries its confidence and the file and line it comes from. Python, Tree-sitter, 30 rule-based checks, version diff and exportable reports.
- **[tasteq](https://github.com/Rafawaldrigues/tasteq)** — open-source equalizer that learns your personal sound. You compare two versions of a song, and Bayesian preference optimization (Gaussian Process) converges on your ideal 10-band EQ for each type of music. Versions are loudness-matched, so louder never wins, and the model only picks EQ gains while the audio path stays deterministic DSP. Python library, CLI and local demo, in early development.
- **[Android Intent Attacks](https://github.com/Rafawaldrigues/android-intent-attacks)** — CTF write-ups on Android vulnerabilities, with new ones added regularly: exported components, intent redirection and hijacking, deep link trust bypass, content provider exposure and SQL injection, and PendingIntent misuse. Each one covers the vulnerability, how I found it, the exploit (Kotlin PoC apps, adb) and the fix.
- **[ASM X](https://github.com/Rafawaldrigues/x86-assembly-visualizer)** — x86-64 assembly simulator and source viewer. Step through programs, inspect registers and memory, and catch common mistakes before assembling. Python, no runtime dependencies.

<details>
<summary>More projects</summary>

<br>

- **[C Compiler Frontend](https://github.com/Rafawaldrigues/c-compiler-frontend)** — lexer and parser in C: Flex/Bison phases plus a hand-written recursive-descent parser.
- **[Network Tools](https://github.com/Rafawaldrigues/network-tools)** — TCP/UDP socket projects covering reliable delivery, file integrity, packet loss and throughput measurement.
- **[Distributed Whiteboard](https://github.com/Rafawaldrigues/sdwb-distributed-whiteboard)** and **[gRPC Bookstore](https://github.com/Rafawaldrigues/minibib-grpc-bookstore)** — distributed systems coursework in Python.

</details>

## Experience

<details>
<summary><b>ORV</b> — Full Stack Intern · Jul 2026–present</summary>

<br>

Native iOS development in Swift, FastAPI services, automation and integrations, client-facing applications, deployment and VPS administration.

</details>

<details>
<summary><b>PET-Saúde I&amp;SD / UEL</b> — Backend Developer · Mar 2025–Jul 2026</summary>

<br>

Built a FastAPI REST API for patient and appointment data. Implemented JWT authentication and role-based permissions, integrated PostgreSQL, wrote endpoint tests, and supported production deployment and logs.

</details>

## Contact

[LinkedIn](https://www.linkedin.com/in/rafael-guerra-05b042248/) · [waldriguesrafa@gmail.com](mailto:waldriguesrafa@gmail.com)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="snake-dark.svg">
  <img alt="Contribution graph" src="snake.svg" width="100%">
</picture>
