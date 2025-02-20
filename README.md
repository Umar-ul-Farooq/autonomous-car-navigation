# Autonomous Car Navigation Project

## **Project Overview**
This project involves developing an autonomous car in Unity that navigates a track with various obstacles. The primary objective was to create a self-driving system capable of completing the track efficiently, avoiding collisions, and maintaining a smooth trajectory.

## **Project Details**
- The autonomous car utilizes built-in Unity physics and sensors to perceive its environment and make navigation decisions.
- The system was designed to optimize movement using Unity's **WheelColliders** for realistic motion and control.
- **Raycast Sensors** were implemented to detect proximity to track edges and obstacles, including:
  - `FRS` (Front Ray Sensor) - Detects forward obstacles.
  - `L1S`, `L2S`, `L3S` - Left-side proximity detection.
  - `R1S`, `R2S`, `R3S` - Right-side proximity detection.
  - `ORS` (Orientation Sensor) - Tracks the robot's angular position.
- The car adjusts its speed dynamically based on the terrain and upcoming turns to ensure smooth navigation.
- A combination of proportional steering and speed adjustments was applied to maintain an optimal trajectory while avoiding obstacles.
- The project focuses on achieving real-time performance and efficiency, ensuring the car successfully completes the track in a reasonable time.
- Users can freely **add cubes or obstacles** in the Unity scene to observe how the car reacts and adjusts its trajectory accordingly.

## **Setup**
### **Requirements**
- Unity (latest stable version)
- C# Development Environment (e.g., Visual Studio, Rider)
- Git (for version control)

### **Installation & Running the Project**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/autonomous-car-navigation.git
   cd autonomous-car-navigation
   ```
2. **Open the Provided Unity Project**
   - Download and extract the provided `cw2.zip` file.
   - Open Unity Hub and select **Open Project**.
   - Navigate to the extracted folder and open the project in Unity.
3. **Copy and Replace the Script**
   - Inside the Unity project, locate `RobotController.cs`.
   - Copy the content of the extracted `.txt` file and paste it into `RobotController.cs`.
4. **Run the Simulation**
   - Press the **Play** button in Unity to start the autonomous car simulation.
   - Experiment by adding cubes or obstacles to test the car's behavior and response to new challenges.

## **Video Demonstration**
A screen recording of the autonomous car completing the track has been uploaded to this repository to showcase its performance.

---

This project demonstrates the effective use of AI techniques in autonomous vehicle navigation within a simulated environment.
