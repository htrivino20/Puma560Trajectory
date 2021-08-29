# Puma560Trajectory for a welding 6DOF manipulator

The project aims to explain and show two different path methods of moving planning to weld a square piece. We used the Puma 560 Manipulator to simulate the motion. The resulting path is shown below.

## Polynomial interpolation
![plot](./res/polinomial_path.gif)

## Trapezoidal interpolation
![plot](./res/trapezoidal_path.gif)

The main differences on motion curves are shown below.

## Displacement vs step (Polynomial and trapezoidal interpolation)
![plot](./res/pol_tra_dis.png)

## Velocity vs step (Polynomial and trapezoidal interpolation)
![plot](./res/pol_tra_vel.png)

## Acceleration vs step (Polynomial and trapezoidal interpolation)
![plot](./res/pol_tra_acc.png)

## Displacement vs step (Screw linear interpolation)
![plot](./res/sli_dis.png)

## Velocity vs step (Screw linear interpolation)
![plot](./res/sli_vel.png)

## Acceleration vs step (Screw linear interpolation)
![plot](./res/sli_acc.png)
