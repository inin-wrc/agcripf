# Risk-inspired Aerial-ground Collaborative Path Finding in Unknown Off-road Environments

# System Overview
![System Overview](https://github.com/inin-wrc/agcripf/blob/main/Images/system-framework.png)

# Simulation Experiments
## Simulation Setup
(1) Terrain models

The normal terrain model was manually designed by using terrain generator software. The complex terrain model was generated by remote sensing terrain data.
<p>
  <img src="Images/normal.png" alt="normal" width="20%" />
  <img src="Images/noram-cloud.png" alt="normal-cloud" width="21%" />
  <img src="Images/complex.png" alt="comlex" caption="far" width="20%" />
  <img src="Images/complex-cloud.png" alt="complex-cloud" width="21%" />
</p>

(2) Robot models

The UAV model was an open-source model called iris and was equppied with a downward solid-state LiDAR called Livox-Mid360. The UGV model was SCOUT MINI which was produced by AGILE·X and carried a VLP-16 LiDAR with 0.1m∼30m measurement range and 10Hz data frequency
<p>
  <img src="Images/ugv-model.png" alt="ugv-model" width="30%" />
  <img src="Images/uav-model.png" alt="uav-model" width="32%" />
</p>

## Some Demos
(1) Task1
<p>
  <img src="Gifs/1_FAR.gif" alt="far"  width="30%" />
  <img src="Gifs/1_Zhang.gif" alt="zhang" width="30%" />
  <img src="Gifs/1_Ours.gif" alt="ours" width="30%" />
</p>
(2) Task2
<p>
  <img src="Gifs/FAR.gif" alt="far"  width="30%" />
  <img src="Gifs/Zhang.gif" alt="zhang" width="30%" />
  <img src="Gifs/ours.gif" alt="ours" width="30%" />
</p>



# Real-world Experiments
## Hardware Setup
The UAV was equipped with a NVIDIA Jetson Xavier NX and a downward Livox-mid360 solid-state LiDAR. The data rate of the LiDAR was set to 10Hz for aerial terrain risk mapping. The UGV was equipped with the NVIDIA Jetson AGX Xavier, a 3D Velodyne-16 LiDAR with 10 Hz and an IMU with 400Hz measurements. Long range Wi-Fi was applied to establish the communication between the robots. 
<p>
  <img src="Images/ugv-real.png" alt="ugv" width="32%" />
  <img src="Images/uav-real.png" alt="uav" width="30%" />
</p>

## Real-world Test
<p>
  <img src="Gifs/real-world-single-ugv.gif" alt="zhang" width="45%" />
</p>

<p>
  <img src="Gifs/real-world-uav-ugv.gif" alt="zhang" width="45%" />
</p>
