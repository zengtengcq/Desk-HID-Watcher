# 🐱 Desk-HID-Watcher

A lightweight, zero-dependency desktop pet for Windows. 

Unlike traditional Electron or .NET applications, this pet uses **PowerShell Inline C# (`Add-Type`)** to compile and run directly in memory. It requires no external SDKs, no runtime installations, and leaves no bloat on your machine.

## ✨ Features
* **Zero Dependencies**: Runs natively on Windows PowerShell 5.1.
* **Ultra-Lightweight**: Low CPU and RAM footprint.
* **HID Aware**: Listens to global keyboard strokes, mouse movements, and USB device insertions.
* **Smooth Animation**: Double-buffered rendering for buttery-smooth sprite animations.

## 🚀 How to Run
1. Clone the repository.
2. Right-click `DeskPet.ps1` and select **"Run with PowerShell"**.
   *(Note: If Windows blocks the script, open PowerShell as Admin and run `Set-ExecutionPolicy Bypass -Scope Process` first.)*
3. Alternatively, double-click `run.vbs` for a seamless, console-less launch.

## ⚠️ Antivirus Warning
Because this project dynamically compiles C# code in memory and hides its window, some antivirus software (like 360 or Huorong) may flag it as a false positive. Please add the script folder to your whitelist.

## 📜 License
MIT
