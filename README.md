# adafruit_tcs34725
Adafruit's TCS34725 Library angepasst für Adafruit's Gemma Board. Statt der Wire.h library wird die TinyWireM.h I2C library für Gemma und Trinket Boards verwendet.
Die angepassten Stellen sind durch Kommentare gekennzeichnet.

## Verwendung mit Arduino-IDE

Die .cpp- und .h-Dateien werden im selben Ordner wie die .ino-Sketch gespeichert. Anschließend wird die Bibliothek mit 
```#include "Adafruit_TCS34725.h"``` 
in die Sketch eingebunden.

## Gemma I2C

Bei Gemma ist Pad #0 Data und Pad #2 Clock.
