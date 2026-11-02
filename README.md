# Rafael Guerra Waldrigues

Full stack developer and Computer Science student at **UEL, Brazil**. I build web and mobile products end to end, and in my free time I take software apart: **Android reverse engineering, dynamic instrumentation and application security** are what I enjoy most.

Currently a **Full Stack Intern at ORV**. Graduating in **July 2027**.

[LinkedIn](https://www.linkedin.com/in/rafael-guerra-05b042248/) · [waldriguesrafa@gmail.com](mailto:waldriguesrafa@gmail.com) · Portuguese (native) · English (advanced)

## Security work

- **[JADX Atlas](https://github.com/Rafawaldrigues/jadx-atlas)** — attack-surface map for Android apps, built on JADX output. It shows which components are exposed, what each class is even when the name is `a.b.c`, where sensitive APIs are used, and possible paths from an exposed entry point to the code worth reviewing. Runs locally, and every result carries its confidence and the file and line it comes from. Python, Tree-sitter, 30 rule-based checks, version diff and exportable reports.
- **[Android Intent Attacks](https://github.com/Rafawaldrigues/android-intent-attacks)** — CTF write-ups on Android Intent vulnerabilities: exported components, deep link and App Link trust bypass, multi-step flows and intent redirection. Each one covers the vulnerability, how I found it, the exploit (Kotlin PoC apps, adb) and the fix. More coming.
- **[ASM X](https://github.com/Rafawaldrigues/x86-assembly-visualizer)** — x86-64 assembly simulator and source viewer. Step through programs, inspect registers and memory, and catch common mistakes before assembling. Python, no runtime dependencies.

## Other projects

- **[C Compiler Frontend](https://github.com/Rafawaldrigues/c-compiler-frontend)** — lexer and parser in C: Flex/Bison phases plus a hand-written recursive-descent parser.
- **[Network Tools](https://github.com/Rafawaldrigues/network-tools)** — TCP/UDP socket projects covering reliable delivery, file integrity, packet loss and throughput measurement.
- **[Distributed Whiteboard](https://github.com/Rafawaldrigues/sdwb-distributed-whiteboard)** and **[gRPC Bookstore](https://github.com/Rafawaldrigues/minibib-grpc-bookstore)** — distributed systems coursework in Python.

## Stack

| | |
|---|---|
| **Languages** | Python · Kotlin · Java · JavaScript · TypeScript · Swift · C · x86-64 assembly · Rust · Go |
| **Reverse engineering** | JADX · Frida (frida-server, frida-trace) · Ghidra · gdb · x64dbg · adb |
| **Security testing** | Burp Suite · AFL++ · Android components, Intents and deep links |
| **Backend** | FastAPI · PostgreSQL · SQLAlchemy · JWT auth · REST · gRPC |
| **Tooling** | Linux · Docker · Git · GitHub Actions · VPS administration |

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

## Open to

Full stack roles, and entry-level positions in mobile security, reverse engineering and vulnerability research.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="snake-dark.svg">
  <img alt="Contribution graph" src="snake.svg" width="100%">
</picture>
