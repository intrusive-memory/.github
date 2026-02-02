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

<div align="center">

<!-- Layer 1: Top-level consumer -->

<a href="https://github.com/intrusive-memory/SwiftEchada">
  <img src="https://img.shields.io/badge/Swift-Echada-blueviolet?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftEchada" height="40"/>
</a>

<br/>
<sub>↓ depends on ↓</sub>
<br/><br/>

<!-- Layer 2: Mid-level consumers -->

<a href="https://github.com/intrusive-memory/SwiftHablare">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftHablare/main/SwiftHablare.jpg" alt="SwiftHablare" width="80" height="80" style="border-radius:12px"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftProyecto">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftProyecto/main/SwiftProyecto.jpg" alt="SwiftProyecto" width="80" height="80" style="border-radius:12px"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftSecuencia">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftSecuencia/main/SwiftSecuencia.jpg" alt="SwiftSecuencia" width="80" height="80" style="border-radius:12px"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftGuion">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftGuion/main/Examples/GuionViewer/GuionViewer/Assets.xcassets/GuionAppIcon.appiconset/appicon_128x128.png" alt="SwiftGuion" width="80" height="80" style="border-radius:12px"/>
</a>

<br/>
<sub>
<a href="https://github.com/intrusive-memory/SwiftHablare">Hablare</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftProyecto">Proyecto</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftSecuencia">Secuencia</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftGuion">Guion</a>
</sub>
<br/>
<sub>↓ depends on ↓</sub>
<br/><br/>

<!-- Layer 3: Foundation libraries -->

<a href="https://github.com/intrusive-memory/SwiftCompartido">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftCompartido/main/SwiftCompartido.jpg" alt="SwiftCompartido" width="80" height="80" style="border-radius:12px"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftFijos">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftFijos/main/SwiftFijos.jpg" alt="SwiftFijos" width="80" height="80" style="border-radius:12px"/>
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftBruja">
  <img src="https://raw.githubusercontent.com/intrusive-memory/SwiftBruja/main/SwiftBruja.jpg" alt="SwiftBruja" width="80" height="80" style="border-radius:12px"/>
</a>

<br/>
<sub>
<a href="https://github.com/intrusive-memory/SwiftCompartido">Compartido</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftFijos">Fijos</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftBruja">Bruja</a>
</sub>

</div>

### Dependency Details

| Package | Depends On |
|---------|-----------|
| **SwiftEchada** | SwiftProyecto, SwiftHablare, SwiftBruja |
| **SwiftHablare** | SwiftFijos, SwiftCompartido, SwiftProyecto |
| **SwiftSecuencia** | SwiftCompartido, SwiftFijos |
| **SwiftGuion** | SwiftFijos |
| **SwiftProyecto** | SwiftBruja |
| **SwiftCompartido** | SwiftFijos |
| **SwiftFijos** | _(leaf)_ |
| **SwiftBruja** | _(leaf)_ |

---

## Experimental Projects

<div align="center">

<a href="https://github.com/intrusive-memory/SwiftFFMpeg">
  <img src="https://img.shields.io/badge/Swift-FFMpeg-yellow?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftFFMpeg" height="40"/>
</a>
&nbsp;&nbsp;
<a href="https://github.com/intrusive-memory/SwiftEspeak">
  <img src="https://img.shields.io/badge/Swift-Espeak-yellow?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftEspeak" height="40"/>
</a>

</div>

These projects are experimental and not ready for production use.

| Project | Description |
|---------|-------------|
| [SwiftFFMpeg](https://github.com/intrusive-memory/SwiftFFMpeg) | Swift wrapper for FFmpeg multimedia framework (96.2% Swift) |
| [SwiftEspeak](https://github.com/intrusive-memory/SwiftEspeak) | Swift wrapper for eSpeak text-to-speech synthesis |

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

### SwiftGuion
[![Tests](https://github.com/intrusive-memory/SwiftGuion/actions/workflows/tests.yml/badge.svg)](https://github.com/intrusive-memory/SwiftGuion/actions/workflows/tests.yml)
[![Open Issues](https://img.shields.io/github/issues/intrusive-memory/SwiftGuion)](https://github.com/intrusive-memory/SwiftGuion/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/intrusive-memory/SwiftGuion)](https://github.com/intrusive-memory/SwiftGuion/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/intrusive-memory/SwiftGuion)](https://github.com/intrusive-memory/SwiftGuion/commits)

Guion means "screenplay" in Spanish. Swift library for screenplay file handling.

[View Repository →](https://github.com/intrusive-memory/SwiftGuion)

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
