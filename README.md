# 📦 sysinfo

A lightweight, fast terminal system information tool for macOS and Linux.

It provides quick access to system stats like CPU usage, memory, disk, battery, network status, and full system specs — all from a simple command-line interface.

---

## 🚀 Features

- 📊 System overview dashboard
- 🖥️ Full hardware specs (CPU, GPU, RAM, OS)
- ⚡ CPU usage monitoring
- 💾 Disk usage stats
- 🔋 Battery status (macOS + Linux)
- 🌐 Network connectivity + latency test
- 🧠 Simple, fast CLI interface
- 🪶 No dependencies (pure Bash)

---

## 📥 Installation

### 1. Clone the repository

```bash
git clone https://github.com/d1gallar/sysinfo.git
cd sysinfo/sysinfo
```

### 2. Make setup executable

```bash
chmod +x ./setup
```


### 3. Install system-wide

```bash
./setup install
```

This installs sysinfo package into your system path (usually /.local/bin).

## 📥 Usage

### Main Command
```bash
sysinfo
```
Shows a system overview dashboard.

## 📚 Commands

| Command           | Description                    |
| ----------------- | ------------------------------ |
| `sysinfo`         | System overview (default)      |
| `sysinfo info`    | System overview (explicit)     |
| `sysinfo specs`   | Full hardware + OS details     |
| `sysinfo cpu`     | CPU usage + cores              |
| `sysinfo disk`    | Disk usage                     |
| `sysinfo battery` | Battery status                 |
| `sysinfo network` | Network latency + connectivity |
| `sysinfo help`    | Show help menu                 |

## ⚙️ Uninstall

Here are the steps to uninstall:

```bash
./setup uninstall
 ```
or manually

```
rm ~/.local/bin/sysinfo
```
## 💻 Installer

### Command Usage

Installs the package into the local path (/.local/bin).
```bash
chmod +x setup.sh
./setup install
```

Uninstalls the package.
```bash
./setup uninstall
```

Checks the status of whether the package was installed.
```bash
./setup status
```
