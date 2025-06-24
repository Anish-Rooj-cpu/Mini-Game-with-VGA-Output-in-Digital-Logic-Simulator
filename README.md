🎮 Built a Mini Game with VGA Output in Digital Logic Simulator!

I'm excited to share a small project I worked on using Digital (by Neeman) — a logic-based game where a RED square moves on a VGA screen based on keyboard inputs (W, A, S, D)!


🛠 Key Features:

i) Real-time control using keyboard input module

ii) VGA monitor output (640×480\@60Hz) to display the moving square

>Modular design with:

 🔹 KeyboardControl subcircuit to decode key inputs

 🔹 VGA Timing subcircuit for HSync, VSync, active display area

 🔹 Logic comparators and counters to handle movement directions


💡 On reset, a red square appears at the centre of the screen, and you can control it like a simple game — moving up, down, left, right based on your keystrokes!


This was a fun exercise in integrating:

✔ VGA signal timing

✔ Keyboard decoding

✔ Logical control for motion


