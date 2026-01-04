# RDR2-pc-guide
pc-graphic setting guide for RED DEAD REDEMPTION 2
## PC Video Settings Explained

### Resolution
Resolution determines how many pixels the game renders on your screen.  
Lowering the resolution can significantly increase FPS, especially if you have a weak GPU.  

⚠️ Warning: Lower resolution reduces image clarity and sharpness.

---

### VSync
VSync helps eliminate screen tearing by syncing the game’s FPS with your monitor’s refresh rate.

- **On:** FPS will not exceed your monitor’s refresh rate.
- **Half:** FPS is limited to half of your monitor’s refresh rate.
- **Off:** Unlimited FPS, but screen tearing may occur.

---

### NVIDIA Reflex Low Latency
NVIDIA Reflex is a technology designed to reduce system latency.  
It makes your actions (mouse clicks, keyboard input) register faster in-game.

If you play **Red Dead Online**, enabling NVIDIA Reflex is recommended and does not negatively impact performance.

---

### Triple Buffering
Triple Buffering improves FPS stability when **VSync is enabled**.  
---

### Texture Quality
Texture Quality affects visual detail and VRAM usage.

- **Low:** Lowest visual quality, best FPS, minimal VRAM usage.
- **Medium:** Slightly better visuals, ~2 FPS loss, minimal VRAM increase (~20 MB).
- **High:** Great visual quality, ~1 FPS loss compared to Medium, but ~1 GB higher VRAM usage.
- **Ultra:** Small FPS drop (~5 FPS compared to High) with little noticeable VRAM usage.

📌 **Recommendation:**  
If you don’t have a high-end GPU, **High** is the best balance between visuals and performance. in this Game.


---


### Anisotropic Filtering
Anisotropic Filtering improves texture sharpness, especially on surfaces viewed at an angle.

Available options:
Off, x2, x4, x8, x16

This setting has very little impact on FPS.  
From Off to x16, the FPS difference is usually around 3 FPS.

📌 Recommendation:  
Based on experience in many games, **x8 or x16** is recommended because it significantly improves texture sharpness with almost no performance cost.

---

### Lighting Quality
Lighting Quality controls the quality and realism of lights, especially noticeable at night.

Available options:
Low, Medium, High, Ultra

- **Low:** Good lighting with the best FPS, but not very realistic.
- **Medium:** Similar FPS to Low, slightly higher VRAM usage, but noticeably better lighting quality.
- **High:** Lighting looks great, but FPS drops around 13 FPS.
- **Ultra:** Best lighting quality in the game, about 5 FPS drop compared to High, very demanding.

⚠️ Warning:  
If your GPU is not strong, **Medium** offers the best balance between performance and visual quality.

---

### Global Illumination
Global Illumination (GI) simulates how light bounces off surfaces, making scenes look more natural and realistic.

Available options:
Low, Medium, High, Ultra

- From **Low to High**, FPS impact is minimal while realism improves a lot.
- **Ultra** causes around 6 FPS drop compared to High, with only minor visual improvement.

📌 Recommendation:  
Use **High** or **Medium** for the best balance.

---

### Shadow Quality
Shadow Quality is one of the most demanding graphics settings.

- **Low:** Poor shadow quality, hard and unrealistic shadows.
- **Medium:** Best balance for most systems.
- **High / Ultra:** Better shadows but very demanding on FPS.

📌 Recommendation:  
Medium is usually the best option unless you have a high-end GPU.

---

### Far Shadow Quality
This option controls shadows for distant objects like trees.

Performance impact is low.

📌 Recommendation:  
Set it to **High** and enjoy the view.

---

### Screen Space Ambient Occlusion (SSAO)
SSAO adds depth by darkening corners and areas where objects are close together, such as:
- Where walls meet the floor
- Under objects
- Around rocks, foliage, and small details

SSAO does not create real shadows, but it greatly improves realism.

In Red Dead Redemption 2:
- Medium to Ultra shows very little visual difference.
- Turning SSAO Off can increase FPS by 6–9 FPS, but makes objects look flat and unrealistic.

📌 Recommendation:  
Keep SSAO **On (Medium)** for better realism.

---

### Reflection Quality
Reflection Quality controls reflections on water, glass, metal, and shiny surfaces.

In Red Dead Redemption 2, this setting has minimal visual impact.

📌 Recommendation:  
Set it to **Medium**.

---

### Mirror Quality
Mirror Quality controls how detailed reflections appear in mirrors.

Mirrors are not very important in RDR2 and have limited use.

📌 Recommendation:  
**Medium** offers the best balance.

---

### Water Quality
Water Quality controls how realistic water looks and behaves.

Red Dead Redemption 2 has some of the best water visuals in any game, but this setting is demanding.

📌 Recommendation:  
Use **Medium** for good visuals and stable performance.


---


### Volumetrics Quality
Volumetrics Quality controls how light interacts with the air, including fog, mist, smoke, god rays, dust, and light beams.  

- From Low to High, FPS drops about 3 FPS, but the game looks like a masterpiece.  
- **Ultra** is very demanding and not recommended.

---

### Particle Quality
Particle Quality controls the detail and number of particle effects such as explosions, fire, smoke, sparks, bullet impacts, dust, rain, snow, and ash.  

- In RDR2, FPS is mostly unaffected.  
📌 Recommendation: **High** for best visuals.

---

### Tessellation Quality
Tessellation Quality controls the geometric detail of surfaces by dynamically adding extra polygons.  

- Makes flat surfaces appear truly 3D.  
- Performance impact is minimal.  
📌 Recommendation: **High**.

---

### NVIDIA DLSS / AMD FSR
DLSS (Deep Learning Super Sampling) is an AI technology by NVIDIA that boosts performance while keeping visuals sharp.  

- In RDR2, using DLSS is **not very effective**.  

**DLSS Modes:**

| Mode | Effect | FPS Impact |
|------|-------|------------|
| Quality | Closest to native resolution | Low FPS gain |
| Balanced | Mix of performance and quality | Medium FPS gain |
| Performance | Lower internal resolution | High FPS gain |
| Ultra Performance | Very low resolution (e.g., 4K → 1080p) | Huge FPS gain, some blur |

---

### TAA (Temporal Anti-Aliasing)
TAA smooths jagged edges by blending information from multiple frames over time.  

- Reduces diagonal lines, thin edges, and stair-step effects.  
- FPS impact is minimal.  
📌 Recommendation: **High** for smooth visuals.

---

### FXAA (Fast Approximate Anti-Aliasing)
FXAA is a simple, light method to smooth jagged edges.  

- Minimal FPS impact.  
📌 Recommendation: **On** for sharper textures.

---

### MSAA (Multisample Anti-Aliasing)
MSAA smooths edges by sampling multiple points per pixel.  

- Very demanding on performance.  
📌 Recommendation: **Avoid** for RDR2.

---

### Near Volumetric Resolution
Controls the detail of volumetric effects (fog, smoke, god rays) near the camera.  

- Very demanding.  
📌 Recommendation: Use **High** for visuals if your GPU is strong; otherwise, **Low**.

---

### Far Volumetric Resolution
Controls volumetric effects far from the camera.  

- Minimal visual impact.  
📌 Recommendation: **Medium**.

---

### Volumetric Lighting Quality
Controls the realism and detail of god rays in fog, smoke, and dust.  

- In RDR2, differences are minimal.  
📌 Recommendation: Any setting is fine.

---

### Particle Lighting Quality
Controls how particles interact with light in the scene.  

- In RDR2, differences are negligible.

---

### Soft Shadows
Controls the smoothness and realism of shadow edges.  

- Minimal FPS impact.  
📌 Recommendation: **High or Ultra**.

---

### Grass Shadows
Controls shadows of grass and small foliage.  

- Enhances realism and beauty.  
- Minimal FPS impact.  
📌 Recommendation: **On**.

---

### Long Shadows
Controls whether shadows stretch realistically during sunrise or sunset.  

- Enhances beauty of sunsets/sunrises.  
- Costs about 4 FPS.  
📌 Recommendation: **On**.

---

### Full Resolution SSAO
Controls how SSAO is calculated at full screen resolution.  

- In RDR2, visual differences are minimal.  
📌 Recommendation: Any setting is fine.

