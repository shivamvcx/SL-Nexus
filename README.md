# SL-Nexus
---

SL-Nexus is a browser based rocketry toolkit for my eco-system called Silicon Labs. Similar projects like these can be found on my github profile like [SL-OmniTrack](https://github.com/shivamvcx/SL-OmniTrack) and main rocket project which is [SL-60T-mk1](https://github.com/shivamvcx/SL-60T-mk1)

---

## What does it do?

[SL-OmniTrack](https://github.com/shivamvcx/SL-OmniTrack)'s avionics bay sits inside rocket during flight and collect datas from multiple sensors and then send all to ground station module of it. Ground station parse those data and save it in a clean `.csv` file.

This project mainly target that `.csv` file and extract important information from it and shows to the user. Some examples will be -
  
### 1. Flight Summary
- Apogee
- Max velocity (with time)
- Max acceleration
- Total flight time
- Avg descent rate (in last 10/5/2 sec)
- Events detected (not sure if'll be able to do it hehe :))
  
### 2. Core Plots
- Altitude vs Time
- Velocity vs Time
- Acceleration vs Time

** I have planned more things but not finalized it so it'll be in [scope.md](/docs/scope.md)  