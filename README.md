# SIT210-Project
Smart Plant Watering System.

The default threshold value for projectArgon's soil moisture is 2800.

If you wish to find out the average soil moisture for a different condition, please run the soilMoistRead file to
find out and change the threshold variable of the projecArgon code.

The projectArgon file is the main file in this repository that will run the system. It must be flashed onto a particle argon device.

The soil moisture sensor must be conntected to A1 and the motor to D2 of the Particle Argon.
If they're connected differently, update the motor and soilSensor variables of the porjectArgon file accordingly.

![Prototype Architecture](https://user-images.githubusercontent.com/54390998/83386913-2c304300-a42f-11ea-84ce-8a17eb30e4ec.jpg)
