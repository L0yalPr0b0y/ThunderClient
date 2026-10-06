<div align="center">

<img src="https://raw.githubusercontent.com/L0yalPr0b0y/ThunderClient/main/assets/thunder_.png" width="520" alt="Thunder Client">

<br>

### ⚡ The Next Generation Minecraft Launcher

**Launch faster. Manage easier. Play better.**

A modern, lightweight and powerful Minecraft: Java Edition launcher<br>
built with **Kotlin** + **JetBrains Compose Desktop**.

<br>

<a href="https://github.com/L0yalPr0b0y/ThunderClient/releases/latest">
  <img src="https://img.shields.io/badge/⚡%20DOWNLOAD%20LATEST-FFC400?style=for-the-badge&labelColor=101010" alt="Download">
</a>
<a href="https://discord.gg/qF26hUTCmD">
  <img src="https://img.shields.io/badge/DISCORD-JOIN%20US-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
</a>
<a href="https://github.com/L0yalPr0b0y/ThunderClient">
  <img src="https://img.shields.io/badge/SOURCE-GITHUB-181717?style=for-the-badge&logo=github" alt="Source">
</a>

<br><br>

<img src="https://img.shields.io/github/downloads/L0yalPr0b0y/ThunderClient/total?style=flat-square&label=Downloads&color=FFC400&labelColor=101010">
<img src="https://img.shields.io/github/stars/L0yalPr0b0y/ThunderClient?style=flat-square&color=FFC400&labelColor=101010">
<img src="https://img.shields.io/github/forks/L0yalPr0b0y/ThunderClient?style=flat-square&color=FFC400&labelColor=101010">
<img src="https://img.shields.io/github/issues/L0yalPr0b0y/ThunderClient?style=flat-square&color=FFC400&labelColor=101010">
<img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-FFC400?style=flat-square&labelColor=101010">
<img src="https://img.shields.io/badge/Java-21-FFC400?style=flat-square&labelColor=101010">

<br><br>

[**About**](#-about) · [**Features**](#-features) · [**Screenshots**](#-screenshots) · [**Install**](#-installation) · [**Roadmap**](#-roadmap) · [**Privacy**](#-privacy--legal) · [**Support**](#-support)

</div>

---

## ⚡ About

**Thunder Client** is a clean, fast and modern launcher for Minecraft: Java Edition. It takes care of versions, profiles, libraries, assets and Java detection for you, so you can spend less time setting up and more time playing.

Built from the ground up with Kotlin and Compose Desktop, wrapped in a dark interface with a signature **thunder-yellow** accent.

<div align="center">

| ⚡ Fast | 🪶 Lightweight | 🎨 Modern | 🔓 Open Source |
|:---:|:---:|:---:|:---:|
| Background downloads | Native desktop app | Premium dark UI | Free, forever |

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎮 Minecraft
- Multiple Minecraft versions
- Vanilla, Fabric, Forge & OptiFine profiles
- Automatic assets & libraries
- Native library handling
- Dedicated game directory

</td>
<td width="50%" valign="top">

### 🚀 Launcher
- Modern dark UI
- Automatic RAM detection
- Manual RAM allocation
- Java 21 detection
- Custom window size
- Persistent settings
- Background downloads

</td>
</tr>
<tr>
<td valign="top">

### 👤 Accounts
- 🪟 **Microsoft account login** (official device-code sign-in)
- Offline profiles for singleplayer & local testing
- Multiple accounts & quick switching
- Minecraft-style username validation

</td>
<td valign="top">

### 🧩 Management
- Version management
- Game-file management
- Download management
- Logs viewer
- Mods directory
- Partner servers panel

</td>
</tr>
</table>

---

## 🔐 Secure Microsoft Sign-In

Thunder Client signs you in with Microsoft's **official device-code flow**:

```text
1. Click "Sign in with Microsoft"
2. Open the Microsoft page and enter the shown code
3. Approve access in your browser
4. Thunder Client receives your Minecraft profile (name + UUID)
```

> 🛡️ **Your Microsoft password is never entered into Thunder Client.**
> Tokens stay on your own computer. No analytics, no tracking.
> See the [Privacy Policy](PRIVACY.md) for details.

---

## 🖥️ Screenshots

<div align="center">

### 🏠 Home
<img src="screenshots/home.png" width="850" alt="Home">

<br><br>

### 📦 Versions
<img src="screenshots/versions.png" width="850" alt="Versions">

<br><br>

### ⚙️ Settings
<img src="screenshots/settings.png" width="850" alt="Settings">

</div>

---

## 📦 Installation

### Requirements

| Requirement | Details |
|---|---|
| 🖥️ OS | Windows 10 / Windows 11 |
| ☕ Java | Java 21 |
| 🌐 Internet | Needed for downloads & sign-in |

### Quick start

1. Go to the [**Releases**](https://github.com/L0yalPr0b0y/ThunderClient/releases/latest) page.
2. Download the latest installer.
3. Run it and launch **Thunder Client**.
4. Sign in with Microsoft (or add an offline profile), pick a version, press **PLAY**.

<details>
<summary><b>🛠️ Run from source</b></summary>

<br>

```bash
git clone https://github.com/L0yalPr0b0y/ThunderClient.git
cd ThunderClient
./gradlew :desktopApp:run
```

Open the project in IntelliJ IDEA with JDK 21 for the best experience.

</details>

<details>
<summary><b>📂 Data directory</b></summary>

<br>

Thunder Client keeps its data separate from the normal Minecraft folder:

```text
%APPDATA%\.thunderclient
│
├── versions/
├── libraries/
├── assets/
├── natives/
├── mods/
└── logs/
```

</details>

---

## 🧱 Architecture

```text
Thunder Client
│
├── Launcher UI
│   ├── Home
│   ├── Profiles
│   ├── Mods
│   ├── Accounts
│   └── Settings
│
├── Account System
│   ├── Microsoft (device-code sign-in)
│   └── Offline Profiles
│
├── Minecraft Manager
│   ├── Versions
│   ├── Libraries
│   ├── Assets
│   └── Natives
│
└── Game Launcher
    ├── Java Detection
    ├── Classpath
    └── Minecraft Process
```

<details>
<summary><b>🎨 Design system</b></summary>

<br>

| Element | Hex |
|---|---|
| ⚡ Thunder Yellow | `#FFC400` |
| 🖤 Background | `#070707` |
| 🖤 Sidebar | `#0B0B0B` |
| ◼ Card | `#101010` |
| ◼ Card Light | `#161616` |
| ⚪ White | `#F5F5F5` |
| 🔘 Gray | `#858585` |
| 🔲 Border | `#252525` |
| 🔴 Error | `#FF5555` |

</details>

---

## 🛠️ Technology

<div align="center">

<img src="https://skillicons.dev/icons?i=kotlin,java,gradle,idea,github">

</div>

| Technology | Purpose |
|---|---|
| Kotlin | Main programming language |
| Compose Desktop | UI framework |
| Java 21 | Runtime |
| Gradle | Build system |
| Coroutines | Background operations |
| Mojang Version Manifest | Minecraft metadata |

---

## 🚀 Roadmap

| Status | Feature |
|:---:|---|
| ✅ | Modern launcher UI & dark theme |
| ✅ | Version management |
| ✅ | Microsoft account login |
| ✅ | Offline profiles |
| ✅ | Java detection |
| ✅ | Asset & library downloading |
| ✅ | RAM & window settings |
| ✅ | Vanilla profiles |
| 🔧 | Fabric / Forge / OptiFine improvements |
| 🔧 | Advanced profile manager |
| 🕒 | Mod manager |
| 🕒 | Resource pack & shader manager |
| 🕒 | Skin manager |
| 🕒 | Server manager |
| 🕒 | Automatic updater |
| 🕒 | Advanced download manager |

<sub>✅ Done · 🔧 In progress · 🕒 Planned</sub>

---

## 🤝 Contributing

Contributions are welcome!

```bash
git checkout -b feature/my-feature
git add .
git commit -m "Add new feature"
git push origin feature/my-feature
```

Then open a Pull Request.

<details>
<summary><b>🐛 Reporting a bug</b></summary>

<br>

Open an [issue](https://github.com/L0yalPr0b0y/ThunderClient/issues) and include:

- Windows version
- Java version
- Minecraft version
- Thunder Client version
- Steps to reproduce
- Error message / crash log
- Screenshot

</details>

---

## 🔒 Privacy & Legal

- 📄 [**Privacy Policy**](PRIVACY.md)
- 📜 [**Terms of Use**](TERMS.md)
- 📘 [Minecraft EULA](https://www.minecraft.net/eula) · [Usage Guidelines](https://aka.ms/mcusageguidelines)

> Thunder Client is **not** an official Minecraft product and is not approved by or associated with Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Studios.

---

## 💬 Support

<div align="center">

<a href="https://discord.gg/qF26hUTCmD">
  <img src="https://img.shields.io/badge/Join%20our%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</a>
<a href="https://github.com/L0yalPr0b0y/ThunderClient/issues">
  <img src="https://img.shields.io/badge/Report%20an%20Issue-FFC400?style=for-the-badge&logo=github&logoColor=black">
</a>

<br><br>

If you like **Thunder Client**, consider giving the repository a ⭐
Every star helps the project grow.

<br>

<img src="https://github.com/L0yalPr0b0y.png" width="90" style="border-radius:50%">

**⚡ Loyalproboy650**<br>
<sub>Creator & Developer of Thunder Client</sub>

<br>

### ⚡ BUILD. LAUNCH. PLAY.

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFC400&height=120&section=footer">

</div>
