# WRO 2026 Future Engineers – SJVL67

<center>
  <img width="600" height="600" src="https://github.com/user-attachments/assets/926b00a1-416a-4c51-b026-9647d3f717bc" />

  [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://www.youtube.com/@SJVL67)
</center>

---


---

##  **Table of Contents**
- [ 1. Complete Documentation Structure](#complete-documentation-structure)
- [ 2. The Team](#the-team)
- [ 3. Challenge Overview](#challenge-overview)
- [ 4. Our Robot](#our-robot)
- [ 5. Electronic Systems](#electronic-systems)
- [ 6. Mechanical Systems](#mechanical-systems)
- [ 7. Software Architecture](#software-architecture)
- [ 8. Performance Videos](#performance-videos)
- [ 9. GitHub Utilization & Development](#github-utilization--development)
- [ 10. License & Replication](#license--replication)

---

## 1. **Complete Documentation Structure** <a id="complete-documentation-structure"></a>

<div align="center">

## **DETAILED TECHNICAL DOCUMENTATION AVAILABLE**

### **Each folder contains comprehensive README documentation with specialized technical content**

| 📁 Folder | 🎯 Technical Content | 📖 Detailed Documentation |
|-----------|----------------------|---------------------------|
| **⚙ Models** | **Mechanical Engineering**<br>• 3D CAD designs<br>• Assembly instructions<br>• Gear system calculations | [🔗 Models Documentation](models/README.md) |
| **🔌 Schemes** | **Electrical Systems**<br>• Wiring diagrams<br>• Power management<br>• Component schematics & datasheets | [🔗 Schematics Documentation](schemes/README.md) |
| **💾 Source Code** | **Software Algorithms**<br>• Navigation logic<br>• Sensor fusion<br>• Control systems | [🔗 Software Documentation](src/README.md) |
| **👥 Team Photos** | **Team Documentation**<br>• Member profiles<br>• Development journey<br>• Competition preparation | [🔗 Team Photos Documentation](t-photos/README.md) |
| **🚗 Vehicle Photos** | **Vehicle Documentation**<br>• Multi-angle views<br>• Component labeling<br>• System integration | [🔗 Vehicle Photos Documentation](v-photos/README.md) |
| **🎥 Videos** | **Performance Validation**<br>• Challenge demonstrations<br>• Engineering tests<br>• System validation | [🔗 Performance Videos Documentation](video/README.md) |
| **📚 Other Resources** | **Technical References**<br>• Component images<br>• Development resources<br>• Additional documentation | [🔗 Additional Resources Documentation](other/README.md) |

</div>

---

## 2. **The Team** <a id="the-team"></a>

Team SJVL67 includes passionate students from Ecuador, guided by a coach. This is our **first year** competing in the WRO Future Engineers category, and each member brings unique skills to the project, from mechanical design to computer vision.

<div align="center">
<img width="447" height="447" alt="images (4)" src="https://github.com/user-attachments/assets/26bf3113-dde3-4416-90f8-930fe24a1e56" />
</div>

### **Members**
- **Eduardo Rivadeneira**  
  *Role*: Electronics, Mechanical Design, Strategy Integration  
  *Background*: Second Bach Student, Physics Area, Robotics club since 2022, American School of Guayaquil  
  *Born*: 2009, Ecuador

- **Henry Riera**  
  *Role*: Computer Vision Research, Strategy  
  *Background*: Second Bach Student, Physics Area, Robotics club since 2023, American School of Guayaquil  
  *Born*: 2010, Ecuador

- **Geovanny Li**  
  *Role*: Computer Vision Research, Strategy  
  *Background*: First Bach Student, Robotics club since 2023, American School of Guayaquil  
  *Born*: 2010, Ecuador

### **Coach**
- **Henry Cercado**  
  *Role*: Team Coach, Connector  
  *Background*: Teacher, Computer Science, Computer Science Engineer, American School of Guayaquil   
  *Born*: 1994, Ecuador


### **Team Journey Moments**


---

## 3. **Challenge Overview** <a id="challenge-overview"></a>
### 3.1 **Open Challenge**
<div align="center">

## 🏁 **WRO 2025 Future Engineers Challenges**

### **Two distinct autonomous navigation challenges testing vehicle intelligence and precision**

</div>

### - **Open Challenge**
<div align="center">

**Objective**: Complete three autonomous laps on dynamically configured tracks

| Aspect | Challenge | Our Solution |
|--------|-----------|--------------|
| **Track Variability** | Random internal wall placements | Adaptive path planning algorithms |
| **Navigation** | Unknown track layouts each round | Robust wall-following with corner detection |
| **Performance** | Consistent lap times across variations | Optimized PID control and sensor fusion |
| **Precision** | Maintain course in narrow lanes | High-accuracy steering and speed control |

</div>

### - **Obstacle Challenge**
<div align="center">

**Objective**: Navigate three laps with traffic sign compliance and precision parking

| Challenge Element | Requirement | Our Implementation |
|-------------------|-------------|-------------------|
| **Traffic Signs** | Red → Right bias<br>Green → Left bias | Real-time color detection with LAB colorspace |
| **Obstacle Avoidance** | Dynamic path adjustment | Smooth following at consistent distances |
| **Parking Maneuver** | Parallel parking after lap completion | Multi-stage parking with sensor validation |
| **Navigation** | Shortest path optimization | Efficient routing around obstacle combinations |
</div>

### 3.2 **Documentation Evaluation Framework**

<div align="center">

## **WRO 2025 Engineering Documentation Scoring (30 points total)**

| Scoring Area | Maximum Points | Our Documentation Coverage |
|--------------|----------------|---------------------------|
| **1. Mobility Management** | 4 points | Complete mechanical design, motor selection, steering system, assembly instructions |
| **2. Power & Sense Management** | 4 points | Power systems, sensor integration, wiring diagrams, component specifications |
| **3. Obstacle Management** | 4 points | Navigation algorithms, parking strategies, source code with detailed comments |
| **4. Pictures – Team and Vehicle** | 4 points | Multi-angle vehicle photos, team photos, component labeling |
| **5. Performance Videos** | 4 points | Complete challenge demonstrations with commentary and analysis |
| **6. GitHub Utilization** | 4 points | Version control, structured documentation, regular commits |
| **7. Engineering Factor** | 4 points | Custom design and manufacturing throughout the vehicle |
| **8. Overall Judge Impression** | 2 points | Clear communication enabling easy replication |
| **Total Documentation Score** | **30 points** | **(≈25% of total competition score)** |
</div>

### - **Key Evaluation Areas**
- **Performance and adaptability** in randomized track conditions
- **Precision in maneuvers**, especially parallel parking execution  
- **Comprehensive public engineering documentation** on GitHub with complete transparency
- **Custom design innovation** and manufacturing process documentation
- **Professional presentation** enabling effortless replication by other teams

**Scoring Philosophy**: Documentation is evaluated based on completeness, structure, and ease of replication - not comparison between teams. Each scoring area uses a 0-4 point scale where "Exceeds Expectations" requires not only enabling exact duplication but also providing improvement suggestions.

### - **Educational Objectives**
- **Advanced Computer Vision**: Real-world implementation of color space theory
- **Sensor Fusion**: Integrating multiple data sources for robust navigation
- **Control Systems**: Precision steering and speed control algorithms
- **Engineering Documentation**: Professional technical communication
- **Problem Solving**: Systematic approach to technical challenges
