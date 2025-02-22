# **Snake Game (C - Linux)**  

### **Overview**  
This project is a **classic Snake game** implemented in **C**, designed to run on **Linux terminals**. It features smooth movement, dynamic gameplay, and score tracking, all handled using minimal system resources. The game uses **NCurses** for rendering and provides a retro gaming experience.  

### **Features**  
✅ **Classic Snake gameplay** with real-time movement  
✅ **NCurses-based UI** for smooth rendering in the terminal  
✅ **Collision detection** for walls and self-hit scenarios  
✅ **Dynamic food spawning** to increase score and snake length  

### **Technologies Used**  
- **C Programming** (Core logic and game mechanics)  
- **NCurses Library** (Terminal-based rendering)  
- **POSIX System Calls** (For input handling and timing)  

### **Installation & Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Snake-Game.git
   cd Snake-Game
   ```
2. Install NCurses (if not already installed):  
   ```bash
   sudo apt-get install libncurses5-dev  
   ```
3. Compile and run the game:  
   ```bash
   gcc snake.c -o snake -lncurses  
   ./snake  
   ```
4. **Controls:**  
   - **Arrow keys** to move  
   - **Q** to quit  

### **Future Enhancements**  
🔹 Add **difficulty levels** with increasing speed  
🔹 Implement **obstacles** to increase complexity  
🔹 Introduce **multiplayer mode** via shared memory  

### **Contributors**  
👤 **Sai Lohith D V S** – [GitHub](https://github.com/ItsHolyCow)  

### **License**  
Unlicensed.
