# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

output

![241132217-ad1b7f75-90bc-40f7-afe9-121c4e683597](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/2843c477-3ec9-494b-84e0-439e46097cbb)




![241132249-436a9ac9-902d-4b6e-9cee-98737c999e13](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/e6daca72-26c1-4891-b31f-f074058e0761)

![241132270-597ea33a-f132-4143-adce-2446a8f883b0](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/253543dd-7692-4821-8cbe-80999a7f7f94)

![241132297-9e4f0097-3f37-4ba7-9773-f9e0053b139c](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/5e939f27-4662-4884-9051-8d01606f50f0)


![241132302-2dae677a-21c4-4054-a964-991daf192b09](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/931a5400-7a06-4328-8d8d-6a40b9c182e0)


Linear Interpolation
![241132311-df0e684f-3c09-4e3f-9678-7ee22acf3e98](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/27435287-d21d-4206-bfca-384a40c89fa5)



Circular Interpolation


![241132323-50c5b959-88f5-49f0-b2e7-4809cc2e3c02](https://github.com/Akashbalakrishnan/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/119291768/26b756bd-4536-422d-96ab-3a48fa1277ae)


Results


A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.
