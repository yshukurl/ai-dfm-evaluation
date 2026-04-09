# AI-Assisted Design for Manufacturability (DFM) Evaluation

## Overview
This project evaluates the effectiveness of artificial intelligence as a tool for Design for Manufacturability (DFM) in CAD-based mechanical design. The study analyzes AI performance across parts of increasing complexity and assesses its ability to identify machining constraints, suggest redesigns, and support engineering decision-making.

## Objective
The goal of this project was to determine how reliable AI is as an engineering support tool for manufacturability analysis and whether it can meaningfully improve design outcomes in real-world scenarios.

## My Role
- Conducted full DFM evaluations on multiple CAD parts  
- Analyzed machining constraints, cost drivers, and process limitations  
- Compared AI responses across different prompts and complexity levels  
- Evaluated implementation feasibility of AI-generated redesigns  
- Documented engineering conclusions and limitations of AI  

## Tools & Methods
- CAD: SolidWorks  
- AI System: Nexus AI (Cosmon)  
- Manufacturing Focus: CNC machining (milling & turning)  
- DFM Principles: tool accessibility, depth-to-diameter ratio, thread engagement, setup reduction  

---

## Engineering Approach

The evaluation followed a structured framework:

1. Extract CAD geometry and describe engineering features  
2. Use AI to identify manufacturability constraints  
3. Compare multiple AI responses for consistency  
4. Implement or validate suggested design changes  
5. Re-evaluate manufacturability after redesign  
6. Assess AI performance across increasing complexity  

---

## Case Studies

### 1. Simple Part — Wrench
- AI consistently identified sharp internal hex corners as non-machinable  
- Recognized 3-axis feasibility and low setup complexity  
- Suggested corner relief radii to eliminate need for EDM or broaching  

**Key Result:**
- Reduced setup count and enabled full machinability using standard tooling  

---

### 2. Medium Complexity — Curved Bracket
- Identified multi-axis machining requirements  
- Flagged inconsistent fillets forcing small tool usage  
- Detected excessive thread engagement (~3.75×D vs 1.5×D guideline)  
- Highlighted poor tool accessibility in concave features  

**Key Result:**
- Standardizing fillets and reducing thread depth improved manufacturability and reduced machining risk  

---

### 3. High Complexity — Multi-Feature Housing
- Detected deep pockets requiring high aspect ratio tools (~6.7× tool diameter)  
- Identified mixed-process manufacturing (milling + turning)  
- Highlighted setup complexity (4–5 setups in 3-axis machining)  
- Recognized inefficient feature interactions driving cost  

**Key Result:**
- Recommended redesign strategies reduced cycle time, setup count, and machining difficulty  

---

## Key Engineering Insights

### What AI Did Well
- Accurately identified real machining constraints (non-machinable geometry, poor access, deep pockets)  
- Consistently recognized major cost drivers (setup count, small tools, feature complexity)  
- Provided useful rule-based redesign recommendations  
- Maintained strong consistency across multiple responses  

### Limitations of AI
- Could not resolve design intent conflicts (function vs manufacturability)  
- Limited ability in full process planning (fixtures, machine selection)  
- Struggled with complex geometry requiring multi-process decisions  
- Required human validation for final engineering decisions  

---

## Results Summary

- Evaluated manufacturability across **3 complexity levels**  
- Achieved measurable improvements in:
  - Setup reduction  
  - Machining feasibility  
  - Tool efficiency  
  - Cycle time reduction (~18% in some cases)  
- Demonstrated that AI is highly effective as a **DFM diagnostic tool**, but not a replacement for engineering judgment  

---

## Conclusion

AI is a powerful tool for early-stage manufacturability analysis and design optimization. It performs exceptionally well in identifying constraints and suggesting improvements, but still depends on human engineers for final decision-making, especially when design intent and function are involved.

---

## Full Report
For complete analysis, methodology, and detailed case studies:

📄 [View Full Report](AI_CAD_DFM_Final_Report.pdf)

---

## Visual Examples
(Add your CAD images here)

![Wrench CAD](images/wrench.png)
![Bracket CAD](images/bracket.png)
![Complex Part](images/complex.png)

---

## Key Takeaway

AI should be used as a **DFM assistant and force multiplier**, not a replacement for engineering expertise.
