# TaskbarXI
An application written in C++ to modify the Windows 11 Taskbar. Current version turns the Windows 11 Taskbar into a dock. New features will be added in the future.  

<h1 align="center">🪟 Windows 11 Mac Look-Alike Taskbar - Free</h1>

<p align="center">
  <img src="https://img.shields.io/badge/100%25-Free-brightgreen" />
  <img src="https://img.shields.io/badge/Built%20with-%E2%9D%A4-red" />
  <img src="https://img.shields.io/badge/Inspired%20by-TaskbarXI-blue" />
  <img src="https://img.shields.io/github/stars/shariquetelco/windows11-mac-look-alike-taskbar-free?style=social" />
  <img src="https://img.shields.io/github/license/shariquetelco/windows11-mac-look-alike-taskbar-free" />
</p>

---

## 🧭 Overview

**Windows11-Mac Look-Alike Taskbar - Free** is a minimal tool that transforms your Windows 11 taskbar into a macOS-style floating dock — sleek, clean, and elegant.

🎉 Completely free and open-source. No ads. No telemetry.

---

## 📥 DOWNLOAD and SETUP

Download the latest version from the [**Releases**](https://github.com/shariquetelco/windows11-mac-look-alike-taskbar-free/releases) page.

> Original binary is from [TaskbarXI](https://github.com/ChrisAnd1998/TaskbarXI/releases)

---

## ✨ Features

- 🖥️ Creates a floating, centered taskbar like macOS
- 🧼 No UI — lightweight and distraction-free
- 🔄 Auto-adjusts based on screen resolution
- 💻 Minimal resource usage

---

## 🛠 Installation

1. 📦 Download the latest `.exe` from [Releases](https://github.com/shariquetelco/windows11-mac-look-alike-taskbar-free/releases).
2. 🖱️ Double-click to launch — no installation needed.
3. ⚙️ Customize using a config file (optional).

---

## 🧑‍💻 Credit

Huge thanks for the work and inspiration 🙌
1. [TaskbarXI](https://github.com/ChrisAnd1998/TaskbarXI)
2. [PrincessAkira](https://github.com/PrincessAkira)
3. [dmitryaleshin](https://github.com/dmitryaleshin)



---

## 📝 License

See the [`LICENSE`](LICENSE) file for details. This project follows the same license as the original.

---

> 💡 Tip: Combine with custom themes for a full macOS feel on Windows 11!


![TaskbarXI](https://user-images.githubusercontent.com/50437199/148023157-7d2c8a9d-cd82-499c-9a98-52d53625296a.png)




## **Features (Release 1.0.3)**
* Turn the Windows 11 Taskbar into a dock.  
* Turn the tray/clock into a dock.  
* Support multiple monitors.  
* Support sepperate DPI scaling. 
* Switch back to normal on maximized window.  
* Support left and centered taskbar.
* Tray icon to exit TaskbarXI and revert to the default taskbar.
* Simple GUI to change the settings.  

&nbsp;

## **Upcoming Features**
* Change taskbar background style and color.  

&nbsp;

## **Parameters**
**With 1.0.3 release all Parameters can be changed with GUI**,<br/><br/> 
If you still want to change properties with console, here are Parameters:
* **`-stop`** parameter (Stops TaskbarXI and reverts the taskbar to default)
* **`-restart`** parameter (Does not refresh the taskbar region when starting)
* **`-square`** parameter (Uses square corners instead of rounded corners)
* **`-radius <radius>`** parameter (Define the corner radius you want to be used)
* **`-ignoremax`** parameter (Does not revert the taskbar on maximized window)
* **`-notray`** parameter (Disables system tray icon)
* **`-hidetraywnd`** parameter (Hides the system tray area)
* **`-createstartup`** parameter (Creates a startup entry including the current parameters)
* **`-removestartup`** parameter (Removes startup entry and exits TaskbarXI)
* **`-console`** parameter (Displays a console window)
* **`-sticky`** parameter (Sticks the system tray to the taskbar (removes the tray icons to keep it stable))
* **`-help`** parameter (Displays a help window)
* **`-smoothresize`** parameter (Resizes the taskbar smoothly)
* **`-expandspeed <speed>`** parameter (Define the speed you want to be used for the expand animation (default: 90))
* **`-shrinkspeed <speed>`** parameter (Define the speed you want to be used for the shrink animation (default: 700))
* **`-blur`** parameter (Makes the taskbar blurred) <-- **EXPERIMENTAL**



  
**CMD Example:** `"TaskbarXI.exe" -ignoremax -expandspeed 100 -square`  