# Unlocking Games & Library Tab

This page covers how to unlock a game in ONENNABE and how to navigate the Library tab, including everything available in the right-click context menu.

---

## Unlocking a Game

### Step 1 — Find the Game in the Store Tab

1. Open **Steam Unlock ONENNABE**
2. Go to the **Store** tab
3. Browse or use the search bar to find the game you want
4. Click the game card to open the Game Detail modal

### Step 2 — Unlock the Game

Inside the Game Detail modal:

1. Click **Unlock Game**
2. ONENNABE will apply the unlock to your Steam account
3. The game will now appear in your Steam library

### Step 3 — Lock the Game Version (Before Downloading)

Before downloading in Steam, lock the game version to prevent Steam from updating it to an incompatible version:

```
SUO > Tools > Game Auto Update > click Open > find the game
```

!!! info "Default state"
    By default, games are already in **Lock** mode.  
    **Disable = Lock** | **Enable = Unlock**  
    Always keep it on Lock (Disable) before downloading.

### Step 4 — Download from Steam

1. Open **Steam**
2. Find the game in your library
3. Click **Install** and wait for it to fully download

---

## Navigating the Library Tab

The Library tab shows all games that have been unlocked and downloaded on your PC.

### Layout

- **Left sidebar** — lists all your unlocked games, searchable by name
- **Right panel** — shows the selected game's details, cover art, and action buttons

### Finding a Game

Use the **search box** at the top of the left sidebar to filter games by name. Click any game to load its detail panel on the right.

---

## Right-Click Context Menu

Right-clicking any game in the Library tab opens a context menu with the following options:

---

### Play

Launches the game. If multiple executables are available, you will be prompted to choose:

- The game's main `.exe`
- `HV-PlugNPlay.bat` / `HV-Launcher.bat` (for Hypervisor games — Windows 11 only)

---

### Bypass Game

Applies the bypass patch to the game. Use this for games tagged `Bypass Available`.

!!! warning
    Turn off antivirus before using this option. Bypass files will be removed by antivirus if real-time protection is on.

---

### Online Patch

Applies the online patch to the game. Use this for games tagged `Online Supported`.

!!! warning
    Turn off antivirus before using this option.

---

### Smart Apply

Runs Smart Apply on the game. This prepares the game files before downloading in Steam. Always run this before downloading a Bypass or Online Supported game.

---

### Inject HV Launch Option

Injects the Hypervisor launch option into Steam so the game can be launched directly from Steam with HV support. Use this if you prefer launching from Steam instead of from ONENNABE.

See [Hypervisor Guide](hypervisor.md) for full details.

---

### Lock / Unlock Version

Toggles the game's auto-update setting in Steam:

- **Lock (Disable)** — prevents Steam from auto-updating the game. Use this to keep the game on a working version.
- **Unlock (Enable)** — allows Steam to update the game normally.

!!! tip
    Always keep games on **Lock** after downloading to prevent Steam updates from breaking the unlock.

---

### Open Game Folder

Opens the game's installation folder in Windows Explorer. Useful for:

- Manually running `.bat` or `.exe` files
- Checking if bypass/patch files are present
- Troubleshooting missing files

---

### Remove from Library

Removes the game from the ONENNABE Library tab. This does **not** uninstall the game from Steam — it only removes it from the ONENNABE list.

---

## Still Not Working?

See the [Troubleshooting](troubleshooting.md) page for step-by-step fixes.
