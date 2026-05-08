# 🎮 Dodge Ice — ESP32 OLED Arcade Game

Dodge Ice is a compact arcade-style survival game developed using an ESP32, SH1106 OLED display, joystick module, and active buzzer.  
The project combines embedded systems, real-time input handling, animation, and game logic to create a smooth handheld arcade experience on minimal hardware.

Players control a movable ball and must survive by dodging continuously falling ice flakes while progressing through increasing difficulty levels and timed boss phases.

---

# ✨ Features

- 🎮 Real-time joystick-controlled movement
- ❄️ Animated falling ice obstacles
- ❤️ Multi-life gameplay system
- ⚠️ Timed boss survival phases
- 📋 Interactive joystick-controlled menu system
- ⚙️ Adjustable difficulty modes
- 🔊 Toggleable sound effects using active buzzer
- 🕹️ Smooth OLED rendering using double buffering
- 📈 Progressive difficulty scaling
- 💥 Collision detection and score tracking

---

# 🌟 Project Highlights / Specialities

Unlike simple OLED demos, this project focuses on creating a complete mini arcade system with multiple integrated systems working together in real time.

### Key Highlights
- Built entirely on resource-constrained hardware
- Uses efficient frame rendering with the U8g2 graphics library
- Implements state-based game architecture
- Includes animation, sound, UI navigation, and gameplay logic simultaneously
- Designed for responsive gameplay despite limited OLED refresh rates

The project demonstrates how small embedded systems can be used for interactive entertainment and game development concepts.

---

# 🧠 Concepts & Skills Learned

This project helped in understanding and implementing:

## Embedded Systems
- ESP32 GPIO handling
- Analog joystick input processing
- Active buzzer interfacing
- I2C OLED communication

## Programming Concepts
- State machines
- Collision detection
- Real-time game loops
- Timing using `millis()`
- Input debouncing
- Dynamic difficulty scaling

## Graphics & UI
- OLED rendering optimization
- Sprite-like animations
- Menu system design
- Frame-based animation techniques

## Game Design
- Balancing gameplay difficulty
- Reward and survival mechanics
- Boss phase implementation
- Player feedback through sound and visuals

---

# 🧰 Components Used

| Component | Quantity |
|---|---|
| ESP32 Dev Module | 1 |
| SH1106 1.3" OLED Display | 1 |
| Joystick Module | 1 |
| Active Buzzer | 1 |
| Jumper Wires | Several |

---

# 🔌 Wiring

## OLED Display (I2C)

| OLED Pin | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| SDA | GPIO 21 |
| SCL | GPIO 22 |

---

## Joystick Module

| Joystick Pin | ESP32 |
|---|---|
| VRx | GPIO 34 |
| SW | GPIO 32 |
| VCC | 3.3V |
| GND | GND |

---

## Active Buzzer

| Buzzer Pin | ESP32 |
|---|---|
| + | GPIO 25 |
| - | GND |

---

# 🎮 Controls

## Menu Navigation
- Move joystick LEFT / RIGHT → Navigate menu
- Press joystick button → Select option

## Gameplay
- Move joystick LEFT / RIGHT → Move player
- Dodge falling ice flakes
- Survive boss phases for high scores

---

# ⚙️ Difficulty Modes

| Mode | Description |
|---|---|
| Easy | Slow obstacle speed |
| Medium | Balanced gameplay |
| Hard | Faster obstacle speed and increased challenge |

---

# 🛠️ Libraries Used

- U8g2 Graphics Library

Install from Arduino IDE Library Manager:

```text
U8g2
```

---

# 🚀 Future Improvements

Planned upgrades and ideas for future versions:

- 🏆 EEPROM-based high score saving
- 🎨 Improved animations and visual effects
- ❄️ Additional enemy types and movement patterns
- 🛡️ Power-ups and temporary shields
- 🔊 Enhanced sound system with tones/music
- 📱 Battery-powered handheld version
- 🌈 Better UI transitions and effects
- ⚡ Smooth analog acceleration physics
- 👾 Multiple boss patterns
- 📊 Statistics and gameplay tracking

---

# 👨‍💻 Author
Suresh Nepali

# 📜 License
Mit license
This project is open-source and free to use for learning and educational purposes.
