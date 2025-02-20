[![CLICK HERE TO SEE A VIDEO DEMO](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/6.jpg?raw=true)](https://www.youtube.com/watch?v=4ALef1g3c2c)

--------------------------------------------------------

# SENSORY BRIDGE is **DIFFERENT**

**This isn't the usual "sound-reactive LEDs" you've seen for years.**

--------------------------------------------------------

**Sensory Bridge is built from the ground up as an open, powerful bridge between sight and sound.** With a show that's reactive to notation, vibrato and more, it produces very unique and pleasant-to-look-at light shows which synchronize to your music without any visible latency. (A built-in MEMS microphone constantly studies what it hears using the [Fast Fourier Transform](https://en.wikipedia.org/wiki/Fast_Fourier_transform), at more than 60 FPS!)

It has to be seen to be believed, *which the video demos below can help with:*

[![STREET BY STREET](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/street_by_street.jpg?raw=true)](https://www.youtube.com/watch?v=trJYa3U8nCU)
[![TRUSTFUL_HANDS](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/trustful_hands.jpg?raw=true)](https://www.youtube.com/watch?v=0EICjxSjveM)
[![ON THE RUN](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/on_the_run.jpg?raw=true)](https://www.youtube.com/watch?v=RWJjWcHplGc)
[![GET YOU](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/get_you.jpg?raw=true)](https://www.youtube.com/watch?v=lk1oRJr7TGo)
[![PLANTASIA](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/plantasia.jpg?raw=true)](https://www.youtube.com/watch?v=Hz8LxBKy5SI)
[![NINA](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/nina.jpg?raw=true)](https://www.youtube.com/watch?v=OXu3x7s3SVE)

# 

--------------------------------------------------------

![SENSORY BRIDGE IS SIMPLE](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/2.jpg?raw=true)

--------------------------------------------------------
# SENSORY BRIDGE is **SIMPLE**
--------------------------------------------------------

**Easy controls provide quick access to changing the brightness, audio gain, and smoothing of the display!**

--------------------------------------------------------
## **KNOBS**
--------------------------------------------------------

### PHOTONS KNOB

Too bright? *Dim down the show* with the **PHOTONS** knob. The FastLED code in the firmware will use dithering to keep producing color nicely at lower brightness levels.

### BOOST KNOB

Need to keep the music down? Turn up the **BOOST** knob, and Sensory Bridge will *adjust its sensitivity to account for quieter or more distant music sources.*

### MOOD KNOB

This knob is special. **MOOD** controls *how quickly your LEDs will react to changes in pitch and volume!* A low "mood" will be very soft and gradual, only showing things like the underlying chord progression of a song, whereas a *high* "mood" will be extremely reactive, and can be a little too flashy for some people's liking. Luckily, you can blend the value to anywhere between those two extremes whenever you want to find what look you prefer!

# 

![KNOBS](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/16.jpg?raw=true)

--------------------------------------------------------
## **BUTTONS**
--------------------------------------------------------

### NOISE BUTTON

Running the A/C? Is the washing machine suddenly on the rinse cycle? Don't worry, just pause the music for a moment and press the **NOISE BUTTON** to run a 3-second calibration to automagically have noisy background ambience removed from your light show.

### MODE BUTTON

Sensory Bridge currently has 6 built-in light show modes that you can cycle through:

#### "Duet Mode"

This is the default show seen in the videos, based on FFT data. Color slowly cycles when silent, and is temporarily cycled faster when all FFT bins trend upward, such as a snare drum hit after a moment of silence.

#### "Duet Mode" (Mirrored)

Same as above, except the image is mirrored out from the middle of the LED strip! This is especially nice looking on horizontally-mounted LED strips.

#### "Duet Mode" (Inverted)

This is the default show seen in the videos, based on FFT data, *however*, the brightness has been inverted. (Silence = all LEDs on) This mode can reduce perceived flashing in a room with no other light sources.

#### "Duet Mode" (Inverted, Mirrored)

Same as above, except the image is mirrored out from the middle of the LED strip!

#### "Bloom Mode"

This mode differs from the others. The intensity of the audio is shown in the center of the LED strip, and is diffused outward as time passes, similar to a "waterfall" display. Color is calculated from the pitches detected in FFT.

#### "VU Meter Mode"

It's a classic! A bouncing bar graph represents the current loudness of the music.

### ***MORE MODES WILL BE RELEASED IN FUTURE FIRMWARE UPDATES!***

# 

![SWEET SPOT](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/3.jpg?raw=true)

--------------------------------------------------------
## **SWEET SPOT**
--------------------------------------------------------

At the front of the base unit are three LEDs, which indicate if you've set your Boost knob correctly for the music volume and distance! Tune the Boost until the center (green) LED is lit up during an average loudness level of your music. Once set, it shouldn't need to be changed between songs!

# 

![SENSORY BRIDGE IS FLEXIBLE](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/12.jpg?raw=true)

--------------------------------------------------------
# SENSORY BRIDGE is **FLEXIBLE**
--------------------------------------------------------

While compatible with any WS2812B-based LED strip, (just use the screw terminals at the back!) there's also the option of using the **"Mini Mast"**, a dense strip of 128 1.5mm RGB LEDs on a 260mm long PCB! It just plugs directly into the Sensory Bridge accessory port, making for a very portable solution!

# 

![SENSORY BRIDGE IS OPEN](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/1.jpg?raw=true)

--------------------------------------------------------
# SENSORY BRIDGE is **OPEN**
--------------------------------------------------------

Powered by an ESP32-S2, Sensory Bridge can be easily reprogrammed for any purpose you'd like! The firmware is [open source](https://github.com/connornishijima/SensoryBridge) under the [MIT License](https://github.com/connornishijima/SensoryBridge/blob/main/LICENSE), so modifying it for your own purposes is quick and easy with the Arduino IDE. You can even download the [board](https://github.com/connornishijima/SensoryBridge/tree/main/extras/OSHW/PCB) and [case STLs](https://github.com/connornishijima/SensoryBridge/tree/main/extras/OSHW/3D%20Printing) to build one yourself!

![OSHW FACTS](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/oshw_facts.svg?raw=true)

# 

![WHATS INCLUDED](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/8.jpg?raw=true)

--------------------------------------------------------
# WHAT'S **INCLUDED:**
--------------------------------------------------------

For $50, you'll receive a ***fully assembled Sensory Bridge***, with the latest firmware already installed. For $25 extra, you can have a **Mini Mast** (128 micro-LED PCB, seen above) sent as well, with an accompanying brace that provides rigidity. (It just plugs right into the accessory port on top of Sensory Bridge!)

--------------------------------------------------------
# EXTRAS YOU **MIGHT NEED:**
--------------------------------------------------------

### **PAY CLOSE ATTENTION TO THIS SECTION!**

To save on redundant materials you might already own, **your Sensory Bridge does *not* come with the following items:**

- **WS2812B LED Strip** - "144-LEDs per meter" variants are recommended, you can cut the 16 excess LEDs off of the end of the strip. ([AMAZON LINK](https://www.amazon.com/WS2812B-Individual-Addressable-144Pixels-Non-Waterproof/dp/B09PBHJG6G/ref=sr_1_5?crid=3KPXUN3NEV06Q&keywords=ws2812b%2Bled%2Bstrip%2B144&qid=1662389723&sprefix=ws2812b%2Bled%2Bstrip%2B144%2Caps%2C128&sr=8-5&th=1))
- **USB-C Cable** ([AMAZON LINK](https://www.amazon.com/JSAUX-Charger-Braided-Compatible-Samsung/dp/B076FPGWNZ/ref=sr_1_9?crid=2YG0J3B874G73&keywords=usb-c+cable&qid=1662388265&sprefix=usb-c+cable%2Caps%2C137&sr=8-9))
- **5V, 2A USB Power Adapter** ([AMAZON LINK](https://www.amazon.com/Certified-Charger-FONKEN-Universal-Compatible/dp/B07DF782WQ/ref=sr_1_4?crid=1WJDP9XHVR3QC&keywords=2a+usb+adapter&qid=1662388344&sprefix=2a+usb+adapter%2Caps%2C131&sr=8-4))
- **Wire Stripper** - If you'd like to use your Sensory Bridge with your own LED strip, you'll either need a wire stripper or strong teeth to get it hooked up neatly! These clamp-style strippers make that process a breeze: ([AMAZON LINK](https://www.amazon.com/Self-Adjusting-Stripper-Klein-Tools-11061/dp/B00CXKOEQ6/ref=sr_1_5?crid=UIAP8SCLPER3&keywords=wire+strippers&qid=1662390513&sprefix=wire+strippers%2Caps%2C141&sr=8-5))

# 

![FUTURE PLANS](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/0.jpg?raw=true)

--------------------------------------------------------
# FUTURE **PLANS**
--------------------------------------------------------

Sensory Bridge is going to undergo some upgrades in the following months! You'll be able to easily update to the latest firmware using the Arduino IDE.

**Currently planned features are:**

## Manual Color Selection

Currently, Sensory Bridge chooses colors for you based on musical data, but an upcoming firmware update will allow you to hold the MODE button and adjust the knobs to manually set hue, saturation, and the color shifting at the edges of notes.

## WiFi Features

Planned for Q1 2023 is a mobile / web app for iOS and Android that will allow users to remotely tweak their display from the couch! This will provide a way to adjust dozens of settings that otherwise couldn't be accessed through just two physical buttons.

## Syncing Multiple Units Together

A feature also based in WiFi capabilities, this will allow you to have two Sensory Bridge units that each study their own audio (think: placing them on top of stereo speakers), but synchronize color and all other settings between them in realtime, via an ad-hoc network between units.

## More Lightshow Modes

Currently in development is a system of determining and synchronizing to the BPM of the playing music. Combining this data with the FFT could mean deducing time signatures, along with musical keys and chord progressions - just another avenue for providing an immersive show!

![AUX PORT](https://github.com/connornishijima/SensoryBridge/blob/main/extras/img/15.jpg?raw=true)

## Support For "DotStar" LEDs

The screw terminal and accessory port also include a "CLOCK" line required for APA102 "DotStar"-type LEDs. By default, the firmware does not use the CLK line, and this ability must be enabled by modifying [system.h](https://github.com/connornishijima/SensoryBridge/blob/main/system.h) in the firmware.

In the near future, holding the "MODE" button down while plugging in Sensory Bridge will switch between LED types.

## Support For Line-In Audio

The accessory port exposes GPIO 17/18 of the ESP32-S2, which are analog inputs. In the future, a PCB can be made to allow Sensory Bridge to use hardwired, passthrough audio via two 3.5mm jacks. This concept does not interfere with the Mini Mast, and the two accessories will be stackable with a modified brace.

![GETTING STARTED GUIDE](https://sensorybridge.rocks/tutorial/img/mast_insert.png)

--------------------------------------------------------
# **GETTING STARTED**
--------------------------------------------------------

The **[GETTING STARTED](https://sensorybridge.rocks/tutorial/) GUIDE** will walk you through the quick-and-easy setup process!

--------------------------------------------------------
# **DISCLAIMER**
--------------------------------------------------------

## **Those with [Photosensitive Epilepsy](https://en.wikipedia.org/wiki/Photosensitive_epilepsy) (PSE) should NOT purchase, operate, or otherwise view Sensory Bridge under any condition.**

## **The seller assumes no legal liability for injury caused to persons with PSE that have ignored this warning.**
