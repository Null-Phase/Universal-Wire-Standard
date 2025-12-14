# The Haptic Circuit Mapping Protocol (HCMP)

> **Status:** v1.0 (Public Release)  
> **Author:** Null-Phase  
> **License:** The Unlicense (Public Domain)

## 1. Statement of Purpose
The **Haptic Circuit Mapping Protocol (HCMP)** establishes a universal safety standard for electrical wiring that transcends visual perception. 

Recognizing that color codes can fail due to lighting conditions, color blindness, or visual obstruction (smoke/darkness), the HCMP binds specific **Haptic Textures** to **Voltage Tiers**. This ensures that critical safety information is physically accessible to all users via touch, creating a fail-safe layer of "Wire Discipline" that operates independently of visual cues.

## 2. Core Philosophy
* **Touch First:** Danger must be perceptible by a gloved hand in zero-visibility conditions.
* **Pattern Over Color:** Visual patterns (Shapes) and Textures take precedence over color coding.
* **The Hybrid Path:** The system supports "Retrofitting" (Patterns on existing colors) and "Standardization" (Patterns aligned with safe colors).

---

## 3. The Haptic Hierarchy (The Standard)
The protocol defines three distinct classes of wire based on function and danger level.

### Class A: SIGNAL (Low Voltage / Data)
* **Function:** Data, Audio, RF, Low-Wattage.
* **Visual Pattern:** **The Wave.** A continuous, smooth sine wave.
* **Haptic Profile:** **Smooth/Bumpy.** A gentle, flowing rise and fall with no sharp edges.
* **Design Intent:** Implies "Flow" and "Safety." Distinguishable from power by lack of sharp texture.

> **Visual Reference:** > (Drag and drop your "Red Wave" Signal image here)

### Class B: POWER L2 (Medium Voltage / 110V-240V)
* **Function:** Standard Household/Industrial Power.
* **Visual Pattern:** **The Stutter.** A spiral wrap interrupted by a longitudinal "cut" line.
* **Haptic Profile:** **Rhythmic/Broken.** A clean coil texture with distinct, periodic gaps.
* **Design Intent:** Implies "Activity" and "Caution." The gap distinguishes it from a simple spring or signal wave.

> **Visual Reference:** > (Drag and drop your "Interrupted Spiral" Power image here)

### Class C: DANGER L3 (High Voltage / 480V+)
* **Function:** High Hazard, 3-Phase, Deadly Voltage.
* **Visual Pattern:** **The Barb.** A tight spiral overlayed with projecting "X" cross-hatching.
* **Haptic Profile:** **Sharp/Spiky.** A dense, aggressive texture with protruding elements.
* **Design Intent:** Implies "Hostility" and "DO NOT TOUCH." The physical change in silhouette (spikes) makes it impossible to mistake for Signal or L2 Power.

> **Visual Reference:** > (Drag and drop your "External X / Barbed" Danger image here)

---

## 4. Implementation Logic (For Developers/Manufacturers)
When generating visuals or code (CSS/SVG/CAD) for this project, prioritize:
1.  **High Contrast:** White patterns on Dark/Color backgrounds.
2.  **Texture Density:** Ensure the "Wave" (Low Density) feels distinct from the "Barb" (High Density).

## 5. Legal Disclaimer & Rights
**This project is dedicated to the Public Domain.**

* **No Claim:** The author (Null-Phase) makes no claim of ownership over these patterns, concepts, or logical structures. They are released freely for the benefit of public safety and industrial standardization.
* **Liability:** This protocol is a proposal for a visual/haptic standard. The author assumes no liability for the implementation, manufacturing, or use of these patterns in real-world electrical systems. Always follow local electrical codes (NEC, IEC, etc.) and consult certified engineers.
* **Patents:** By publishing this prior art to the public domain, the intent is to prevent the patenting of these specific safety patterns, ensuring they remain free for any manufacturer to adopt.

---
*End of Protocol.*
