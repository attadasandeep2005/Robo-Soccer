# 🤖 Robo Soccer Bot – Ojass’25 | NIT Jamshedpur ⚽

Welcome to the documentation of our **Robo Soccer bot** developed for **Ojass’25** at **NIT Jamshedpur**!  
This little beast was designed, built, and debugged with a lot of passion, late nights, and a few *"why is it going that way?"* moments.

---

## 🔧 Project Overview:

We designed a Bluetooth-controlled soccer-playing robot that competes on speed, precision, and ball-chasing madness.

### 🎯 Key Features:
- Controlled via smartphone using a **Bluetooth app** (available on Play Store)
- Compact, agile, and responsive movement (after we fixed the wiring confusion 😅)
- Capable of sharp turns, quick sprints, and occasional chaos

---

## ⚙️ Hardware Specifications:

| Component | Details |
|----------|---------|
| **Motors** | 500 RPM Side Shaft DC Gear Motors (x4) |
| **Battery** | 11.2V LiPo Battery, 30C Discharge |
| **Motor Driver** | BTS7960 Series High-Current Motor Driver |
| **Microcontroller** | ESP32 (Bluetooth & GPIO Control) |
| **Chassis** | Custom Acrylic/Aluminum Frame |
| **Control App** | Generic Bluetooth Controller from Play Store |

---

## 📲 How It Works:

1. Download any **Bluetooth Controller App** from the Play Store (we used the one with directional buttons).
2. Power on the bot using the LiPo battery.
3. Connect your phone to **ESP32 Bluetooth**.
4. Use the app's direction controls to drive the bot.

---

## 🧠 Pro Tips & Notes:

> ⚠️ **READ THIS IF YOUR BOT IS BEHAVING LIKE A REBEL**

If:
- You press **Left** and the bot goes **Right**, or  
- You press **Forward** and it moonwalks backward...  

Then you most likely messed up the **motor connections**.  
We did the same. 😅

### ✅ **Quick Fix**:
- Swap the motor connections on **either the left or right side**
- OR correct the logic in your ESP32 code (if you're handling direction in software)
- After the fix, test each command (Forward, Backward, Left, Right)

---

## 💡 Lessons Learned:

- Always double-check motor polarity before closing the chassis  
- LiPo batteries are powerful — respect the current!  
- Sometimes the bot just needs a motivational push (or a soldering fix)  
- **Never forget to carry a spare motor and accessories** 🔧  
  > One of our motors *froze at the last moment* during the competition, and we had no time to replace it.  
  > We had to operate the bot using just **three working motors** — it was chaotic, but it moved (mostly in circles). Lesson learned the hard way.



---

## 📸 Coming Soon:
- Bot demo videos 🏎️  
- 3D model of the chassis  
- Circuit diagrams and PCB layout  
- Code (if not already in this repo)

---

## 🙌 Built With Passion By:
**Team Garuda**  
Proudly representing our institution at Ojass’25

---

> _"Not every bot is born perfect — some have to take a wrong turn to find the right direction."_  
— Team Garuda 

---

⭐ Star this repo if your bot has ever driven itself into a wall.
