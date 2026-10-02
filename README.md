<div align="center">

# ⚡ THUNDER CLIENT

### A Modern • Lightweight • Powerful Minecraft Launcher

<p>
<img src="https://img.shields.io/badge/Kotlin-2.4+-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
<img src="https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Compose%20Desktop-UI-4285F4?style=for-the-badge">
<img src="https://img.shields.io/badge/Minecraft-Launcher-FFC400?style=for-the-badge">
</p>

<p>
<img src="https://img.shields.io/github/stars/L0yalPr0b0y/ThunderClient?style=flat-square&color=FFC400">
<img src="https://img.shields.io/github/forks/L0yalPr0b0y/ThunderClient?style=flat-square">
<img src="https://img.shields.io/github/issues/L0yalPr0b0y/ThunderClient?style=flat-square">
</p>

<br>

<a href="https://github.com/L0yalPr0b0y/ThunderClient/releases">
<img src="https://img.shields.io/badge/⚡%20DOWNLOAD-FFC400?style=for-the-badge">
</a>

<a href="https://github.com/L0yalPr0b0y/ThunderClient">
<img src="https://img.shields.io/badge/💻%20SOURCE%20CODE-181717?style=for-the-badge&logo=github">
</a>

</div>

---

## ⚡ About Thunder Client

**Thunder Client** is a modern Minecraft launcher built with **Kotlin** and **JetBrains Compose Desktop**.

The goal is simple:

> **Fast. Clean. Lightweight. Powerful.**

Thunder Client is designed to make managing Minecraft versions, profiles, Java and game files simple while keeping the launcher lightweight and easy to use.

---

## ✨ Features

### 🎮 Minecraft

* Multiple Minecraft versions
* Vanilla profiles
* Fabric profiles
* Forge profiles
* OptiFine profiles
* Automatic libraries
* Automatic assets
* Native library support

### ⚡ Launcher

* Modern dark interface
* Lightweight design
* Custom window size
* Persistent settings
* Automatic RAM detection
* Manual RAM selection
* Java 21 detection
* Background downloads

### 👤 Accounts

* Offline accounts
* Multiple profiles
* Account selection
* Minecraft-style usernames
* Offline UUID generation

### 🧩 Game Management

* Automatic version downloads
* Library management
* Asset management
* Native extraction
* Minecraft logs
* Separate launcher directory

---

# 🖥️ Screenshots

Screenshots will be added as the launcher UI develops.

<div align="center">

### 🏠 Home

<img src="screenshots/home.png" width="850">

<br><br>

### 📦 Versions

<img src="screenshots/versions.png" width="850">

<br><br>

### ⚙️ Settings

<img src="screenshots/settings.png" width="850">

</div>

---

# 🎨 Design

Thunder Client uses a dark interface with a signature thunder-yellow accent.

| Element          | Color     |
| ---------------- | --------- |
| ⚡ Thunder Yellow | `#FFC400` |
| 🖤 Background    | `#070707` |
| 🖤 Sidebar       | `#0B0B0B` |
| ◼ Card           | `#101010` |
| ◼ Card Light     | `#161616` |
| ⚪ White          | `#F5F5F5` |
| 🔘 Gray          | `#858585` |
| 🔲 Border        | `#252525` |
| 🔴 Error         | `#FF5555` |

---

# 🛠️ Built With

| Technology                  | Purpose                    |
| --------------------------- | -------------------------- |
| **Kotlin**                  | Main programming language  |
| **Compose Desktop**         | User interface             |
| **Java 21**                 | Runtime                    |
| **Gradle**                  | Build system               |
| **Kotlin Coroutines**       | Background operations      |
| **Mojang Version Manifest** | Minecraft version metadata |

---

# 📦 Installation

## Requirements

* Windows 10 / Windows 11
* Java 21
* Internet connection

## Run From Source

Clone the repository:

```bash
git clone https://github.com/L0yalPr0b0y/ThunderClient.git
```

Enter the project:

```bash
cd ThunderClient
```

Run Thunder Client:

```powershell
.\gradlew.bat :desktopApp:run
```

---

# 📁 Project Structure

```text
ThunderClient/
│
├── desktopApp/
│   └── src/
│       └── main/
│           ├── kotlin/
│           │   └── com/
│           │       └── thunderclient/
│           │           └── launcher/
│           │               └── main.kt
│           │
│           └── resources/
│               └── images/
│                   └── thunder_logo.png
│
├── shared/
│
├── gradle/
│
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

---

# 📂 Minecraft Data

Thunder Client keeps its Minecraft data inside:

```text
%APPDATA%\.thunderclient
```

Example:

```text
.thunderclient/
│
├── versions/
├── libraries/
├── assets/
├── natives/
├── mods/
└── logs/
```

---

# 🗺️ Roadmap

### Launcher

* [x] Modern launcher UI
* [x] Dark theme
* [x] Minecraft version management
* [x] Offline accounts
* [x] Java detection
* [x] Asset downloading
* [x] Library downloading
* [x] RAM settings
* [x] Window settings

### Profiles

* [x] Vanilla profile
* [ ] Fabric improvements
* [ ] Forge improvements
* [ ] OptiFine improvements
* [ ] Advanced profile manager

### Future

* [ ] 🧩 Mod Manager
* [ ] 🎨 Resource Pack Manager
* [ ] ✨ Shader Manager
* [ ] 👕 Skin Manager
* [ ] 🌐 Server Manager
* [ ] 🔄 Auto Updater
* [ ] 📥 Advanced Download Manager
* [ ] 🎮 More Minecraft Versions

---

# 🤝 Contributing

Contributions and suggestions are welcome.

Fork the repository, create your feature branch and submit a Pull Request.

```bash
git checkout -b feature/my-feature
```

```bash
git add .
git commit -m "Add new feature"
git push origin feature/my-feature
```

---

# 🐛 Bug Reports

Found a bug?

Please open a GitHub Issue and include:

* Windows version
* Java version
* Minecraft version
* Thunder Client version
* Steps to reproduce
* Error message
* Crash log
* Screenshot

---

# 👨‍💻 Developer

<div align="center">

## ⚡ Loyalproboy650

**Creator & Developer of Thunder Client**

Building a modern Minecraft launcher with Kotlin and Compose Desktop.

<br>

<a href="https://github.com/L0yalPr0b0y">
<img src="https://img.shields.io/badge/GitHub-L0yalPr0b0y-181717?style=for-the-badge&logo=github">
</a>

</div>

---

# ⭐ Support The Project

If you like **Thunder Client**, consider giving the repository a ⭐.

Your support helps the project grow.

<div align="center">

## ⚡ Build. Launch. Play.

# THUNDER CLIENT

**A lightweight Minecraft launcher by Loyalproboy650.**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=FFC400&height=100&section=footer">

</div>
