<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img src="assets/logo-light.png" alt="MAGtelligent" width="360">
  </picture>
</p>

<h1 align="center">MAG AI Connector</h1>

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
