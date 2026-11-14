# GS USB Runner V2.1.1

### Free Portable Windows Automation & Cybersecurity Education Platform

**Created by GhostStrats LLC** | **Windows 10/11 (64-bit)** | **100% FREE** | **Portable**

# ⬇️ [DOWNLOAD THE LATEST GS USB RUNNER RELEASE](https://github.com/Ghoststrats/GS-USB-RUNNER/releases/latest)

**[Download V2.1.1 Directly](https://github.com/Ghoststrats/GS-USB-RUNNER/releases/tag/V2.1.1)** | [All Releases](https://github.com/Ghoststrats/GS-USB-RUNNER/releases) | [Report an Issue](https://github.com/Ghoststrats/GS-USB-RUNNER/issues)

**Quick Start:** Open the latest release, download `GS_USB_Runner_V2.1.1_DOWNLOAD_HERE.zip` or the `START_HERE.exe`, extract the ZIP if necessary, copy the executable onto your USB drive, and double-click it.

**No traditional installation required!**

**SAFETY IS AN ILLUSION.**

---

## What Is GS USB Runner?

GS USB Runner is a free, portable Windows automation and cybersecurity learning platform created by GhostStrats LLC.

Originally developed to make keyboard and mouse automation easier for beginners, GS USB Runner has expanded into an educational ecosystem containing custom scripting tools, cybersecurity demonstrations, networking utilities, privacy controls, and system automation applications.

The goal is to help bridge the gap between complete beginners and more advanced cybersecurity and scripting tools.

GS USB Runner includes its own beginner-friendly scripting language called **GS Script**, along with a visual editor, educational examples, integrated HID Script Builder, and Custom GS Runners.

**Important:** GS USB Runner does not turn an ordinary USB drive into a physical HID keyboard. Applications and scripts are launched manually, and Windows permissions still apply.

---

## What's New in V2.1.1?

Version 2.1.1 expands the Custom GS Runners collection from three tools to six.

### Three Additional Custom Runners

- **GS Shadow Tracker** — Offline wardrive analysis and historical wireless-device investigations.
- **GS Blackout** — Manual controls for supported network interfaces, Bluetooth, cameras, and microphones.
- **GS Null Out** — Automatic inactivity-based Windows shutdown utility.

### Additional Improvements

- Updated GhostStrats purple-eyes branding.
- Improved Custom Runner integration.
- Updated GS Blackout launch behavior.
- GS Shadow Tracker startup and shutdown helpers.
- Continued portable USB storage support.
- All original GS Script tools remain included.

---

## Main GS USB Runner Features

| Feature | Description |
|---|---|
| GS Script Editor | Create, edit, save, and execute beginner-friendly automation scripts |
| My Scripts | Organize and manage saved scripts |
| Quick Launch | Create supported standalone script executables |
| DuckyScript Converter | Convert supported DuckyScript instructions |
| GS Script Guide | Learn scripting commands and examples |
| GS HID Script Builder | Visual script creation and educational workspace |
| Custom GS Runners | Launch six included cybersecurity and system utilities |
| System Monitor | View available system information |
| Execution Logs | Review script execution and feedback |
| Settings | Customize supported interface themes and backgrounds |
| Ghost Run | Hidden GhostStrats arcade mini-game |

---

## Installation — Windows 10/11

GS USB Runner is designed to be portable.

### Step 1 — Download

Visit:

**https://github.com/Ghoststrats/GS-USB-RUNNER/releases/latest**

Download either:

- `GS_USB_Runner_V2.1.1_DOWNLOAD_HERE.zip`
- `GS_USB_Runner_V2.1.1_START_HERE.exe`

### Step 2 — Prepare Your USB Drive

Insert a writable USB flash drive into your Windows computer.

You can also run GS USB Runner from a normal folder on your PC.

### Step 3 — Extract the Files

If you downloaded the ZIP, right-click it and select **Extract All**.

Copy the `START_HERE.exe` executable onto your USB drive.

### Step 4 — Launch

Double-click:

`GS_USB_Runner_V2.1.1_START_HERE.exe`

### Step 5 — Allow Initial Setup

During the first launch, GS USB Runner prepares its supporting files, initializes its scripting engine, and creates necessary folders.

On slower USB drives, the first startup may take 20 seconds or longer.

The main interface opens in your default web browser through a local service running on your own computer.

**Do not manually launch supporting executables labeled `DO_NOT_OPEN`.**

### Step 6 — Start Exploring

Choose GS Script Editor, HID Script Builder, or Custom GS Runners to begin.

The prebuilt main application does not require a separately installed Go environment. Some older companion applications, particularly GS Shadow Tracker in this version, may have additional runtime requirements.

---

## How GS USB Runner Works

GS USB Runner uses a Go-based launcher that prepares the GS Script execution engine and starts a local dashboard.

The interface connects to a service hosted on your own computer, typically using `127.0.0.1`.

This is not a public GhostStrats cloud server.

GS USB Runner has two primary execution methods.

### GS Script Execution

GS Script uses readable text commands interpreted by the GS Script engine.

Examples include typing text, pressing keys, moving the mouse, clicking, scrolling, and waiting between actions.

### Custom GS Runner Execution

Custom GS Runners are separate compiled applications.

Instead of interpreting a `.gs` script, GS USB Runner prepares and launches the selected companion application.

These tools can contain their own graphical interfaces, visual simulations, or system-control functions.

The integrated GS HID Script Builder provides a third educational workspace for visual script creation.

---

## GS Script Editor

GS Script is a beginner-friendly scripting language developed to introduce people to keyboard and mouse automation.

It intentionally avoids much of the complexity of advanced scripting languages.

The goal is not to compete with PowerShell, Python, Bash, or advanced HID scripting systems.

Instead, GS Script helps beginners understand automation fundamentals before learning more advanced languages.

### Supported Automation Concepts

- Typing text
- Keyboard shortcuts
- Key presses
- Mouse movement
- Mouse clicks
- Scrolling
- Delays
- Sequential automation

GS Script is deliberately limited and does not provide every advanced feature of full programming languages, such as general-purpose loops or complex conditional logic.

### Your First GS Script

Open GS Script Editor and enter:

```text
# Safe beginner demonstration
PRESS WINDOWS + R
WAIT 1 SECOND
TYPE "notepad"
PRESS ENTER
WAIT 2 SECONDS
TYPE "Hello from GS USB Runner V2.1.1!"
PRESS ENTER
```

This example opens Windows Notepad and types a message.

Save your script using My Scripts, then execute it manually.

**Important:** Keyboard and mouse automation generally acts on the currently focused window. Make sure the correct application is selected before running a script.

### Basic GS Script Commands

| Command | Function |
|---|---|
| `TYPE "Hello"` | Type text |
| `PRESS ENTER` | Press Enter |
| `PRESS CTRL + S` | Send a keyboard shortcut |
| `WAIT 2 SECONDS` | Pause execution |
| `MOVE MOUSE TO 500, 300` | Move the mouse pointer |
| `CLICK LEFT` | Left-click |
| `SCROLL DOWN 3` | Scroll downward |

Refer to the built-in GS Script Guide for supported syntax and additional examples.

Never execute scripts you have not reviewed.

---

## My Scripts

The My Scripts section allows users to save and organize their automation scripts.

You can create a script once, save it, and reuse it whenever needed.

Saved scripts are designed to remain on your portable drive so they can travel with your GS USB Runner workspace.

---

## Quick Launch EXE Builder

Quick Launch allows supported GS Script automations to be packaged into standalone Windows executables.

This is useful when users want to manually launch an automation without opening the full editor each time.

**Important:** A Quick Launch executable does not automatically run when a USB drive is inserted.

It must be launched by the user.

---

## DuckyScript Converter

GS USB Runner includes a converter for supported DuckyScript instructions.

The purpose is to help beginners understand similarities between GS Script and more advanced HID automation languages.

Not every DuckyScript command has a GS Script equivalent.

Unsupported commands or advanced programming features may require manual changes.

---

## GS HID Script Builder

GS HID Script Builder is integrated directly into GS USB Runner.

It provides an educational workspace for people who prefer visual, guided script creation.

### Features

- Visual script building
- Script editor and laboratory
- Supported DuckyScript conversion
- Step-by-step previews
- Script explanations
- Educational examples
- Safety controls
- Execution confirmation
- Stop functionality

### How to Use

1. Open GS USB Runner.
2. Select **GS HID Script Builder**.
3. Click **Start Studio**.
4. Choose a supported scripting or learning function.
5. Create or inspect your script.
6. Review its actions before executing.

The Builder launches its own local service when needed and displays its workspace within GS USB Runner.

Additional information is available at:

**https://github.com/Ghoststrats/GS-HID-Script-Tool**

---

# Custom GS Runners

Version 2.1.1 includes **six Custom GS Runners**.

These applications are launched individually from the main Custom GS Runners page.

They are standalone Windows applications rather than GS Script files.

---

## 1. GS Ransomware Awareness Simulator

GS Ransomware Awareness is an educational cybersecurity demonstration designed to simulate the visual experience of a ransomware warning.

### Features

- Full-screen ransomware-style warning
- Simulated countdown
- Digital glitch effects
- Screen corruption visuals
- Simulated crash sequence
- Educational ending

### How It Works

The application displays a staged ransomware scenario using visual effects.

It demonstrates how alarming messages and countdowns can influence user behavior.

The simulator does not intentionally encrypt files, demand real payment, or damage the operating system.

### How to Launch

1. Open **Custom GS Runners**.
2. Select **GS Ransomware Awareness**.
3. Click **Launch**.
4. Follow the demonstration.

Use only during authorized demonstrations and tell participants that the experience is simulated.

---

## 2. GS Network View

GS Network View is a networking visualization and diagnostic application.

It is designed to help users learn about network interfaces, connectivity, and available traffic information.

### Features

- Network visualization
- Network interface information
- Diagnostic information
- Available network activity monitoring
- Educational network inspection

### How to Launch

1. Open **Custom GS Runners**.
2. Select **GS Network View**.
3. Click **Launch**.
4. Review the information displayed by the application.

Network visibility depends on Windows permissions, adapter support, and the selected network interface.

Not every visualization represents complete packet capture.

Use only on networks you own or have permission to inspect.

---

## 3. GS BSOD Simulator

GS BSOD Simulator creates a visual imitation of a Windows blue screen of death.

### Features

- Classic Windows blue-screen appearance
- Custom GhostStrats blue screen
- Full-screen visual demonstration
- Escape-key exit

### How It Works

The simulator displays a staged blue-screen sequence without intentionally causing an actual Windows system crash.

### How to Launch

1. Open **Custom GS Runners**.
2. Select **GS BSOD Simulator**.
3. Click **Launch**.
4. Watch the demonstration.
5. Press **Escape** to exit.

This application is intended for educational demonstrations and should not be misrepresented as a real system failure.

---

## 4. GS Shadow Tracker

GS Shadow Tracker is an offline wardriving analysis application designed to examine previously collected Wi-Fi, Bluetooth, and GPS observation data.

It is intended for historical review and defensive research.

**GS Shadow Tracker does not perform live wireless scanning.**

### Main Features

- Import previously captured wardriving data
- Review historical Wi-Fi and Bluetooth sightings
- Analyze repeated device identifiers
- Examine recorded signal-strength values
- Review GPS and timestamp information
- Identify potentially suspicious recurring patterns
- Investigate possible tracker-device indicators
- Store recorded investigations on USB
- Explore fictional demonstration data

### How to Use

1. Collect wireless observations using appropriate equipment and software.
2. Open GS USB Runner.
3. Select **Custom GS Runners**.
4. Launch **GS Shadow Tracker**.
5. Choose **Try Demo** to explore fictional example data, or select **Import Run** to import supported recorded files.
6. Review the available dashboard, map, journey, and device information.
7. Examine recurring device patterns and supporting evidence.
8. Save or review your investigation.
9. Use **Quit App** or the Runner's **STOP** control before ejecting the USB drive.

### Known Tracker Analysis

Where supported information is present in imported data, Shadow Tracker can review possible tracker-related identifiers or names.

Examples include metadata associated with Apple AirTag/Find My, Samsung SmartTag, Tile, Chipolo, Pebblebee, Google Find Hub, and compatible tracker systems.

These detections are not guarantees. Some trackers may not be identifiable from available wardriving logs.

### Risk Analysis

Shadow Tracker can prioritize suspicious patterns using categories such as:

- High
- Elevated
- Review

These are heuristic investigation priorities.

They do not prove that someone is tracking or following a person.

GPS coordinates show where the collecting device was located when an observation was recorded, not necessarily the location of the transmitting wireless device.

### Portable Data Storage

Shadow Tracker stores investigation information within:

`GS_Shadow_Tracker_Data/`

This folder may include its database, archived original captures, and investigation records.

Back up the entire folder before changing or deleting stored data.

### Important V2.1.1 Limitation

The Shadow Tracker edition included with GS USB Runner V2.1.1 uses a Go wrapper around a Python-based local analysis service.

It may require additional runtime preparation and has known startup issues on some Windows systems.

This is the early Shadow Tracker edition, not the later native-Go rewrite.

---

## 5. GS Blackout

GS Blackout is a Windows privacy and device-control utility.

It provides manual controls to disable and restore supported network and peripheral interfaces.

### Supported Controls

Depending on the computer and Windows permissions:

- Wi-Fi interfaces
- Ethernet interfaces
- Bluetooth devices
- Cameras
- Microphones

### How to Use

1. Open **Custom GS Runners**.
2. Select **GS Blackout**.
3. Click **Launch**.
4. Approve the Windows administrator/UAC prompt when appropriate.
5. Review the controls and warnings.
6. Disable the supported device categories you choose.
7. Use **Restore** when you want the interfaces re-enabled.

### Keyboard Shortcut

Supported builds include a **G + S hold** shortcut for changing Blackout state.

### Emergency Restoration

After preparation, a recovery helper may be located at:

`GS_Custom_Runners/GS_Blackout/Restore GS Blackout.cmd`

Keep this helper available if you use Blackout.

### Important Warnings

Disabling networking can terminate remote connections.

Disabling Bluetooth may disconnect wireless keyboards and mice.

Use GS Blackout locally, preferably with a wired keyboard and mouse available.

Not every radio or hardware component can be fully controlled by software.

**GS Blackout is not guaranteed to eliminate all wireless transmissions or provide complete RF isolation.**

---

## 6. GS Null Out

GS Null Out is a portable Windows inactivity-shutdown application.

Unlike the visual simulations, **GS Null Out can perform a real system shutdown**.

### Features

- User inactivity monitoring
- Shutdown countdown
- Optional rapid-shutdown shortcut
- Portable operation
- User-controlled activation

### How to Use

1. Save your work.
2. Open **Custom GS Runners**.
3. Select **GS Null Out**.
4. Click **Launch**.
5. Enable inactivity monitoring when you want to use it.
6. Review the countdown.
7. Disable monitoring or close the application when finished.

Inactivity monitoring starts disabled until enabled by the user.

### Quick Shutdown Shortcut

The V2.1.1-bundled Null Out application includes an optional quick-shutdown function.

When separately armed, holding **G + S for approximately three seconds** can initiate shutdown without an additional in-app warning.

This functionality is disabled by default.

### Important Warning

GS Null Out may cause unsaved work to be lost.

Do not enable automatic or quick shutdown on critical systems unless you understand and accept the consequences.

---

## Understanding GS Script vs. Custom GS Runners

| GS Script | Custom GS Runner |
|---|---|
| Plain-text automation commands | Standalone compiled application |
| Uses GS Script engine | Uses application launcher |
| Keyboard and mouse automation | Dedicated visual or system utility |
| Saved as script files | Prepared in Custom Runner folders |
| Manually executed through Run | Manually launched through Launch |

GS USB Runner is designed to introduce both forms of automation in a single beginner-friendly platform.

---

## Portable USB File Structure

Depending on which applications you launch, GS USB Runner may create a folder layout similar to:

```text
YOUR_USB_DRIVE/
|
|-- GS_USB_Runner_V2.1.1_START_HERE.exe
|
|-- GS_USB_Runner_V2.0_Script_Engine_DO_NOT_OPEN.exe
|
|-- scripts/
|
|-- themes/
|
|-- settings.json
|
|-- GS_Custom_Runners/
|   |-- GS_Ransomware_Awareness.exe
|   |-- GS-Network-View.exe
|   |-- GS_BSOD_Simulator.exe
|   |-- GS-HID-Script-Portable.exe
|   |-- GS_Shadow_Tracker/
|   |-- GS_Blackout/
|   |-- GS_NullOut/
|
|-- GS_Shadow_Tracker_Data/
|   |-- wardrive.sqlite3
|   |-- originals/
```

Exact filenames and folders may vary depending on the companion application and which features have been used.

The internal script-engine executable is managed automatically. Do not launch it manually.

Some supporting diagnostic or runtime files may be stored in Windows-local application directories.

---

## Updating GS USB Runner

Before updating:

1. Close GS USB Runner.
2. Close HID Script Builder and all running Custom Runners.
3. Properly stop GS Shadow Tracker.
4. Back up your saved scripts.
5. Back up your settings and themes.
6. Back up the entire `GS_Shadow_Tracker_Data/` folder.
7. Download the new release.
8. Copy the new `START_HERE.exe` onto your USB drive.
9. Launch the updated application.
10. Verify your saved data remains available.

Avoid running multiple versions of GS USB Runner simultaneously.

---

## Safely Removing Your USB Drive

Because GS USB Runner can launch other applications and write data to the flash drive, always close running programs before unplugging it.

1. Exit active Custom Runners.
2. Stop GS Shadow Tracker properly.
3. Exit the HID Script Builder.
4. Restore interfaces disabled by GS Blackout.
5. Exit GS USB Runner.
6. Use Windows **Safely Remove Hardware**.

Removing the drive while an application is writing files may corrupt saved information.

---

## Troubleshooting

### Nothing Happens When I Plug In My USB

This is normal.

Standard USB drives do not automatically execute GS USB Runner.

Open the flash drive and manually launch the executable.

### The First Launch Is Slow

The application may need to prepare supporting files, initialize its local service, and create folders.

Performance depends on USB drive speed and Windows security scanning.

### Two Runner Executables Appear

This can be expected.

The main launcher may prepare an internal script-engine executable marked `DO_NOT_OPEN`.

Always start the application using `START_HERE.exe`.

### My Script Types Into the Wrong Window

GS Script sends simulated input to the active Windows desktop application.

Make sure the correct window is focused.

Use additional WAIT commands if the application needs time to load.

### HID Script Builder Does Not Launch

Close any existing HID Script Builder process and restart Runner.

Windows may prevent updating an executable while it is already running.

### Shadow Tracker Exits on Startup

The early V2.1.1 Shadow Tracker includes a Python-based service and has known compatibility issues on some Windows computers.

Review available logs and diagnostics. Do not delete saved investigations to troubleshoot the issue.

### Custom Runner Appears Behind the Browser

Use the Windows taskbar or **Alt+Tab** to bring the application forward.

Windows manages foreground-window focus.

### Windows Shows a Security Warning

Unsigned programs may receive additional Windows SmartScreen or antivirus checks.

Download from the official GitHub repository and verify available checksums.

Do not disable security protections simply to force the application to run.

### Cannot Safely Eject USB Drive

Close GS USB Runner and all companion programs.

Check for remaining processes that may be using files on the drive.

### Reporting Bugs

Open an issue at:

**https://github.com/Ghoststrats/GS-USB-RUNNER/issues**

Include:

- Windows version
- GS USB Runner version
- Application or feature affected
- Steps to reproduce
- Exact error message
- Screenshot if helpful

Remove any personal or sensitive information before sharing logs or screenshots.

---

## Hidden Ghost Run Mini-Game

GS USB Runner includes a hidden GhostStrats-themed arcade mini-game.

### How to Unlock

In the original V2.0/V2.1 interface, click **GHOSTSTRATS** in the lower-left footer ten times within approximately twelve seconds.

### Controls

- **W/A/S/D** or arrow keys — Move
- **P** — Pause
- **Escape** — Return to Runner

Ghost Run is a browser-based mini-game and does not execute GS Scripts or scan networks.

---

## Source Code and Developer Information

The V2.1.1 GitHub release includes source packages for users interested in learning how the application is constructed.

### GS USB Runner Integration Source

`GS_USB_Runner_V2.1.1_Integration_Source.zip`

Contains:

- Go integration launcher source
- Windows process-management components
- Web interface integration
- Custom Runner support
- GS Blackout source assets
- Build instructions
- Required precompiled dependencies

### GS Shadow Tracker Source

`GS_Shadow_Tracker_USB_Runner_Source_v1.0.3.zip`

Contains the corresponding early Shadow Tracker Go-wrapper and Python-based analysis source.

### Building the Integration Host

Install Go 1.23 or newer.

Extract the integration source package and run:

```bat
BUILD_V2.1.1_WINDOWS.bat
```

The integration host can be rebuilt from the included source and build assets.

**Source Availability Notice:** Some bundled applications and the original script engine are provided as compiled dependencies without their complete original source trees. Rebuilding the launcher does not independently rebuild every included program.

This release should be described as **source-available**, rather than a fully open-source distribution.

Review the included licensing and source documentation before modifying or redistributing components.

---

## Educational Purpose and Responsible Use

GS USB Runner was created for:

- Cybersecurity education
- Authorized security testing
- Defensive research
- Networking education
- Desktop automation
- Privacy awareness
- Technical demonstrations
- Beginner scripting education

Use these tools only on computers and networks you own or have explicit authorization to test.

### Important Safety Notes

**GS Ransomware Awareness** is a visual simulation. It does not intentionally encrypt files.

**GS BSOD Simulator** displays simulated system-failure screens and does not intentionally crash Windows.

**GS Network View** is intended for authorized networking diagnostics.

**GS Shadow Tracker** analyzes previously collected wireless observations. Its findings are not proof that someone is following you.

**GS Blackout** changes real device settings and may disconnect hardware.

**GS Null Out** can shut down Windows and cause unsaved data loss.

**GS Script** can send real keyboard and mouse input and should be reviewed before execution.

A normal USB flash drive does not automatically run GS USB Runner and does not function as a physical HID injection device.

The software is provided **AS IS**, subject to applicable licensing terms. Hardware compatibility and operation are not guaranteed.

---

## About GhostStrats

GhostStrats develops accessible educational projects focused on cybersecurity, automation, privacy, networking, and technological preparedness.

GS USB Runner was created with a simple purpose:

**Make cybersecurity and automation easier to learn without requiring expensive hardware or years of technical experience.**

The platform will continue evolving through community feedback, new educational tools, and additional Custom GS Runners.

### Official Links

**GhostStrats GitHub:**  
https://github.com/Ghoststrats

**GS USB Runner Repository:**  
https://github.com/Ghoststrats/GS-USB-RUNNER

**Latest GS USB Runner Release:**  
https://github.com/Ghoststrats/GS-USB-RUNNER/releases/latest

**GS HID Script Tool:**  
https://github.com/Ghoststrats/GS-HID-Script-Tool

**Report Issues:**  
https://github.com/Ghoststrats/GS-USB-RUNNER/issues

---

## Thank You!

Thank you to everyone supporting GhostStrats and helping develop these community projects.

Your feedback, testing, suggestions, and continued support help make these tools better and more accessible.

GS USB Runner is more than a scripting application. It's the foundation of a beginner-friendly cybersecurity learning ecosystem.

**Developed by GhostStrats LLC**

**SAFETY IS AN ILLUSION.**
