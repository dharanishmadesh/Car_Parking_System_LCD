# 🚗 Smart Car Parking System 🅿️

This is a project of a **Smart Car Parking System** using an Arduino, an IR sensor array, and a servo motor. The system tracks parking slots and allows entry/exit of cars, displaying the status of each slot on an LCD screen.

---

### 🛠️ Components Used:
- **Arduino Uno**
- **Servo Motor** (for gate control)
- **IR Sensors** (to detect parking space occupancy)
- **LCD Display** (I2C) for real-time display
- **Wires and Connectors** for connections

---

### 📦 Features:
- 🚗 **Car Slot Detection**: The system detects the availability of parking slots using IR sensors.
- 🚪 **Gate Control**: A servo motor opens the parking gate when a slot is available.
- 📱 **LCD Display**: Displays the parking status in real-time, showing which slots are filled and which are empty.
- 🔴 **Full Parking Alert**: Displays an alert when the parking is full.

---

### 💡 How It Works:
1. **IR Sensors**: Detect the presence of a car in each parking slot (S1 to S6).
2. **Servo Motor**: Opens the parking gate when there is an available slot.
3. **LCD Display**: Continuously updates the parking status, showing which slots are filled or empty.

---

### 📋 Pin Mapping:

- **IR Sensors**:
  - S1: Pin 5
  - S2: Pin 6
  - S3: Pin 7
  - S4: Pin 8
  - S5: Pin 9
  - S6: Pin 10
- **Servo Motor**: Pin 3
- **IR Enter**: Pin 2
- **IR Back**: Pin 4

---

### ⚙️ Setup Instructions:
1. **Wire the IR Sensors** to the Arduino as per the pin mapping mentioned above.
2. **Connect the Servo Motor** to pin 3.
3. **Connect the LCD Display** using the I2C interface (pins SDA and SCL).
4. **Upload the Code** to your Arduino and power up the system.
5. The system will start and show the status of the parking slots on the LCD.

---

### 🚀 Improvements:
- Add an app interface to check parking availability remotely.
- Implement a real-time slot reservation system.
- Introduce a payment mechanism for parking.

---

### 📝 License:
This project is licensed under the MIT License.

