# 🏠 Home Automation System (ESP32 + Blynk)

This project is a smart home automation system using ESP32, controlling Light and Fan using the Blynk app.

# 🚀 Project Title:
**Home Automation System (ESP32 + Blynk)**

This project is a smart home automation system using **ESP32**, enabling the control of **light and fan** through the **Blynk IoT mobile app**. It demonstrates the use of cloud-based platforms in building a smart, connected environment — an essential application in the field of the **Internet of Things (IoT)**.

---

## 📋 Intern Details

- 👨‍💼 **Name**:  Mohammed Abdul ALi Nabeel
- 🎓 **Intern ID**:CITS0D781  
- 🏢 **Company**: CodTech IT Solutions  
- 🌐 **Domain**: Internet of Things  
- 📅 **Internship Duration**: 4 Weeks  
- 🧑‍🏫 **Mentor**: Neela Santhosh  

---

## 📌 Project Overview

This IoT-based home automation project is designed to control household appliances such as lights and fans using a smartphone. The system uses the **ESP32 microcontroller** and connects to the **Blynk Cloud** platform via Wi-Fi. The user can interact with the devices through virtual switches on the Blynk app. The project emphasizes **real-time remote device control**, a crucial feature in modern smart homes.

---

## 🔧 Components Required

| Component           | Quantity |
|---------------------|----------|
| ESP32 Dev Module    | 1        |
| Relay Module , LEDs | 4,4    |
| Push Buttons        | 4  |
| Jumper Wires        | As needed |
| Breadboard          | 1        |
| Smartphone (with Blynk App) | 1 |
| Internet (Wi-Fi)    | 1        |

---

## 🔗 Wokwi Simulation

👉 [Click here to open Wokwi Simulation](https://wokwi.com/projects/your-wokwi-link-here)

---

## 📱 Blynk Setup

- Platform: [https://blynk.cloud](https://blynk.cloud)
- Virtual Pins:
  - `V0`: Light Control
  - `V1`: Fan Control
- WiFi SSID (for Wokwi): `Wokwi-GUEST`
- No password needed

---

## 🧠 How It Works

1. **ESP32** connects to Wi-Fi and syncs with Blynk Cloud.
2. The **Blynk app** sends ON/OFF commands through virtual pins.
3. **Relay modules or LEDs** simulate the activation of **light and fan**.
4. Circuit and logic can also be tested in **Wokwi** using LEDs instead of actual hardware.

-----
## 🔧 Circuit Diagram
<img width="891" height="751" alt="image" src="https://github.com/user-attachments/assets/26922f72-9faf-4f6a-a6e9-e7fffa324221" />

---

## 💻 Code Snippet

```cpp
#define lightPin 4
#define fanPin 5

void setup() {
  pinMode(lightPin, OUTPUT);
  pinMode(fanPin, OUTPUT);
}

void loop() {
  // Logic triggered via Blynk (use BLYNK_WRITE() in real deployment)
}











