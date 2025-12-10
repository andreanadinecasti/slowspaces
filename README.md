# **The Slow Space Editor — Broadening Access to Restorative XR**  
*A research prototype for creating restorative, meditative XR spaces for people with limited access to nature*

The **Slow Space Editor** is a two-part prototype (a simple 2D editor + a 3D preview/VR experience) that helps users create and inhabit restorative XR environments. The project explores how XR can provide contemplative, reflective, and mindfulness-supporting experiences for people who are unable to access physical green spaces due to mobility, health, or other barriers.

This repository documents the project’s concept, user studies, materials, and the contributions I made during evaluation and analysis.

---

## ✨ Project Overview

**Goal:** Provide an accessible, easy-to-use toolchain to design and experience restorative virtual spaces (slow spaces) that encourage reflection, calm, and mindfulness.

**Key ideas:**
- A **2D editor** (web-based) for fast, low-friction layout and placement of natural elements (grass, water, trees, walls, items).
- A **3D preview** for real-time visualization and a **VR experience** (Meta Quest / Unreal) to inhabit the created spaces.
- Target users include people with limited mobility, hospital patients, older adults, and others with reduced access to restorative green environments.
- Emphasis on **simplicity**, **territorial personalization**, **safe/comfortable design**, and **slow, contemplative interaction** rather than gamified efficiency.

---

## 🧩 System Components

- **2D Editor (Web)**  
  - Drag-and-drop grid-based editor (built with Phaser).  
  - Simple palette to place terrain (grass/rock/water) and objects.  
  - Time-of-day toggle (morning / dusk / night).  
  - Real-time updates to preview via WebSockets.

- **3D Preview & VR Experience (Unreal)**  
  - High-fidelity preview window that mirrors the 2D layout.  
  - VR mode for immersion on standalone headsets (tested with Quest 3 + Unreal Engine).  
  - Focus on nature-like dynamism (audio, moving leaves, optional fauna) and comfortable scene composition.

---

## 🧠 Research & Study Summary

**Research questions explored:**
- Can radically simplified creation tools let non-experts build restorative XR spaces?
- How do users experience restoration, safety, and personalization in created virtual spaces?
- Which features (dynamism, sound, personalization) most strongly support meditative experience?

**Study structure (lab-based):**
1. Brief introduction to slow spaces and the editor.
2. Participant builds a space in the 2D editor while thinking aloud.
3. Participant spends time (e.g., 2 minutes) in the VR preview/experience.
4. Semi-structured interview and follow-up questions.
5. Researchers transcribe sessions and analyze qualitative responses.

**Main qualitative observations (sample):**
- Participants quickly grasped the 2D-to-3D workflow and created personally meaningful spaces.  
- Users emphasized **safety**, **privacy**, and bodily comfort when designing spaces (even when physical interaction wasn’t possible).  
- Dynamism (birds, water sounds, moving elements) strongly increased perceived realism and restorative value.  
- Many participants expressed interest in sharing or inviting others — indicating social potential for community-made slow spaces.

---

## 🙋 My Role & Contributions

I joined during the later stages (testing & analysis) and led several important activities:

### Participant Sessions & Facilitation
- Recruited participants and ran full study sessions independently.  
- Walked participants through onboarding, observed in-session behavior, and conducted follow-up interviews.  
- Ensured standardized procedures across sessions.

### Qualitative Analysis & Synthesis
- Coded transcripts and researcher notes.  
- Helped build the codebook and surfaced themes about restoration, ritual, personalization, and dynamism.  
- Participated in weekly analysis meetings and contributed to shaping findings and recommendations.

### Prototype Testing & Iteration
- Performed internal testing of editor/preview builds.  
- Identified usability issues, suggested refinements to onboarding and UI flows.  
- Reported edge cases (e.g., perceived lack of variety, desire for procedural variety and liveliness).

My contributions are described in the attached recommendation letter from the research lead (included in `/letters`).

---

## 🛠 Tools & Technologies Used

- **Phaser** (2D editor frontend)  
- **WebSockets** (real-time 2D → 3D syncing)  
- **Unreal Engine (5.x)** for 3D preview and Quest VR experiences  
- **Meta Quest 3** (device used in testing)  
- Research tools: interview scripts, recording, transcription, qualitative coding workflows


