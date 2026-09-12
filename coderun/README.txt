In competitive racing, engineering teams evaluate driver reaction times to ensure rapid responses to
starting signals and track hazards. This project is a standalone hardware device built to measure and
display this specific metric.

Hardware Interface
The physical setup consists of a straightforward user interface. It features a 4-digit 7-segment
display for numerical output, a single LED used as the visual stimulus, and two distinct push
buttons: one designated as the "Start" button and the other as the "Play" button.

The Test Sequence
The user initiates a test by pressing the "Start" button. During this phase, the digital display is kept
off to prevent visual distractions. The device waits for a random duration before turning on a single
LED, which serves as the visual trigger.

Measurement and Display
The instant the LED turns on, the user must press the "Play" button. Pressing this button
immediately turns the LED off and calculates the elapsed time. The user's exact reaction time in
milliseconds is then output to the digital display. The score remains visible until the user presses the
"Start" button again to reset the system and begin a new round