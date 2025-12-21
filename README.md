# 🧩 HelperPackage

**HelperPackage** is a simple terminal-based guide designed to help new and intermediate users understand and use common CLI tools.  
It provides quick, organized slides with explanations and usage examples for packages available in Termux or Linux.

---

## 📘 About

HelperPackage works as a **wrapper** around pre-made Markdown guides that are displayed using the `slides` tool.  
Each guide contains essential information about a specific command-line tool — its purpose, syntax, and examples — all presented in a clean, scrollable TUI format.

---

## ⚙️ How It Works

The command structure is:

```
helperpackage -g <package>
```
For example:
```
helperpackage -g ffmpeg
helperpackage -g python
helperpackage -g shell
```
You can also list all available guides:
```
helperpackage -lg
```
And, of course, see help:
```
helperpackage -h
```

also, you can look for updates using `--update` or `-u`:
```
helperpackage --update
```
or:
```
helperpackage -u
```
---

📚 Available Guides

Category	Packages Covered

* 🖼️ Media Manipulation;	ffmpeg, imagemagick
* 🌐 Web Tools;	curl, wget
* 🧮 Programming; python
* 📁 Git & Version Control
* 💻 Text Editor:	nano, micro, vi, vim, nvim, etc.
* ⚙️ Termux & System in android version: termux-tools, termux-x11
* 🐚 Shell / CLI: bash, sh, cli-tools, and general shell commands



---

📱 Android (Termux) Version

This version of HelperPackage was built specifically for Termux users.

---

💻 Future Desktop (Linux) Version

A dedicated Linux (Debian-based) version is planned.
It will:

Install guides in /usr/share/helperpackage

Work out of the box in any Debian-based distro (Ubuntu, Mint, etc.)

Include some PC-specific tools (like mount.)

---

🧠 Notes

HelperPackage is not meant to replace man pages or full documentation.
It provides quick, summarized learning slides for everyday CLI use.

You can request new guide topics by messaging on Discord or opening an issue on the GitHub repo.

my discord: @night_dragon_0

<details>
  <summary>Code Info</summary>
  if you dont know if the project is open or closed source, check the `sourcenote.md` file.
</details>
