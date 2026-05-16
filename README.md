# Course Control

**Remote control for GS Pro golf simulator.** Control GS Pro from your phone or tablet over local WiFi — no app install on your phone.

Scan the QR code from the Course Control desktop app and start playing.

## Download

Go to the [latest release](https://github.com/coursecontrol/coursecontrol-releases/releases/latest) and download the installer for your system:

| File | Who it's for |
| --- | --- |
| **CourseControl-Setup-x64.exe** | Most Windows PCs (Intel / AMD) — **download this one** |
| CourseControl-Setup-arm64.exe | ARM-based Windows PCs (Surface Pro X, etc.) |

> The `.blockmap`, `latest.yml`, and source code files are used internally for auto-updates. You don't need to download them.

## Installation

Course Control is currently in beta and not yet code-signed, so Windows will show a few warnings during installation. This is normal for beta software — here's exactly what to expect.

### Step 1: Download

- Click the **x64** installer link from the [latest release](https://github.com/coursecontrol/coursecontrol-releases/releases/latest)
- **Chrome may warn** that the file "is not commonly downloaded" — click the **up arrow (^)** next to the warning, then **"Keep"**
- If Chrome blocks it entirely, go to `chrome://downloads` and click **"Keep dangerous file"** (it's not dangerous, just unsigned)

### Step 2: Run the Installer

- Double-click the downloaded `.exe`
- **Windows SmartScreen** will show a blue popup: *"Windows protected your PC"*
  - It only shows a **"Don't run"** button at first — **don't click that**
  - Click **"More info"** (small text link below the warning)
  - Then click **"Run anyway"**
- Follow the installer prompts

### Step 3: Allow Through Firewall

- On first launch, Windows Firewall will ask: *"Allow Course Control to communicate on networks?"*
- Click **"Allow access"** — this lets your phone connect over WiFi

### Step 4: Connect Your Phone

- Course Control opens and shows a **QR code**
- Scan it with your phone's camera
- The remote control opens in your phone's browser — no app install needed
- Both devices must be on the **same WiFi network**

> **These warnings only happen once.** After installation, Course Control starts cleanly from the Start Menu or system tray. Future updates install automatically with no warnings.

## Security

Course Control runs entirely on your local network — no data is sent to external servers. All control signals stay between your phone and your PC over WiFi.

Each release is scanned by 70+ antivirus engines on VirusTotal. Scan results are posted in the release notes on the [Releases page](https://github.com/coursecontrol/coursecontrol-releases/releases).

## Requirements

- Windows 10 or later (x64 or ARM64)
- GS Pro running on the same PC
- Phone or tablet on the same WiFi network as your PC

## Beta Access

Course Control includes a **14-day free trial** that starts automatically when you install it.

After the trial, you'll need a license key or beta key. If you received a beta key, enter it in the app: click **"Enter license key"** on the dashboard and paste your key.

Need a beta key? Contact the developer.

## Auto-Updates

Once installed, Course Control checks for updates automatically on every launch. When a new version is available:

1. The dashboard shows download progress
2. An **"Install and restart"** button appears when the download finishes
3. Click it — the app restarts with the new version in a few seconds

Updates also install silently when you quit the app. You never need to re-download from this page after the initial install.

## Troubleshooting

- **Phone can't connect?** Make sure you clicked "Allow" on the Windows Firewall prompt. If you missed it, search Windows for "Allow an app through firewall" and enable Course Control.
- **Wrong IP showing?** If you use a VPN, disconnect it — VPNs can change your PC's IP address.
- **Controls not working?** GS Pro must be the active (foreground) window for controls to work.
- **QR code not scanning?** You can also type the address shown on the dashboard directly into your phone's browser.
- **App not starting?** Check that Course Control isn't already running in the system tray (bottom-right of your taskbar).
