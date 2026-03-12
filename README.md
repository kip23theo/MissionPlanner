# Mission Simulation Using Mission Planner

## Course
Drone Technology and its Transformative Applications

## Project Batch
Batch 94

## Institution
L&T EduTech  
Department of Electronics and Computer Engineering  
CHRIST (Deemed to be University), Bangalore

---

## Project Overview

This project demonstrates the simulation of a drone mission using **Mission Planner** integrated with the **ArduPilot SITL (Software-In-The-Loop) simulation environment**. The objective is to test and validate a complete drone mission virtually before real-world deployment.

The simulation includes configuration of mission parameters, creation of GPS waypoints, autonomous flight execution, and safe landing. By simulating the mission in a virtual environment, drone operators can verify mission logic, reduce operational risks, and improve mission planning efficiency.

---

## Objectives

- Configure mission parameters such as home location, altitude, waypoint radius, and loiter radius.
- Create a structured GPS waypoint-based flight path.
- Upload the mission to the autopilot using Mission Planner.
- Simulate drone takeoff, waypoint navigation, and landing using SITL.
- Monitor telemetry data including altitude, speed, battery voltage, and GPS status.
- Document the mission simulation results.

---

## Software Used

- **Mission Planner** – Ground Control Station for ArduPilot
- **ArduPilot SITL** – Software-in-the-loop simulation environment
- **GitHub** – Version control and project repository hosting

---

## Mission Plan

The simulated mission consists of the following sequence:

1. **Takeoff** – Drone ascends to 20 meters.
2. **Waypoint 1** – Navigate to the first GPS coordinate.
3. **Waypoint 2** – Continue flight to the second waypoint.
4. **Waypoint 3** – Navigate to the third waypoint.
5. **Landing** – Controlled descent and landing at the designated location.

The mission path forms a triangular flight pattern executed autonomously by the autopilot.

---

## Repository Structure
mission-planner-simulation
│
├── mission.waypoints
├── Mission_Simulation_Report.pdf
│
└── screenshots
├── missionplannerinterface.jpeg
├── waypoinconfig.jpeg
└── takeoff.jpeg
└── landing.jpeg


- **mission.waypoints** – Mission file containing GPS waypoint commands.
- **Mission_Simulation_Report.pdf** – Full project report.
- **screenshots/** – Visual documentation of the simulation stages.

---

## Simulation Results

The mission simulation was successfully executed using the SITL environment.  
The drone completed the entire flight path autonomously including:

- Automatic takeoff
- GPS waypoint navigation
- Stable flight trajectory
- Controlled landing

The simulation confirmed that the waypoint configuration and mission parameters were correctly interpreted by the autopilot.

---

## Key Features Demonstrated

- Autonomous waypoint navigation
- Mission planning using Mission Planner
- SITL-based drone simulation
- Telemetry monitoring and flight analysis
- Safe mission validation before real deployment


---

## References

1. ArduPilot Documentation – Mission Planner  
2. ArduPilot SITL Simulation Guide  
3. Drone Technology and its Transformative Applications – L&T EduTech Course Material

---

## Conclusion

This project demonstrates how mission simulation using Mission Planner and SITL provides a safe and efficient method to validate drone missions before real-world deployment. Simulation helps identify potential issues early, improves mission reliability, and enhances operator confidence in autonomous drone operations.
