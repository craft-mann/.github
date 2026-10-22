<p align="center">
  <a href="https://www.craftmann.app">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/mark-on-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="./assets/mark-on-light.svg">
      <img alt="CraftMann — Well-made tools for people who make things." src="./assets/mark-on-dark.svg" width="128px">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://www.craftmann.app"><b>craftmann.app</b></a> ·
  <a href="#-the-apps">Apps</a> ·
  <a href="#-how-we-build">How we build</a> ·
  <a href="#-contributing">Contributing</a> ·
  <a href="#-security">Security</a>
</p>

---

**CraftMann** is an independent software studio that builds focused desktop apps for Windows and macOS. Each app does one job and does it properly. Each one is free and open source, keeps your files on your machine, and can be driven by you or by your AI agents through MCP and a CLI.

We're starting with **CaptureMann**, and more tools are on the workbench.

## 🧰 The apps

<table>
  <tr>
    <td width="96" align="center" valign="top">
      <a href="https://www.craftmann.app/capturemann"><img src="./assets/capturemann-light.svg" width="72" height="72" alt="CaptureMann icon"></a>
    </td>
    <td valign="top">
      <h3><a href="https://www.craftmann.app/capturemann">CaptureMann</a></h3>
      <p><b>Capture anything. Ship it anywhere.</b><br>
      Screenshots and screen recordings at your display's native resolution, with a webcam bubble. Save locally or to Google Drive, OneDrive or Dropbox, publish to YouTube, TikTok and Facebook, or let your AI agents do it all over MCP and CLI.</p>
      <p>
        <img alt="Status" src="https://img.shields.io/badge/status-v0.1-3DD68C?style=flat-square&labelColor=161619">
        <img alt="Platforms" src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows-EDEDEF?style=flat-square&labelColor=161619">
        <img alt="License" src="https://img.shields.io/badge/license-Apache--2.0-F0B43C?style=flat-square&labelColor=161619">
        <img alt="MCP" src="https://img.shields.io/badge/MCP-ready-5B8CFF?style=flat-square&labelColor=161619">
      </p>
      <p>
        <a href="https://github.com/trung-tlt/capturemann/releases/latest"><b>Download</b></a> ·
        <a href="https://github.com/trung-tlt/capturemann">Source</a> ·
        <a href="https://www.craftmann.app/capturemann">Website</a> ·
        <a href="https://github.com/trung-tlt/capturemann/issues">Issues</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="96" align="center" valign="top">🔜</td>
    <td valign="top">
      <h3>Next app: on the workbench</h3>
      <p>Have a tool you wish existed? <a href="https://github.com/trung-tlt/capturemann/issues">Tell us</a>. Watch this org or follow <a href="https://www.craftmann.app">craftmann.app</a> to hear when it ships.</p>
    </td>
  </tr>
</table>

## 🪵 How we build

| | Principle | What it means |
|---|---|---|
| **1** | **One job, done properly** | Each app solves one problem end to end instead of doing everything halfway. |
| **2** | **Your files, your machine** | Local first. The cloud is somewhere you choose to send things, not where they live. |
| **3** | **Made for humans and agents** | A good interface for you, and an MCP server and CLI for your AI agents and scripts. |
| **4** | **Free, no strings** | No account, no watermark, no subscription. |
| **5** | **Built in the open** | Source you can read, fork and improve, under Apache-2.0. |

## 🤖 Agent-ready by design

Every CraftMann app exposes its features as **MCP tools** and **CLI commands**, so you can run them yourself, script them, or let an AI assistant use them for you. Apps ask before doing anything sensitive, such as saving to the cloud or publishing.

Example: connect CaptureMann to an MCP-compatible client.

```json
{
  "mcpServers": {
    "capturemann": {
      "command": "capturemann-mcp"
    }
  }
}
```

Then ask your agent something like *"Record a 30-second demo of the settings page and upload it unlisted."* See each app's README for its full tool list.

## 🤝 Contributing

Contributions are welcome: bug reports, feature ideas, docs, translations and code.

1. **Find something to work on.** Browse open issues in the app's repo, or open a new one to discuss an idea before writing code.
2. **Read the guide.** Each repo has a `CONTRIBUTING.md` with build steps and conventions.
3. **Open a pull request.** Keep it focused, describe the *why*, and link the issue.

New here? Look for issues labelled `good first issue`.

## 🔒 Security

Please **don't** report security vulnerabilities in public issues. Use GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) on the affected repository (**Security → Report a vulnerability**), or email **[SECURITY EMAIL]**. We'll acknowledge your report and keep you updated while we fix it.

## 🎨 Brand

The CraftMann mark is the **Tool Rack M**: three bars like tools hanging on a workshop rack. Each app has its own symbol and color on a shared dark icon tile. If you're writing about CraftMann or one of its apps, please use the official assets rather than recreating them: [brand kit](https://github.com/craftmann/.github/tree/main/profile/assets) · [craftmann.app](https://www.craftmann.app).

## 📬 Stay in touch

- 🌐 Website: [craftmann.app](https://www.craftmann.app)
- 🐙 GitHub: watch the repos you care about for release notifications
- ✉️ Contact: **[CONTACT EMAIL / LINK]**

---

<p align="center">
  <sub>Made with care by CraftMann · Apps are open source under their own licenses (CaptureMann: Apache-2.0)</sub>
</p>
