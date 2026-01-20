# AeroArcadia - Rocket Modelling and Analysis 
<h2>Description</h2>

**AeroArcadia** is an iterative aerospace project focused on the development of an Active Thrust Vectoring (TVC) rocket platform. The project evolved from a basic PLA-printed proof-of-concept to a high-performance Carbon Fiber vehicle, utilizing data-driven design to double mission performance.
<br />

<h3>Technical Skills & Competencies Developed</h3>

**Mechanical Design & Engineering**
* **High-Performance Composites:** Gained experience in structural application of Carbon Fiber, focusing on strength-weight optimization and bonding techniques for high-vibration environments.
* **Thermal Management:** Identified material failure points in PETG prototypes and pivoted to high-temperature composites to withstand motor heat soak.

**Simulation & Analysis**
* **Flight Dynamics Modeling:** Utilized Python and OpenRocket to predict apogee and descent rates, achieving high fidelity between simulated models and actual flight telemetry.

**Systems & Robotics** 
* **Active Rocvery Systems:** Developed an independent energetic ejection system (Black Powder) triggered by an onboard altimeter, decoupling recovery from propulsion timing for increased reliability.
* **Prototyping & Fabrication:** Proficient in precision machining, 3D printing, and composite layup to translate CAD designs into flight-ready hardware.


<h2>Prototype 1</h2>
<h3>Initial Design Choices</h3>

* **Material:** Polyethylene Terephalate Glycol (PETG)
  * Justication: Rapid iteration for initial fit-testing and aerodynamic shell.

* **Motor:** Estes C5-3 Motor
  * Justification: Provided a low-cost, low-impulse platform to test basic flight stability.

* **Recovery:** Integrated Motor Ejection (Nosecone)
  * Justification: Utilized the motor's built-in black powder delay; minimized weight and complexity for the first flight.

<p align="center">
<br/>
<img src="https://i.imgur.com/gWxkYmH.png" height="50%" width="50%" alt="CAD Model of AeroArcadia"/>
<br/>

<h2>Results of Prototype 1</h2>
<p align="center">
<br/>
<img src="https://i.imgur.com/TPAQndN.png" height="70%" width="70%" alt="Simulation Performance AeroArcadia"/>
<br/>

* **Max Altitude(Apogee):** 375 Meters
  * 

* **Total Flight Time:** 19 Seconds

* **Airframe Efficient:** Validated basic aerodynamic stability and drag coefficient ($C_d$) predictions.

* **Recovery:** Integrated motor ejection fired post-apogee; identified need for independent deployment to reduce structural shock.

<h2>Prototype 2</h2>
<p align="center">
<br/>
<img src="https://i.imgur.com/4BfQbhG.png" height="50%" width="50%" alt="CAD Model of AeroArcadia"/>
<br/>

* **Material:** Carbon Fiber
  * Justication: Maximized stiffness-to-weight ratio to handle the high axial loads of the D12-3 and prevent aeroelastic flutter.

* **Motor:** Estes D12-3 Motor
  * Justification: Higher total impulse required to maintain a > 5: 1 thrust-to-weight ratio for active vectoring control.

* **Recovery:** Integrated Motor Ejection (Nosecone)
  * Justification: Decoupled recovery from motor timing; utilized an onboard altimeter for precise apogee deployment.

<h2>Results of Prototype 2</h2>
<p align="center">
<br/>
<img src="https://i.imgur.com/U2x7bxi.png" height="70%" width="70%" alt="Simulation Performance AeroArcadia"/>
<br/>

* **Max Altitude(Apogee):** 665 Meters (**+77% increase**)
  * 

* **Total Flight Time:** 26 Seconds (**+37% increase**)

* **Airframe Efficient:** CF airframe maintained high rigidity during the 30N peak thrust event of the D12-3 motor.
  
* **Recovery:** Implemented active black powder ejection via onboard altimeter; achievd consistent deployment at $V_z$ = 0.
