ML8511 UV sensor library for Arduino.

### Usage

```c++
#include "lib/ML8511.h"

String uvString;

#define SENSOR_PIN_UV_VREF A1
#define SENSOR_PIN_UV_VO A0

ML8511 sensorUV(SENSOR_PIN_UV_VO, SENSOR_PIN_UV_VREF);

void run() {
  uvString = String(sensorUV.readUVIntensity());
}

```

### Schematic

