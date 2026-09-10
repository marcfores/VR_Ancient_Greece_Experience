# VR Ancient Greece: Interactive Animation Experience

A Virtual Reality environment prototype focused on Level Design, Physically Based Rendering (PBR), and advanced humanoid animation systems within the Unity engine. 

Developed during a series of VR practical workshops, this project explores environmental storytelling and proximity-based character interactions.

---
### **[Download / Access the Full VR Project Files Here](https://upvedues-my.sharepoint.com/:u:/r/personal/mfordom_upv_edu_es/Documents/ProyectoRV-TemploGriego.zip?csf=1&web=1&e=xT2RIb)**
---

## Level Design & Environment

*   **PBR & URP Integration:** The environment utilizes Unity's Universal Render Pipeline (URP) with Physically Based Rendering materials (concrete, ceramic, wood) and pre-calculated Lightmapping to achieve realistic lighting and shadows while maintaining high VR framerates.
*   **Spatial Composition:** Designed with three distinct zones to guide user flow: an exterior Greek Temple, an interior Museum Welcome Hall, and a designated Animation/Interaction Capsule.

## Animation & State Machines

*   **Humanoid Rigging & Retargeting:** External character models (Mixamo) were processed in Blender (mesh adjustment, armature linking, weight painting) before importing as Humanoid rigs in Unity to ensure accurate animation mapping.
*   **Proximity-Triggered Interactions:** Implemented a proximity-based event system using `Box Collider` triggers and custom C# scripts (`ControlPuerta.cs`). The `XR Origin`'s presence dynamically transitions the Animator Controller state machine from idle to complex motion sequences.
*   **Object Animation:** Precise pivot-point configuration and animation clips (`Abrir_Puerta.anim`) for fluid, realistic environmental interactions (e.g., door hinges).

## Repository Structure
*   `/docs`: Contains the technical documentation, including initial storyboards, environment breakdowns, and state-machine logic diagrams.
*   *Note: Due to the large file size of 3D assets and Unity builds, the executable and full project repository are hosted externally (see link above).*
