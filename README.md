#Digital Processors Practices – Master Repository

Welcome to the **Digital Processors Practices Master Repository**! This repository serves as a central hub for all the submodules containing individual practice exercises for the Digital Processors course using the ESP32.

Each submodule contains a specific practice with detailed **English** and **Spanish** versions, including code explanations, diagrams, and resources.

---

## Table of Contents

### Practice 1: LED Blink with ESP32

- **Description:** Learn how to blink an LED on the ESP32 using **PlatformIO**. This practice helps understand the `setup()` and `loop()` functions, and basic digital I/O.
- **Submodule:** [Practice 1](P1-LED-Blink-ESP32)
- **Materials:**
  - ESP32
  - LED
  - 470-ohm resistor
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P1-LED-Blink-ESP32/assets/practica1_video.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **Arduino digitalWrite Reference:** [Arduino digitalWrite](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalwrite/)  
  - **Arduino pinMode Reference:** [Arduino pinMode](https://docs.arduino.cc/language-reference/en/functions/digital-io/pinMode/)  
  - **ESP32 GPIO Guide:** [ESP32 GPIO Reference](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)  


### Practice 2-A: Button Interrupt on ESP32

- **Description:** Learn how to use **Interrupt Service Routines (ISR)** on the ESP32. This practice demonstrates triggering an interrupt via a push button and counting the number of presses.
- **Submodule:** [Practice 2-A](P2A-Button-Interrupt-ESP32)
- **Materials:**
  - ESP32
  - Push Button
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P2A-Button-Interrupt-ESP32/assets/practica2avideo.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **Arduino attachInterrupt Reference:** [Arduino attachInterrupt](https://docs.arduino.cc/language-reference/en/functions/external-interrupts/attachInterrupt/)  
  - **ESP32 Interrupts Documentation:** [ESP32 Interrupts](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/system/intr_alloc.html)  


### Practice 2-B: Timer Interrupt on ESP32

- **Description:** Learn how to use **timer interrupts** on the ESP32. Timer interrupts allow code to run at precise intervals, independently of the main loop.
- **Submodule:** [Practice 2-B](P2B-Timer-Interrupt-ESP32)
- **Materials:**
  - ESP32
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P2B-Timer-Interrupt-ESP32/assets/practica2Bvideo.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP32 Timer API Documentation:** [ESP32 Timers](https://docs.espressif.com/projects/esp-idf/en/v4.3/esp32/api-reference/peripherals/timer.html)  
  - **Arduino Timer Interrupt Reference:** [Arduino TimerInterrupt](https://docs.arduino.cc/libraries/timerinterrupt/)  


### Practice 3-A: ESP32 Wi-Fi Web Server

- **Description:** Learn how to create a simple **web page** using the Wi-Fi peripheral of the ESP32. The ESP32 acts as a **web server** and serves an HTML page accessible from a browser.
- **Submodule:** [Practice 3-A](P3A-WiFi-WebServer-ESP32)
- **Materials:**
  - ESP32
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P3A-WiFi-WebServer-ESP32/assets/practica3A.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP32 Wi-Fi Library Documentation:** [ESP32 WiFi](https://github.com/espressif/arduino-esp32/tree/master/libraries/WiFi)  


### Practice 3-B: ESP32 Bluetooth Serial

- **Description:** Learn how to use the **Bluetooth peripheral** of the ESP32 to communicate with a mobile device. The ESP32 acts as a **Bluetooth Serial device**, sending and receiving data between the board and a paired device.
- **Submodule:** [Practice 3-B](P3B-Bluetooth-Serial-ESP32)
- **Materials:**
  - ESP32
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P3B-Bluetooth-Serial-ESP32/assets/practica3Bvideo.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP32 Bluetooth Serial Documentation:** [ESP32 BluetoothSerial](https://github.com/espressif/arduino-esp32/tree/master/libraries/BluetoothSerial)  
  - **Arduino Bluetooth Reference:** [Arduino Bluetooth](https://docs.arduino.cc/libraries/bluetoothserial/)  
  - **ESP32 Bluetooth Guide:** [ESP32 Bluetooth Tutorial](https://randomnerdtutorials.com/esp32-bluetooth-classic-arduino-ide/)  


### Practice 3 Extra: ESP32 Web Server with 2 LEDs

- **Description:** Learn how to use the **Wi-Fi peripheral** of the ESP32 to create a web server that controls **two LEDs**. Each LED has its own ON/OFF button on the web page. Clicking the button toggles the corresponding LED.
- **Submodule:** [Practice 3 Extra](P3E-WebServer-2LEDs-ESP32)
- **Materials:**
  - ESP32
  - 2 LEDs
  - 2 resistors (470Ω – 1kΩ)
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P3E-WebServer-2LEDs-ESP32/assets/practica3extra.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP32 Wi-Fi Documentation:** [ESP32 Wi-Fi API](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/network/esp_wifi.html)  
  - **Arduino Wi-Fi Library Reference:** [Arduino WiFi](https://www.arduino.cc/en/Reference/WiFi)  


### Practice 4-A: Multi-Core LED Tasks on ESP32

- **Description:** Learn how to create tasks that run on multiple cores of the ESP32 using FreeRTOS. This practice demonstrates task scheduling and concurrent execution by blinking two LEDs independently on separate cores.
- **Submodule:** [Practice 4-A](P4A-Multicore-Tasks-ESP32)
- **Materials:**
  - ESP32
  - 2 LEDs
  - 2 resistors (470Ω)
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P4A-Multicore-Tasks-ESP32/assets/practica4ej1.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **FreeRTOS Reference (ESP32 / ESP-IDF):** [FreeRTOS Documentation](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/system/freertos.html)  


### Practice 4-B: LED Task Synchronization on ESP32

- **Description:** Learn how two tasks can synchronize on the ESP32 to alternately turn a single LED on and off, demonstrating task coordination in FreeRTOS.
- **Submodule:** [Practice 4-B](P4B-LED-Task-Sync-ESP32)
- **Materials:**
  - ESP32
  - 1 LED
  - 1 resistor (470Ω)
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P4B-LED-Task-Sync-ESP32/assets/practica4ej2.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **FreeRTOS Reference (ESP32 / ESP-IDF):** [FreeRTOS Documentation](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/system/freertos.html)  

### Practice 5: I2C OLED Display with HTU21D Sensor on ESP32

- **Description:** Learn how to use the **I2C bus** on the ESP32 to interface an OLED display and a HTU21D humidity & temperature sensor. The OLED shows **current humidity (%)** and **temperature (ºC)** in real time.
- **Submodule:** [Practice 5](P5-I2C-Temp-Humidity-ESP32)
- **Materials:**
  - ESP32
  - OLED Display (I2C)
  - KYYKA HTU21D I2C - Humidity & Temperature Sensor
- **Languages:** English / Spanish
- **Resources:**  
  - **Video demonstration:** [Watch video](P5-I2C-Temp-Humidity-ESP32/assets/practica5.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **OLED Library GitHub:** [ESP8266 and ESP32 OLED driver for SSD1306 displays](https://github.com/ThingPulse/esp8266-oled-ssd1306)  
  - **Temperature Sensor Library:** [SparkFun HTU21D](https://github.com/sparkfun/SparkFun_HTU21D_Breakout_Arduino_Library)  
  - **PlatformIO Dependencies (in `platformio.ini`):**  
    ```ini
    lib_deps = 
      sparkfun/SparkFun HTU21D Humidity and Temperature Sensor Breakout@^1.1.3
      thingpulse/ESP8266 and ESP32 OLED driver for SSD1306 displays@^4.2.1
    ```


### Practice 6: RFID Reader with ESP32

- **Description:** Learn how to use an RC522 RFID reader with the ESP32 via SPI. Read RFID tags (cards and key fobs) and display their IDs in decimal and hexadecimal on the Serial Monitor.
- **Submodule:** [Practice 6](P6-RFID-Reader-ESP32)
- **Materials:**
  - ESP32
  - RC522 RFID Reader Module
  - RFID Card
  - RFID Key Fob
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P6-RFID-Reader-ESP32/assets/practica6.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **MFRC522 Library:** [GitHub MFRC522](https://github.com/miguelbalboa/rfid)  
  - **Arduino SPI Reference:** [Arduino SPI](https://docs.arduino.cc/language-reference/en/functions/communication/SPI/)  
- **PlatformIO Dependencies (`platformio.ini`):**
  ```ini
  lib_deps = miguelbalboa/MFRC522@^1.4.10
  ```

### Practice 7-A: I2S Audio with ESP32

- **Description:** Learn to use the I2S bus on the ESP32 to play audio through an amplifier and speaker. The ESP32 acts as I2S master, sending digital audio to the amplifier with DAC functionality.
- **Submodule:** [Practice 7-A](P7A-I2S-Audio-ESP32)
- **Materials:**
  - ESP32 
  - Audio Amplifier with I2S DAC (unfiltered)
  - Speaker
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P7A-I2S-Audio-ESP32/assets/Practica7ej1.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP8266Audio Library:** [GitHub ESP8266Audio](https://github.com/earlephilhower/ESP8266Audio)  
  - **I2S Documentation:** [I2S Wikipedia](https://en.wikipedia.org/wiki/I%C2%B2S)
- **PlatformIO Dependencies (`platformio.ini`):**
  ```ini
  lib_deps = earlephilhower/ESP8266Audio@^1.9.6
  ````

### Practice 7-B: WiFi Audio Streaming with ESP32

- **Description:** Extend I2S audio playback by streaming online radio via WiFi. The ESP32 connects to a radio host and outputs audio through an I2S DAC amplifier to a speaker.
- **Submodule:** [Practice 7-B](P7B-AudioWiFi-ESP32)
- **Materials:**
  - ESP32
  - Audio Amplifier with I2S DAC (unfiltered)
  - SPI SD Card Reader
  - Speaker
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P7B-AudioWiFi-ESP32/assets/practica7ej2.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **ESP32 Audio I2S Library:** [GitHub ESP32-audioI2S](https://github.com/schreibfaul1/ESP32-audioI2S)  
  - **I2S Documentation:** [I2S Wikipedia](https://en.wikipedia.org/wiki/I%C2%B2S)
- **PlatformIO Dependencies (`platformio.ini`):**
  ```ini
  lib_deps = schreibfaul1/ESP32-audioI2S@^1.2.0
  ```

### Practice 8: Serial Communication with ESP32

- **Description:** Explore serial communication on ESP32, including bidirectional communication between Serial and Serial2 ports.
- **Submodule:** [Practice 8](P8-SerialCommunication-ESP32)
- **Materials:**
  - ESP32
- **Languages:** English / Spanish
- **Resources:**  
  - **Video Demonstration in Spanish:** [Watch video](P8-SerialCommunication-ESP32/assets/practica8.mp4)  
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)  
  - **Arduino Serial documentation:** [Arduino Serial](https://www.arduino.cc/reference/en/language/functions/communication/serial/)


# Final Project: Music Through Temperature

- **Description:** A system using an ESP32 to control music playback based on ambient temperature. Users can select radio stations, SD card audio files, or adjust volume through an OLED menu interface and push buttons. Temperature is measured with the HTU21D sensor.
- **Developers:** [Milene Granda](https://github.com/milenegranda) & [Ada Salvador Avalos](https://github.com/AdaSalvadorAvalos)
- **Submodule:** [Final Project](PF-TempControlledAudio-ESP32)
- **Materials:**
  - ESP32
  - 3 push buttons
  - Speaker
  - Audio Amplifier with I2S DAC
  - SPI SD Card Reader
  - OLED Display (I2C)
  - KYYKA HTU21D Temperature & Humidity Sensor (I2C)
  - Breadboard & jumper wires
- **Languages:** English / Spanish
- **Resources:**
  - **Demo Video in Spanish:** [Watch video](PF-TempControlledAudio-ESP32/assets/proyecto_final.mp4)
  - **ESP32 Documentation:** [Espressif ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)
  - **Audio Library:** [ESP32-audioI2S / Audio](https://github.com/schreibfaul1/ESP32-audioI2S)
  - **OLED Library:** [Adafruit SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
  - **HTU21D Library:** [SparkFun HTU21D](https://github.com/sparkfun/SparkFun_HTU21D_Breakout_Arduino_Library)
  - **PlatformIO Dependencies (`platformio.ini`):**
    ```ini
    lib_deps = 
        adafruit/Adafruit SSD1306@^2.5.3
        kosme/arduinoFFT@^1.5.6
        sparkfun/SparkFun HTU21D Humidity and Temperature Sensor Breakout@^1.1.3
    ```


---

## How to Use This Repository

1. **Clone the Master Repository with Submodules:**
```bash
git clone --recurse-submodules https://github.com/AdaSalvadorAvalos/Digital-Processors.git
```

2. **Update Submodules:**
```bash
git submodule update --init --recursive
```
3. **Navigate to Any Practice:**
```bash
cd P1-LED-Blink-ESP32
# or cd P2A-Button-Interrupt-ESP32, P2B-Timer-Interrupt-ESP32, etc.
```
4. **Open in PlatformIO / VS Code**
- All projects are PlatformIO compatible.
- Follow the README inside each submodule for running instructions.

