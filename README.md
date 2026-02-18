---

# 🌊 Submarine Sonar Simulator – *“Eyes in the Depths”*

A sonar interface simulation inspired by the tension of the **Cuban Missile Crisis**, where underwater detection was crucial.  
This project recreates a **minimalist yet functional sonar system** using **Java Swing**, paying tribute to ingenuity under pressure and the pursuit of vital information.

---

##  Features
- **Intuitive GUI**: Built with `javax.swing`, displayed in a full-screen borderless `JFrame`.  
- **Continuous Animation**: Radar beam updated every 50 ms with `ActionListener` for smooth scanning.  
- **Clear Visual Representation**:
  - Black background → deep ocean environment.  
  - Green concentric rings → sonar distance ranges.  
  - Radial lines every 45° → cardinal/intercardinal directions.  
  - Rotating semi-transparent green beam → scanning for targets.  
- **Precise Motion Logic**: Beam angle increments by 2° per update for constant rotation.  

---

## 📂 Project Structure
```
Submarine/
│── src/
│   ├── main/java/
│   │   ├── module-info.java
│   │   └── radarSubmarine/
│   │       ├── package-info.java
│   │       └── radar_Submarine_sonar.java
│   └── test/java/
│── docs/
│   └── sonar_preview.png
│── LICENSE
│── README.md
```

---

##  How to Run
### Prerequisites
- **Java Development Kit (JDK) 11+** (modules required).  

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/GabrielSantana1996sp/Submarine.git
   cd Submarine
   ```
2. Compile:
   ```bash
   javac -d out src/main/java/module-info.java src/main/java/radarSubmarine/*.java
   ```
   *(If using modules, adjust with `--module-source-path` as needed.)*
3. Run:
   ```bash
   java --module-path out -m Submarine/radarSubmarine.radar_Submarine_sonar
   ```
4. The sonar interface will launch in full screen.

---

##  Purpose
This project demonstrates:
- **Java Swing graphics** with `Graphics2D`.  
- **Animation handling** via `Timer` and `ActionListener`.  
- **Modular Java project structure**.  

---

## Contributing
1. Fork the project.  
2. Create a feature branch (`git checkout -b feature/NewFeature`).  
3. Commit changes (`git commit -m 'Add new feature'`).  
4. Push to branch (`git push origin feature/NewFeature`).  
5. Open a Pull Request.  

---

## License
This project is licensed under the **Apache-2.0 License**.  
---

## Author
Developed by **Gabriel Santana**  
Contact: GabrielSantana1996sp on GitHub
---
