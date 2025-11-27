# 🐦 Flappy Bird — Canvas Game
A modern, browser-based recreation of the classic *Flappy Bird*, built from scratch using **HTML Canvas**, **CSS**, and **JavaScript**.  
Tap, click, or press space to fly — survive the pipes and chase a new high score.

👉 **Play it here:**  
https://noanonoa.github.io/flappy-bird/

---

## 🎮 About the Game
Flappy Bird is a simple side-scrolling skill game where you control a bird trying to navigate through endless pipes.  
Each successful pass earns a point, and one collision ends the run.

This version focuses on smooth animation, responsive controls, and accurate collision mechanics.

---

## 🧩 Wireframes
Initial sketches used to plan the gameplay layout and collision logic:

![wireframe for game screen](/img/001-wireframe.png)
![wireframe for collision mechanics](/img/002-wireframe.png)

---

## 🔧 Technology Stack
- **HTML5 Canvas** — rendering
- **CSS3** — layout & styling
- **JavaScript (Vanilla)** — physics, logic, collisions, audio, scoring

---

## 🖼️ Assets

### Images  
Sprites used for background, pipes, ground, and bird animation.

![flappy bird theme](/img/og-theme.png)
![flappy bird theme v2](/img/og-theme-2.png)

### Audio  
Sound effects for:
- flap  
- score  
- collision/hit  
- falling  
- game over  

(From various public sprite/sound resources.)

### Screenshot
![flappy bird screenshot](/img/001-screenshot.png)

---

## 🏗️ MVP Features
- ✔️ Start screen
- ✔️ Tap/click/space to flap
- ✔️ Bird gravity + velocity physics
- ✔️ Randomized pipe pairs
- ✔️ Endless pipe spawning
- ✔️ Score tracking
- ✔️ Collision detection (pipes, ground, ceiling)
- ✔️ Game over screen
- ✔️ Restart on click

---

## 🚀 Stretch Features
- Animated bird (wing flaps + rotation)
- Sounds: flap, score, hit, fall, game over
- Customizable theme
- Animated idle state on start screen
- Day/night mode
- Running timer display
- Responsive layout for mobile screens

---

## 🧠 Development Breakdown

### 🟦 HTML
- Canvas container
- Game title
- Wrapper for layout

### 🟩 CSS
- Centered layout
- Fixed canvas viewport
- Clean and simple UI

### 🟨 JavaScript

#### Core Logic
- Canvas setup & game loop  
- Background rendering  
- Ground scrolling  
- Bird sprite drawing  
- Pipe generation & movement  
- Score system  
- Game states (ready → playing → game over)

#### Physics
- Gravity applied every frame  
- Velocity changes to simulate falling  
- Upward force on flap  
- Bird rotation based on movement direction  

#### Pipe System
- Random pipe heights  
- Constant vertical gap  
- Scoring when bird passes pipe center  
- Resetting pipes on restart  

#### Collision System
- Bird ↔ pipe collision  
- Bird ↔ ground  
- Bird ↔ ceiling  
- Freeze scene & show game over screen  

#### Game Over Handling
- Display current + best score  
- Reset all values on restart  
- Clean pipe respawn  

---

## 📝 Final Thoughts
Building this game from scratch was a great deep dive into:

- Canvas rendering  
- Frame-based animation  
- Object-oriented state management  
- Physics simulation  
- Sprite-based graphics  
- Collision detection  

Working with gravity and velocity made the bird feel natural, and implementing randomized pipes taught a lot about object lifecycle and timing. Recreating classic mechanics like scoring and sprite-number rendering was challenging but rewarding.

This project strengthened fundamentals across JavaScript: loops, events, objects, arrays, animation, and canvas techniques.

---

## 📌 Summary
This is a self-built Flappy Bird clone created step-by-step — from wireframes to full game logic — without relying on a copied or forked repo.  
A fun, complete JavaScript canvas game that’s easy to run, play, and extend.

---

