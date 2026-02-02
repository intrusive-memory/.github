# Intrusive Memory

A collection of Swift libraries and frameworks for multimedia and UI development.

## Homebrew Tap

Install CLI tools via Homebrew:

```bash
brew tap intrusive-memory/tap
brew install proyecto
brew install bruja
```

| Formula | Description | Source |
|---------|-------------|--------|
| `proyecto` | CLI tool for analyzing directories and generating PROJECT.md files using local LLM inference | [SwiftProyecto](https://github.com/intrusive-memory/SwiftProyecto) |
| `bruja` | CLI tool for on-device LLM queries on Apple Silicon | [SwiftBruja](https://github.com/intrusive-memory/SwiftBruja) |
| `hablare` | Audio and speech processing CLI | [SwiftHablare](https://github.com/intrusive-memory/SwiftHablare) |
| `echada` | AI-powered cast management for screenplay projects | [SwiftEchada](https://github.com/intrusive-memory/SwiftEchada) |

Requires **macOS 26+** and **Apple Silicon** (M1/M2/M3/M4).

[View Tap Repository →](https://github.com/intrusive-memory/homebrew-tap)

---

## Dependency Graph

<table width="100%">
<tr>
<td colspan="5" align="center">

**Application Layer**

</td>
</tr>
<tr>
<td colspan="5" align="center">
<a href="https://github.com/intrusive-memory/SwiftEchada">
<img src="https://img.shields.io/badge/Swift-Echada-blueviolet?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftEchada"/>
</a>
<br/><sub>AI-powered cast management</sub>
</td>
</tr>
<tr>
<td colspan="5" align="center"><code>depends on ↓</code></td>
</tr>
<tr>
<td colspan="5" align="center">

**Library Layer**

</td>
</tr>
<tr>
<td width="25%" align="center">
<a href="https://github.com/intrusive-memory/SwiftHablare">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftHablare/development/icon-sm.png" alt="SwiftHablare" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftHablare">Hablare</a></strong>
<br/><sub>Audio &amp; speech</sub>
</td>
<td width="25%" align="center">
<a href="https://github.com/intrusive-memory/SwiftProyecto">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftProyecto/development/icon-sm.png" alt="SwiftProyecto" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftProyecto">Proyecto</a></strong>
<br/><sub>Build automation</sub>
</td>
<td width="25%" align="center">
<a href="https://github.com/intrusive-memory/SwiftSecuencia">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftSecuencia/development/icon-sm.png" alt="SwiftSecuencia" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftSecuencia">Secuencia</a></strong>
<br/><sub>FCPXML timelines</sub>
</td>
<td width="25%" align="center">
</td>
</tr>
<tr>
<td colspan="5" align="center"><code>depends on ↓</code></td>
</tr>
<tr>
<td colspan="5" align="center">

**Foundation Layer**

</td>
</tr>
<tr>
<td width="20%" align="center">
<a href="https://github.com/intrusive-memory/SwiftCompartido">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftCompartido/development/icon-sm.png" alt="SwiftCompartido" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftCompartido">Compartido</a></strong>
<br/><sub>Shared utilities</sub>
</td>
<td width="20%" align="center">
<a href="https://github.com/intrusive-memory/SwiftFijos">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftFijos/development/icon-sm.png" alt="SwiftFijos" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftFijos">Fijos</a></strong>
<br/><sub>Fixed data structures</sub>
</td>
<td width="20%" align="center">
<a href="https://github.com/intrusive-memory/SwiftBruja">
<img src="https://raw.githubusercontent.com/intrusive-memory/SwiftBruja/development/icon-sm.png" alt="SwiftBruja" width="100"/>
</a>
<br/><strong><a href="https://github.com/intrusive-memory/SwiftBruja">Bruja</a></strong>
<br/><sub>On-device LLM</sub>
</td>
<td width="20%" align="center">
</td>
<td width="20%" align="center">
</td>
</tr>
</table>

<details>
<summary><strong>Dependency Details</strong></summary>

| Package | Depends On |
|---------|-----------|
| **SwiftEchada** | SwiftProyecto, SwiftHablare, SwiftBruja |
| **SwiftHablare** | SwiftFijos, SwiftCompartido, SwiftProyecto |
| **SwiftSecuencia** | SwiftCompartido, SwiftFijos |
| **SwiftProyecto** | SwiftBruja |
| **SwiftCompartido** | SwiftFijos |
| **SwiftFijos** | _(leaf)_ |
| **SwiftBruja** | _(leaf)_ |

</details>

---

## Projects

### SwiftHablare
[![Tests](https://github.com/intrusive-memory/SwiftHablare/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftHablare/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftHablare)](https://github.com/intrusive-memory/SwiftHablare/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftHablare)](https://github.com/intrusive-memory/SwiftHablare/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftHablare)](https://github.com/intrusive-memory/SwiftHablare/commits)

A Swift library for audio and speech processing.

[View Repository →](https://github.com/intrusive-memory/SwiftHablare)

---

### SwiftProyecto
[![Tests](https://github.com/intrusive-memory/SwiftProyecto/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftProyecto/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftProyecto)](https://github.com/intrusive-memory/SwiftProyecto/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftProyecto)](https://github.com/intrusive-memory/SwiftProyecto/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftProyecto)](https://github.com/intrusive-memory/SwiftProyecto/commits)

A Swift project management and build automation framework.

[View Repository →](https://github.com/intrusive-memory/SwiftProyecto)

---

### SwiftCompartido
[![Tests](https://github.com/intrusive-memory/SwiftCompartido/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftCompartido/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftCompartido)](https://github.com/intrusive-memory/SwiftCompartido/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftCompartido)](https://github.com/intrusive-memory/SwiftCompartido/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftCompartido)](https://github.com/intrusive-memory/SwiftCompartido/commits)

Shared Swift utilities and common components for cross-project development.

[View Repository →](https://github.com/intrusive-memory/SwiftCompartido)

---

### SwiftFijos
[![Tests](https://github.com/intrusive-memory/SwiftFijos/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftFijos/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftFijos)](https://github.com/intrusive-memory/SwiftFijos/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftFijos)](https://github.com/intrusive-memory/SwiftFijos/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftFijos)](https://github.com/intrusive-memory/SwiftFijos/commits)
![Version](https://img.shields.io/badge/version-1.0.1-blue.svg)

Swift utilities for fixed and constrained data structures.

[View Repository →](https://github.com/intrusive-memory/SwiftFijos)

---

### SwiftBruja
[![Tests](https://github.com/intrusive-memory/SwiftBruja/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftBruja/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftBruja)](https://github.com/intrusive-memory/SwiftBruja/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftBruja)](https://github.com/intrusive-memory/SwiftBruja/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftBruja)](https://github.com/intrusive-memory/SwiftBruja/commits)

On-device LLM for Apple Silicon — CLI and Swift library for downloading models and running queries locally.

[View Repository →](https://github.com/intrusive-memory/SwiftBruja)

---

### SwiftEchada
[![Tests](https://github.com/intrusive-memory/SwiftEchada/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftEchada/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftEchada)](https://github.com/intrusive-memory/SwiftEchada/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftEchada)](https://github.com/intrusive-memory/SwiftEchada/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftEchada)](https://github.com/intrusive-memory/SwiftEchada/commits)

AI-powered cast management for screenplay projects. Extracts characters from screenplay files using local LLM inference and matches them to TTS voices.

[View Repository →](https://github.com/intrusive-memory/SwiftEchada)

---

### SwiftSecuencia
[![Tests](https://github.com/intrusive-memory/SwiftSecuencia/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftSecuencia/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftSecuencia)](https://github.com/intrusive-memory/SwiftSecuencia/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftSecuencia)](https://github.com/intrusive-memory/SwiftSecuencia/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftSecuencia)](https://github.com/intrusive-memory/SwiftSecuencia/commits)

A Swift library for generating and exporting Final Cut Pro X timelines via FCPXML.

[View Repository →](https://github.com/intrusive-memory/SwiftSecuencia)

---

### SwiftPruebas
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftPruebas)](https://github.com/intrusive-memory/SwiftPruebas/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftPruebas)](https://github.com/intrusive-memory/SwiftPruebas/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftPruebas)](https://github.com/intrusive-memory/SwiftPruebas/commits)

Swift testing utilities.

[View Repository →](https://github.com/intrusive-memory/SwiftPruebas)

---

## Experimental Projects

| Project | Description |
|---------|-------------|
| [SwiftFFMpeg](https://github.com/intrusive-memory/SwiftFFMpeg) | Swift wrapper for FFmpeg multimedia framework (96.2% Swift) ![Experimental](https://img.shields.io/badge/status-experimental-yellow.svg) |
| [SwiftEspeak](https://github.com/intrusive-memory/SwiftEspeak) | Swift wrapper for eSpeak text-to-speech synthesis ![Experimental](https://img.shields.io/badge/status-experimental-yellow.svg) |

---

## Archived Projects

| Project | Description |
|---------|-------------|
| [SwiftGuion](https://github.com/intrusive-memory/SwiftGuion) | Swift library for screenplay file handling. Depended on SwiftFijos. |

---

## Infrastructure & Tools

| Repository | Description |
|------------|-------------|
| [homebrew-tap](https://github.com/intrusive-memory/homebrew-tap) | Homebrew tap for proyecto, bruja, and hablare CLI tools |
| [github-actions](https://github.com/intrusive-memory/github-actions) | Shared GitHub Actions for intrusive-memory projects |
| [skills](https://github.com/intrusive-memory/skills) | Claude Code skills for iOS/macOS development, UI/UX design, and automation |
| [app-store-connect-mcp-server](https://github.com/intrusive-memory/app-store-connect-mcp-server) | App Store Connect MCP server |
| [pipeline](https://github.com/intrusive-memory/pipeline) | A Swift framework for working with Final Cut Pro X FCPXML files |
| [espeak-ng](https://github.com/intrusive-memory/espeak-ng) | Fork of eSpeak NG speech synthesizer |
| [espeak](https://github.com/intrusive-memory/espeak) | Fork of eSpeak speech synthesizer |
| [ffmpeg-framework](https://github.com/intrusive-memory/ffmpeg-framework) | FFmpeg framework for Swift integration |
| [package-collection](https://github.com/intrusive-memory/package-collection) | Swift Package Collection for Intrusive Memory libraries |
| [swift-cmark](https://github.com/intrusive-memory/swift-cmark) | Fork of CommonMark parsing and rendering library in C |
| [swift-markdown](https://github.com/intrusive-memory/swift-markdown) | Fork of Swift package for parsing, building, and analyzing Markdown |

---

## About

Intrusive Memory develops Swift-based tools and frameworks with a focus on multimedia processing, audio handling, and developer utilities. All projects are open source and available under permissive licenses.

## Contributing

Contributions are welcome! Please check individual project repositories for specific contribution guidelines.

## License

Each project has its own license. Please refer to the LICENSE file in each repository for details.
