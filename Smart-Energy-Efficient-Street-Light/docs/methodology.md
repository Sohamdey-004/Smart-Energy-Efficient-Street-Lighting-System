## Methodology

The proposed system follows a sensor-based adaptive lighting approach.

### 1. Day/Night Detection
An LDR connected in a voltage divider configuration is used to sense ambient light intensity.
When sufficient daylight is detected, the street light remains OFF to prevent unnecessary energy usage.

### 2. Threshold Adjustment
A potentiometer allows manual calibration of the day–night threshold, enabling adaptability to different environmental conditions.

### 3. Motion Detection
A PIR sensor detects moving vehicles or pedestrians.
When motion is detected during nighttime, the street light switches to full brightness.

### 4. Active Presence Detection
An ultrasonic distance sensor is used as an active sensing device.
Unlike PIR sensors, it continuously measures distance and detects stationary vehicles.
This ensures that the street light does not turn OFF when a vehicle is stopped.

### 5. Control and Output
An Arduino Uno processes sensor inputs and controls the street light using PWM.
A 16×2 LCD displays the system status, and a buzzer with status LEDs provides visual and audible indications.
