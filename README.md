🎮 Controls in Your Script
Movement Keys

The script lets you move in 24 directions (every 15° on a circle), instead of just the usual 8-way (WASD + diagonals).

W → Up (north)

S → Down (south)

A → Left (west)

D → Right (east)

👉 You can combine keys (like W+A for up-left, or S+D for down-right).
The script automatically normalizes the vector so you move at the correct angle.

Tilt Modifiers

This is what gives you the extra in-between angles (24 total).

C → Tilt clockwise (+)

V → Tilt counter-clockwise (–)

How it works:

If you just hold a direction key (like A left), you’ll get the standard 8-way angle.

If you hold C or V while pressing a direction, it tilts that direction by ±20°.

If you press both C and V in sequence, you can get double tilt (±40°).

Example:

A → Left (180°)

A + C → Tilted left (160°)

A + V → Tilted left (200°)

A + C then V → Double tilt left (140° or 220°, depending on order)

This is how you go from 8 base angles → 24 total movement directions.

HUD (On-Screen Display)

A small transparent window appears bottom-left of your screen.

It shows:

A circle gate with 24 colored ridges (each ridge = one possible movement angle).

A white dot in the center (neutral stick).

A red line showing your current stick direction.

Other Controls

ESC → Quit the script.

When quitting, the joystick is reset so it doesn’t keep drifting.

✅ In short:

Use WASD for base movement.

Combine them for diagonals.

Add C or V to tilt into extra angles.

HUD shows you which way you’re pointing.
