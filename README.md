
<!-- <div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/acc_vehicle_simulation.gif">
</div> -->
<!-- <div style="display: flex; justify-content: center;">
    <div style="margin: 10px;">
        <img src="assets/acc_vehicle_simulation.gif" alt="Simulation 1" style="width: 200px;">
    </div>
    <div style="margin: 10px;">
        <img src="assets/vehicle_overtaking.gif" alt="Simulation 2" style="width: 200px;">
    </div>
</div> -->
<p align="center">
  <img src="assets/acc_vehicle_simulation.gif" alt="Simulation 1" width="400" />
  <img src="assets/vehicle_overtaking.gif" alt="Simulation 2" width="400" />
  <img src="assets/case5_traj_gif.gif" alt="Simulation 3" width="400" />
  <img src="assets/predictions_gif.gif" alt="Simulation 4" width="400" />
</p>

## 📊 Results
### 📈 Adaptive Cruise Control
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/acc_vehicle_simulation.gif">
</div>
<div style="width: 80%; text-align: center;">
      <img style="width:80%" src="assets/acc_vehicle_velocity.png">
</div>

### 📈 Trajectory tracking (using Linear MPC)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/vehicle_traj_track.gif">
</div>

### 📈 Car Overtaking (using Non-Linear MPC)
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/vehicle_overtaking.gif">
</div>
<div style="width: 75%; text-align: center">
      <img style="width:75%" src="assets/trajectory.png">
</div>

### 📈 Drag Racing (using Non-Linear MPC)
- Case 1:
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/case1_traj_gif.gif">
</div>
<div style="height: 250%; text-align: center">
      <img style="height: 75px; width: 600px;" src="assets/case1_traj.png">
</div>

- Case 2:
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/case2_traj_gif.gif">
</div>
<div style="height: 250%; text-align: center">
      <img style="height: 100px; width: 600px;" src="assets/case2_traj.png">
</div>

- Case 3:
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/case3_traj_gif.gif">
</div>
<div style="height: 250%; text-align: center">
      <img style="height: 100px; width: 600px;" src="assets/case3_traj.png">
</div>

- Case 4:
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/case4_traj_gif.gif">
</div>
<div style="height: 250%; text-align: center">
      <img style="height: 150px; width: 600px;" src="assets/case4_traj.png">
</div>

- Case 5:
<div style="width: 100%; text-align: center; margin:auto;">
      <img style="width:100%" src="assets/case5_traj_gif.gif">
</div>
<div style="height: 250%; text-align: center">
      <img style="height: 150px; width: 750px;" src="assets/case5_traj.png">
</div>

### 📈 Image Classification (Cars vs Person vs None)
- Challenging because low-resolution 32x32 blurry RGB images...still achieved 90% accuracy

<div style="width: 75%; text-align: center">
      <img style="width:75%" src="assets/image_classification.jpg">
</div>

### 📈 Object Detection (Traffic sign Detection)
- Achieved ~48 mAP with an average FPS of 43

<div style="width: 75%; text-align: center">
      <img style="width:75%" src="assets/object_detection_gif.gif">
</div>

### 📈 Scene segmentation (Comprising 14 classes from urban scenario + background class)
- Achieved 81.2 mIoU

<p align="center">
  <img src="assets/real_gif.gif" alt="Simulation 1" width="400" />
  <img src="assets/predictions_gif.gif" alt="Simulation 2" width="400" />
</p>



