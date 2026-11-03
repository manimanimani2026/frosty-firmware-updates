# Frosty V2 releases

## 2.1.0 (2026-11-03)

Fixes from a full code review: a quiet hold now ends if the room sensor goes silent or Comfort hold is switched off; turning Follow Me off no longer turns it back on or changes Silent/Turbo; the louvre comes back after a hold ended by the remote; a hold pause and a schedule time missed during a restart are no longer lost; taps in Frosty no longer bounce back; the Matter panel refreshes; a failed install brings Install back; hold offsets show in °F; the Unit beeper setting shows again. 

## 2.0.10 (2026-11-01)

Check now shows "Checking… · about 20 s", finishes as soon as the bridge's check is done, and then says "Up to date · checked just now" (or which update is available). 

## 2.0.9 (2026-11-01)

Schedule times can also set the fan speed and louvre position (Keep leaves them as they are). The hold's running time stays visible when a reading is missed or right after a restart, instead of showing "…". 

## 2.0.8 (2026-11-01)

When Comfort hold is collapsed, its line shows "Holds in 4m" while waiting and "Holding for 12m" during a hold, and nothing when it's simply on

## 2.0.7 (2026-10-30)

Settings sections laid out like Controls; Logs has its own tab at the bottom; Check now waits for the answer

## 2.0.6 (2026-10-30)

Fixes Follow Me stopping after a Wi-Fi blip on bridges with Home apps on; the Settings dot only shows when something needs attention

## 2.0.5 (2026-10-29)

Settings is back as a tab under Schedule; the − and + buttons sit closer to the dial.

## 2.0.4 (2026-10-29)

The rescue firmware (what the bridge starts after a factory reset) can now be updated from Frosty: Settings → Software update. It downloads, checks the signature, then installs

## 2.0.3 (2026-10-28)

The rescue firmware is signed too and only installs signed releases (takes effect after a USB flash of this release's image).

## 2.0.2 (2026-10-28)

Updates are now signed: the bridge installs only firmware signed by Frosty.

## 2.0.1 (2026-10-27)

Frosty shows the louvre position after using the handheld remote again, and the unit's own Follow Me and display reports.

## 2.0.0 (2026-10-27)

Matter: Frosty in Apple Home, Google Home and Alexa (off until switched on in Settings → Home apps). Updates and installs pause Bluetooth to save memory. Frosty no longer flashes when switching views.

## 1.2.3 (2026-10-26)

A schedule entry during a Comfort hold now releases it right away if the room needs it, without waiting out Min Hold. Holds that start right after a restart are timed correctly.

## 1.2.2 (2026-10-25)

New: Settings screen behind the gear; the main page keeps the dial, Controls, Comfort hold and Schedule Settings: General, Connections and Software update open by default, Logs folded; an "Update available" line and a dot on the gear when an update is waiting. Controls: Gear is now "Power cap"; Active clean moved here and asks before starting. 

## 1.2.1 (2026-10-25)

Fix: Sweep (and the other louvre positions) now come back when the unit is switched on by the Schedule or from Frosty Comfort hold: "Holding in 7m" countdown while the room waits at the hold point; Hold at least moved under Wait before holding. Comfort hold: Resume at no longer shows the swing note. 

## 1.2.0 (2026-10-25)

New: Comfort hold at the setpoint, with adjustable band and wait

## 1.1.10 (2026-10-23)

New: Gear power cap (100/75/50%), Super heat preset, and Active clean in Settings

## 1.0.9 (2026-10-23)

Louvre and display changes no longer beep, and the display can be switched during quiet holds.

## 1.0.8 (2026-10-23)

Settings: choose Serial or IR for the unit's display and °C/°F.

## 1.0.7 (2026-10-23)

Settings: choose Serial or IR for the unit's display and °C/°F.

## 1.0.6 (2026-10-23)

Unit display button no longer flips back for a moment.

## 1.0.5 (2026-10-23)

Switching the unit's display and °C/°F no longer beeps (with the Unit beeper off).

## 1.0.4 (2026-10-23)

Logs: heating times now leave out time the unit was off.

## 1.0.3 (2026-10-22)

Open Frosty at frosty.local — no address to remember.

## 1.0.2 (2026-10-22)

Simpler Connections settings: the temperature sensor Frosty follows is now listed as "Temp sensor".

## 1.0.1 (2026-10-22)

Tidier firmware: no changes you'll notice. The heat pump connection shows as built in.

## 1.0.0 (2026-10-22)

First V2 release: Frosty over the unit's own serial port, no dongle needed.

