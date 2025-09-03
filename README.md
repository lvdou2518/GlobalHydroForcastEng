# GRiFFS: The Global River Flow Forecasting System
## Introduce:
The Global River Flow Forecast System (GRiFFS) is a web-based GIS river basin simulation cloud computing platform developed using the Adobe RIA (Rich Internet Application) framework Flex. Registered users can browse and query numerical weather prediction data and animations from different institutions through this platform. They can create simulation scenarios in regions of interest, set scenario parameters, select target river reaches and computational methods. After constructing a scenario, users can submit it online to a high-performance computing (HPC) cluster for simulation. The simulation results (discharge and water level processes) can be displayed in graphical form. Users can also configure the system to perform daily flood simulations based on rolling forecast rainfall data.

### Key functionalities include:
- Rainfall Forecast Animation Playback: Allows users to view numerical weather prediction data from different institutions.
- Create Scenario: Enables users to create simulation scenarios.
- Set Parameters: Allows users to configure simulation start and end times, warm-up periods, rainfall data parameters, runoff models, and river channel models.
- Select Simulation Area: Users can interact with the GIS map to select simulation areas and target river reaches by clicking or drawing rectangles.
- Rolling Simulation: Supports configuration of scenarios to perform daily rolling simulations based on updated weather forecast data.
- Submit Scenario: Submits the selected scenario to the HPC cluster for computation.
- Result Visualization: Displays simulation results graphically, including discharge and water level processes at basin outlets and target river reaches.
