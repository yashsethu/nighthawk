# Nighthawk 
Nighthawk is a budget, beginner friendly core-xy printer inspired by the Voron 0.2!

## Planning
Desired specifications:
- 300 x 300 x 300 build volume
- Core-xy design, with linear rails for all axes and lead screws for z-axis screws
- Custom (not just configured) DragonBurner toolhead (Orbiter v2, Phaetus Dragonfly BMS, CRTouch)
- Klipper run on a Raspberry Pi 4B
- Enclosed in a polycarb shell (1/8 inch thick?)

## Phase 1: Toolhead
The Dragon Burner is a really popular toolhead, so a great start, but it doesn't support BLTouch or CRTouch and has some issues in supporting the Orbit v2.0 and Phaetus Dragonfly BMS. So, a redesign is neccesary.

- Added BLTouch support + CRTouch (whatever turns out to be cheaper)
<img width="683" alt="image" src="https://github.com/user-attachments/assets/c4ec1481-69ac-4911-b312-9d5f36b1f316" />

- Added Phaetus Dragonfly BMS support (the configuration from Dragon Burner was a little scuffed, had to redesign) + Orbiter v2.0 support
<img width="684" alt="image" src="https://github.com/user-attachments/assets/f7a08082-c974-4e8e-b4e1-f10df41b9544" />

## Phase 2: Gantry
For the gantry, I'm going to reuse the basic config and geometry of the Voron gantry, but change up spacing + mounts to fit my toolhead and remove some unneccesary stuff
