# Star Citizen T.16000M Config

A right-handed Thrustmaster T.16000M starter profile for Star Citizen.

## Included Profile

| File | Description |
|---|---|
| [`mappings/layout_2026_T16000M_exported.xml`](mappings/layout_2026_T16000M_exported.xml) | Exported right-handed T.16000M control profile |

## Quick Reference

```text
THRUSTMASTER T.16000M — RIGHT-HANDED QUICK REFERENCE
====================================================

AXES
-----
X Axis                     -> Yaw
Y Axis                     -> Pitch
Stick Twist / Z Axis       -> Roll
Slider 1                   -> Throttle Increase
                              Inverted
                              Deadzone 0.20
                              Down / toward player = 0 throttle
                              Up / toward stick   = more throttle

GRIP
----
B1 Trigger                 -> Fire Weapon Group 1
                              / Launch Missiles in Missile Operator Mode
B2 Lower centre            -> Fire Weapon Group 2
                              / Cycle Next Missile Type in MOM
B3 Left                    -> Cycle Lock — In View — Under Reticle
B4 Right                   -> Missile Operator Mode

HAT — TARGETING
---------------
Up                         -> In View Forward + Under Reticle
Down (single press)        -> Hostiles — Reset to Closest
Down (double press)        -> Attackers — Reset to Closest
Left                       -> Hostiles Back (-)
Right                      -> Hostiles Forward (+)

LEFT BASE
---------
B5                         -> Noise — Deploy
B6 Tap                     -> Cycle Master Mode — Short Press
B6 Hold                    -> Cycle Master Mode — Long Press (SCM / NAV)
B7                         -> Boost
B8                         -> Space Brake
B9                         -> Landing System
B10                        -> Decoy
                              Tap  -> Launch Burst
                              Hold -> Set & Launch Burst

RIGHT BASE
----------
B11                        -> Request Landing
B12                        -> Increase Scanning Angle
B13                        -> Toggle Scanning Operator Mode
B14                        -> Activate Ping — Hold & Release
B15                        -> Decrease Scanning Angle
B16                        -> Toggle Headlights

BASE LAYOUT
-----------

                    FRONT / STICK
                         ^

        LEFT BASE                         RIGHT BASE

   +------+------+------+            +------+------+------+
   |  B5  |  B6  |  B7  |            | B13  | B12  | B11  |
   |Noise |Modes |Boost |            | Scan | Scan+| ATC  |
   +------+------+------+            +------+------+------+
   | B10  |  B9  |  B8  |            | B14  | B15  | B16  |
   |Decoy | Gear |Brake |            | Ping | Scan-|Lights|
   +------+------+------+            +------+------+------+

                    YOU / REAR
```

## Bindings

### Axes

| Control | Assignment |
|---|---|
| X Axis | Yaw |
| Y Axis | Pitch |
| Stick Twist / Z Axis | Roll |
| Slider 1 | Throttle Increase; inverted; deadzone 0.20 |

The throttle slider is set so that moving it down, toward the player, gives zero throttle; moving it up, toward the stick, increases throttle.

### Grip

| Button | Assignment |
|---|---|
| B1 — Trigger | Fire Weapon Group 1; Launch Missiles in Missile Operator Mode |
| B2 — Lower centre | Fire Weapon Group 2; Cycle Next Missile Type in Missile Operator Mode |
| B3 — Left | Cycle Lock — In View — Under Reticle |
| B4 — Right | Missile Operator Mode |

### Hat — Targeting

| Direction | Assignment |
|---|---|
| Up | In View Forward + Under Reticle |
| Down — one press | Hostiles — Reset to Closest |
| Down — double press | Attackers — Reset to Closest |
| Left | Hostiles Back (-) |
| Right | Hostiles Forward (+) |

### Left Base

| Button | Assignment |
|---|---|
| B5 | Noise — Deploy |
| B6 — Tap | Cycle Master Mode — Short Press |
| B6 — Hold | Cycle Master Mode — Long Press (SCM / NAV) |
| B7 | Boost |
| B8 | Space Brake |
| B9 | Landing System |
| B10 | Decoy — Tap: Launch Burst; Hold: Set & Launch Burst |

### Right Base

| Button | Assignment |
|---|---|
| B11 | Request Landing |
| B12 | Increase Scanning Angle |
| B13 | Toggle Scanning Operator Mode |
| B14 | Activate Ping — Hold & Release |
| B15 | Decrease Scanning Angle |
| B16 | Toggle Headlights |

## Installation

1. Download or clone this repository.
2. Copy `layout_2026_T16000M_exported.xml` to:

   ```text
   StarCitizen\LIVE\USER\Client\0\Controls\Mappings\
   ```

3. Start Star Citizen.
4. Open:

   ```text
   Options > Keybindings > Advanced Controls Customization > Control Profiles
   ```

5. Select and load the profile.

## License

This project is licensed under the GNU General Public License v3.0 or later. See [`LICENSE.txt`](LICENSE.txt) for the complete license text.