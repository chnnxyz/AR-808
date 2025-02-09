# AR-808
AR-808 (named after Roland's iconic TR-808 Rhythm Composer) is the project of building a fully fledged drum machine with a 16-step step sequencer with arduino.

The current design uses sampled sounds and runs on two Arduino Uno R3 boards, one serving as a clock and another one in charge of the sampling.

## Currently considered components
- **LCD** used to receive feedback on what settings are to be changed
- **KY-040 rotary encoder** for changing settings
- **7-segment display** to show beat number and honestly because it looks cute even if it is a pain to wire and code
- *4x push button** for setting selection (next/previous) and instrument selection
- **16x push button** set up as a matrix, to control the step sequencer
- **16x leds ofyour favorite color** as status indicators
- **3x potentiometera** for master volume, cutoff and velocity
- **Audio jack** because you need an output (can also be an 8 ohm speaker with resistors
- **LM386** for audio amplification
- **Storage module** USB or SD

