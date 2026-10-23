# GS USB Runner

**Free, Portable Windows Keyboard and Mouse Automation Powered by GS Script**

**Version:** V1.2  
**Developer:** GhostStrats LLC  
**Platform:** Windows  
**Cost:** Completely Free

## What Is GS USB Runner?

GS USB Runner is a free educational application designed to teach the fundamentals of HID-style keyboard and mouse automation without requiring specialized USB hacking hardware.

The idea behind this project was simple: What if you could use an ordinary USB flash drive to carry a program capable of automating keyboard and mouse actions?

That's exactly what GS USB Runner does.

Instead of making a flash drive physically identify itself as a keyboard, GS USB Runner uses software to communicate with the Windows operating system and simulate keyboard and mouse input.

We accomplished this using **Go**, a programming language that powers the application, alongside our own beginner-friendly scripting language called **GS Script**.

The goal is to make automation accessible to everyone, especially beginners who want to understand how HID-style scripting works without purchasing expensive equipment.

**An ordinary flash drive. One executable. No complicated installation.**

## How Does GS USB Runner Actually Work?

To understand GS USB Runner, it helps to understand what is happening behind the scenes.

### Step 1 — The USB Flash Drive

GS USB Runner can run directly from a standard USB flash drive.

The flash drive simply stores the application, your scripts, settings, and customizations.

When you connect the flash drive to a Windows computer, nothing automatically executes. You manually launch the application.

The USB drive does not become a physical HID keyboard.

### Step 2 — The Go Programming Language

GS USB Runner was developed using Go, also known as Golang.

Go is the programming language responsible for the application's underlying functionality.

It handles:

- Processing GS Script instructions.
- Communicating with Windows.
- Simulating keyboard and mouse input.
- Managing scripts and saved files.
- Creating standalone executables.
- Running the local application server.
- Managing execution speed and timing.

Go is essentially the engine that makes everything work.

### Step 3 — The Local Application Server

When GS USB Runner launches, the Go application starts a local server on your computer.

It then opens the GS USB Runner interface through your default browser.

This interface is hosted locally on your computer using the loopback address `127.0.0.1`.

The application does not require an external website or internet connection for its core functionality.

The browser is simply the graphical interface used to interact with the Go engine.

### Step 4 — GS Script

GS Script is a custom scripting language developed by GhostStrats to make keyboard and mouse automation easier to learn.

Instead of writing complicated programs, users can create automation using simple instructions.

For example:

```text
PRESS WINDOWS + R
WAIT 1 SECOND
TYPE "notepad"
PRESS ENTER
WAIT 2 SECONDS
TYPE "Hello from GS USB Runner!"
```

This script opens Windows Run, launches Notepad, and types a message.

GS Script is intentionally designed for basic automation. It is not intended to replace full programming languages such as Python or PowerShell.

### Step 5 — Go Interprets the Script

When you execute a GS Script, the application reads the commands and interprets them in sequence.

For example:

- `TYPE` tells the application to simulate typing.
- `PRESS` tells it to simulate a keyboard key.
- `WAIT` pauses execution.
- Mouse commands simulate movement, clicks, and scrolling.

The Go engine translates these instructions into actions supported by Windows.

### Step 6 — Windows Performs the Automation

GS USB Runner uses Windows input APIs, including SendInput, to generate simulated keyboard events and uses Windows input functionality for mouse actions.

This allows the application to automate typing, keyboard shortcuts, mouse movement, clicking, and scrolling.

The simulated inputs are directed toward the appropriate focused application, subject to Windows security restrictions.

**This is software-based HID-style automation, not physical USB HID emulation.**

### Step 7 — Watch Everything Happen

GS USB Runner includes a live execution trace.

This allows users to see how their scripts communicate with the Go engine and how the engine processes actions for Windows.

The execution trace displays:

- Script validation.
- Command processing.
- Script line numbers.
- Keyboard and mouse action types.
- Timing and execution delays.
- Execution status.
- Quick Launch build activity.

The trace is enabled automatically and includes a Clear Logs option.

For privacy, it does not expose the actual text being typed.

### Understanding the Process

```text
USB FLASH DRIVE
       |
       v
GS USB RUNNER
       |
       v
GO APPLICATION ENGINE
       |
       v
LOCAL BROWSER INTERFACE
       |
       v
GS SCRIPT INSTRUCTIONS
       |
       v
GO SCRIPT INTERPRETER
       |
       v
WINDOWS INPUT APIS
       |
       v
KEYBOARD AND MOUSE AUTOMATION
```

**USB = Storage**

**Go = Engine**

**GS Script = Instructions**

**Windows = Performs the simulated input**

That is how GS USB Runner works.

---

## Installation

Getting started with GS USB Runner is incredibly simple.

**No traditional installation is required.**

### Recommended Setup

1. Visit the official GitHub repository: https://github.com/Ghoststrats/GS-USB-RUNNER
2. Download the latest Windows release.
3. Extract the downloaded ZIP file.
4. Find the GS USB Runner executable.
5. Grab a USB flash drive. I recommend using a blank, properly formatted drive.
6. Drag or copy the executable onto the flash drive.
7. Connect the flash drive to your Windows computer.
8. Double-click the executable.

That's it!

When GS USB Runner launches, it automatically creates the folders and settings files required to save your work.

### Automatically Created Files

```text
FLASH DRIVE/
|
|-- GS-USB-Runner.exe
|
|-- scripts/
|    Your saved GS Scripts
|
|-- themes/
|    Your custom backgrounds and themes
|
|-- settings.json
     Your saved application preferences
```

Your scripts and settings remain alongside the executable, allowing you to move your work between compatible Windows computers.

You can also run GS USB Runner directly from a folder on your computer without using a flash drive.

---

## What Is GS Script?

GS Script is a custom beginner-friendly language created specifically for learning keyboard and mouse automation.

The commands are designed to be simple, readable, and easy to understand.

### Example Commands

| Command | Purpose |
|---|---|
| `TYPE "Hello"` | Types text |
| `PRESS ENTER` | Presses Enter |
| `PRESS CTRL + A` | Performs a keyboard shortcut |
| `WAIT 2 SECONDS` | Pauses execution |
| `MOVE MOUSE TO 500, 300` | Moves the mouse |
| `CLICK LEFT` | Simulates a left mouse click |
| `SCROLL DOWN 3` | Scrolls downward |

GS Script is focused on basic HID-style automation.

Advanced programming features such as loops, variables, and conditional statements are not part of the current language.

The intention is to help beginners understand automation before moving on to more advanced scripting languages.

---

## Features

### GS Script Editor

Create, edit, save, and execute your own GS Scripts.

The editor includes:

- Script editing and validation.
- Keyboard and mouse commands.
- Script naming and saving.
- Execution controls.
- Execution speed settings.
- Built-in command guidance.
- Support for unfinished drafts.

### Built-In Script Library

GS USB Runner includes educational demonstrations designed to help people understand different automation techniques.

Examples include:

- Hello World.
- Notepad automation.
- Keyboard shortcuts.
- Typing and delays.
- Mouse movement.
- Scrolling.
- GS Matrix.
- Help Desk Helper.
- Rick Roll.

Examples are provided for learning and should be reviewed before execution.

### Protected Demonstration Scripts

Official GhostStrats demonstration scripts cannot be permanently overwritten through the editor.

Users can open an example, experiment with it, add commands, and save a personal copy.

When switching away from an unsaved script, the application offers:

- Save & Continue.
- Discard Changes.
- Keep Editing.

Reopening an official demonstration restores its original instructions.

### My Saved Scripts

Save your custom scripts directly to the USB flash drive.

Saved scripts can be reopened, edited, and executed through the library.

### Keyboard and Mouse Automation

GS USB Runner supports simulated keyboard and mouse actions, including:

- Typing text.
- Keyboard shortcuts.
- Individual key presses.
- Mouse movement.
- Mouse clicking.
- Scrolling.
- Timed delays.

### Quick Launch EXE Builder

GS USB Runner allows users to convert supported GS Scripts into standalone Windows executables.

This makes it possible to create an automation script and package it into an executable that can be manually launched without opening the full GS Script Editor.

The builder includes improved temporary-file handling, completion verification, and build status reporting.

Exported applications run only when manually opened. A regular flash drive does not automatically execute them when connected.

### DuckyScript Converter

GS USB Runner includes a converter for translating supported DuckyScript commands into GS Script.

This allows users to learn the similarities and differences between automation scripting languages.

Not all DuckyScript features are supported, particularly hardware-specific instructions.

### Execution Speed Controls

Three execution modes are available.

**Normal — Recommended**

Designed for reliable keyboard and mouse automation.

**Fast**

Reduces typing and action delays.

**Turbo**

Maximum supported execution speed.

Turbo may introduce stability issues or cause applications to miss keystrokes. Normal mode is recommended.

### Live Go → Windows Execution Trace

GS USB Runner includes an always-active execution trace.

Users can observe how scripts are validated, processed, and executed through the Go engine.

The trace provides educational insight into how the program communicates with Windows.

A **Clear Logs** button allows users to clear the visible log history without interrupting future logging.

### GS Script Guide

The built-in Guide includes:

- Beginner instructions.
- GS Script command references.
- Example scripts.
- Insertable commands.
- Keyboard and mouse automation explanations.
- Quick Launch instructions.
- USB setup information.
- Troubleshooting tips.
- An explanation of how Go communicates with Windows.

### Live System Monitor

View available local system diagnostics and resource information while using GS USB Runner.

### Customizable Cyberpunk Interface

GS USB Runner features GhostStrats' signature cyberpunk-inspired appearance.

Customization includes:

- Purple and other accent colors.
- Custom background images.
- Looping MP4 and WebM backgrounds.
- Built-in GhostStrats glitch background.
- Interface animation effects.
- Portable theme settings.

### Hidden Easter Eggs

There are several hidden GhostStrats Easter eggs throughout the application.

Some things are meant to be discovered.

No spoilers.

---

## What's New in V1.2?

Version 1.2 focuses on reliability, transparency, and improving the learning experience.

### Improvements

- Go → Windows execution trace is now always enabled.
- Added Clear Logs functionality.
- Protected official demonstration scripts from accidental overwriting.
- Added reminders for unsaved changes.
- Improved Quick Launch EXE building and temporary-file handling.
- Improved build verification.
- Removed the boot animation.
- The application now opens directly into the workspace.
- Expanded the GS Script Guide.
- Improved explanations of script execution and Go communication.

---

## Updating GS USB Runner

Updating the application is simple.

1. Close GS USB Runner.
2. Download the latest Windows release.
3. Extract the executable.
4. Replace the older executable on your flash drive.
5. Keep your existing `scripts/`, `themes/`, and `settings.json` files.
6. Launch the updated application.

Your saved scripts and preferences should remain available.

---

## Troubleshooting

### Script Not Typing Correctly

Make sure the intended application has keyboard focus.

Try using Normal execution speed and adding additional WAIT commands.

### Keyboard Shortcuts Not Working

Some applications take longer to load or may restrict simulated input.

Increase delays and verify the target application is ready.

### Saved Demo Changes Disappeared

Official demonstration scripts are protected.

Save your modified demonstration as a personal script before switching.

### Executable Build Problems

Check the activity log for build errors.

If an older interrupted build left a temporary file, close the application and confirm your completed executable exists before deleting the abandoned temporary file.

### Windows Defender Warning

Windows security software may flag unsigned automation utilities.

Review the exact detection before deciding how to proceed.

Do not disable Windows Defender or create blanket security exclusions.

### Internet Requirements

GS USB Runner's core editor, locally stored scripts, and built-in backgrounds work offline.

Scripts that open online resources require internet access to load those resources.

---

## Building From Source

The source code is available through the project's distributed source package.

Developers can build GS USB Runner using Go.

Example:

```powershell
go test ./...
go build -o GS-USB-Runner.exe .
```

Users downloading the prebuilt executable do not need to install Go.

---

## Educational Use and Disclaimer

GS USB Runner is completely free and intended for educational purposes and authorized automation.

Use the software only on computers you own or systems where you have permission to perform automation.

Always review scripts before executing them.

GS USB Runner uses software-based Windows keyboard and mouse input simulation.

It does not transform an ordinary USB flash drive into a physical HID keyboard, and scripts do not automatically execute when a flash drive is connected.

The software is provided without guarantees of compatibility with every system or application.

Review the included LICENSE and DISCLAIMER documents for additional terms.

The project is source-available under a custom educational software license, not an OSI-approved open-source license.

---

## About This Project

GS USB Runner was created by **GhostStrats LLC** to provide the community with a free and accessible way to learn automation.

The purpose is not to replace established programming languages or expensive hardware solutions.

It's about making the fundamentals easier to understand and giving people an opportunity to learn something new.

You don't need expensive equipment to begin learning.

Sometimes all you need is an ordinary flash drive, a little curiosity, and the willingness to experiment.

**Created by GhostStrats LLC**

**SAFETY IS AN ILLUSION.**
