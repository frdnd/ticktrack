# ticktrack - Awesome electromechanical projects

## Sequencer
 * [Teensy midi euclidean sequencer (arduino IDE)](https://www.youtube.com/watch?v=aqOsPZUo860)
   * frdnd will build a variant based on 3x 24-led-rings
     * interface will be 3x3 sliders for step-length, num-steps, offset
     * based either on teensy playing digital samples or arduino activating solenoids

## Solenoid based instruments
 * [Solenoid acoustic drum machine](https://www.youtube.com/watch?v=m6YOYpnz9Lw)
 * [MIDI Solenoid Drummer #crickit #feather @adafruit #adafruit](https://www.youtube.com/watch?v=Lcz0BvNOc4c)
 * frdnd will build a variant of the above based on 5v and 12v solenoids
   * either combining the solenoids with a euclidean sequencer
   * or replaying a mp3 and syncing the stems of kick/drums/highhat to the solenoids (will be difficult to get the stems correctly)
   * midi maybe later

## Music cocreation
 * [piano genie blog post](https://magenta.tensorflow.org/pianogenie)
   * [github](https://github.com/magenta/magenta/tree/main/magenta/models/piano_genie), tensorflow
   * [pytorch port and tutorial by pg author](https://pythonrepo.com/repo/chrisdonahue-music-cocreation-tutorial-python-deep-learning)

## Talks
 * [Motors, Magnets and Motion/Ableton](https://www.youtube.com/watch?v=hJHwhb99Bzo)
   * the first two artists are quite interesting
 * frdnd plans to build a variant above
   * based on teensy and piezo microphones, how to design the amp-circuit?
    
## Resources

### Electronics
 * [Piezo contact microphone hi-Z amplifier low noise version](https://www.richardmudhar.com/blog/piezo-contact-microphone-hi-z-amplifier-low-noise-version/)
 * [Teensy multiple Analog Input project](https://forum.pjrc.com/threads/61764-Help-for-multiple-Analog-Input-project)
 * [Multiple rotary encoder and MCP23017 ](https://arduino.stackexchange.com/questions/52909/reading-several-rotary-encoders)
 * [I2C port exapander](https://www.mikrocontroller.net/articles/Port-Expander_PCF8574)

### Music source separation
 * [Bytedances music source separation tool (GPU based)](https://github.com/bytedance/music_source_separation)
   * not tested yet

### Available Hardware
 * frdnd
   *  arduino*, esp8266, esp32, coral devboard, (jetson nano)
  
