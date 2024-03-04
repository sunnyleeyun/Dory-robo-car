<img src="https://github.com/sunnyleeyun/Dory-robo-car/assets/20850892/2148b7ad-ac7f-4117-a4aa-ce9d354c75fd" alt="Dory Robot" align="right" width="100">

# Dory - Self-Driving Robot


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Project Overview](#project-overview)
- [License](#license)

## Introduction

Dory is a self-driving robot that evolves through multiple phases, starting from a basic kit assembly to becoming a miniature self-driving car. The goal for this project is to touch base on different autonomous vehicles tech and hands-on building them! This README provides an overview of the project, its goals, and guidance on the upcoming phases, showcasing the evolution of Dory from a basic kit assembly to a miniature self-driving car.

## Features

- Kit assembly with wheels, breadboard, engines, and battery case.
- Motion-activated guard robot
- Line-tracking robot
- Light-tracking robot
- Obstacle-avoiding robot
- Miniature self-driving car

## Project Overview

### Phase 1: Kit Assembly [8 hours]
In this phase, I assemble the basic robot kit named Dory.

[![Kit Assembly](https://markdown-videos-api.jorgenkh.no/youtube/bzxTaA192z4)](https://youtu.be/bzxTaA192z4)

*Watch Dory's Kit Assembly.*

---

### Phase 2: Motion-Activated Guard Robot [8 hours]
Transform Dory into a motion-activated guard robot. This phase focuses on implementing motion detection and response mechanisms. Begin by assembling the circuit, mounting the PIR (Passive Infrared) sensor, and conducting thorough testing to ensure optimal functionality.

[![Motion-Activated Guard Robot](https://markdown-videos-api.jorgenkh.no/youtube/tmjtvHnfMyI)](https://youtu.be/tmjtvHnfMyI)

*See Dory as a Motion-Activated Guard Robot in action.*

#### Next Steps:
- [x] The PIR sensor is very sensitive to movements. The next plan is to create a blocker for it with toilet tubes to block the side views so that the sensor can focus on the views in front of the car.

---

### Phase 3: Line-Tracking Robot [16 hours]
Implement line-tracking algorithms with IR sensors, detecting white and black, and spinning specific wheels accordingly to enable Dory to follow predefined paths.

[![Line-Tracking Robot](https://markdown-videos-api.jorgenkh.no/youtube/kHvJrKbQ_h0)](https://youtu.be/kHvJrKbQ_h0)


#### Debugging Process:

**Observations:** 
- The sensors were not turning a specific wheel but activating both wheels.

**Issues:** 
- Previous project wires were not removed, causing interference.


<img src="https://github.com/sunnyleeyun/Dory-robo-car/assets/20850892/c1948292-2c80-461a-80e5-445c63345484" alt="Battery Case" align="right" width="100">
<img src="https://github.com/sunnyleeyun/Dory-robo-car/assets/20850892/1ab9032f-a311-4e0b-a117-9227e2718b74" alt="Additional Wires" align="right" width="100">
<img src="https://github.com/sunnyleeyun/Dory-robo-car/assets/20850892/4b3a6254-276f-443f-88af-c56853aae331" alt="Multimeter" align="right" width="100">

**Solutions:**
1. **Adjustments for Speed:**
   - Adjusted the battery and resistor to smaller ohms to slow down the robot.
3. **Connection Verification:**
   - Utilized a multimeter and crocodile clips to ensure the connection status of each wire.
   - Checked each wire individually for potential issues, such as a disconnected jump wire, a depleted battery, or a malfunctioning sensor.
5. **Wire Removal and Checks:**
   - Found an additional jump wire from a previous project connecting both motors, removed unnecessary wires, and performed thorough checks.
7. **Track Redesign:**
   - Initially used a whiteboard, but it didn't work well with the IR sensor, which requires the detection of infrared (IR) light.
   - Considered line width, ensuring it wasn't too wide or too slim for optimal sensor performance.
   - Switched to drawing the line on normal white paper for better sensor compatibility.
8. **Positioning of IR Sensor:**
   - Encountered challenges in stabilizing the IR sensor due to the dynamic height of the sensor to the ground, influenced by the ground texture and stability.
   - Balancing the need for flexibility in sensor adjustment with the challenge of achieving a precise height for optimal results.
   - Experimented with additional stabilization methods to find an effective approach.

#### Next Steps:
- [ ] As the project progresses towards assembling all components into a miniature self-driving car, the IR sensors shall be better stabilized.


---

### Phase 4: Light-Tracking Robot (Coming Soon!)
Enhance Dory's capabilities by making it capable of tracking and following light sources. **Expected Launch: Mar. 05**

*Watch Dory's Light-Tracking capabilities.*

---

### Phase 5: Obstacle Avoiding Robot
Equip Dory with obstacle avoidance capabilities using sensors to navigate its environment.

*Observe Dory's Obstacle Avoidance capabilities. (Coming Soon)*

---

### Phase 6: Miniature Self-Driving Car
The final phase involves turning Dory into a miniature self-driving car. Implement computer vision and machine learning techniques for autonomous navigation.
*Experience Dory as a Miniature Self-Driving Car. (Coming Soon)*

---

## License

This project is licensed under the MIT License - see the [LICENSE.md]([link-to-license.md](https://github.com/sunnyleeyun/Dory-robo-car/blob/main/LICENSE)) file for details.
