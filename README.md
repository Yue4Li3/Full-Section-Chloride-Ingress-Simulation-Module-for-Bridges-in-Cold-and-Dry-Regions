# Full-Section Chloride Ingress Simulation Module for Bridges in Cold and Dry Regions

This repository contains a simulation module for analyzing **chloride ingress in concrete bridge structures** located in inland continental climates characterized by cold winters, dry conditions, and seasonal de-icing salt usage.  
The current release provides documentation and a **protected ZIP package** of the code. Updated extractable code will be shared in a later version.

---

## 📖 Background

In inland regions of China, bridge structures often face **continental climate conditions**:
- Dry and semi-arid environments  
- Cold, long winters and short, hot summers  
- Low precipitation but high evaporation  
- Frequent winds in winter and spring  
- Intensive use of de-icing salts during icy road conditions  

These factors create a **severe chloride-induced deterioration environment** for bridge concrete.  
Particularly, the use of de-icing salts on bridge decks introduces chloride ions, which penetrate into the structure, damage the passive film around reinforcement, and accelerate steel corrosion.  

For performance assessment and disaster prediction of large bridges, **full-section numerical simulations** are necessary to analyze time-dependent chloride ingress and resulting durability degradation.

---

## ⚙️ Methodology

- **Concrete Material**: Typically, high-performance C60 concrete is used in superstructures of inland bridges.  
- **Chloride Source**: Unlike marine environments, the chloride exposure comes mainly from **winter de-icing salt applications**.  
- **Boundary Conditions**:  
  - Chloride ingress considered only on the **deck surface** and **side faces** of the girder.  
  - Time-varying exposure modeled as seasonal boundary input.  
- **Numerical Simulation**:  
  - A representative **standard cross-section model** is established.  
  - Macroscopic simulation methods are applied.  
  - Chloride ion diffusion is analyzed across the entire girder section to predict long-term service degradation.  

---

## 💡 Module Features

- Case study based on a **prestressed concrete cable-stayed bridge** in Inner Mongolia, China.  
  - Bridge type: 160 + 440 + 160 m span, double-tower, double-plane cable-stayed bridge.  
  - Simulation of half-girder sections sufficiently represents full-bridge behavior.  
- Enables **durability performance assessment** under cold-dry climate with de-icing salts.  
- Supports extension to other degradation phenomena:  
  - Carbonation  
  - Local cracking  
  - Combined deterioration processes  

---

## 🎯 Application Scenarios

- **Bridge design and durability assessment** in cold, dry inland regions.  
- **Prediction of chloride ingress depth and distribution** across girder cross-sections.  
- **Extension to different structural components**: girders, piers, decks.  
- **Integration with life-cycle performance analysis** for large-scale bridges.  

---

## 📂 Usage Notes

- This version includes a **protected ZIP file** containing the module.  
- Extraction-ready and updated code will be provided in a **future release**.  
- Tutorial materials and demonstration videos will be added later.  

---

## 📚 References

1. *A study on the mechanical corrosion degradation of steel based on 3D reconstruction of rough surface.* Engineering Structures.  
2. Mahboob Kanafi M. *Rocky road – surface roughness impacts on rubber friction.* Doctoral Dissertation, Aalto University, 2017.  

---

## 📜 License

This repository follows an **Open Science, Non-Commercial License**:  
- Free for academic and research purposes.  
- Commercial use requires explicit permission from the author.  

---

## 🚧 Status

- 🔒 Code available as a protected archive (ZIP).  
- 🛠️ Open extractable code and tutorials will be updated in later versions.  

