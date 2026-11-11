# Version history

**English** · [简体中文](CHANGELOG.zh-CN.md) · [繁體中文](CHANGELOG.zh-TW.md) · [日本語](CHANGELOG.ja.md)

What each version added. Downloads: [Releases](https://github.com/techinfo-apps/UnitCtrl/releases) (Mac, Windows, Linux) · Android: Google Play closed test ([how to join](README.md#android)).

## Mac

### 1.4 — 2026-11-11
- **Spaces** (Settings → Spaces): share one Wi‑Fi — an office, a dorm, a shared flat — and keep your devices to yourselves. Join or create a space with a name and a password, or a random pairing code.
- Phones in the same space connect without anyone tapping “Allow”; devices in other spaces aren't listed and can't get in.
- The password never goes over the network: the Mac and the phone each prove they know it. Phones need UnitCtrl 1.15 or later; older phones work as before.

### 1.3 — 2026-11-07
- **Desktop Mode** (what used to be called “Phone Apps”): put any app from your phone in a Mac window of its own and use it like a Mac app — resize it, line it up beside your other windows, copy and paste with the Mac, type Chinese or Japanese with your own input method. The phone's own screen stays as it is.
- Several apps at once, each in its own window. A window you can't see — covered by another window, or minimized — costs the phone nothing: it stops encoding for that window until you look at it again.
- One window per app: asking for an app that already has a window brings that window forward, rather than taking the app off it.
- A window that loses its connection opens the app again by itself, instead of asking you to close it and start over.
- Needs Android 10 or later, over a cable or wireless debugging. Nothing is installed on the phone.

### 1.2 — 2026-10-25
- Clipboard shared with your phones (Settings → Clipboard, on by default): copy on the Mac and paste on the phone; on the phone, send text back with “Send to Computer” in the quick settings or the share menu. What one phone sends reaches your other phones too, through the Mac. Text only; copies from password managers stay on the Mac. Needs the phone app 1.13 or later.

### 1.1 — 2026-10-21
- The live screen over your network shows the delay, frames per second and Mbit/s next to “Live” (the delay needs the Android app 1.12 or later).
- A menu picks how the picture is made: **Automatic**, **Picture First** (the whole screen, sharper) or **Smoothness First** (smaller, skips late pictures). It can also hide the numbers.
- Pictures show as soon as they're complete, with less delay (with the Android app 1.12 or later).
- About: “Free forever. No ads, ever.”, a link to the downloads, and **Buy the Developer a Coffee…**, one click away.
- The Android app now comes from Google Play only. The Mac app no longer carries a copy, which halves the download. Setting up a phone that already has it still gives it its permissions and allows your Mac.
- The system's Local Network and Photos prompts now say UnitCtrl, in every language.

### 1.0 — 2026-10-19
- First public test. Every Android phone and tablet at home in one window, over USB or Wi‑Fi.
- Live screen: click, drag and scroll with the mouse, type with your Mac keyboard in any language, hear the sound.
- Apps, files, screenshots and screen recording, photos straight to the device's gallery, screen-on and app history, notifications from the menu bar.

## Windows

### 1.0 — 2026-10-21
- First public test. See and control your Android devices from a Windows PC over your local network: the mouse as a finger, typing in any language, scrolling, Back and Home, sound on the PC (or only on the PC), three picture levels, round trip / frame rate / bit rate shown.
- Devices on the same network show up by themselves, or add one by its IP address.
- With a USB cable or wireless debugging (adb): device overview, Apps, Files, Photos, screenshots and screen recording, keep the screen on, send files, phone apps in windows of their own, and Computer Folders.
- Portable zip for x64 and ARM64; Windows 10 (2004 or later) or Windows 11. A license agreement on first launch.

## Linux

### 1.0 — 2026-10-21
- First public test. See and control your Android devices from a Linux PC over your home network: the mouse as a finger, typing in any language, scrolling and pinch, Back / Home / Recents, sound on the PC (or only on the PC), three picture levels, delay / round trip / frame rate shown. .deb for Ubuntu / Debian and an AppImage for other distributions, x64 and ARM64.

## Android (Google Play closed test)

### 1.15 — 2026-11-11
- **Spaces**: join or create a space with a name and a password, or a random pairing code. Devices in the same space see each other and connect without tapping “Allow”; devices in other spaces aren't listed and can't get in.
- “Only devices in my spaces”: turn away everyone else without being asked.
- The old “let every device on the network in” switch is gone: spaces replace it.

### 1.14 — 2026-10-30
- Shared videos for UnitPlayer on your other devices; a link to rate UnitCtrl and to write to us at the bottom of Settings.

### 1.13 — 2026-10-25
- Clipboard shared with your computer: “Send to Computer” in the quick settings and the share menu.
- “Open-source licenses” at the bottom of Settings.

### 1.12 — 2026-10-21
- Lower remote-screen delay: when the phone can't keep up, it drops frames instead of falling further behind.
- Sound can play only on the side that's listening; the phone you control mutes itself.

### 1.0 — 2026-10-19
- First closed test. The other devices at home show up as cards: tap one to see its screen, tap and type on it.
- The first time a device wants to control yours, you're asked; nothing gets in without your “Allow”.
- Choose what each device is for: control others, be controlled, or both.

---

Free forever. No ads, ever. · Contact: sublueai@gmail.com · Website: https://techinfo-apps.github.io/
