# Star Citizen Configuration

Control profiles and configuration notes for **Star Citizen**, focused on the **Thrustmaster T16000M** joystick, **Drake Cutlass Black** and **Greycat ROC**.

> **Status:** Work in progress. Bindings configured and tested in-game with Alpha 4.9.

---

## Hardware

| Component | Details |
| --- | --- |
| OS | Windows 11 Pro |
| CPU | Intel Core i7-14700K |
| RAM | 32 GB |
| GPU | MSI NVIDIA GeForce RTX 4070 SUPER |
| Joystick | Thrustmaster T16000M (right-handed, green) |

## Primary Vehicles

- **Drake Cutlass Black** — main ship
- **Greycat ROC** — ground mining vehicle

---

## Thrustmaster T16000M — Full Joystick Mapping

### Axes and Slider

| Control | Star Citizen Action | Notes |
| --- | --- | --- |
| X Axis | Yaw | Turn the ship left / right |
| Y Axis | Pitch | Move the ship nose up / down |
| Z Axis (twist grip) | Roll | Roll axis |
| Slider 1 | Throttle Increase | **Inverted**; deadzone set to **0.20**; slider down = 0 m/s, slider up = full advance |

### Left Base Buttons (accessible while holding the stick — priority controls)

| Button | Star Citizen Action | Notes |
| --- | --- | --- |
| Button 5 | Noise - Deploy | Countermeasure — electronic interference against missile lock |
| Button 6 (tap) | Cycle Master Mode (Short Press) | Change sub-mode (Flight / Quantum / Scan) |
| Button 6 (hold) | Cycle Master Mode (Long Press) | Toggle between **SCM** and **NAV** |
| Button 7 | Boost | Temporary thrust boost |
| Button 8 | Space Brake | Rapid deceleration / cancel inertia |
| Button 9 | Landing System | Landing gear toggle — **use two short taps** to deploy/retract |
| Button 10 (tap) | Decoy - Launch Burst | Launch flares / decoys (configure burst size with Alt+H) |
| Button 10 (hold) | Decoy - Set and Launch Burst | Increase burst count then release to launch |

### Right Base Buttons (scanning and utilities — can release stick to use)

| Button | Star Citizen Action | Notes |
| --- | --- | --- |
| Button 11 | Request Landing | ATC landing / takeoff request — no need to open mobiGlas |
| Button 12 | Increase Scanning Angle | Widen scan cone |
| Button 13 | Toggle Scanning Operator Mode | Enter / exit scan mode (equivalent to V) |
| Button 14 | Activate Ping (Hold & Release) | Hold and release to emit scanning ping |
| Button 15 | Decrease Scanning Angle | Narrow scan cone |
| Button 16 | Toggle Headlights | Ship headlights (equivalent to L) |

### Hat Switch (8-way)

| Direction | Star Citizen Action | Notes |
| --- | --- | --- |
| Hat (all directions) | Target cycling (default profile) | Cycle Lock: Hostiles / Attackers — kept from loaded profile |

> Hat directions are reserved for targeting. Adjust if a second hat or TWCS throttle is added.

### Keyboard Fallbacks (essential shortcuts to keep memorised)

| Key | Action |
| --- | --- |
| W / S | Throttle forward / backward |
| A / D | Strafe left / right |
| Space / Ctrl | Strafe up / down |
| Q / E | Roll left / right |
| Left Shift | Boost |
| X | Space Brake |
| B (hold) | Toggle SCM / NAV |
| N | Landing gear |
| V | Toggle Scanning Operator Mode / Ping |
| H | Launch Decoy (short press) |
| J | Deploy Noise |
| L | Toggle Headlights |
| R | Flight Ready |
| F | Interact |
| Y | Exit seat |
| Z | Freelook toggle |
| F4 | External camera |

---

## Axis Inversion and Deadzone Settings

| Setting | Value | Path |
| --- | --- | --- |
| Throttle Increase — Inversion | **Yes** | Options > Controls > Inversion Settings > Flight > Flight Movement |
| Deadzone Slider 1 | **0.20** | Options > Controls > Joystick Sensitivity Curves |
| Pitch inversion | No (default) | Adjust if pulling stick raises nose unexpectedly |

---

## Planned Files

```text
bindings/
└── thrustmaster-t16000m-cutlass-black.xml
```

The exported Star Citizen control profile (`.xml`) will be added after the full configuration has been completed and tested in-game.

To export: **Control Profiles → Export** inside Star Citizen keybindings menu.

---

## Notes

- Profile built and tested with **Star Citizen Alpha 4.9**.
- AsUpIO.sys (ASUS driver) must be stopped/disabled before launching the game or EAC will block it.
- The Cutlass Black may occasionally require reclaiming from ASOP terminal if controls become unresponsive — this is a known session state issue, not a bindings problem.
- Throttle Increase binding is used instead of Throttle Forward/Backward to give the full slider range to forward thrust only; reverse thrust uses **S** on keyboard.
