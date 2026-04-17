<div align="center">

<img src="https://i.ibb.co/DfSLQhWX/Screenshot-2026-04-16-140219.png" alt="Lofi Focus Room Banner" width="100%">

</div>

# **🎧 Lofi Focus Room**

*"A minimalist, high-performance productivity workspace designed for deep work."*

**Lofi Focus Room** is a specialized web application that facilitates focused work sessions by combining the proven **Pomodoro technique** with high-fidelity, immersive ambient soundscapes. It provides a distraction-free digital environment where audio and visual aesthetics adapt to your workflow.

## **✨ Key Features**

* **Immersive Ambient Mixer**: Create your perfect focus environment by mixing high-quality concurrent audio streams including Rain, Fire, Cafe, and Nature.  
* **Precision Pomodoro Engine**: Integrated Focus and Break cycles (25/5 minutes) with clear visual countdowns and automated state transitions.  
* **Dynamic Theme Engine**: A unique system where the entire UI aesthetic (background gradients and accent colors) automatically shifts to match your active audio environment.  
* **Integrated Goal Management**: A real-time task tracker designed to help you organize and check off objectives without leaving your focus session.  
* **Glassmorphism UI**: A modern, translucent interface designed to be visually soothing and completely distraction-free.  
* **Adaptive Design**: Fully optimized for a seamless transition between desktop, tablet, and mobile orientations.

## **🛠️ Tech Stack**

* **Frontend Framework**: HTML5 & JavaScript (ES6+)  
* **Styling Engine**: Tailwind CSS (Utility-first framework)  
* **Audio Engineering**: Web Audio API (Low-latency stream management)  
* **Typography**: Google Fonts (*Varela Round*, *Space Mono*, *Playfair Display*)

## **🏗️ Technical Deep Dive**

### **Audio Engineering**

The core of the application leverages the **Web Audio API** to handle multiple concurrent high-definition audio streams. To navigate modern browser autoplay restrictions, I implemented a tactical initialization layer that unlocks the AudioContext upon the first user interaction, ensuring a seamless and reliable audio experience.

### **State Synchronization**

I developed a custom JavaScript engine to keep the Pomodoro timer state perfectly in sync with the UI components. This engine handles the complex logic required for transitioning between focus and break modes, including automatic audio cues and mode-switching notifications.

### **Responsive Glassmorphism**

Using **Tailwind CSS**, I utilized a mobile-first approach to architecture. Visual depth is achieved through advanced backdrop filters, while theme transitions are handled via managed CSS variables to ensure smooth color shifting during environment changes.

## **📜 License**

This project is licensed under the **MIT License**.

**Designed and Built with ❤️ by [Anuj Tiwari](https://anujtiwari.vercel.app/)**
