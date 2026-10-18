<img src="assets/profile-header-v2.svg" alt="Mr. Lowprofile" width="100%">

<h1 align="center">MrLowPr</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Reverse%20Engineering-6E4B8A?style=for-the-badge" alt="Reverse engineering">
</p>

---

## 📌 Featured work — The Ultimate CTF Utils

### Six CTF triage tools, one `npm install`

[![The Ultimate CTF Utils](https://img.shields.io/badge/npm-the--ultimate--ctf--utils-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/the-ultimate-ctf-utils)
[![Repo](https://img.shields.io/badge/github-MrLowPr%2FThe--Ultimate--CTF--Utils-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MrLowPr/The-Ultimate-CTF-Utils)

Packaged the CTF triage tools into a single installable npm package. Each tool keeps its own
dependencies, so you install only what the challenge needs.

<table>
  <tr>
    <td width="140" valign="top"><b>Install</b></td>
    <td valign="top"><code>npm install -g the-ultimate-ctf-utils</code> — Node 16+ and Python 3.8+</td>
  </tr>
  <tr>
    <td valign="top"><b>Commands</b></td>
    <td valign="top"><code>ctf-utils</code> dispatcher plus six direct commands: <code>webparamtrace</code>, <code>cryptoattack-triage</code>, <code>pyunpack-trace</code>, <code>heapviz</code>, <code>pcap-stream-extractor</code>, <code>audio-stego-analyzer</code></td>
  </tr>
  <tr>
    <td valign="top"><b>Web</b></td>
    <td valign="top">Hidden parameter discovery by response similarity · SSTI payload matrix for Jinja2, Twig, Freemarker, Velocity, Smarty, ERB, Mako, Handlebars · recursive LFI mapper with PHP wrappers</td>
  </tr>
  <tr>
    <td valign="top"><b>Crypto</b></td>
    <td valign="top">RSA triage (small <code>e</code>, small <code>n</code>, Fermat) · common-modulus · Hastad broadcast · ECC parameter checks · ECDSA nonce reuse recovery · LCG state recovery</td>
  </tr>
  <tr>
    <td valign="top"><b>Reverse engineering</b></td>
    <td valign="top">PyInstaller / py2exe extraction with PE section info · <code>.pyc</code> decompile with disassembly fallback · AST and pattern scan for string obfuscation, XOR and anti-debug checks</td>
  </tr>
  <tr>
    <td valign="top"><b>Binary exploitation</b></td>
    <td valign="top">GDB extension that renders glibc heap chunks, tcache and fastbin chains, unsorted bins, and scans for leaked libc and heap pointers — no pwndbg or GEF required</td>
  </tr>
  <tr>
    <td valign="top"><b>Forensics</b></td>
    <td valign="top">TCP/UDP session reconstruction · HTTP, FTP and SMB file carving · DNS exfiltration detection by label length and entropy · non-standard ICMP payload analysis</td>
  </tr>
  <tr>
    <td valign="top"><b>Steganography</b></td>
    <td valign="top">LSB extraction with magic-byte detection · spectrogram energy pattern scan · DTMF tone decoding via Goertzel · Morse code detection and decode</td>
  </tr>
  <tr>
    <td valign="top"><b>License</b></td>
    <td valign="top">MIT</td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/MrLowPr/The-Ultimate-CTF-Utils"><b>Source code</b></a> &nbsp;·&nbsp;
  <a href="https://www.npmjs.com/package/the-ultimate-ctf-utils"><b>npm package</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/MrLowPr/The-Ultimate-CTF-Utils#readme"><b>Usage</b></a>
</p>

---

## 📌 Featured work — Overdrive (fork)

### A PS5 homebrew game store — **1,800+ titles** — rebuilt from its own compiled bundle

[![Overdrive banner](assets/banner.svg)](https://github.com/MrLowPr/overdrive)

A working store front that shipped only as compiled output — no readable source. I recovered the
source from the bundle, rebuilt the interface as React + esbuild, and now maintain it as a fork of
the original project.

<table>
  <tr>
    <td width="140" valign="top"><b>Problem</b></td>
    <td valign="top">1,800+ games in a working app that shipped as compiled output only — unmaintainable and impossible to change.</td>
  </tr>
  <tr>
    <td valign="top"><b>Approach</b></td>
    <td valign="top">Bundle analysis → source recovery → static analysis of the compiled app → reimplementation in a maintainable stack → documented fork.</td>
  </tr>
  <tr>
    <td valign="top"><b>Result</b></td>
    <td valign="top">Readable, buildable source again. Browse, search, queue downloads, install and update games from the console UI — no PC required.</td>
  </tr>
  <tr>
    <td valign="top"><b>Engineering</b></td>
    <td valign="top">Focus-driven controller navigation · 15 interface languages · RTL-aware layout · resumable download queue across multiple providers.</td>
  </tr>
  <tr>
    <td valign="top"><b>My role</b></td>
    <td valign="top">Fork owner and maintainer — source recovery, interface rewrite, localisation, download queue, upstream sync.</td>
  </tr>
  <tr>
    <td valign="top"><b>License</b></td>
    <td valign="top">MIT</td>
  </tr>
  </table>

<p align="center">
  <a href="https://github.com/MrLowPr/overdrive"><b>Source code</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/MrLowPr/overdrive/releases/tag/v1.1.0"><b>Release v1.1.0</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/MrLowPr/overdrive/blob/main/FORK-NOTES.md"><b>Fork notes</b></a>
</p>

Maintained as a fork of [MyLuxy/overdrive](https://github.com/MyLuxy/overdrive). Every fork-specific
change is listed in [FORK-NOTES.md](https://github.com/MrLowPr/overdrive/blob/main/FORK-NOTES.md).

---

## Other work

- **[SandiGenerate](https://github.com/MrLowPr/SandiGenerate)** — password generator and strength tester running on `crypto.getRandomValues` (CSPRNG) instead of `Math.random`, so the output is not guessable.
- **[MrLowPr/overdrive](https://github.com/MrLowPr/overdrive)** — the Overdrive fork, with source recovered and every fork-specific delta documented.
- **[The Ultimate CTF Utils](https://github.com/MrLowPr/The-Ultimate-CTF-Utils)** — six CTF triage tools shipped as one npm package.

---

## Currently

- Working mostly in **Java** and **Python**, deployed with **Docker**.
- Spending most of my time on **reverse engineering**.

## Contact

- GitHub — [@MrLowPr](https://github.com/MrLowPr)

<p align="center">
  <sub>Hand-written Markdown, no trackers, no build step.</sub>
</p>