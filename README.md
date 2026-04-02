# LED CHASER PCB BADGE

The main goal of this project was to make a simple, small LED chaser using basic ICs. It has 10 SMD LEDs arranged in a way that makes a smooth running light effect. It is a small PCB that runs on a CR2032 coin cell battery.

---
<img width="820" height="560" alt="Screenshot From 2026-04-01 09-38-24" src="https://github.com/user-attachments/assets/2f5c27cb-4a53-41e1-af0c-4320ea5924ae" />
<img width="909" height="606" alt="Screenshot From 2026-04-01 09-38-38" src="https://github.com/user-attachments/assets/2d355a67-b4c6-4b3c-99e0-d84692e3d617" />

# Explain PCB
In short, this board is a simple LED chaser circuit that makes LEDs turn on one by one in a pattern, making an animation that flows. You can change the speed of the animation with a potentiometer. I made the design simple and clean by using fewer parts. This way, it doesn't look crowded and works well on low power. To save battery, a slide switch has been added to make it easy to turn the circuit on and off.

---
# Important Parts
The main timing controller is the TLC555 (CMOS version for low power), and the CD4017 is the decade counter that makes the LEDs light up one after the other. The LEDs are 0603 SMD type and have resistors to keep the current low. A potentiometer is what you use to change the speed of the LED pattern. Adding decoupling capacitors makes the circuit more stable. A CR2032 coin cell with a holder and a slide switch powers the circuit.

---
# Specs Power: 
- 3V CR2032 coin cell
- TLC555 Timer IC is the controller.
- CD4017 Decade Counter: Counter
- LEDs: 10 SMD LEDs in size 0603
- Control: 100k Potentiometer (for controlling speed)
- Switch: Slide Switch (ON/OFF)
- Low-Power Design
EasyEDA and JLCPCB can be used to design and make it.
