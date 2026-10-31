# Flappy Pipeline Studio - Web Game Generator 2026

> **Flappy Pipeline Studio runs in the browser and generates HTML games: tweak a Flappy Bird-style game to your liking, export it, and optionally ship it through a pipeline built on Agent-Fabric, claude-tunnel, and Caddy.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/junglouis984/flappy-pipeline-studio-2026?style=flat-square)](https://github.com/junglouis984/flappy-pipeline-studio-2026)

---

<p align="center">
  <a href="https://junglouis984.github.io/flappy-pipeline-studio-2026/">
    <img src="https://img.shields.io/badge/Download-Flappy%20Pipeline%20Studio%20Latest-brightgreen?style=for-the-badge" alt="Download Flappy Pipeline Studio">
  </a>
</p>

> **[Direct Download - Flappy Pipeline Studio](https://junglouis984.github.io/flappy-pipeline-studio-2026/)**

---

[Download](https://junglouis984.github.io/flappy-pipeline-studio-2026/)

---

## What Flappy Pipeline Studio Is

Flappy Pipeline Studio lets you build a customized Flappy Bird-style game without leaving the browser. A template-driven HTML generator sits at the center, paired with controls for the bird, the visual theme, and the game's physics. That makes it a practical choice for fast experiments, demos, and game prototypes you want to share.

Beyond the generator, the project demonstrates a role-chain pipeline running over an Agent-Fabric channel. Finished games can be served through an HTTPS tunnel backed by claude-tunnel and Caddy, and the lifecycle can be toggled on or off as needed. What you end up with is one standalone HTML file that downloads and opens on its own.

---

## Features

- Tune the bird's look, the game theme, and physics parameters.
- Export a self-contained HTML game you can download.
- Generate games entirely on the client side from a template.
- Show a role-chain pipeline in action via Agent-Fabric.
- Serve the web experience over HTTPS through a tunnel.
- Turn the pipeline lifecycle on or off whenever needed.
- Work in the browser with no separate game engine.
- Lay groundwork for the planned LLM-agent pipeline generation.

---

## Installation

### Get the repository

```bash
git clone https://github.com/junglouis984/flappy-pipeline-studio-2026.git
cd REPO
```

The project is HTML-based, so the basic local workflow needs no package installation. You can open the main HTML entry point straight in a browser, or serve the directory with a static server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

For the hosted build, use the [Download](https://junglouis984.github.io/flappy-pipeline-studio-2026/) link.

---

## Usage

1. Launch Flappy Pipeline Studio in a current web browser.
2. Pick the bird appearance and the visual theme.
3. Set the physics options that are available.
4. Generate the game from the client-side template.
5. Download the standalone HTML file that results.
6. Open the exported file locally or host it on a web server.
7. To try the pipeline demonstration, enable the relevant lifecycle and set up HTTPS tunnel delivery through the supported Agent-Fabric, claude-tunnel, and Caddy workflow.

Once generated, the HTML file works as a self-contained game artifact you can share, and it does not need the generator interface.

---

## Configuration

You configure the core generator through its browser interface: choose the bird, theme, and physics values, then generate the HTML output.

Pipeline behavior is governed by the project deployment workflow. Where relevant, review the local pipeline and tunnel configuration for:

- How the lifecycle is enabled or disabled.
- Agent-Fabric role-chain settings.
- claude-tunnel connection details.
- Caddy HTTPS delivery settings.

Keep deployment-specific values in the local configuration your environment uses instead of embedding them in generated game files.

---

## Requirements

- A current web browser with JavaScript enabled.
- A local web server for convenient development and testing.
- Python 3 or another static HTTP server for local hosting.
- Network access when using hosted delivery or tunnel-based workflows.
- Caddy and claude-tunnel when running the HTTPS pipeline demonstration.
- Agent-Fabric access when running the role-chain workflow.
- Enough storage for the repository and the generated HTML files.

---

## FAQ

### Do I need the pipeline to use the generator?

No. You can customize and export an HTML game with the client-side generator on its own, without the pipeline delivery workflow.

### Where does the generated game end up?

The result is a standalone HTML file. Save it locally through the browser's download flow or the project interface.

### Can I alter how the game plays?

The physics controls are there to adjust the generated game's behavior. Which options you see depends on the current template and interface.

### What is the quickest way to run it locally?

Clone the repository, start a static server such as `python3 -m http.server 8000`, and open the local address it prints in a browser.

### The hosted page will not load properly. What should I check?

Confirm JavaScript is enabled, then try serving the project through a local HTTP server rather than opening files directly. If you are using tunnel delivery, also check the claude-tunnel and Caddy configuration.

### How do updates arrive?

Updates may be published through the repository and its hosted build. Check the project page for the latest version and generated assets.

### Is LLM-agent generation available yet?

Not yet; LLM-agent pipeline generation is planned. For now the project centers on the client-side generator and the role-chain pipeline demonstration.

---

## Roadmap

- Expand LLM-agent pipeline generation.
- Add more customization options for generated games.
- Refine the role-chain pipeline controls.
- Improve hosted HTTPS delivery workflows.
- Extend configuration and export guidance.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
