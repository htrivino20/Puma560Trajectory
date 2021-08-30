# Puma560Trajectory for a welding 6DOF manipulator

The project aims to explain and show three different interpolation methods on moving planning to weld a square piece. We used the Puma 560 Manipulator to simulate the motion. 

## Joint effector cartesian motion
The main differences on the end effector cartesian motion curves are shown below.

### Displacement vs step
![plot](./res/cart_dis.png)

### Velocity vs step
![plot](./res/cart_vel.png)

### Acceleration vs step
![plot](./res/cart_acc.png)

## Joints motion
Meanwhile the main differences on the joint motion curves are shown bellow.

### Displacement vs step
![plot](./res/joint_dis.png)

### Velocity vs step
![plot](./res/joint_vel.png)

### Acceleration vs step
![plot](./res/joint_acc.png)

## Trajectory animation

The resulting path is shown below.

### Polynomial interpolation
![plot](./res/polinomial_path.gif)

### Trapezoidal interpolation
![plot](./res/trapezoidal_path.gif)

### Screw Linear interpolation
![plot](./res/screw_linear_int_path.gif)
