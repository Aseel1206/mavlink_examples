<h2>SITL Setup</h2><br><br>
<b>Steps:</b><br>
1. cd ardupilot<br>
2. cd ArduCopter<br>
3. ../Tools/autotest/sim_vehicle.py --map --console <br>
4. ../Tools/autotest/sim_vehicle.py --map --console -l 13.0310227,77.5654036,925.640000,90 (Change home location)
<br><br>


<h2>Python Scripts</h2><br><br>
<b>1. Take Off</b>

  Perform a simple take-off and landing operation.<br>

  Steps:

  -Change Mode: Set the drone mode to GUIDED.

  -Arm the Drone: Arm the motors.

  -Set Altitude: Command the drone to ascend to 10 meters.

  -Land: Once the desired altitude is reached, initiate landing.<br><br>

<b>2. Circle</b>

  Make the drone fly in a circular pattern.<br>

  Steps:

  -Arm the Drone: Arm the motors.

  -Take Off: Ascend to a safe altitude.

  -Get Current Location: Retrieve the drone’s current GPS coordinates.

  -Set Parameters:

  -Define the radius of the circle.

  -Calculate and set the waypoints for the circular path.

  -Execute Command: Instruct the drone to perform 2 laps of the circle.<br><br>

<b>3. Mission</b>

  Plan and execute a mission with predefined waypoints.<br>

  Steps:

  -Change Waypoint File Location: Prepare the waypoint file.

  -Create Waypoints:

  -Use Mission Planner to design the mission path.

  -Save the waypoint file.

  -Upload Waypoints: Upload the mission waypoints to SITL (Software In The Loop).
  
  -Arm the Drone: Arm the motors.
  
  -Set Mode: Change the drone mode to AUTO.
  
  -Start Mission: Begin the mission and monitor the drone as it follows the uploaded waypoints.<br><br>
