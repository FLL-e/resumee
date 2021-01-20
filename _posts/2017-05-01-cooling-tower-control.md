---
title: "Cooling tower power control"
last_modified_at: 2017-09-01T00:00:00
categories:
  - Work
tags:
  - TFG
  - Arduino
header:
  teaser: /assets/images/control_box.png
---

**DATE** from may to sep of 2017

I developed the control system of a closed-circuit cooling tower. 

It was a project carried out by the Thermodynamics department at the **University of Córdoba** to proof their research about energy efficiency. I made a control box and I integrated it with the tower through I2C communication. In summary, _the box_ handles the power of the motors to modify the process variables and achieve the required set-points (using PID control) for the experiments. Also, the control box can work separately from the cooling tower, being controlled through USB connection, and allowing the department to use it with other projects easily.

Motors involved: 
- Fan, creating an air flow from outside to renew the humid satured air 
- Fluid pump. Water was the target fluid to refrigerate and this pump allowed to control its flow
- Spray pumps. They control the flow of water that is throwed to the heat exchanger pipes lines and with evaporation extrat the heat from the target fluid

The project was developed using Arduino platform to increase accessibility and ease of modification for the mechanical department.

You can download the [project documentation from here](https://www.dropbox.com/s/n6h6rqpq7n540p1/TFG_F_Luque.pdf?dl=0)

![Power box](https://fll-e.github.io/resumee/assets/images/control_box.png){: .align-center}