Link to tutorials : https://drive.google.com/drive/folders/1nqxfuD7wAAD-HR2VoSw8K5kLOtLSeNfj

Mini Project: Fly a Simulated Drone in QGroundControl

You are required to launch a simulated drone and fly it through the map given to you.

Setup
Install Ubuntu 22.04 (or WSL2 on Windows)
Install PX4 and run the simulator using make px4_sitl gz_x500
Install QGroundControl and confirm it connects to the simulated drone automatically
Manual flight
Arm the drone and take off to 10 m
Fly it around using the virtual joystick or by clicking on the map
Land safely
Mission flight
Using the map given to you, plan a mission in QGC that visits checkpoints A, B and C in order
Hover for 5 seconds at each checkpoint
End the mission with Return to Launch
Safety
Add a geofence around the flying area
Mark the no fly zone shown on the map and make sure your path avoids it
Bonus
Write a Python script using MAVSDK that flies the same mission without touching QGC
Submission
Screen recording of the full mission
Your saved .plan file
Flight log (.ulg) uploaded to PX4 Flight Review, with a screenshot of the flight path
