# RTC Driven Event Board – Message Display System

## 📌 Project Overview

The **RTC Driven Event Board – Message Display System** is an embedded systems project developed using the LPC2148 ARM7 microcontroller. It is designed to display important announcements, events, schedules, and real-time date and time information on a 16×2 LCD.

The system uses a Real-Time Clock (RTC) to maintain accurate time and date information. Users can manage and edit messages through a 4×4 matrix keypad using an admin interface with password authentication.

This project provides an efficient and user-friendly solution for displaying automated announcements in educational institutions, offices, and public places.

## 🎯 Objectives

- Display real-time date, time, and day information.
- Display important announcements and event messages.
- Allow administrators to add, edit, and manage messages.
- Provide password-based access to the admin menu.
- Display temperature readings using the LM35 sensor.
- Indicate system status using LEDs.

## 🛠️ Hardware Requirements

- LPC2148 ARM7 Microcontroller
- 16×2 LCD Display
- RTC Module
- 4×4 Matrix Keypad
- LM35 Temperature Sensor
- LEDs (Green and Red)
- Push Button
- Power Supply
- Connecting Wires

## 💻 Software Requirements

- Embedded C
- Keil µVision IDE
- Flash Magic
- Embedded C Programming Tools

## ⚙️ Technologies Used

- ARM7 Architecture
- Embedded C Programming
- Microcontroller Interfacing
- LCD Interfacing
- RTC Communication
- ADC Interfacing
- Keypad Interfacing
- GPIO Programming

## 🔑 Key Features

1. **Real-Time Clock:** Displays the current time, date, and day.
2. **Message Display:** Displays predefined announcements and event notifications.
3. **Message Editing:** Allows authorized users to edit messages through the keypad.
4. **Password Authentication:** Protects administrative functions.
5. **Temperature Monitoring:** Reads temperature data from the LM35 sensor using ADC.
6. **Status Indication:** Uses LEDs to indicate different system conditions.
7. **LCD Scrolling:** Displays longer messages using scrolling functionality.

## 🔌 System Working

1. The LPC2148 microcontroller initializes the LCD, RTC, keypad, ADC, and GPIO peripherals.
2. The RTC provides real-time date and time information.
3. The LCD displays the current time, date, and scheduled announcements.
4. The user can access the admin menu using the keypad.
5. Password authentication is performed before allowing message modifications.
6. Authorized users can edit and update stored messages.
7. The LM35 sensor provides temperature readings through the ADC interface.
8. LEDs indicate the system status.

## 📂 Block Diagram

<img width="1536" height="1024" alt="RTC-Driven Event Board System" src="https://github.com/user-attachments/assets/4572b38a-5d9d-4cc4-b9d8-f854328f0475" />

## 🚀 Applications

- Educational institutions
- College notice boards
- Office announcement systems
- Hospitals
- Public information display systems
- Event management systems

## 🌟 Future Enhancements

- Wireless message updates using Wi-Fi or Bluetooth.
- Integration with IoT platforms.
- Mobile application for remote message management.
- Larger LCD or graphical display support.
- Cloud-based announcement scheduling.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- ARM7 LPC2148 microcontroller programming.
- Embedded C development.
- Peripheral interfacing and driver development.
- RTC, LCD, keypad, and ADC interfacing.
- Real-time data handling.
- Debugging and hardware-software integration.

## 👩‍💻 Author

**Vasantha Ch**

B.Tech – Electronics and Communication Engineering (ECE)

**Project:** RTC Driven Event Board – Message Display System

---

⭐ If you find this project useful, feel free to star this repository!
