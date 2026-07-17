# 📡 APRS_Wx_v2 — Powered by Python  ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) (Windows Only)
## 🧠 Zero Hardware. Zero Hardcoding. Zero Hassle.
No sketches, no soldering, and absolutely **no library dependencies!** 😎  
Just a lightweight, plug-and-play APRS weather beacon — configurable using **any text editor**.

## 📢 Latest Update (17-july-2026)

- **`APRS_HOST`** has been updated to improve server connectivity and reliability.

---

💡 **No installation required!**  
Runs directly as a **portable application** — from your PC or even a **USB pendrive**. 🧳💻

---

## 🔧 Dependencies

> **None.**  
> 100% standalone — no external libraries or APIs needed to run locally.
>
> 

---

## ⚙️ Configuration Steps

1. 📦 **Download** the `aprs.zip` folder from this repository and **extract** it to any location on your system.  
         You’ll find both **`aprs.exe`** and **`config.ini`** in the same folder.
   
   ![extract2](https://github.com/user-attachments/assets/9c8de663-d42a-48d6-9d38-940a3818e5d0)
3. 📝 Open **`config.ini`** in your favorite text editor (e.g. Notepad, VS Code, Notepad++).
4. ✏️ Fill in the following fields:
   - 📍 **Latitude** & **Longitude**
   - 📡 **User Callsign**
   - 🔐 **APRS Passcode**
   - ⏱️ **Time Interval (in minutes)**
5. 💾 Save the file.
6. 🚀 Run **`aprs.exe`** — just like any other software!

   


> [!NOTE]
> Once your callsign & passcode are verified, your WX station will automatically appear on [**aprs.fi**](https://aprs.fi).

---

### 📝 Example: Notepad
<img width="1479" height="440" alt="Config Example (Notepad)" src="https://github.com/user-attachments/assets/a8d5d079-7aed-4fe4-96cd-b3582f9a1c9e" />

### 📝 Example: Notepad++
<img width="1441" height="358" alt="Config Example (Notepad++)" src="https://github.com/user-attachments/assets/8461aa41-e1f4-47fb-855e-28f29119c991" />

---

## ✨ Features

- 💻 **No Hardware Required**
- 🌦️ Fetches real-time weather data from **Open-Meteo.com**.
- ⚡ Deploy an APRS WX beacon within minutes.
- 🔁 Supports running on system startup.

---

## 💾 Requirements

- 🪟 **Windows PC**  
- ✅ *No additional hardware needed!*. 😁

---

## 🌐 Usage Guide

Follow the configuration steps above, and you’ll be live on APRS in minutes!. 📡

---
### 🚀 Add to Startup (Windows)

To automatically start **APRS_Wx_v2** whenever you log into Windows:

1. Create a folder on your **C:** drive (for example, `C:\APRS`) and move the extracted **`aprs.exe`** and **`config.ini`** files into this folder.

2. Right-click **`aprs.exe`** and select **Create shortcut**.
   - If Windows asks to place the shortcut on the desktop instead, click **Yes**.
   - A shortcut named **`aprs.exe - Shortcut`** (or similar) will be created on your desktop.

3. Open the Windows Startup folder:
   - Press **Win + R**
   - Type:
     ```text
     shell:startup
     ```
   - Press **Enter**.

4. Copy the shortcut from your desktop and paste it into the **Startup** folder.

5. Restart your computer. **APRS_Wx_v2** will automatically launch when you log in.

6. After restarting, open **[aprs.fi](https://aprs.fi)** to verify that your weather station data is being uploaded successfully.

> **Note:** It is recommended to place a **shortcut** in the Startup folder rather than moving the actual `aprs.exe` file. This keeps the program in its original location while allowing Windows to launch it automatically at login.

---

## 🛠️ Roadmap

- [x] Add startup instructions for running the software on system startup.  
- [ ] Include extended atmospheric gas composition data

---






<!--

# 📡 APRS_Wx_v2 — Powered by Python 🐍
![Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)

![Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


# 📡  APRS_Wx_v2 Powered by Python

## NO HARDWARE !! 
NO hardcoding, no sketch modifications, and absolutely no library dependency. :trollface: <br>
Lightweight and Configurable using any text editor. 😮 👀

### configuration steps:
>- Open **config.ini** using any __text editor__
>- Add your station latitude and longitude
>- User callsign
>- Passcode for APRS
>- Time interval in minutes
>- Save file config.ini
>- Run __aprs.exe__ as any other software

> [!NOTE]
> Once your callsign & passcode is verified by server, Wx station details will be visible on [aprs.fi](https://aprs.fi)

EXAMPLE: _notepad_
<img width="1479" height="440" alt="1wx" src="https://github.com/user-attachments/assets/a8d5d079-7aed-4fe4-96cd-b3582f9a1c9e" />

EXAMPLE: _notepad++_
<img width="1441" height="358" alt="2wx" src="https://github.com/user-attachments/assets/8461aa41-e1f4-47fb-855e-28f29119c991" />


## ✨ Features
No Hardware needed <br>
Data automatically fetched from Open-Meteo.com <br>
Deploy APRS Wx beacon within minuites <br>
Run on system start <br>


## 📦 Hardware Requirements
 ⋅⋅⋅⋅* Windows PC <br>
⋅⋅⋅⋅* `No other hardware is required` ☺️


## 🌐 Usage Guide
⋅⋅⋅⋅* Please follow configuration steps

## 🔧 Dependencies
~~NoThInG~~

## 🛠️ Roadmap
- [ ] Instruction to run software on system start
- [ ] Add other gases composition
---
-->
