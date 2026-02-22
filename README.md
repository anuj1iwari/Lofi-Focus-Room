🎧 Lofi Focus Room
A high-performance, minimalist productivity web application designed to facilitate deep work through a combination of the Pomodoro technique and immersive ambient soundscapes.

🚀 Live Demo
https://lofi-focus-room.vercel.app/

✨ Features
Immersive Ambient Mixer: Mix and match high-quality sounds including Rain, Fire, Cafe, and Nature.

Pomodoro Engine: Built-in Focus and Break cycles (25/5 minutes) with visual countdowns.

Dynamic Theme Engine: The UI aesthetic (background and accent colors) automatically adapts based on the active audio environment.

Goal Management: A real-time task tracker to manage objectives during sessions.

Glassmorphism UI: A modern, translucent interface designed for a distraction-free experience.

Fully Responsive: Optimized for desktop, tablet, and mobile orientations.

🛠 Tech Stack
Frontend: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (Utility-first framework)

Audio Logic: Web Audio API (for low-latency, concurrent stream management)

Fonts: Google Fonts API (Varela Round, Space Mono, Playfair Display)

🏗 Technical Deep Dive
Audio Engineering
The app leverages the Web Audio API to handle multiple concurrent audio streams. To comply with modern browser autoplay policies, I implemented an initialization overlay that "unlocks" the AudioContext upon the first user interaction, ensuring a seamless audio experience.

State Management
I developed a custom JavaScript engine to synchronize the Pomodoro timer state with the UI. The timer handles transition logic between focus and break modes, triggering notifications and automatic mode switches.

Responsive & Adaptive Design
Using Tailwind CSS, the application utilizes a mobile-first approach. Visual depth is achieved through backdrop filters (Glassmorphism), and transitions are handled via CSS variables to ensure smooth color shifting when themes change.
