# GS USB Runner

**A free, portable Windows automation tool built around GS Script, a beginner-friendly scripting language created by GhostStrats.**

GS USB Runner is designed to help people learn the fundamentals of keyboard and mouse automation through a simple, easy-to-understand scripting language.

Create your own GS Scripts, execute them directly on your Windows computer, convert supported DuckyScript commands, and build standalone Quick Launch executables.

The entire project is free and was created for educational purposes. Whether you're completely new to automation or already have experience with scripting, GS USB Runner provides a hands-on learning environment.

**No installation required. Just download, copy, and launch.**

## Installation — Getting Started

GS USB Runner is a portable application. You do not need an installer, Python, or any additional software.

**Recommended USB setup:**

1. Download the latest `GS-USB-Runner.exe` from the GitHub Releases section.
2. Grab a USB flash drive. I recommend using a blank, properly formatted flash drive.
3. Drag or copy the executable directly onto your USB flash drive.
4. Plug the flash drive into a Windows computer.
5. Double-click `GS-USB-Runner.exe` to launch the application.
6. GS USB Runner automatically creates the folders and settings files it needs.

That's it. You're ready to start learning GS Script.

The application automatically prepares its portable storage, including:

- `scripts/` — Your saved GS Script files.
- `themes/` — Custom backgrounds and themes.
- `settings.json` — Your application preferences.

You can also run GS USB Runner directly from a folder on your Windows computer if you don't want to use a flash drive.

## What Is GS Script?

GS Script is a custom scripting language developed by GhostStrats to make keyboard and mouse automation easier to understand.

Instead of learning a complicated programming language, you can write simple instructions describing what you want the computer to do.

For example:

```text
# Open Notepad
PRESS WINDOWS + R
WAIT 1 SECOND
TYPE "notepad"
PRESS ENTER
WAIT 2 SECONDS

# Type a message
TYPE "Hello from GS USB Runner!"
```

GS USB Runner interprets the script and simulates the necessary keyboard and mouse actions on the Windows computer.

You can automate typing, keyboard shortcuts, mouse movements, clicks, scrolling, and delays.

**Important:** GS USB Runner performs software-based HID-style automation. A normal USB flash drive does not become a physical HID keyboard, and scripts do not automatically execute when the flash drive is plugged in.

## Features

### GS Script Editor

Create, edit, save, and execute custom GS Script files.

The editor allows you to:

- Write your own automation scripts.
- Edit existing scripts.
- Save scripts directly to your USB flash drive.
- Reopen saved scripts through the library.
- Execute scripts locally.
- Validate commands and identify errors.
- Control typing speeds and delays.

### Built-In Script Library

GS USB Runner includes educational examples to help beginners learn how automation works.

Examples include:

- Hello World and Notepad demonstrations.
- Keyboard shortcuts.
- Mouse movement and scrolling.
- Typing and delays.
- GS Matrix.
- Help Desk Helper.
- Rick Roll.
- Additional educational demonstrations.

You can load examples into the editor, study how they work, modify them, and save your own versions.

### My Saved Scripts

All saved scripts are stored in the portable `scripts/` folder.

Your scripts stay with your flash drive, so you can bring your work between compatible Windows computers.

### Keyboard and Mouse Automation

GS Script supports simulated keyboard and mouse input, including:

- Typing text.
- Pressing individual keys.
- Keyboard combinations.
- Mouse movement.
- Mouse clicks.
- Scrolling.
- Timed delays.

### Quick Launch EXE Builder

One of the main features of GS USB Runner is the ability to convert your GS Scripts into standalone Windows executable files.

You can create your own script, review it, and build a Quick Launch EXE that runs the automation when manually opened.

This allows you to package supported GS Script automation without needing the full editor for execution.

### DuckyScript Converter

GS USB Runner includes a converter that translates supported DuckyScript commands into GS Script.

This provides another way to learn scripting concepts and understand how common HID automation commands work.

Some DuckyScript commands may require manual adjustment if they do not have a supported GS Script equivalent.

### GS Script Guide

A built-in educational guide helps users understand the scripting language.

It includes:

- Beginner-friendly explanations.
- Supported command references.
- Script examples.
- Insertable sample commands.
- Saving and execution instructions.
- Troubleshooting assistance.
- USB portability information.
- Quick Launch EXE instructions.

### Execution Speed Controls

Choose between three execution speeds:

- **Normal — Recommended:** Best for stability and reliability.
- **Fast:** Reduced typing and execution delays.
- **Turbo:** Maximum execution speed.

Turbo mode may cause applications to miss keystrokes or fail to keep up with automation. Normal mode is recommended.

### Live System Monitor

GS USB Runner includes a system monitor that displays available system information and activity.

Monitor system resources and view local activity while using the application.

### Customizable Cyberpunk Interface

GS USB Runner features GhostStrats' signature cyberpunk-inspired design with dark backgrounds, purple highlights, and animated interface elements.

Customization includes:

- Multiple accent colors.
- Built-in backgrounds.
- Animated, looping video backgrounds.
- Custom MP4 and WebM backgrounds.
- Custom background images.
- Interface animation effects.
- Persistent appearance settings.

GS USB Runner includes built-in GhostStrats looping video backgrounds that work offline.

### Portable Design

The entire application is designed to run directly from a USB flash drive.

Your scripts, themes, and application settings can travel with you.

There is no traditional installation process.

### Hidden Easter Eggs

There are also several hidden GhostStrats Easter eggs throughout the application.

Some things are meant to be discovered.

No spoilers.

## Creating Your First Script

1. Launch GS USB Runner.
2. Open **GS Script Editor**.
3. Start a new script or select an example from the library.
4. Write or modify your GS Script commands.
5. Give your script a filename ending in `.gs`.
6. Click **Save Your Script**.
7. Select **Execute Script** when you're ready.

Your saved scripts will appear under **My Saved Scripts**.

For the most reliable execution, make sure the intended application or window has keyboard focus.

## Updating GS USB Runner

Updating is simple.

1. Close GS USB Runner.
2. Download the newest executable from GitHub.
3. Replace the older executable on your flash drive.
4. Keep your existing `scripts/`, `themes/`, and `settings.json` files.

Your saved scripts and customization settings should remain available.

## Educational Use and Disclaimer

GS USB Runner is provided as a free educational tool for learning keyboard and mouse automation.

It is intended for use on computers you own or systems where you have explicit permission to perform automation.

Always review scripts before executing them.

GS USB Runner uses software-based Windows input simulation. It does not turn a standard USB flash drive into a physical HID device, and it does not automatically execute when connected to a computer.

Unsigned executables may trigger warnings from Windows Security. Review any detection carefully rather than disabling your computer's protection.

The software is provided without any guarantee of compatibility with every Windows configuration or application.

## Project Information

**Project:** GS USB Runner

**Developer:** GhostStrats LLC

**Platform:** Windows

**Scripting Language:** GS Script

**Cost:** Free

**Purpose:** Education, learning, and authorized automation.

GS USB Runner was created to make scripting and automation more accessible to the community.

The goal is simple: give people a free tool they can experiment with, learn from, and use to develop their own automation skills.

**SAFETY IS AN ILLUSION.**
