# Candy-Case
A Non-PCB case for SlimeVR trackers, over engineered and optimized for being compact. They're only 61.8mm(L)x60.5(W)x16.2mm(H) in size WITH strap loops, and only weigh about 50 grams with all the components inside and wired up(Including the battery I chose, your millage may vary).

![Alt text](<Photos/First Print of V9.0.jpg>)
![Alt text](<Photos/IMG_4716.jpg>)
![Alt text](<Photos/IMG_4719.jpg>)
![Alt text](<Photos/IMG_4720.jpg>)
![Alt text](<Photos/IMG_4722.jpg>)
![Alt text](<Photos/IMG_4717.jpg>)

I've looked at every problem available to me at a technical level, from cable routing causing issues with the Wifi antenna, to a size problem when it comes to Non-PCB cases, the goal of this project was to be as optimized as I could. There were some issues I could not fix due to the design, and decided to compromise.

The issues are as follows:
1. The D1 Mini's USB port is inaccesible when you close up the case, this is due to me wanting the antenna to be close to the walls and away from all the cables. Not a huge issue in my opinion as you'll only need this to flash the firmware, calibration can be done wirelessly, a bit hard tho.
2. Soldering it is a lot harder than other cases due to the layout I chose as it is incredibly compact, and the IMU being under the D1 Mini makes it hard as well.
3. You will need to cut up a battery holder or some kind of battery contacts for your 14500 battery as these are designed with DIY battery contacts in mind, these can't be too thick either, I chose to cut one up with flush cutters and super glue them in place.
4. Double sided tape might be required for some parts, I used it for the IMU because cable tension kept pushing it into a non-flat position and also used tape on the lid to keep the switch from sliding into the case as the lid has a slight issue, you can also super glue the switch in, I opted not to.

Parts: 
1. Wemos D1 Mini V4.0
2. BMI160
3. TP4056 (Type C version)
4. SS12D10 Switch
5. Some kind of battery contacts, I used a cut up BH-311-1A AA Battery Holder
6. 14500 Lithium-Ion Battery 800-1000mAh, I used a Vapcell H10 as they're rated well
7. M2 screws, 8mm in length, Countersunk Flat Heads
8. M2 Heat threaded insert (OD)3.5mm (H)6mm