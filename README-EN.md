# LivingMesh_SlimeTentacle V1.1  
### Procedural Slime / Tentacle Deformation Shader for Unity & VRChat

![shader_preview](./preview.png)

**LivingMesh_SlimeTentacle** is a custom Unity shader that transforms any mesh into  
a **living, organic slime / tentacle-like surface** using procedural deformation and lighting.

Designed for **stable use in VRChat**, it works without bones and is independent of mesh topology.

---

## 📌 About This Repository (Important)

⚠ **This GitHub repository does NOT distribute the shader source code.**

This repository exists **only as a reference and public notice**  
to describe the shader’s behavior, features, and official distribution policy.

The actual shader is distributed **exclusively via BOOTH**.

👉 **Official distribution:**  
🔗 **[BOOTH – O-TYAN Shop](https://o-tyan64.booth.pm/items/7760459)**

---

## ✨ Features

- 🐙 **Procedural Tentacle Deformation**
  - Organic, animated mesh deformation
  - No bones or animations required

- 🧠 **VRChat-Stable Vertex Deformation**
  - Object-origin–based deformation using `unity_ObjectToWorld`
  - Prevents distortion during world movement

- 🩸 **Flesh Gradient Shading**
  - Root-to-tip color blending
  - Pseudo depth shading for inner volume

- 💧 **Slime Rim & Wet Look**
  - Wet-looking rim light
  - Organic slime glow effect

- 🔥 **Berserk Mode**
  - Pulsing, aggressive visual state
  - Suitable for emotes and special effects

- 🎨 **MatCap Support**
  - Optional MatCap-based material enhancement

---

## 🎮 Usage (Conceptual)

1. Create a material in Unity
2. Assign the LivingMesh_SlimeTentacle shader
3. Apply it to any mesh
4. Adjust parameters via Inspector

※ Shader source files are **not included** in this repository.

---

## ⚙ Main Parameters

### Host / Motion
| Parameter | Description |
|---------|-------------|
| Host Intensity | Deformation influence |
| Deform Amplitude | Deformation strength |
| Deform Speed | Motion speed |
| Deform Frequency | Motion complexity |

### Flesh / Slime
- Base Flesh Color
- Tip Flesh Color
- Inner Darkness
- Slime Rim Color
- Wet Strength

### Berserk
- Berserk Level
- Berserk Color
- Pulse Speed

### MatCap
- MatCap Texture
- MatCap Strength

---

## 🧪 Environment

- Unity 2022 LTS
- Built-in Render Pipeline
- Intended for VRChat SDK

※ URP / HDRP not supported

---

## ⚠ License & Usage Notice

This repository contains **reference information only**.

### ✔ Allowed
- Viewing this repository
- Reading documentation and behavior descriptions
- Personal learning and research

### ❌ Prohibited
- Obtaining the shader source outside BOOTH
- Redistribution (modified or unmodified)
- Commercial use
- Inclusion in assets for sale (Booth, Gumroad, Unity Asset Store, etc.)
- Reverse engineering for redistribution purposes

**All Rights Reserved.**

---

## 🛒 Official Distribution

The full version (shader source, presets, documentation, and support)  
is available exclusively on BOOTH:

👉 **[BOOTH – O-TYAN Shop](https://o-tyan64.booth.pm/items/7760459)**

- VRChat tested
- Tuned presets included
- Support provided

---

## 👤 Author

**O-TYAN64**  
Unity / VR / Shader / Tool Developer  

GitHub: https://github.com/O-TYAN64

---

## 💬 Notes

This repository serves as a **public reference and notice**  
to clearly define the official distribution route and usage rules.

If you like this shader, please consider supporting development via the official release.
