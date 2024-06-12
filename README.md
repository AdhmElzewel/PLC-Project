# PLC-Project
## Height sorting system

In this system, the boxes are sorted on the production line according to the height of the box with the ballet, where there are two main sizes, which are the small size and the large size. 
 the boxes are passed randomly on the production line and then pass on a height sensor, where the height of the box is classified according to the number of beams that have been penetrated into the sensor, and on this basis ,the signal is transferred to a conveyor containing a selector that works in both directions, where the direction in which the box will be transferred is determined according to the height of the box, whether to the right or to the left. If the size of the box is small, it is transferred to convyer1or convyer2 if big.
There is a retroreflective sensor in the entrance of conveyor 1 which send signal to plc to open the conveyor, this means that the box reaches the conveyor, so the conveyor is turned on to move the box and then stops when the another retroreflective sensor at the end of the belt picks up a signal. And then this process is repeated with large boxes.

![image](https://github.com/AdhmElzewel/PLC-Project/assets/108629950/e0dbee8c-3f47-40d5-9acf-45315f11a673)

**This process requires that boxes moving on a conveyor be automatically sorted by height.** The sequence of operation for the continuous filling operation is as follows:

⦁	Start the system when the start button is momentarily pressed
⦁	Stop the system when the stop button is momentarily pressed
⦁	When the proximity sensor has no signal, the conveyor is turned on 
⦁	When the proximity sensor receives the signal and the selector turned left or right, the LED is on (sensor on LED) and the selector led also is on for 2 sec and the counter starts to count the total boxes.
⦁	When the selector is on right side then the right conveyor is on for 4 sec and the counter starts to count for large boxes. 
⦁	When the selector is on left side then the left conveyor is on for 4 sec and the counter starts to count for small boxes.

## The simulation of the system in factory IO:

![image](https://github.com/AdhmElzewel/PLC-Project/assets/108629950/6a9cd245-9528-4ebf-8da8-ad012f4b1adb)

## TABLE OF INPUTS & OUTPUTS:

![image](https://github.com/AdhmElzewel/PLC-Project/assets/108629950/567256d3-c9b7-4a4f-9cb3-9443204ffb39)

## Hardware: 

![image](https://github.com/AdhmElzewel/PLC-Project/assets/108629950/1d3533b2-c169-4f9e-8c69-d9e6dc053a3c)

## Automation studio:

![image](https://github.com/AdhmElzewel/PLC-Project/assets/108629950/589b6a93-5c90-456e-a9f5-bf32c5d524a6)




