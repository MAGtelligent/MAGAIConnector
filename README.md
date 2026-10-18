<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img src="assets/logo-light.png" alt="MAGtelligent" width="360">
  </picture>
</p>

<h1 align="center">
  <img src="assets/app-icon.png" alt="" width="40" height="40" align="absmiddle">&nbsp;MAG AI Connector
</h1>

<p align="center">
  Connect your Autodesk design apps to AI assistants, in a few clicks.<br>
  <a href="https://github.com/MAGtelligent/MAGAIConnector/releases/latest"><b>Download the latest version</b></a>
</p>

---

MAG AI Connector lets AI assistants such as **Claude**, **Codex** and **Cursor** work directly with your open
**Revit**, **Navisworks**, **Civil 3D** and **AutoCAD** models: ask questions about a model, find and select
elements, check clashes, draw, and more. You choose which design apps and which AI apps to connect; the app installs
everything they need, connects them, and tests the connection for you. No programming is needed.

## Supported apps

| Design apps | Versions |
|---|---|
| Autodesk Revit | 2024 – 2027 |
| Autodesk Navisworks Manage / Simulate | 2025 – 2027 |
| Autodesk Civil 3D | 2025 – 2027 |
| Autodesk AutoCAD (and products built on it) | 2018 and newer (not AutoCAD LT) |

| AI apps |
|---|
| Claude Desktop · Claude Code · OpenAI Codex · Cursor · OpenCode |

## MCP servers used

Each design app is connected through an open-source **MCP server**: the part that gives the AI its tools (for
example "list the levels", "select these elements" or "draw a line"). To see exactly which tools the AI gets in each
app, open its GitHub page:

| Design app | MCP server (tools listed on its page) | Version installed |
|---|---|---|
| Revit | [mcp-server-for-revit-python](https://github.com/mcp-servers-for-revit/mcp-server-for-revit-python) (runs inside Revit through pyRevit) | [6ca46b3](https://github.com/mcp-servers-for-revit/mcp-server-for-revit-python/tree/6ca46b3ea96a8f7cce9894cf865d8f19ca2c549d) |
| Navisworks | [Navisworks_MCP](https://github.com/Aitology/Navisworks_MCP) by Aitology | [97c3b63](https://github.com/Aitology/Navisworks_MCP/tree/97c3b63d798f3ce9e6cec320fb13560a3165be2d) |
| Civil 3D | [Civil3D-mcp](https://github.com/Sacred-G/Civil3D-mcp) by Sacred-G | [9e437a3](https://github.com/Sacred-G/Civil3D-mcp/tree/9e437a3bab6df4ba13fabc2e909e138e8ac15896) |
| AutoCAD | [CAD-MCP](https://github.com/daobataotie/CAD-MCP) by daobataotie | [bfcf9bb](https://github.com/daobataotie/CAD-MCP/tree/bfcf9bb1da8f828b0787af12194717364a7c4a50) |

- **Version installed** is the exact version the latest release was tested with; MAG AI Connector downloads that
  version, not the newest one, so the tools on the project's main page may differ.
- MAG AI Connector makes a few small changes for safety and reliability, for example the read-only modes for
  Navisworks and AutoCAD (under **Settings**) and making the AutoCAD server use the AutoCAD that is already open
  instead of starting one.
- These projects belong to their authors and are not part of MAG AI Connector.

## Install

1. Download **MAGAIConnector-Setup-&lt;version&gt;.exe** from the [latest release](https://github.com/MAGtelligent/MAGAIConnector/releases/latest).
2. Run it. No administrator rights are needed.
   If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**.
3. Start **MAG AI Connector** and follow the steps: choose your apps, click **Install**, connect, and test.

**Requirements:** Windows 10 (version 1809 or later) or Windows 11, 64-bit, and an internet connection during setup.

## Good to know

- The AI can change your models. You stay in control under **Settings**: Revit can ask before changes and before
  running code, Navisworks and AutoCAD can be made read-only, and Civil 3D can require your approval for
  destructive changes.
- Settings files of your AI apps are backed up before they are changed, and only the MAG AI Connector entries are
  touched.
- To remove the app, use **Settings › Apps › Installed apps** in Windows. Disconnect your AI apps inside MAG AI
  Connector first if you also want their entries removed.

## Support

Found a problem or have an idea? [Open an issue](https://github.com/MAGtelligent/MAGAIConnector/issues).

---

<sub>© MAGtelligent · Software & AI Solutions. Autodesk, Revit, Navisworks, Civil 3D and AutoCAD are trademarks of
Autodesk, Inc.; Claude of Anthropic; Codex of OpenAI; Cursor of Anysphere. MAG AI Connector is not affiliated with or
endorsed by them.</sub>
