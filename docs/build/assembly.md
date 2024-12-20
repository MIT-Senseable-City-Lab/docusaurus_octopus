---
sidebar_label: '🧩 Assembly'
sidebar_position: 6
---

# 🧩 Assembly

This section looks into how to assemble your own Octopus. 

---

## Overview

This guide will help you assemble your own Octopus based on the configuration you’ve chosen. This process should take you about **20 minutes maximum**. <br/>
It is divided into two parts accordingly:
1. **Small octopus (standard configuration)**  : For use cases like **air temperature monitoring** or **flower classification**.
2. **Long octopus (expanded configuration)**  : For **air quality monitoring** with additional components.


## Standard Configuration (Air Temperature and Flower Classification)


### Step 1: Prepare the bottom layer

**1.** Place the **battery** into the bottom section. <br/><br/>
![a1](../../static/img/assembly/step1_assembly.png)

 <br/>
**2.** Position the GPS module on top of the battery in the designated slot.<br/><br/>
![a2](../../static/img/assembly/step2_assembly.png)


 <br/>
**3.** Secure both the battery and GPS module using rubber bands around the protruding securing parts.<br/><br/>
![a3](../../static/img/assembly/step3_assembly.png)
 

### Step 2: Prepare the top layer

**1.** Place the **fan** in the head layer with the blades facing the interior of the print  and push it into position until secure. 

:::tip

To safely secure the fan into position, push it from its center until you hear a *'click'* sound. 
:::
<br/>
![a4](../../static/img/assembly/step4_assembly.png)



 <br/>
**2.** Pick up the PCB and plug the battery into the port labeled “battery” on its back. 
<br/>
![a5](../../static/img/assembly/step5_assembly.png)


 <br/>
**3.** After selecting the appropriate head variation for the given arduino *(Nikla vision for camera use, Nano for temperature and air quality)*, **turn on** the Arduino board by pressing the white button as shown in the picture.
<br/>
![a6](../../static/img/assembly/step6_assembly.png)


 <br/>
**4.** Insert an **SD card** into the PCB designated slot for data storage.
<br/>
![a7](../../static/img/assembly/step7_assembly.png)


 <br/>
**5.** Securely place the Arduino board in the print, making sure it is properly oriented as per the following image.
<br/>
![a8](../../static/img/assembly/step8_assembly.png)



 <br/>
**6.** Use **rubber bands** to secure the PCB to the head’s protruding securing parts.
<br/>
![a9](../../static/img/assembly/step9_assembly.png)


### Step 3: Plug electronics

 <br/>
**1.** Connect the GPS module to the PCB at the “QWIIC” port.
<br/>
![a10](../../static/img/assembly/step10_assembly.png)

 <br/>
**2.** Solder the black wire of the fan to the 'GROUND' solder pad and the red wire to the '5V' pad - as shown below. 
<br/>
[image here]


### Step 4: Final assembly

**1.** Attach the bottom part to the head section by screwing them together.
<br/>
![a11](../../static/img/assembly/step11_assembly.png)

:::tip

Ensure the wires are long enough to twist comfortably during this step.
:::




## Optional / Expanded Configuration (Air Quality Monitoring)

This version includes the **middle section** for housing the Sensirion SPS30 sensor.

### Step 1: Prepare the middle layer

Insert the **Sensirion SPS30 sensor** into the middle section and ensure it is placed in its correct orientation.
<br/>
![a12](../../static/img/assembly/step12_assembly.png)

:::info

When mounting the Sensirion SPS30 sensor, ensure the **top side with the logo and connection pins is visible**, with the smaller hole (air inlet) and the larger hole (air outlet) facing outward **towards the part openings**.
:::


### Step 2: Connect electronics

 Plug the Sensirion SPS30 sensor into the “air quality” port on the PCB.
<br/>
![a13](../../static/img/assembly/step13_assembly.png)


### Step 3: Integration into final octopus assembly

**1.** Attach the middle section to the bottom section, ensuring wires pass through the ventilation cores.
<br/>
![a14](../../static/img/assembly/step14_assembly.png)


:::tip

Hold onto the wires as they pass through the ventilation cores and during the twisting process to ensure they don’t get caught between the layers.
::: 
 <br/>


**2.** Screw the head section onto the middle section after inserting all required wires to the PCB - as per previous instructions.
<br/>
![a15](../../static/img/assembly/step15_assembly.png)


---


**With your Octopus fully assembled, you’re now ready to dive into the next step: setting up the Octopus firmware!**<br/>
<!-- ![ay](../../static/img/assembly/stepy_assembly.png) -->
