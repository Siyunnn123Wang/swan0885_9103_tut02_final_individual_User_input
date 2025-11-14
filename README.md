# swan0885_9103_tut02_final_individual_User_input

# wheels-of-fortune — interactive p5.js sketch_User Input

## Part 1: Concept & Inspiration
Inspired by **Pacita Abad’s _Wheels of Fortune_**, this sketch turns spinning ornaments into a small metaphor for **fate vs. choice**. Users “choose” by hovering/clicking; physics “decides” through gravity and bounce.  
I also borrow the casual drop-and-see loop from the game **_Synthetic Watermelon_** to keep interactions lightweight and repeatable.

---

## Part 2: How to interact
-**Dope Mode**
- **Click empty canvas** → **drop** a new circle that falls with gravity and bounces.  
- **Game Mode**
- **Hover over a circle** → that circle **rotates** (closer cursor = faster spin).  
- **Click a circle** → **remove** it.  
- **Press `1` or `2`** → **randomize the background color**.  
- **Press `R` or `r`** → **Restart all**


---

## Part 3: My individual approach (what animates & how it differs)
- **Driver:** interaction (**mouse + keys**), not time/audio/Perlin.  
- **Animated properties:**  
  - **Motion:** `x/y`, `vx/vy`, **gravity**, **bounciness**, **minimum speed** clamp so wheels can truly rest.  
  - **Rotation:** angle `theta` increases while hovered; spin eases out when the cursor leaves.  
  - **Color:** hotkeys switch **background** for contrast.
  
---

## Part 4: Short technical explanation


---



---
