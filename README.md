# NiriDots
A Niri build, created for void and neko void, it strikes a balance between comfort, visual appeal, and performance



# Screenshot
<img width="1824" height="1024" alt="image" src="https://github.com/user-attachments/assets/986e4694-22bd-4e11-909a-ee5f7262ec4a" />
<img width="1824" height="1024" alt="image" src="https://github.com/user-attachments/assets/b0048fd1-0f4e-489a-915c-49083f1a9ef2" />



# Deps

```
foot
adw-theme or similar
dbus
niri
noctalia V5 or >
cozette
pamixer
pcmanfm
xdg-desktop-portal-gnome
xwayland-satellite
```
# Keybinds
 // General

| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>T</kbd>| Open Terminal (foot)
|<kbd>Super</kbd> + <kbd>B</kbd>| Browser (Waterfox)
|<kbd>Super</kbd> + <kbd>E</kbd>| File Manager (PCmanFM)
|<kbd>Super</kbd> + <kbd>Space</kbd>| Show Launcher
|<kbd>Super</kbd> + <kbd>S</kbd>| Toggle Control Center
|<kbd>Super</kbd> + <kbd>,</kbd>| Toggle Noctalia Settings
|<kbd>Super</kbd> + <kbd>D</kbd>| Toggle Overview
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>/</kbd>| Show Hotkey Overlay
|<kbd>Super</kbd> + <kbd>Alt</kbd> + <kbd>L</kbd>| Lock Screen (swaylock)
|<kbd>Alt</kbd> + <kbd>Tab</kbd>| Window Switcher
|<kbd>Super</kbd> + <kbd>Tab</kbd>| Window Switcher

 // Navegation
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>←</kbd> / <kbd>→</kbd>| Focus Column Left / Right
|<kbd>Super</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd>| Focus Window Up / Down
|<kbd>Super</kbd> + <kbd>J</kbd> / <kbd>L</kbd>| Focus Column Left / Right
|<kbd>Super</kbd> + <kbd>K</kbd> / <kbd>I</kbd>| Focus Window Down / Up
|<kbd>Super</kbd> + <kbd>Home</kbd>| Focus First Column
|<kbd>Super</kbd> + <kbd>End</kbd>| Focus Last Column

 // Move
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>←</kbd> / <kbd>→</kbd>| Move Column Left / Right
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd>| Move Window Up / Down
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>H</kbd> / <kbd>L</kbd>| Move Column Left / Right
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>J</kbd> / <kbd>K</kbd>| Move Window Down / Up
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>Home</kbd>| Move Column to First
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>End</kbd>| Move Column to Last
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>←</kbd> / <kbd>→</kbd>| Consume / Expel Window Left / Right
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd>| Move Window Up / Down
|<kbd>Super</kbd> + <kbd>G</kbd>| Consume Window Into Column
|<kbd>Super</kbd> + <kbd>H</kbd>| Expel Window From Column

 // Monitors
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>←</kbd> / <kbd>→</kbd> / <kbd>↑</kbd> / <kbd>↓</kbd>| Move Column to Monitor
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>H</kbd> / <kbd>J</kbd> / <kbd>K</kbd> / <kbd>L</kbd>| Move Column to Monitor

 // Workspace
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>PgDn</kbd> / <kbd>PgUp</kbd>| Focus Workspace Down / Up
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>PgDn</kbd> / <kbd>PgUp</kbd>| Move Column to Workspace Down / Up
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>U</kbd> / <kbd>I</kbd>| Move Column to Workspace Down / Up
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>PgDn</kbd> / <kbd>PgUp</kbd>| Move Workspace Down / Up
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>U</kbd> / <kbd>I</kbd>| Move Workspace Down / Up
|<kbd>Super</kbd> + <kbd>1-9</kbd>| Switch to Workspace 1-9
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>1-9</kbd>| Move Column to Workspace 1-9
|<kbd>Super</kbd> + <kbd>Wheel</kbd> ↑ / ↓| Switch Workspace
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>Wheel</kbd> ↑ / ↓| Move Column to Workspace
|<kbd>Super</kbd> + <kbd>Wheel</kbd> ← / →| Focus Column Right / Left
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>Wheel</kbd> ← / →| Move Column Right / Left

 // Windows & Layouts
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>Q</kbd>| Kill Focused Window
|<kbd>Super</kbd> + <kbd>F</kbd>| Maximize Column
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>F</kbd>| Fullscreen Window
|<kbd>F11</kbd>| Fullscreen Window
|<kbd>Super</kbd> + <kbd>M</kbd>| Maximize Window to Edges
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>F</kbd>| Expand Column to Available Width
|<kbd>Super</kbd> + <kbd>C</kbd>| Center Column
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>C</kbd>| Center Visible Columns
|<kbd>Super</kbd> + <kbd>R</kbd>| Cycle Preset Column Width
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>| Cycle Preset Column Width (Reverse)
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>R</kbd>| Reset Window Height
|<kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd>| Cycle Preset Window Height
|<kbd>Super</kbd> + <kbd>-</kbd>| Decrease Column Width (-10%)
|<kbd>Super</kbd> + <kbd>=</kbd>| Increase Column Width (+10%)
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>-</kbd>| Decrease Window Height (-10%)
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>=</kbd>| Increase Window Height (+10%)
|<kbd>Super</kbd> + <kbd>V</kbd>| Toggle Window Floating
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd>| Switch Focus Floating ↔ Tiling
|<kbd>Super</kbd> + <kbd>W</kbd>| Toggle Column Tabbed Display

// Screenshots
| Keys | Action |
|:-|:-|
|<kbd>Print</kbd>| Screenshot
|<kbd>Ctrl</kbd> + <kbd>Print</kbd>| Screenshot Screen
|<kbd>Alt</kbd> + <kbd>Print</kbd>| Screenshot Window

 // Audio & Brightness
| Keys | Action |
|:-|:-|
|<kbd>XF86AudioRaiseVolume</kbd>| Volume Up
|<kbd>XF86AudioLowerVolume</kbd>| Volume Down
|<kbd>XF86AudioMute</kbd>| Mute Volume
|<kbd>XF86MonBrightnessUp</kbd>| Brightness Up
|<kbd>XF86MonBrightnessDown</kbd>| Brightness Down
|<kbd>Super</kbd> + <kbd>Touchpad Scroll</kbd> ↑ / ↓| Volume Up / Down

 // Session
| Keys | Action |
|:-|:-|
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>E</kbd>| Quit Niri (muestra confirmación)
|<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Delete</kbd>| Quit Niri (muestra confirmación)
|<kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>| Power Off Monitors
|<kbd>Super</kbd> + <kbd>Escape</kbd>| Toggle Keyboard Shortcuts Inhibit


# Credits

Thanks to niri and noctalia dev
