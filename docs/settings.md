# Settings

Access the Settings panel by clicking **⚙ Settings** in the top navigation bar.

---

## Account

### 🔑 Activate App

Opens the CD Key activation screen. Use this if your activation has expired or you need to re-enter your key after a reinstall.

See [CD Key Activation](cd-key-activation.md) for full details.

### 🗑️ Reset Activation

Removes the currently bound CD Key and Steam account binding from this installation. Use this only if you need to re-activate on a different Steam account.

!!! danger
    Resetting activation will unbind your CD Key from this machine. Contact your seller before doing this.

---

## Settings

### Parental Control

**Hides adult content** from the Store tab.

When enabled, a **4–8 digit PIN** is required to turn it off again.

#### How to Enable

1. Open **⚙ Settings**
2. Toggle **Parental Control** to ON
3. A PIN setup dialog will appear
4. Enter a 4–8 digit PIN
5. Confirm the PIN
6. Click **OK**

Adult content is now hidden from the Store tab.

#### How to Disable

1. Open **⚙ Settings**
2. Toggle **Parental Control** to OFF
3. Enter your PIN when prompted
4. Click **OK**

!!! warning "Do not forget your PIN"
    There is no PIN recovery option. If you forget your PIN, contact support.

---

### OpenSteamTool

Enables or disables the **OpenSteamTool.dll** — the core unlocker that hooks into Steam to apply game unlocks.

| State | What Happens |
|---|---|
| **ON** (default) | OpenSteamTool is active — games are unlocked via the DLL hook |
| **OFF** | OpenSteamTool is disabled — reverts to using Steam's built-in tools |

!!! tip "When to turn this OFF"
    Turn off OpenSteamTool if:

    - Your **Denuvo borrow account** is not working
    - You are experiencing Steam login issues caused by the hook

    **Steam must be restarted** after toggling for the change to take effect.

#### How to Toggle

1. Open **⚙ Settings**
2. Find **OpenSteamTool** under the Settings section
3. Toggle it ON or OFF
4. **Restart Steam** to apply the change

---

### Resize UI

Adjusts the zoom level of the ONENNABE interface.

- Press **＋** to zoom in
- Press **−** to zoom out

Useful if the interface appears too small or too large on your display.

---

## Window

### Minimize to System Tray

When enabled, closing the ONENNABE window keeps the app running in the **system tray** (bottom-right corner of the taskbar) instead of fully exiting.

- Right-click the tray icon to open or exit the app
- Useful if you want ONENNABE to stay running in the background

### Always Ask Before Closing

When enabled, ONENNABE will always ask whether to **minimize to tray** or **quit** when you close the window.

When disabled, ONENNABE remembers your last choice and applies it automatically without asking.
