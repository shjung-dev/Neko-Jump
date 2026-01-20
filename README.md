# Neko Jump 🐾

**Neko Jump** is a 2D endless runner game inspired by *Flappy Bird*, featuring **Neko** from Sumikko Gurashi. Players tap to make Neko jump and navigate through an infinite series of pipes, aiming for the highest score possible.  

Built with **Unity**, this project also explores game publishing workflows, having been released on the **Microsoft Store**.  

---

## 🎮 Gameplay

- Tap or click to make Neko jump.  
- Avoid colliding with pipes and the ground.  
- Each successfully passed pipe increases your score.  
- The game gradually increases difficulty as you progress.  

---

## ⚙️ Features & Technical Details

- **Jump Mechanism:**  
  Uses Unity 2D physics. Player input applies vertical force to Neko for natural jumping motion.  

- **Infinite Pipe Generation:**  
  Procedurally spawns pipes at random vertical positions.  
  Implements **object pooling** to recycle pipes and optimize performance.  

- **Collision Detection:**  
  Unity 2D colliders detect collisions with pipes or ground and trigger game-over.  

- **Scoring System:**  
  Player score increments each time Neko passes between pipes. High scores are saved locally using `PlayerPrefs`.  

- **Visuals & Audio:**  
  Cute Sumikko Gurashi-inspired sprites and sound effects enhance the game experience.  

- **UI & Game Loop:**  
  Includes main menu, gameplay, and game-over screens with retry and score display.  

- **Publishing Experience:**  
  Published on **Microsoft Store**, gaining practical experience in game packaging, submission, and deployment.  

---

## 🛠️ Tools & Technologies

- **Game Engine:** Unity 2D  
- **Language:** C#  
- **Platform:** Windows (Microsoft Store)  
- **Version Control:** Git/GitHub  

---

## 📚 Learning Outcomes

- Developed skills with Unity 2D physics, input handling, and object pooling.  
- Learned procedural generation techniques for endless gameplay.  
- Implemented collision detection, scoring systems, and UI menus.  
- Gained hands-on experience in publishing a game to a commercial platform.  
- Practiced debugging, gameplay balancing, and creating user-friendly mechanics.  
