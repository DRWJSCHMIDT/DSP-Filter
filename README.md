# DSP-Filter
This is a Variable SDP filter for Ham Radio in the audio stage.
It allows 4 filters: CW, SSB, RTTY, and NOTCH or variable widths up to 3000 hz.
There are two modes. Mode 1: Enter ceter frequency and Bandwidth, Mode 2: Enter upper and lower frequency.
This filter uses a Arduino Teensy 3.2, the PRCJ.com Arduino Audio shield, two encoders with push buttons for selecting 
frequency and input mode, an additional push button for scrolling through the 4 filters.  It also uses a color SPI
display for showing the filter visually.  Schematics of the connections and the code are contained in this github post.
I will post a Youtube video of the filter in operation shortly.  Dr. Bill K9HZ.
