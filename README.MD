This application is build with HTML, CSS, and Javascript.
To Run the Application, we can choose any of the following ways:
1) We can Run the file directly in "Chrome" or "Mozzila Firefox".
2) Launch Visual Studio by Installing "Extension" (i used chrome extension).
Here to see the output, we have to right click on the file then select "Preview in Default browser".

This application is related to scenario with vehicles. where we have create, display, update, delete Scenario and Vehicle. Scenario can have multiple vehicles.

This application contain Navigation bar with Four Pages.

1) Add Scenario 
- The scenario have following fields: Scenario id, Scenario name, Scenario Time.
- Also we have Add, Reset, GoBack Buttons.
   By Clicking Add button all the data mentioned in this fields will be stored in "Local Storage" and viewed in "All Scenarios" page in the form of Table.

2) All Scenarios
- Here we can see all the created scenarios in the form of table with Add Vehicle, Edit, Delete data option.
- Also we have New Scenario, Add Vehicle, Delete All buttons.
    By Clicking New Scenario, we can create a New Scenario.
    By Clicking Add Vehicle, We can add new vehicle.
    By Clicking Delete All, All the data will be Deleted from the Local Storage.

3) Add Vehicle
- Here we have following Fields: Scenario List, Vehicle name, Initial Position X, Initial Position Y, Speed and Direction.
    Scenario List: we can see all the created Scenario Names in the form of dropdown where we have to select one.
    Vehicle name, Position X, Position Y, Speed: User can give the values according to them.
    Direction: User can see 4 options Towards, Backwards, Upwards, Downwards in the form of Dropdown.
- Also we have Add, Reset, GoBack Buttons.
    By Clicking Add button all the data mentioned in this fields will be stored in "Local Storage" and viewed in Home page in the form of Table.

4) Home Page 
- Here we have Scenario Field which contain created Scenario Names in form of drop down which should be seleted.
    Based on the Scenario Name we will get the related data in the form of table.
- Also we have Start Simulation and Stop Simulation buttons.
    By Clicking Start Simulation, the vehicle will move Based on Scenario and vehicle parameters. We can have the look of simulation in the form of Graph below.
    By Clicking Stop Simulation, Simulation will be Stopped.

