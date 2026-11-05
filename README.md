Link to tutorials : https://drive.google.com/drive/folders/1nqxfuD7wAAD-HR2VoSw8K5kLOtLSeNfj

# Mini Project: Fly a Simulated Drone in QGroundControl

You are required to launch a simulated drone and fly it through the map given to you.

1. Setup
   1. Install Ubuntu 22.04 (or WSL2 on Windows)
   2. Install PX4 and run the simulator using `make px4_sitl gz_x500`
   3. Install QGroundControl and confirm it connects to the simulated drone automatically
2. Manual flight
   1. Arm the drone and take off to 10 m
   2. Fly it around using the virtual joystick or by clicking on the map
   3. Land safely
3. Mission flight
   1. Using the map given to you, plan a mission in QGC that visits checkpoints A, B and C in order
   2. Hover for 5 seconds at each checkpoint
   3. End the mission with Return to Launch
4. Safety
   1. Add a geofence around the flying area
   2. Mark the no fly zone shown on the map and make sure your path avoids it
5. Bonus
   1. Write a Python script using MAVSDK that flies the same mission without touching QGC
6. Submission
   1. Screen recording of the full mission
   2. Your saved `.plan` file
   3. Flight log (`.ulg`) uploaded to PX4 Flight Review, with a screenshot of the flight path

---

# Hackathon: Drone Delivery Run

Teams of 3 to 4. Duration: 6 hours. Everyone uses the same simulator setup as the mini project.

1. Problem statement
  
