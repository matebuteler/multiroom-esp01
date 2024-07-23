# ESP8266-Powered Multiroom solution [WIP]

ESP8266-powered multiroom audio, with ESP-NOW running under the hood. Each board outputs a single I2s digital audio signal (for use with i2s DACs).
Audio is streamed via ESP-NOW, MP3-codified. Based on https://github.com/espressif/esp8266_mp3_decoder.

# Unanswered questions
- By simply streaming the MP3 audio at the same time, is the audio going to be synced? Will it be noticeable?
- Will the use of Bluetooth-oriented (note Bluetooth isn't present in the ESP8266, nor is it present in this project) tools, like SBC, be necessary? If so, what would be the audio quality obtained from it?
- Should we stream different signals for each individual speaker? Something like 7.1 placement?
- What the hell is Dolby Atmos? 

# Image Gallery
Concept sketch
![Concept sketch](Sketches%20&%20Diagrams/First%20Sketch%20(Concept).png)

# Env variables
- IDF_PATH : See https://github.com/espressif/ESP8266_RTOS_SDK/blob/master/README.md
