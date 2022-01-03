# DIY-mini-braiding-machine

![image](https://user-images.githubusercontent.com/19898602/147900905-14be71d8-5b36-40dd-8ad7-ef338551a9f8.png)


Are you an avid knitter, or know someone who is? Do you fancy making a machine that helps you custom weave your own tri-color, or more, braided thread? 

Perhaps, by chance, you also like to tinker around with Arduino-powered gadgets as well. If so, then this Arduino-based DIY braiding machine is right up your street.

Like most projects of this nature, you'll need a few basic tools (listed below) and some other bits and bobs to get the job done. 

We have included links to some of the products in case you need to buy them: 

Main components:

> 1/2 inch (12 mm) thick wood or MDF board 

> 1/4 inch (4 or 5mm) thick plywood

> Various 3D printed gears and wool spools, etc

> 3 no. 626 zz ball bearings

> 2 no. NEMA 17 stepper motor

> 1 No. NEMA 17 stepper motor mounting bracket

> 1 no. custom PCB board (or just use a sandwich board and connector wiring). 

> 2 no. A4988 stepper driver

> 1 no. Arduino Nano

> 1 no. L293D 16-pin IC stepper motor driver controller

> M5 threaded rods

> 1 x 1 inch (20 x 20 mm) Aluminum Extrusion bar

> Various bolts and nuts and acorn cap nuts. 




The first thing to do is to cut and shape the wooden board to shape to form the base of the machine. No specific dimensions are given by the creator, so ensure it is at least large enough to incorporate all the components. 


![image](https://user-images.githubusercontent.com/19898602/147900940-54fb46df-2a36-46d4-8f0a-ebf4424526f1.png)


Once cut to size, sand down and round the edges as needed using either sandpaper or a bench mounted belt sander if you have one. 

Next, you will need some 3D printed gears and other bits to move the wool spools in order to braid the thread. The models for these pieces can be found by following this link. 

You will need to print:

Three main gears.

One driver gear for one of the stepper motors.
One figure-of-eight piece.
Two teardrop pieces.
Three each of the two halves of the wool spool carriers (oval-shaped pieces).

![image](https://user-images.githubusercontent.com/19898602/147900957-d5c4afa2-7d5e-40cf-add9-1a88c5d72586.png)
![image](https://user-images.githubusercontent.com/19898602/147900965-0f4948d1-dc29-4bc9-ab72-b692af72ef03.png)


Next, mark out a bisecting line on the wooden base and place the gears so they meet directly in the center of the board. Once happy mark out the point of contact and also the position of the holes of the ball bearings.  


![image](https://user-images.githubusercontent.com/19898602/147900972-38a95bd7-0d59-424c-a5f2-f8cc91ba5725.png)

Now drill two equally sized holes in the positions marked for the centers of the ball bearings. Countersink the underside of the holes using a 5/8 inch (12 mm) spade drill bit to house the head of some suitably sized threaded bolts.

Now take the figure-of-eight 3D-printed piece and place over the drilled holes so that the drill holes are in the epicenter of each circle. Once happy, mark out the position of the drill holes in each corner. 


![image](https://user-images.githubusercontent.com/19898602/147900984-09e5ce75-57d4-4b47-9fa5-ec180433f2c6.png)

Drill the holes as shown in the video. Now insert the bolts into the central holes, add one large washer each and place the 3D-printed gear and ball bearing components onto the bolts. 

Add an extra washer to each bolt, and secure it into place using sufficiently large enough nuts. 

![image](https://user-images.githubusercontent.com/19898602/147900996-d586b377-c767-4df1-a483-cbd39b008913.png)


Next, add four other bolts and nuts to the figure of eight drill holes as shown in the video. These will hold another wooden figure of eight-piece (next phase) at a height above the gears similar to a table.

Next, make wooden copies of the teardrop and figure-of-eight 3D-printed pieces. Use the same dimensions as the 3D-printed models, mark out on the plywood, cut out and sand down, as necessary. 

Alternatively, you could probably get away with just using the 3D-printed pieces instead. 

Secure in place the teardrop wooden/plastic piece on top of each gear (and using an acorn capping nut to hold in place). Do the same for the figure-of-eight wooden or plastic piece too. 


![image](https://user-images.githubusercontent.com/19898602/147901003-f71165c8-5ac6-456e-8679-2ab5ba023cd2.png)


Now for that extra gear. Assemble as the other two with a ball bearing and mark up its position so it sits directly adjacent one of the other two.

It will need to turn the other two so make sure its position is right before finalizing. Once happy, mark its central position, drill a hole, countersink it, and fix it into place like the other two (but with a shorter bolt). 

![image](https://user-images.githubusercontent.com/19898602/147901010-a43b75de-7c9d-4ab8-acf1-348705ef858c.png)

Next up create another wooden piece (or 3D print) to mount on the stepper motor. It will need to be slightly larger than the motor to accommodate four bolts on each corner. 

It will also need a hole in the middle to allow the motor's axle to freely rotate. Once happy with the design, glue, or bolt on to (depending on your wishes) onto the stepper motor. 

You will also need another 3D gear that has to be designed to fit onto the axle and drive the other three gears. This will take some trial and error. 


![image](https://user-images.githubusercontent.com/19898602/147901015-839de6e9-ad57-4eda-8fc4-7bbd2ad93bcb.png)


Now mark out and drill four more drill holes directly below the third gear. These will hold the stepper motor assembly in place. 

Make sure they match the position of the stepper motor mount corner holes and that the central gear cleanly contacts the third wheel. 



Now mark out and drill four more drill holes directly below the third gear. These will hold the stepper motor assembly in place. 

Make sure they match the position of the stepper motor mount corner holes and that the central gear cleanly contacts the third wheel. 



With the mechanical bits more or less finished, let's turn our attention to the electrical pieces. For this part, you will need a custom-designed PCB board. 

It will need sections to mount the Arduino Nano, motor driver, and other components. You will need to watch the video for more information on this. 

Mount and solder into place the various micro-components as shown below. 

# Build the PCB

![FTQFHXZKLBNXU2X](https://user-images.githubusercontent.com/19898602/123725479-bd305280-d8ab-11eb-8709-c680e91e1300.jpg)
![MVI_0001_2 mp4 00_06_55_14 Still001](https://user-images.githubusercontent.com/19898602/123725534-d5a06d00-d8ab-11eb-9645-d2a05880e79a.jpg)
![MVI_0001_2 mp4 00_07_11_00 Still002](https://user-images.githubusercontent.com/19898602/123725542-d933f400-d8ab-11eb-9a7f-d88351d6a952.jpg)

I designe this multipurpose PCB Those who ever worked with arduino they know the pain of connecting multiple components to the arduino for there projects. so here is the answer for you all.

Not only 2 or 3 you can connect 11 components at same time & on board 5V & 9V regulator,

cross polarity protection, power indication LED,

motor power selection provision (5V or 9V or 12V) manual provision for stepper motor microstepping setting.

Wide range of input supply (9V to 24V). This is my multipurpose PCB works with Arduino Nano, I have designed it in a way that you can run 2 Stepper motors, 2 DC motors, 2 Servo motors at same time and this is not it you can even connect BT module, rotary encoder, I2C device, potentiometer at same time.

This PCB is very much helpful in building any project and no need to worry about messy wire connections.

![image](https://user-images.githubusercontent.com/19898602/123725769-50698800-d8ac-11eb-83b0-fbdab6a23ec1.png)
![image](https://user-images.githubusercontent.com/19898602/123725784-5a8b8680-d8ac-11eb-9a51-bb9042d974ec.png)


He we first see the overview of PCB means what is this PCB capable of and which components you can connect to the PCB.

# List of the Components you can connect to the PCB

> 2 DC motor ( 9V to 24V DC)

> 2 Potentiometer

> 2 Servo motors ( 5V to 9V DC)

> 1 Serial device (BT module, HMI, Communication module, RX, TX)

> 1 Encoder (2 interrupt pin & 1 PB pin)

> 1 I2C device (SCL/SDA Device, display, MPU6050 etc)

> 2 Stepper motors


# Special features of PCB

> Wide range of power input 9V to 24V DC

> Cross polarity protection

> DC motor voltage selection 9V or 12 V DC

> Servo motor voltage selection 5V or 9V DC

> Manual microstepping setting for stepper motor

> Power indication LED

> L298N IC for heavier DC motor

> ON board 5V and 9V regulator no need to arrange different power sources

> Header pins and screw terminals for easy connections




I have designe this PCB and order it from [JLCPCB.com](https://jlcpcb.com/IAT)

I always prefer [JLCPCB.com](https://jlcpcb.com/IAT) for my PCB needs, [JLCPCB.com](https://jlcpcb.com/IAT) have best deals for their customers
$2 for 1-4 Layer PCBs, free SMT assembly monthly.


If new user signup today from this link [JLCPCB](https://jlcpcb.com/IAT ) you will get 27$ coupon from [JLCPCB](https://jlcpcb.com/IAT ).


[Click here to visit JLCPCB.com](https://jlcpcb.com/IAT)



![image](https://user-images.githubusercontent.com/19898602/147901028-71491174-d889-4499-9b09-9475ecbbb900.png)

Next insert the Arduino Nano into place, as well as the A4988 motor drivers, and the stepper driver motor controller, as seen below. 

Now place onto the baseboard adjacent to the stepper motor. Mark out the mounting holes, drill them out and secure the custom PCB into place. 

Now place onto the baseboard adjacent to the stepper motor. Mark out the mounting holes, drill them out and secure the custom PCB into place. 

Next another critical component -- the Arduino code. Here it is in all its glory: 

#include
#include "BasicStepperDriver.h"
#include "MultiDriver.h"
#include "SyncDriver.h"


#define MOTOR_STEPS 200
#define MOTOR_X_RPM 30 // change this value to change to winding motor speed
#define MOTOR_Y_RPM 90 // change this value o change bottom motor speed


#define DIR_X 8
#define STEP_X 9


#define DIR_Y 6
#define STEP_Y 7


#define MICROSTEPS 32


BasicStepperDriver stepperX(MOTOR_STEPS, DIR_X, STEP_X);
BasicStepperDriver stepperY(MOTOR_STEPS, DIR_Y, STEP_Y);


MultiDriver controller(stepperX, stepperY);


void setup() {

stepperX.begin(MOTOR_X_RPM, MICROSTEPS);
stepperY.begin(MOTOR_Y_RPM, MICROSTEPS);

}

void loop() {

controller.rotate(360, 360);

}

And now back to finishing the mechanical parts of the machine. 

Now cut two equally lengthed sections of the 3M threaded rods and one slightly longer one. All three of them will be used to mount the wool spool carrier 3D printed pieces. Assemble these as shown in the video and below.

These pieces will be used to guide the wool spools around the figure-of-eight track once complete. They will sit in and pass between, the U-shaped grooves in the main gears once assembled. 

![image](https://user-images.githubusercontent.com/19898602/147901050-228c61ec-7009-4643-a4bc-f96c9ffcd8a4.png)

Now to make the actual spools. The creator in this video machined three of them from a metal rod, but you could probably design, or indeed purchase, plastic alternatives too.

Alternatively, you could whittle from wood, or other material, a set if you are up to the task. However you do it, remember these spools need to fit fairly loosely so they can be removed. 

You will also need a fourth to receive the braided thread latter. For this reason, you can either machine or 3D print one more too. This last spool will need to be mounted right on the other stepper motor axle, so bear that in mind whatever you decide to do. 

To faithfully recreate this device, watch the video for more details. 

![image](https://user-images.githubusercontent.com/19898602/147901060-49859ab0-006a-44a2-8344-8c7cd3039e1b.png)

Next up, cut a length of the 20 x 20 aluminum rod. Bracket into place between the braiding assembly and the PCB board using either purchased or 3D-printed brackets. 

![image](https://user-images.githubusercontent.com/19898602/147901068-041fbff0-cd60-469e-8e88-5b472702dab1.png)

Next, mount the second NEMA stepper motor into the mounting bracket and affix near the top of the central aluminum shaft. The mount should come with all the nuts and bolts necessary.

Now, wire up the motors to their respective ports on the custom PCB, add some colored yarn to the spools and secure in place on the carriers, tie their ends together, feed through the loop, and tie to the receiving spool.

![image](https://user-images.githubusercontent.com/19898602/147901086-46dd37c6-89a6-4332-a519-ec6b9030c8e4.png)


With all that done, simply power up the Arduino, and watch it braid away on all its glory. Happy automated braided!


