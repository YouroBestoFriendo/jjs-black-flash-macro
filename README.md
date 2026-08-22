# ⚡ JJS Black Flash Macro v5.0 — Multi-Theme Ultra Edition ⚡

An advanced AutoHotkey v1.1 utility tailored specifically for **Jujutsu Shenanigans (JJS)** on Roblox. Features a dynamic GUI overlay, customizable themes, preset combo routines, and rapid-execution pro techs.

---

## 🚀 Installation & Usage

1. Download and install [AutoHotkey v1.1+](https://www.autohotkey.com/).
2. Create a new text file, paste the macro script into it, and save it as `JJS_Macro.ahk`.
3. Double-click `JJS_Macro.ahk` to launch the macro.
4. Open **Roblox** and join **Jujutsu Shenanigans**.

---

## 🌟 Key Features

* **🎨 Multi-Theme System:** Switch seamlessly between 4 visual styles (Dark Neon, Clean Light, RGB Light, and Dynamic RGB Dark).
* **⚡ Character Presets:** Pre-configured combos and timings engineered for 5 different character kits.
* **🖥️ Dynamic Overlay (HUD):** Real-time status tracker, drag-and-drop movement, and automatic window coordinate saving.
* **🛠️ Advanced Pro Techs:** Instant macros for feint cancels, ragdoll cancels, slide walking, and 3x M1 bursts.
* **🔒 Awakening Safety Lock:** Toggle lock to prevent accidental base-form combo execution while in Awakened form.

---

## 🎭 Supported Characters & Combos

| Character | Cursed Tech / Role | Default Combo Sequence | Accent Color |
| :--- | :--- | :--- | :--- |
| **⚡ Yuji Itadori** | The Vessel // Cursed Strike | `[3] ──► [3]` | Neon Pink (`#FF1493`) |
| **🌀 Satoru Gojo** | The Honored One // Limitless | `[2] ──► [R x10]` | Electric Cyan (`#00FFFF`) |
| **💀 Mahito** | Perfection // Idle Transfiguration | `[3] ──► [3]` | Vibrant Purple (`#A020F0`) |
| **✨ Aoi Todo** | Boogie Woogie // Switcher | `[3] ➔ [R] ➔ [2] ➔ [2]` | Cyber Gold (`#FFD700`) |
| **🎯 Kento Nanami** | 7:3 Ratio // Salaryman | `[R] ──► [R]` | Acid Lime (`#39FF14`) |

---

## 🎮 Keybindings & Controls

### 🗲 Core Commands
* **`F1`** — Execute Black Flash Combo
* **`F2`** — Cycle Character Next
* **`F3`** — Cycle Character Previous
* **`F4`** — Toggle Awakening State *(Locks base-form macros)*
* **`F5`** — Decrease Latency Delay (-5ms)
* **`F6`** — Increase Latency Delay (+5ms)
* **`~` (Tilde)** — Toggle HUD Visibility

### ⚡ Advanced Pro Techs
* **`F7`** — Feint Cancel
* **`F8`** — Ragdoll Cancel (`A` + `Q`)
* **`F9`** — Slide Walk (`W` + Dash)
* **`F10`** — Perfect 3x M1 Burst

### 🎨 System Controls
* **`F11`** — Cycle GUI Theme
* **`F12`** — Save Configuration & Shutdown

---

## ⚙️ Configuration & Save Data

The script automatically generates and updates a `jjs.ini` file in the same directory to remember settings across sessions:

```ini
[cfg]
mode=0       ; Current character index (0-4)
delay=350    ; Active delay timing in milliseconds
theme=0      ; Theme selection (0-3)
x=20         ; Screen X position
y=20         ; Screen Y position
