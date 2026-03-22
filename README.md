# The Hiddens

**The Hiddens** is a VR escape room project developed for the **LED CAVE at the Leibniz Supercomputing Centre (LRZ)**.  
The experience combines **environmental storytelling**, **horror atmosphere**, and **puzzle-based interaction** inside a mysterious apartment environment.

Players take on the role of an investigator following a missing person case. After entering the apartment, they become trapped in a disturbing, crime-scene-like space and must uncover clues, solve puzzles, and reveal the hidden story behind the scene.

For teaser: [Teaser](https://youtu.be/25tzcKgVytU)

For full game play video: [Full Game Play](https://youtu.be/MLnuCygSu2c)

---

## Project Overview

- **Project Type:** VR Escape Room
- **Platform:** LED CAVE
- **Location:** Leibniz Supercomputing Centre (LRZ)
- **Engine:** Unreal Engine
- **Genre:** Horror / Puzzle / Narrative Exploration

---

## Controls

| Action | Function |
|--------|----------|
| Restart | Restart the game |
| Interact | Trigger object interaction |
| Pickup | Pick up and carry objects |
| Highlight | Show interactable objects in range |
| Flashlight | Toggle flashlight for dark areas |

![Controls Placeholder](images/controller-layout-placeholder.png)

---

## Technical Implementation

### Highlight System
A custom outline material highlights objects when the player is within interaction range.

- Material-based outline in Unreal Engine
- Triggered by overlap detection
- Helps guide attention in dark scenes

![Highlight System Detail Placeholder](images/highlight-detail-placeholder.png)

### Pickup System
Players can grab and carry physics-enabled objects as part of the puzzle flow.

- Uses line trace from the controller (joystick)
- Objects are handled with a physics handle
- Tuned for more stable object movement

![Pickup System Placeholder](images/pickup-detail-placeholder.png)

### Puzzle Logic
Objects must be placed in the correct location based on puzzle conditions.

- Overlap-based validation
- Checks object type and properties
- Correct placement locks the object and updates progress
- Light feedback indicates success

![Puzzle Validation Placeholder](images/puzzle-validation-placeholder.png)

### Portal VFX
A procedural portal material was created to enhance the supernatural atmosphere.

- Built with animated noise textures
- Uses radial masks for shape and glow
- Designed as a lightweight real-time effect

![Portal VFX Placeholder](images/portal-vfx-detail-placeholder.png)

---

## Design Focus

The project explores how the LED CAVE can support immersive horror experiences through:

- spatial presence
- environmental storytelling
- puzzle-based exploration
- visual tension and atmosphere

## Contributions

| Contributor | Role | Contact |
|-------------|------|---------|
| **Shiyi Gou** | Team Lead, Unreal Engine Developer, Technical Artist | goumaja@gmail.com |
| **Can Yang** | Environmental Artist | Can.Yang@campus.lmu.de|
| **Yousri Cherif** | Environmental Artist | Cherif.Yousri@campus.lmu.de |

