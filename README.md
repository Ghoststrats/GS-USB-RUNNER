# GS USB Runner V2.0
### The Next Evolution of Portable Automation & Cybersecurity Education

**Free Windows Automation, Custom Runners, GS HID Script Builder & Educational Cybersecurity Tools**

**Developer:** GhostStrats LLC  
**Version:** 2.0  
**Platform:** Windows 10 / Windows 11 (64-bit)  
**Programming Language:** Go (Golang), HTML, CSS & JavaScript  
**Cost:** 100% FREE  
**Installation:** Portable — No traditional installation required  
**Purpose:** Cybersecurity Education, Automation, Networking & Authorized Testing

**Official Repository:**  
https://github.com/Ghoststrats/GS-USB-RUNNER

**SAFETY IS AN ILLUSION.**  
**PRIVACY IS REBELLION.**

---

# 1. What Is GS USB Runner?

GS USB Runner is a free, portable Windows application developed by GhostStrats LLC to make keyboard automation, mouse automation, scripting, and cybersecurity education accessible to everyone.

The original idea behind GS USB Runner was simple:

**What if you could take an ordinary USB flash drive and turn it into a portable automation workspace without purchasing specialized HID hardware?**

That is exactly what GS USB Runner was created to accomplish.

Instead of requiring a dedicated USB automation device, GS USB Runner uses software to simulate keyboard and mouse actions through Windows.

The application is powered by Go and uses a beginner-friendly scripting language developed for this project called **GS Script**.

Users can create automation scripts, save them, modify them, build executable applications, and learn how software-based HID-style automation works.

With the release of **V2.0**, GS USB Runner has evolved beyond its original scripting environment.

It now supports two different execution workflows:

1. **GS Script Automation** — Traditional keyboard and mouse automation using readable GS Script commands.
2. **Custom GS Runners** — Standalone Windows applications that can be launched directly through GS USB Runner.

V2.0 also introduces the full integrated GS HID Script Builder, three custom GhostStrats programs, improvements to the portable workflow, and a hidden arcade mini-game.

Our goal is to make GS USB Runner more than a simple script executor.

We want it to become a versatile, free, beginner-friendly platform for learning automation and exploring cybersecurity concepts.

---

# 2. What's New in GS USB Runner V2.0?

V2.0 is one of the largest updates to GS USB Runner since its original release.

### Major New Features

- NEW Custom GS Runners category.
- NEW application-launching engine.
- NEW GS Ransomware Awareness Simulator.
- NEW GS Network View.
- NEW GS BSOD Simulator.
- NEW integrated GS HID Script Builder.
- NEW hidden Ghost Run mini-game.
- Improved USB portability.
- Improved first-launch initialization.
- Improved background-process management.
- Improved application window handling.
- Improved organization of the tool interface.
- Preserved GS Script functionality.
- Preserved Quick Launch executable building.
- Preserved DuckyScript conversion.
- Preserved customization and themes.

**The biggest difference in V2.0 is that users are no longer limited to traditional GS Script automation demonstrations.**

The new architecture allows supported, packaged Windows applications to be launched through the GS USB Runner interface.

This expands the types of educational demonstrations the platform can provide.

---

# 3. Understanding How GS USB Runner V2.0 Works

To understand V2.0, it helps to understand how the original application operated.

## The Original GS USB Runner

The original GS USB Runner was developed using the Go programming language.

Go serves as the software engine responsible for processing script instructions and communicating with Windows.

When you launch the original GS USB Runner, the application starts a local service on your computer.

The interface opens through your web browser, but the application itself is running locally.

That distinction is important.

**GS USB Runner is not an online website.**

Your browser acts as the graphical interface for the locally running software.

The Go engine handles the underlying automation.

### Original Execution Process

**Step 1 — Launch GS USB Runner**

You open the executable from your computer or USB flash drive.

**Step 2 — Start the Go Engine**

The Go application initializes the local environment and prepares the script-processing engine.

**Step 3 — Open the Interface**

The application opens its user interface in your default web browser.

**Step 4 — Create or Select a Script**

You can write a GS Script, select an included example, or open a previously saved script.

**Step 5 — Interpret GS Script**

The engine reads the commands and determines the requested actions.

**Step 6 — Communicate With Windows**

The engine uses Windows input functionality to simulate keyboard and mouse interactions.

**Step 7 — Execute the Automation**

Windows processes the simulated input in the appropriate focused application, subject to operating-system permissions and security restrictions.

### Example GS Script

    PRESS WINDOWS + R
    WAIT 1 SECOND
    TYPE "notepad"
    PRESS ENTER
    WAIT 2 SECONDS
    TYPE "Hello from GS USB Runner!"
    PRESS ENTER

This example opens Windows Notepad and types a message.

No specialized USB hardware is necessary.

This method is commonly described as software-based HID-style automation.

It does **not** turn the USB flash drive into an actual HID keyboard.

---

# 4. NEW — Understanding the V2.0 Execution Architecture

One of the biggest changes in GS USB Runner V2.0 is the addition of a new application-launching layer.

Previously, GS USB Runner primarily focused on interpreting GS Script commands.

Now, GS USB Runner can also launch specific standalone Windows applications packaged with the program.

These are two different ways of executing educational demonstrations.

## Engine 1 — The Original GS Script Engine

The original GS Script engine remains responsible for processing traditional automation.

This includes:

- Keyboard input.
- Typing text.
- Keyboard shortcuts.
- Timed delays.
- Mouse movement.
- Mouse clicks.
- Mouse scrolling.
- Script validation.
- Script execution.
- Existing GS Script functionality.

This engine uses the existing Go-based automation architecture.

It interprets human-readable instructions and translates them into supported Windows input operations.

For example:

    TYPE "Hello World"
    PRESS ENTER
    WAIT 2 SECONDS

These commands are interpreted by the engine rather than compiled as separate Windows programs.

## Engine 2 — The New Custom Runner Application Launcher

V2.0 introduces a new application-launching system.

Instead of reading GS Script commands, this component launches specific, bundled Windows executable applications.

This is how the new Custom GS Runners work.

When a user selects a custom runner, the main application can prepare the packaged executable and request that Windows launch it.

The standalone application then operates using its own program logic and interface.

This makes it possible to deliver demonstrations that would be difficult or impractical to build using simple keyboard-and-mouse commands alone.

Examples include:

- Visual cybersecurity simulations.
- Network monitoring interfaces.
- Interactive diagnostic tools.
- Full-screen educational demonstrations.
- Graphical training applications.

### Important Technical Distinction

The V2.0 application launcher is an additional execution mechanism, not a replacement for the original GS Script engine.

It does not make GS Script capable of interpreting arbitrary EXE files.

The current release contains a predefined collection of approved, bundled custom applications.

**V2.0 does not provide an unrestricted executable importer or automatically execute arbitrary programs from a USB drive.**

The custom programs run only when deliberately launched by the user.

---

# 5. Why Are There Two Runner Components?

Some users may notice that GS USB Runner creates an additional executable on their USB flash drive.

For example:

**GS_USB_Runner_V2.0_START_HERE.exe**

This is the main application.

And:

**GS_USB_Runner_V2.0_Script_Engine_DO_NOT_OPEN.exe**

This is the internal script engine used by GS USB Runner.

These are not two different versions that users need to choose between.

The V2.0 release uses a main application layer that coordinates the original GS Script engine and the new integrated features.

### Main Application — START HERE

The main executable is responsible for coordinating:

- Application startup.
- The integrated V2.0 interface.
- Communication with the original GS Script engine.
- Custom GS Runner launching.
- HID Script Builder integration.
- Local service communication.
- Session management.
- Background-process cleanup.
- The hidden mini-game interface.

This is the only executable normal users should manually launch.

### Internal Script Engine — DO NOT OPEN

The second executable contains the original GS Script functionality.

It runs as a managed background process and supports the core automation features.

The main application starts it automatically.

**Users do not need to open the internal script engine themselves.**

The current architecture retains the original compiled engine rather than replacing its entire implementation.

This allows the V2.0 integration layer to add capabilities while preserving the established GS Script workflow.

### How Everything Works Together

    USB FLASH DRIVE
           |
           v
    GS USB RUNNER V2.0
       MAIN APPLICATION
           |
           |
       LOCAL INTERFACE
           |
           +-----------------------+
           |                       |
           v                       v
    ORIGINAL SCRIPT          NEW CUSTOM RUNNER
        ENGINE                    LAUNCHER
           |                       |
           v                       v
    GS SCRIPT COMMANDS       STANDALONE WINDOWS
                                   PROGRAMS
           |                       |
           v                       v
    KEYBOARD & MOUSE         CUSTOM GRAPHICAL
       AUTOMATION              APPLICATIONS

                  |
                  v
          GS HID SCRIPT BUILDER
          INTEGRATED COMPANION

The HID Script Builder is a separate bundled companion that can start its own local service when requested.

**GS USB Runner V2.0 provides one main download, but its supporting components can run as separate Windows processes.**

This is intentional in the current architecture.

---

# 6. NEW — Custom GS Runners

V2.0 introduces a new section called:

## CUSTOM GS RUNNERS

This category allows users to launch additional GhostStrats applications directly through the GS USB Runner interface.

These applications are separate from traditional GS Scripts.

Rather than simply typing commands or controlling mouse input, each custom runner is a standalone program with its own functionality.

The programs are bundled with the main release so users do not need to download each one individually.

### Included Applications

**1. GS Ransomware Awareness Simulator**

**2. GS Network View**

**3. GS BSOD Simulator**

Each program serves a different educational purpose.

---

# 7. GS Ransomware Awareness Simulator

**Category:** Cybersecurity Awareness  
**Type:** Educational Visual Simulation  
**Platform:** Windows

GS Ransomware Awareness is an educational application designed to demonstrate how convincing ransomware-style warning screens can appear.

The goal is to teach people about cyber threats and the importance of understanding what is actually happening on their computers.

### Features

- Full-screen-style visual simulation.
- Ransomware-inspired warning interface.
- Countdown sequence.
- Dramatic digital corruption effects.
- Red glitch effects.
- Simulated system instability.
- Staged digital crash sequence.
- Final educational reveal.

The simulation is deliberately designed to look intimidating.

However, **appearance does not equal functionality**.

### What This Application Does NOT Do

- Does not intentionally encrypt files.
- Does not intentionally delete personal documents.
- Does not intentionally lock Windows.
- Does not demand actual ransom payments.
- Does not intentionally corrupt your operating system.
- Does not intentionally deploy malware.

The purpose is visual education.

A convincing ransomware warning can create fear and confusion, but that does not automatically mean an actual ransomware attack has occurred.

This application helps demonstrate that difference.

### Educational Uses

- Cybersecurity awareness presentations.
- Classroom demonstrations.
- Security training.
- Visual threat education.
- Controlled cybersecurity demonstrations.

The simulator should only be used in environments where participants have been informed and have consented.

It is not intended for pranks involving unsuspecting people.

**Exit:** Escape is the intended quick-exit control.

Some display configurations may affect whether the presentation fully covers the Windows taskbar.

The application's simulation behavior should not be confused with an actual ransomware attack.

---

# 8. GS Network View

**Category:** Networking & Cybersecurity  
**Type:** Network Diagnostic Application  
**Platform:** Windows

GS Network View is a network-focused application designed to help users visualize and better understand network activity and connected systems.

It is particularly useful for people interested in networking, network administration, and defensive cybersecurity.

### Main Goals

- Make network information easier to understand.
- Provide visual representations of network activity.
- Help users explore available network diagnostics.
- Introduce networking concepts.
- Provide useful information for educational troubleshooting.

### Features

Depending on available Windows networking capabilities and permissions, its interface provides network-related views such as:

- Network information.
- Connected-device discovery information.
- Network activity displays.
- Inbound and outbound traffic indicators.
- Graphical network visualization.
- Diagnostic information.
- Interface-related status and statistics.

Some information may be unavailable without the necessary adapter support, permissions or network visibility.

### Important Limitations

Network discovery is not the same as full packet capture.

Traffic statistics are not necessarily a complete record of everything traveling across a network.

GS Network View should not be assumed to capture every packet, discover every connected device or identify every network threat.

Results depend on the underlying network, operating system, adapters, and available permissions.

### Educational Uses

- Networking education.
- Network troubleshooting.
- Defensive security research.
- Network-monitoring demonstrations.
- Understanding basic network visibility.

**Only monitor networks and systems you own or are authorized to inspect.**

The application may use its own locally hosted browser interface.

V2.0 attempts to bring the Network View interface forward when launched, although Windows sometimes restricts applications from forcing a browser window into focus.

---

# 9. GS BSOD Simulator

**Category:** Windows Education  
**Type:** Visual System Failure Simulation  
**Platform:** Windows

GS BSOD Simulator is an educational application that reproduces the appearance of Windows blue-screen errors.

It is designed for visual demonstrations and training.

### Features

- Classic Windows BSOD-style presentation.
- Custom GhostStrats blue-screen design.
- Direct transition between screen styles.
- Full-screen visual experience.
- Escape-to-exit functionality.

The simulation demonstrates how convincing a Windows system failure screen can look.

### What It Does NOT Do

- Does not intentionally crash Windows.
- Does not intentionally cause a genuine system stop error.
- Does not intentionally damage system files.
- Does not intentionally modify Windows boot configuration.

The application is a visual simulation.

It should never be represented as evidence of an actual Windows system failure.

### Educational Uses

- Computer training.
- Understanding Windows error screens.
- Cybersecurity awareness.
- Controlled demonstrations.

**Press Escape to exit the simulation.**

---

# 10. How Custom GS Runners Launch

When GS USB Runner starts, it does not automatically execute all the bundled applications.

Instead, the user selects the program they want to launch.

### Execution Process

**Step 1:** Open GS USB Runner V2.0.

**Step 2:** Select Custom GS Runners from the application menu.

**Step 3:** Review the available applications.

**Step 4:** Choose the desired program.

**Step 5:** Click Launch and approve the launch confirmation.

**Step 6:** The new application-launching layer prepares the bundled executable if necessary.

**Step 7:** Windows starts the selected application.

**Step 8:** The launcher attempts to bring the program into the foreground.

If a program is already running, the launcher is designed to attempt to restore the existing instance rather than create unnecessary duplicates.

Actual foreground behavior depends on Windows and the design of the individual application.

### Background Process Management

V2.0 includes process-management functionality intended to reduce applications being left running after the main program exits.

When you select Exit Runner, the application attempts to close the supporting processes that it started.

If a managed process does not close normally, stronger termination may be used.

**Important:** This applies to processes the launcher owns or tracks. It does not mean that every browser tab or independently spawned process on Windows will automatically close.

Always save important work before exiting.

---

# 11. NEW — GS HID Script Builder Integration

Another major addition in V2.0 is the integration of the full GS HID Script learning tool.

The new menu section is named:

## GS HID Script Builder

It appears directly below GS Script Guide in the main Runner menu.

This makes it easier for users to move between learning about GS Script and building their own automation.

### What Is GS HID Script Builder?

GS HID Script Builder is a beginner-friendly learning environment for creating keyboard and mouse automation.

It provides a visual approach to scripting so users can build automation without needing to memorize every command.

The tool is based on the existing GS HID Script project.

### Included Features

**Visual Script Builder**

Choose keyboard and mouse actions through the interface and generate supported script commands automatically.

**GS HID Script Lab**

Write, edit, load and save automation scripts.

**Explain My Script**

Review what individual script instructions are intended to do.

**Step-Through Preview**

Inspect an automation sequence without immediately sending real input to Windows.

**Keyboard Automation**

Learn about typing, keyboard shortcuts, and key presses.

**Mouse Automation**

Explore mouse movement, clicking, scrolling and timed actions.

**DuckyScript Converter**

Convert supported commands between GS HID Script and DuckyScript.

Not every command or hardware-specific feature has an equivalent representation.

**Learning Center**

Explore scripting fundamentals, supported commands, timing, shortcuts and automation concepts.

### Integrated Application Experience

Within V2.0, the HID Script Builder is designed to load directly inside the GS USB Runner workspace.

You can access its features without separately launching its standard browser interface.

The Builder still uses a local background service when selected, but its interface is embedded inside Runner.

Select:

**GS HID Script Builder → Start Studio**

### Safety Features

The HID Script tool includes important execution safeguards.

- Safety Switch.
- Script preview.
- Execution confirmation.
- Stop functionality.
- Authorization reminders.
- Windows F12 emergency-stop request.

The safety switch is intended to start enabled so scripts cannot immediately execute without deliberate user action.

A stop request cannot undo keyboard or mouse actions that already occurred.

### Standalone GS HID Script Tool

The full standalone application is still available separately.

Users who prefer working outside GS USB Runner can download it from the official project.

**Official GS HID Script Tool:**  
https://github.com/Ghoststrats/GS-HID-Script-Tool

The integrated version is a bundled companion, not a replacement for the independently distributed application.

---

# 12. What Is GS Script?

GS Script is a human-readable automation language designed to make keyboard and mouse scripting easier to learn.

Instead of requiring complicated programming syntax, GS Script uses simple commands.

### Example Commands

| Command | Purpose |
|---|---|
| `TYPE "Hello World"` | Types the specified text |
| `PRESS ENTER` | Simulates the Enter key |
| `PRESS CTRL + C` | Performs a keyboard shortcut |
| `PRESS WINDOWS + R` | Opens the Windows Run dialog |
| `WAIT 2 SECONDS` | Adds a delay |
| `MOVE MOUSE TO 500, 300` | Moves the mouse pointer |
| `CLICK LEFT` | Simulates a left mouse click |
| `CLICK RIGHT` | Simulates a right mouse click |
| `SCROLL DOWN 3` | Scrolls downward |

### Example Automation

    # GS USB Runner demonstration

    PRESS WINDOWS + R
    WAIT 1 SECOND
    TYPE "notepad"
    PRESS ENTER
    WAIT 2 SECONDS

    TYPE "Welcome to GS USB Runner V2.0!"
    PRESS ENTER

    TYPE "Safety is an Illusion."
    PRESS ENTER

This example demonstrates how a series of simple instructions can control ordinary Windows applications.

The engine interprets the commands one at a time.

### Important Information

GS Script is designed for basic software automation.

It is not a complete replacement for Go, Python, PowerShell or other general-purpose programming languages.

Advanced control structures are not necessarily supported by the existing interpreter.

Always review commands before executing them.

---

# 13. Quick Launch EXE Builder

GS USB Runner includes its existing Quick Launch feature.

Quick Launch allows users to package supported GS Scripts into standalone Windows executables.

This means a script can be converted into a manually launched application without opening the full GS Script Editor every time.

### How It Works

1. Create a supported GS Script.
2. Review and validate it.
3. Open Quick Launch.
4. Build the script into an executable.
5. Save the resulting application.
6. Manually launch it on a compatible Windows computer.

### Quick Launch vs. Custom GS Runners

These features are different.

**Quick Launch:**

Builds supported GS Script automation into a standalone executable.

**Custom GS Runners:**

Launches independently developed Windows applications packaged with GS USB Runner.

Quick Launch applications are based on the GS Script workflow.

Custom GS Runners can contain application logic, graphical interfaces and other functionality independent of the GS Script interpreter.

Neither feature makes an ordinary USB drive automatically execute software when inserted.

---

# 14. DuckyScript Converter

GS USB Runner includes a converter designed to help users understand how supported DuckyScript instructions relate to GS Script.

DuckyScript is commonly associated with keyboard automation hardware and related educational tools.

GS Script uses a separate software-based approach.

The converter allows users to explore the similarities between supported instructions.

### Example

DuckyScript-style input:

    DELAY 1000
    GUI r
    DELAY 500
    STRING notepad
    ENTER

Equivalent GS Script-style output:

    WAIT 1 SECOND
    PRESS WINDOWS + R
    WAIT 500 MILLISECONDS
    TYPE "notepad"
    PRESS ENTER

Conversion is limited to supported commands.

Hardware-specific features, advanced syntax and incompatible mouse functions may not translate.

Users should inspect converted scripts before executing them.

---

# 15. GS Script Editor

The GS Script Editor remains one of the primary features of the application.

It allows users to create and modify their own automation instructions.

### Features

- Write GS Script commands.
- Open existing scripts.
- Save personal scripts.
- Load educational examples.
- Validate supported instructions.
- Select execution speed.
- Execute scripts manually.
- Review execution results.

The editor is designed to provide a practical learning environment.

Users can begin with simple commands and gradually explore more complex automation sequences supported by the engine.

---

# 16. Built-In Script Library

GS USB Runner includes educational example scripts to help beginners learn the language.

Examples include demonstrations of:

- Typing and keyboard automation.
- Notepad automation.
- Keyboard shortcuts.
- Mouse movement.
- Scrolling.
- Timing and delays.
- GS Matrix.
- Help Desk Helper.
- Rick Roll.

Official demonstration scripts are intended as educational starting points.

Users can open them, review the commands and create modified personal copies.

The original protected-example behavior is retained so the built-in library is not accidentally overwritten by user edits.

**Always inspect any downloaded or shared script before running it.**

---

# 17. My Scripts

The My Scripts section allows users to organize and reopen their saved GS Script files.

The application stores portable script files alongside its working directory.

When using a USB flash drive, this allows scripts to travel with the application.

### Benefits

- Keep your own automation scripts.
- Reopen previously saved projects.
- Make modifications.
- Build new executable versions.
- Organize educational demonstrations.
- Transfer portable work between compatible Windows computers.

Scripts should be treated like other executable instructions.

Do not automatically trust scripts received from unknown sources.

---

# 18. Execution Speed Controls

GS USB Runner includes multiple speed settings for keyboard and mouse automation.

### Normal

Recommended for everyday use and learning.

Provides additional timing between operations to improve reliability.

### Fast

Reduces delays and performs supported automation actions more quickly.

Some programs may require additional wait time.

### Turbo

Uses the fastest supported execution timing.

Turbo mode may cause certain applications to miss keyboard or mouse events.

**Normal speed is recommended for beginners and reliability testing.**

Adding appropriate `WAIT` commands can improve automation stability.

---

# 19. Live Execution Trace & Logs

The original GS USB Runner includes execution logging designed to help users understand what happens when scripts run.

The log shows information such as:

- Script validation.
- Command processing.
- Instruction line numbers.
- Execution status.
- Keyboard action types.
- Mouse action types.
- Timing operations.
- Quick Launch build events.
- Error messages.

This helps users understand how GS Script instructions are translated into Windows automation actions.

The original execution trace is designed not to expose the exact text typed by scripts in its routine log output.

A Clear Logs option allows users to clear the visible history.

The logs are educational and diagnostic tools, not a guarantee that every Windows action can be recorded or reversed.

---

# 20. System Monitor

GS USB Runner also includes a built-in System Monitor.

This provides access to available local system information.

The goal is to allow users to view basic computer performance and resource information while working in GS USB Runner.

This is separate from the more specialized GS Network View application.

The information available depends on the operating system and the existing monitoring implementation.

---

# 21. Custom Themes & Interface

GS USB Runner features the recognizable GhostStrats black-and-purple cyberpunk appearance.

The interface is designed to give the application a distinctive look while keeping its features organized.

### Customization Features

- Purple GhostStrats default theme.
- Alternate accent colors.
- Custom background images.
- Supported animated backgrounds.
- MP4 and WebM background support.
- Visual effects.
- Local theme settings.

Theme and background files can be stored in the portable application's working folders.

The original customizable interface remains available in V2.0.

---

# 22. NEW — Hidden GhostStrats Easter Egg

GS USB Runner V2.0 includes a hidden surprise.

Somewhere inside the application is a secret GhostStrats-themed arcade mini-game called:

## GHOST RUN

The game features:

- A purple GhostStrats ghost.
- Angry, slanted glowing eyes.
- A futuristic digital environment.
- Purple intel collectibles.
- Red security drones.
- Score tracking.
- Shields.
- A 60-second survival mission.

### How to Unlock It

**Hint: Check the bottom-left corner of the application.**

For those who want the full secret:

Click the **GHOSTSTRATS** text in the lower-left footer **10 times within approximately 12 seconds**.

The hidden arcade game will appear.

### Controls

| Control | Action |
|---|---|
| W / A / S / D | Move |
| Arrow Keys | Move |
| Mouse | Steer the ghost |
| P | Pause or resume |
| ESC | Exit the mini-game |

### Mission

Collect purple intel.

Avoid the red security drones.

Keep your shields intact.

Survive for 60 seconds.

Try to beat your previous score.

Ghost Run is a visual entertainment feature included for the community.

It does not execute scripts or perform cybersecurity operations.

---

# 23. Installing GS USB Runner V2.0

Installation is intentionally simple.

**No traditional Windows installation wizard is required.**

### Requirements

- Windows 10 or Windows 11.
- 64-bit Windows computer.
- USB flash drive or writable local folder.
- Enough free storage for the main EXE, extracted components, scripts and settings.
- A supported modern web browser.
- Permission to run the application.

Python and Go do not need to be installed to run the prebuilt executable.

### Installation Steps

**Step 1**

Visit the official repository:

https://github.com/Ghoststrats/GS-USB-RUNNER

**Step 2**

Open the Releases section.

**Step 3**

Download the latest GS USB Runner V2.0 portable executable.

**Step 4**

If downloaded as a ZIP, extract it first.

**Step 5**

Insert your USB flash drive.

**Step 6**

Copy the main application onto the drive:

`GS_USB_Runner_V2.0_START_HERE.exe`

**Step 7**

Wait for Windows to finish copying the file.

**Step 8**

Double-click the executable.

**Step 9**

Allow the application to complete first-time initialization.

**Step 10**

Once the interface opens, begin exploring the tools.

That's it!

**One primary executable. No traditional installation process.**

---

# 24. IMPORTANT — First Launch May Take Longer

One important change in V2.0 is the first-time preparation of its supporting components.

**The first launch may take approximately 20 full seconds or a little longer.**

This is a practical expectation, not a guaranteed maximum.

The actual duration depends on your computer, USB flash drive, filesystem, security software and Windows environment.

### What Happens During the First Launch?

When the application is first executed, it performs several setup operations.

**1. Prepare the Working Directory**

GS USB Runner determines where the executable is located.

If running from a USB drive, that location becomes the portable workspace.

**2. Create User Folders**

The program creates the necessary folders for scripts and themes.

**3. Prepare the Original Script Engine**

V2.0 extracts the supporting GS Script engine from the main executable.

**4. Start the Original Engine**

The application starts the local Go-based script-processing service.

**5. Detect the Local Engine**

The main launcher establishes communication with the script engine using a local Windows loopback connection.

**6. Initialize the V2.0 Interface**

The application starts the integrated local host, which combines the original Runner interface with the new V2.0 features.

**7. Open Your Default Browser**

The application opens the local GS USB Runner workspace.

### Why Is the First Launch Slower?

The application must prepare files and initialize its environment.

A slower flash drive may take longer to perform these operations.

Windows Defender or other security software may also inspect newly extracted executable files.

### What Happens on Later Launches?

On subsequent launches, the existing support files can generally be reused.

That means the application usually does not need to extract the entire original engine again.

**After the initial setup, startup should generally be much faster.**

### Important

Simply copying the executable onto your flash drive will not start the setup process.

The folders are created when you **run the application for the first time**, not when you drag the file onto the drive.

This is normal Windows behavior.

---

# 25. Portable Folder Structure

After first launch and use of the various tools, the USB drive may contain a structure similar to:

    USB DRIVE
    |
    |-- GS_USB_Runner_V2.0_START_HERE.exe
    |
    |-- GS_USB_Runner_V2.0_Script_Engine_DO_NOT_OPEN.exe
    |
    |-- scripts/
    |     Saved GS Scripts
    |
    |-- themes/
    |     Backgrounds and theme files
    |
    |-- settings.json
    |     Saved application preferences
    |
    |-- GS_Custom_Runners/
          |
          |-- GS_Ransomware_Awareness.exe
          |
          |-- GS-Network-View.exe
          |
          |-- GS_BSOD_Simulator.exe
          |
          |-- GS-HID-Script-Portable.exe

The exact folder contents depend on which features have been used.

Some custom applications are extracted only when they are selected for the first time.

The script engine is an internal helper.

**Always launch the START HERE executable.**

Do not manually launch or modify the internal engine.

---

# 26. Does GS USB Runner Require Internet?

The main application is designed to operate locally.

The original GS Script engine and the interface do not require a GhostStrats cloud account.

The core application can operate without an active internet connection.

However, internet access may be needed for:

- Scripts that visit online websites.
- Online content opened by a demonstration.
- Certain network diagnostics.
- External resources.
- Downloads and updates.

### Local Browser Interface

GS USB Runner uses a local service that communicates through an address similar to:

`http://127.0.0.1:<local-port>`

The port is assigned locally when the application starts.

The address `127.0.0.1` refers to your own computer.

The interface uses your browser to communicate with the locally running program.

This does not mean your scripts or application interface are being hosted on a public website.

---

# 27. What Does the Go Engine Actually Do?

Go, commonly called Golang, is the main programming language used for the original Runner and the V2.0 integration host.

Go is responsible for coordinating application operations and communicating with Windows.

### In the Original Engine

Go helps perform:

- GS Script interpretation.
- Script validation.
- Windows keyboard input simulation.
- Mouse input simulation.
- Script execution timing.
- Script file handling.
- Existing user-interface services.
- Quick Launch executable building.

### In the New V2.0 Host

Go helps perform:

- Main application startup.
- Local service management.
- Communication with the original engine.
- Custom program launching.
- Preparation of bundled executable files.
- Background-process tracking.
- Application lifecycle management.
- Communication between the browser interface and the local engines
