# Some Possible Starting Points
Presented here are some projects that you can use to guide your submission. These are merely provided to give participants ideas as to how they can fulfill the rubric requirements.

## Cube Satellite
This submission would use the CubeSat standard dimensions to constrain a basic communications satellite. 
* Sketches and Relations: Basic sketches for each of the subsystem components, including the electrical power, data handling, attitude determination, and communication elements.
* Part Modeling: Basic models for each of the aforementioned components, specifically covering the design of the frame within the Design Report.
* Assembly Modeling: Exploded-view of each of the components slotting into the frame, with a couple section views to see the internal parts.
* Engineering Drawings: Drawings for each of the components, including a BOM.
* Parametric Design and Configurations: Multiple configurations for the antenna, conforming to different data transmission bands. These have different mounting requirements, so the differences in the whole assembly are compared via an assembly configuration.
* Electrical CAD: Wiring connections between each of the parts, using specific space-grade wiring and connections. 
* Simulation: A basic thermal simulation for the electrical and heat dissipation elements. 

## Robotic Arm
This project focuses on the design of a simple, two-degree-of-freedom mechanical gripper arm for a mobile robotics platform.
* Sketches and Relations: Detailed sketches for the mechanical linkages and jaw profiles.
* Part Modeling: Modeling the servo/motor mount bracket and the main linkages, using features like sweeps or lofts for weight-saving profiles.
* Assembly Modeling: Assembly of the two primary linkages, the fixed mount, and the servo motor, using advanced mates (like Limit Angle) to define the mechanism's range of motion.
* Engineering Drawings: Detailed manufacturing drawing of the main mounting bracket, including cut-out views and a BOM.
* Geometric Dimensioning and Tolerances: Define the Datum Reference Frame and apply a Position tolerance to the bolt hole pattern for the motor mount, ensuring the motor shaft is correctly aligned with the input linkage.
* Simulation: Run a simple Static Analysis (FEA) on the gripper jaw while applying a maximum clamping force to check the Factor of Safety against failure.

## Quadcopter Drone
This submission would focus on designing the frame and motor mounts for a small, customizable quadcopter.
* Sketches and Relations: Sketches for the motor mounting patterns and internal electronic board placement, ensuring all necessary dimensions are driven by equations.
* Part Modeling: Design the four primary arms and the top/bottom plates of the frame using surface or complex solid modeling to achieve an aerodynamic, lightweight profile.
* Assembly Modeling: Assemble the main frame structure and mount the four motors and propellers.
* Engineering Drawings: Drawing of the main frame plate showing section views for internal electronic mounting bosses, complete with a BOM.
* Parametric Design and Configurations: Create configurations to show the drone with different arm lengths, with all associated part dimensions updating automatically via equations.
* Sheet Metal: Design the central electronics bay housing as a sheet metal part, using features like edge flanges and hems to define mounting and cable routing points. 

## Fixed Wing Drone
This project involves modeling a specific structural element, like the wing fairing or tail section that requires smooth geometry.
* Sketches and Relations: Use 3D sketches and guide curves to define the aerodynamic profile of the chosen section.
* Part Modeling: Model the main body section. Use draft analysis to ensure the part is manufacturable via molding or casting processes.
* Assembly Modeling: Assemble the tail section to a portion of the main fuselage and confirm structural clearances.
* Engineering Drawings: Drawing of the primary wing attachment interface.
* Surfacing: Create the primary geometry (wing-to-fuselage fairing) using Boundary Surface and Knit Surface features, ensuring curvature continuity for a smooth transition.
* Electrical CAD: Create the wiring harness for the drone, ensuring that enough space is provided to route wires to their proper locations.

## Ergonomic Device Mount
This submission designs a comfort-focused bracket or mount that conforms to a specific body part outline.
* Sketches and Relations: Use splines and curve-driven patterns to define the ergonomic contact surface.
* Part Modeling: Design the mount using multi-body modeling techniques and heavy use of variable fillets for comfort.
* Assembly Modeling: Assemble the two-part mount and use limit distance mates to define the adjustable range of the device.
* Engineering Drawings: Drawings of the primary mounting clasp showing critical dimensions and fit.
* Geometric Dimensioning and Tolerances: Apply GD&T to the small feature that holds the sensor block, using a Position tolerance relative to the primary datum to ensure the sensor's accuracy is maintained relative to the body.
* Surfacing: Model the body-contact side of the mount using a Boundary or Fill Surface to ensure a smooth, comfortable interface. Document the Curvature Analysis to prove quality.

## FPGA Enclosure
Design a compact, protective housing for a high-performance FPGA circuit board, focusing on thermal management and manufacturability. 
* Sketches and Relations: Detailed sketches for the mounting hole patterns and cutouts for I/O ports.
* Part Modeling: Design the enclosure body with integrated heat sink fins or airflow vents.
* Assembly Modeling: Assemble the enclosure with the FPGA board and any necessary thermal components (fans/heat pipes). Use in-context modeling to size the enclosure walls relative to the PCB.
* Engineering Drawings: Manufacturing drawing of the enclosure base, including a section view to show internal clearances.
* Electrical CAD: Model the cable routing path for the main power input and a data port, ensuring the bend radius is respected and providing adequate clearance within the tight enclosure.
* Sheet Metal: Design the main chassis of the enclosure as a sheet metal part, including vent features for heat dissipation and generating the necessary Flat Pattern.
