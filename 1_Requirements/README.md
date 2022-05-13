
# **Wiper Control System**

## **Introduction**

In cars, a wiper control system replaces the standard wiper blade with an electrical component. In this setup, the ignition button (on the motor) will be controlled by a single switch in the ACC position. Switch on the wiper system with a second press, then vary the wiper speed with a third press, and finally turn off the motor with a fourth press. All of this was done with the help of LEDs and a simulation tool.A wiper is a vital component that removes rainfall or any other liquid from the windscreen of a vehicle. The previous method required manual wiper activation, and raising the wiper was a tough task. As a result, this system is being presented as a solution to these problems. The project's goals are to supply wiping systems for older automobiles, improve the system by using actuators and pull switches (using the same switch for various functions by stepwise switching), and manage engine and wiper speed with a single switch. This System regulates the wiper's operation speed in response to the amount of rain. This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen.

## **SOFTWARE REQUIREMENTS**
* STM32 IDE

## **COMPONENTS**
* STM32F407VG MICROCONTROLLER BOARD
* 
## **STM32F407VG**
* The STM32F405xx and STM32F407xx family depends on the superior execution Arm® Cortex®-M4 32-digit RISC center working at a recurrence of up to 168 MHz. The Cortex-M4 center highlights a Floating point unit (FPU) single accuracy which upholds all Arm single-accuracy information handling directions and information types. It likewise executes a full arrangement of DSP directions and a memory insurance unit (MPU) which upgrades application security. The STM32F405xx and STM32F407xx family integrates fast installed.

## **Xpack Packages**
* Windows Build Tools: The xPack Windows Build Tools is a standalone Windows binary distribution of GNU make and a few of other tools required by the Eclipse Embedded CDT (formerly GNU MCU/ARM Eclipse) project, but the binaries can also be used in generic build environments.

## **OpenOCD**
* Open On-Chip Debugger (OpenOCD) is a free, open-source project that aims to provide debugging, in-system programming, and boundary scan using a debug adapter. The adapter is a hardware module that provides the right signals for the target to understand.

## **QEMU**
* The xPack QEMU Arm is a standalone cross-platform binary distribution of QEMU, with several extensions for Arm Cortex-M devices.


## **Features**

When the button is pressed ONCE, the automobile will be locked.

When the button is pressed TWICE, the automobile will open.

When the button is pressed THREE times, it will turn on and move clockwise.

When the button is pressed FOUR times, it will wiper off and move in an anticlockwise manner.

When the button is pressed FIVE times, the wiper will complete one cycle.

## **SWOT Analysis**

### **Strength**

Visual clarity.
Operation Silent.
The wiper does not stop in the middle of the window.
We can control the wiper speed using just one button.

### **Weakness**

Increased Replacement Costs
Rubber Blades are required.
Wiper motor problems

### **Opportunities**

Opportunities for safety and good health
Possibilities for Promotion
Increase as a wiper system is required for installation.

### **Threats**

Advance Technology has taken its place.
In the rain, wiper blend could be a problem.


## **4'W & 1'H**

### **Who**

Anyone who wishes to be safe and have clear visibility in bad weather.

### **What**

It is a Wiper Speed Control System programme for all automobiles.

### **Why**

Switching between controls and wipers is simple.

### **When**

In difficult environmental conditions, such as a rainy climate,

### **How**

After wiping the windsheet of motor vehicles, the LED displays the position of the wiper and returns to its normal state.


## **Requirements**

### **High level requirements**

<html>
<body>
<!--StartFragment-->

ID | Discription | status
-- | -- | --
HR_01 | Lock and Unlock of car | Implemented
HR_02 | be able to ON the wipers and control their speed | Implemented
HR_03 | Activating the Wiper System | Implemented
HR_04 | Deactivating the Wiper System. | Implemented

<!--EndFragment-->
</body>
</html>

### **Low level requirements**

<html>
<body>
<!--StartFragment-->

ID | Discription | status
-- | -- | --
LR_01 | If the Button pressed ONCE - ON RED LED | Implemented
LR_02 | If the Button pressed TWICE - OFF RED LED | Implemented
LR_03 | If the Button pressed THRICE - ON BLUE,GREEN,ORANGE LEDs | Implemented
LR_04 | If the Button pressed FOUR times - ON ORANGE,GREEN,BLUE LEDs | Implemented

<!--EndFragment-->
</body>
</html>
