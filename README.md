# 🔧 Ultra-Mini DIY Electric Screwdriver

A compact **DIY electric screwdriver** designed to make repetitive screw tightening and removal effortless.  
This tool is **barely thicker than a lithium-ion cell**, yet provides enough torque for small electronics and hardware tasks.

The project demonstrates **miniaturization, creative reuse of components, and simple control mechanisms** to build a practical handheld tool.

---

## 📸 Project Overview

Manually tightening screws during electronics projects can be slow and tiring. To solve this problem, I built a **mini electric screwdriver using salvaged components and simple electronics**.

Despite its small size, the tool provides reliable torque and convenient bidirectional control.

---

## ⚡ Features

- 🔋 **Ultra-compact design** – almost the size of a single Li-ion cell  
- 🔄 **Bidirectional rotation** – tighten and loosen screws (CW / CCW)  
- 🖱️ **Limit switch control** for motor direction  
- 🔌 **Rechargeable battery system** using TP4056 charging module  
- ♻️ **Repurposed components** from old electronics  
- 🛠️ Designed for **electronics and small hardware work**

---

## 🧰 Components Used

| Component | Description |
|-----------|-------------|
| Li-ion Cell | Salvaged from an old laptop battery |
| N20 Gear Motor | Provides required torque for screw driving |
| Limit Switches | Taken from an old mouse for CW / CCW control |
| TP4056 Charging Module | Safe charging for Li-ion battery |
| Copper Wire (<1 mm) | Used for compact wiring |
| Screwdriver Bit Holder | For attaching screwdriver bits |

---

## ⚙️ Working Principle

The screwdriver uses a **simple mechanical switching mechanism**:

- Pressing one limit switch rotates the motor **clockwise (tightening screws)**  
- Pressing the other rotates the motor **counter-clockwise (loosening screws)**  
- When neither switch is pressed, the **motor stops automatically**

Power is supplied by a **rechargeable Li-ion battery**, which can be safely charged using the **TP4056 module**.

---

## 🔌 Circuit Overview

```
Li-ion Battery
      │
      │
  TP4056 Charger
      │
      │
Limit Switches (Direction Control)
      │
      │
   N20 Gear Motor
```

The limit switches reverse polarity to control motor direction.

---

## 🛠️ Build Steps

1. Salvage a **Li-ion battery** from an old laptop pack.
2. Mount the **N20 gear motor** inside a compact housing.
3. Connect **limit switches** to control motor direction.
4. Integrate the **TP4056 charging module** for safe battery charging.
5. Carefully wire everything using **thin copper wires**.
6. Attach the **screwdriver bit holder** to the motor shaft.
7. Enclose the system in a **compact casing**.

---

## 💡 Key Learnings

- Miniaturization requires **careful wiring and component placement**
- Old electronics are a **great source of reusable components**
- Simple mechanical switches can provide **reliable control without complex electronics**
- Compact DIY tools can be surprisingly powerful

---

## 🚀 Future Improvements

- Add **speed control (PWM)**
- Include **torque limiting mechanism**
- Design a **3D printed enclosure**
- Add **battery level indicator**
- Implement **USB-C charging**

---

## 📌 Applications

- Electronics assembly
- Robotics projects
- Small device repair
- Hobby projects

---

## 🤝 Contribution

Suggestions and improvements are welcome!  
Feel free to open an **issue or pull request**.

---

⭐ If you like this project, consider **starring the repository**.
