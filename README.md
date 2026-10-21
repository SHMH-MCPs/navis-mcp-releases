# Navisworks MCP

**AI clash detection and model review in Navisworks Manage 2025–2027.**

Navisworks MCP is a free plug-in for Autodesk Navisworks Manage with a [Model Context Protocol](https://modelcontextprotocol.io)
(MCP) server. Claude, ChatGPT, Codex, Cursor and other AI assistants use it to work with the coordination model open in
Navisworks — clashes, sets, viewpoints and QA reports — and learn, with your team, from every fix.

**Website:** https://aecomcps.com/navisworks · **Download:** [Install-Navisworks-MCP.cmd (latest release)](https://github.com/SHMH-MCPs/navis-mcp-releases/releases/latest/download/Install-Navisworks-MCP.cmd)

[![Install Navisworks MCP and start using it — about 2 minutes](https://aecomcps.com/media/install-navisworks-mcp.jpg)](https://aecomcps.com/navisworks#video)

## What it does

- **Clash Detective** — create, edit, run, import and export tests; review, assign, comment, group and summarise clashes
- **Coordination QA** — check the model against a clash matrix (Excel, CSV, JSON or XML), audit the NWF, write
  interactive HTML, Excel, CSV or JSON reports
- **Model and properties** — browse the selection tree, read and compare properties, find items by any property
- **Sets and viewpoints** — create, edit, import and export search sets, selection sets and viewpoints
- **Views and display** — colour, hide and isolate items, section, set the camera, measure, take screenshots
- **TimeLiner and quantities** — read and edit TimeLiner tasks and data sources, read Quantification
- **Files and exports** — append and merge models, save and publish NWD, export DWF
- **Learns from fixes** — lessons from jobs that went well are shared, privacy-filtered, with the team

Deletes are previewed first, each change is one Undo step, source models (RVT, DWG, IFC) are never changed, and a
read-only mode is available.

## Supported versions

| | |
|---|---|
| Navisworks | Manage 2025, 2026, 2027 (Navisworks Freedom has no plug-in support) |
| Windows | 64-bit |
| Account | Google or GitHub (the same sign-in as Revit MCP) |
| Price | Free |

## Install

1. Download **[Install-Navisworks-MCP.cmd](https://github.com/SHMH-MCPs/navis-mcp-releases/releases/latest/download/Install-Navisworks-MCP.cmd)**
   and open it. No administrator rights needed.
2. Choose your Navisworks versions (the ones on this PC are ticked) and sign in once with **Google** or **GitHub**.
3. Restart your AI assistant, open Navisworks Manage and your model, and ask — for example "Run the clash tests and show
   me the 10 deepest clashes with their grid locations." Updates install themselves.

Guide: [AI clash detection in Navisworks with Navisworks MCP](https://aecomcps.com/guides/ai-clash-detection-navisworks).

## Supported AI apps

- **Connected automatically:** Claude Code, the Claude app (also the Microsoft Store version), Codex, Cursor, VS Code,
  Windsurf, Gemini CLI, Cline
- **Any MCP client:** `navis-mcp.exe` over stdio
- **ChatGPT and claude.ai in the browser:** optional cloud AI access (off until you switch it on), connector address
  `https://aecomcps.com/mcp/navisworks`

## Privacy

The model, its properties and clash results go only to the AI assistant you connected, under its provider's terms.
Navisworks MCP shares only AI-learning information — names, paths, GUIDs, numbers and values removed on the PC and
again at the gateway — and learning can be switched off. Reports stay on your PC in
`Documents\MCPs\Navisworks MCP reports`. Details: [privacy policy](https://aecomcps.com/privacy).

## Questions

shady.hefilla@hotmail.com · [Revit MCP](https://github.com/SHMH-MCPs/revit-mcp-releases) works the same way for Revit 2024–2027.

---

Revit and Navisworks are trademarks of Autodesk, Inc. AECO MCPs is independent and not affiliated with Autodesk.
