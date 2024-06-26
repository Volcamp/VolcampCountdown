# Volcamp Countdown

An electronic countdown to timekeep our Volcamp's talk

![Volcamp Countdown](/img/Countdown.png)

# Development

Based on Arduino

You need :
- an Arduino Nano
- 1 TM1637 7 Segment 4 bits anonde
- 5 press buttons
- 5 10 kΩ resistors (Brown - Black - Orange + Gold)
- 5 1 kΩ resitors (Brown - Black - Brown + Gold)
- 3 220 Ω resistors (Red - Red - Brown + Gold)
- 5 10nF capacitors
- 1 green LED
- 1 orange LED
- 1 red LED
- An USB sector adaptator

![Volcamp Countdown](/img/VolcampCountdown.png)


# Code

Code is available on [arduino code folder](/arduino%20code/volcampcountdown.ino).


# Gerber

For minimized place in the box, 2 PCB have been designed.

First for all 3 LEDs

![LED](/img/gerberLed.png)

[Gerber file for LED](/gerber%20files//ledVolcampCountdown.zip)

Another one for the 5 buttons

![LED](/img/gerberBtn.png)

[Gerber file for LED](/gerber%20files/btnVolcampCountdown.zip)


# Usage

The start button launches the countdown (45 minutes by default) with green LED lights up.
- When 66% was done, the orange LED lights up (15 min remaining by default).
- When 11% was done, the red LED lights up (5 min remaining by default).
- When countdon was finished, the countdown and the red LED flash.

Reset buttom rollbacks countdown to origin value.

Position, up and down buttons can be used to change started value.

