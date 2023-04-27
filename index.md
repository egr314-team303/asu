                                                                        
                                                           Title: Mobile Environmental Sensings
                                                                      
- [Table of Contents](#table-of-contents)
## Table of Contents

1. [Link to our team's Youtube presentation video](https://egr314-team303.github.io/#link-to-our-teams-youtube-presentation-video)
2. [Title](https://egr314-team303.github.io/#title)
3. [Team Organization](https://egr314-team303.github.io/#team-organization)
4. [User Needs,Benchmarking,and Requirements](https://egr314-team303.github.io/#user-needsbenchmarkingand-requirements)
5. [Product Requirement](https://egr314-team303.github.io/#product-requirement)
6. [Design Ideation](https://egr314-team303.github.io/#design-ideation)
7. [Block Diagram](https://egr314-team303.github.io/#block-diagram)
8. [Component Selection](https://egr314-team303.github.io/#component-selection)
9. [Power Budget](https://egr314-team303.github.io/#power-budget)
10. [Final Hardware Implementation](https://egr314-team303.github.io/#final-hardware-implementation)
11. [Final Software Implementation](https://egr314-team303.github.io/#final-software-implementation)
12. [Lesson Learned](https://egr314-team303.github.io/#lesson-learned)
13. [Recommdations for future students](https://egr314-team303.github.io/#recommendations-for-future-students)
14. [MQTT Topic Table](https://egr314-team303.github.io/#appendix-a)
15. [C Code](https://egr314-team303.github.io/#appendix-b)
16. [MCC Configuration](https://egr314-team303.github.io/#appendix-c)
17. [Bill of Materials](https://egr314-team303.github.io/#appendix-d)

## Link to our team's Youtube presentation video

* [Checkpoint 1](https://youtu.be/aUGKlzh9vjw)

<iframe width="560" height="315" src="https://www.youtube.com/embed/aUGKlzh9vjw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Title

* Mobile Environmental Sensings
* Team 303
* 2023 Spring
* ASU,EGR314,Travis Kelley


## Team Organization
(The Complete Team Organization is here<a href="Team Charter.pdf">Complete Team Oraganization</a>))

* Charter

**Success Metrics**

1. Products need to convey information to users as accurately as possible
1. The product ideally should have a rechargeable battery with a lifespan of at least one hour.
1. The product needs to be low energy so as to not be a danger to users.
1. The product needs to have a sustainable lifespan.
1. The product needs to be portable

**Shared Goals**

Our team looks to find success within this project by creating a robotic system that can accurately detect and provide to those who are wanting to detect nearby temperature and humidity anywhere. By creating a design that is elegant and works efficiently, we hope to present to our stakeholders a project that we can all be proud of.

* Mission Statement

Our mission is to design and construct a robotic device that can demonstrate the advantages of simplicity, portability and precise detection of temperature and humidity. Our team is committed to developing a product which is safe for stakeholders to interact with a mobile phone connected via WiFi, while also providing a motion capability that can be detected by moving into tight places.

## User Needs,Benchmarking,and Requirements

The complete User Needs is here<a href="User Needs and Benchmarking 303.pdf">Complete User Needs and Benchmarking</a>

* The first thing we did for user needs was that we set up a jam board so that each member of the team could write down the user needs they thought were important.

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230118_120048.png?raw=true)

Then we separated them into 3 seperate catergories, "Tech Constraints", "Function", "Interactivity".

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_105314.png?raw=true)

Lastly, we ranked them in order of importance. The proccess in which we ranked them was done by taking the user needs that we came up with and comparing them with customer needs from the voice of the customer.

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_105829.png?raw=true)

After that we started Benchmarking and started listening to the voice of our Customer. 

Here is a example of our selected product:

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_111104.png?raw=true)

:star: From the example of our selected product,We found out that Products have longer lifespan, power efficient and power supplies need to be replaceable are really important.

## Product Requirement

I have only listed the most important aspects here (importance ranked from P1 to P10, with P10 being the most important). The complete product requirement can be found at the above "Complete User Needs and Benchmarking" link.

Aspects
1.   	Product Design
   * The product will utilize the Microchip microcontroller as the main controller for sensor inputs and motors (P10)
   * The product will adapt to two (2) sensor inputs connected to the microcontroller (P10)
   
2.   	Functionality
 * The product will feature a rechargeable battery life of over one (1) hour        （P10）
 
3.   	Interactivity
* Product should provide more than one action for interacting with visitors.     （P10）
* Product should have multiple choices in the interaction process for users.  （P10）
* Product should have multiple outcomes based on previous choices.（P10）

And here is the user story we collected 

William is a father with two children. He wants to give his children an intellectual education of engineers at an early stage. He needs a robot that can attract children's attention with interesting performances, and at the same time has monitoring functions (such as temperature, humidity, wind, atmospheric pressure, etc.)

The user story proves that how necessary this product in the society.

* Then we researched the source and price of this product and the description of this product. At the same time, we also conducted research on the after-sales evaluation of this product. We extracted the customer needs we need from customer evaluations, and then transformed them into product requirements for our own robot research and development. (For complete research, please see the complete User Needs above)

Open Question

* Can the product be designed with only recyclable materials in mind?

Yes, it is possible to design a product with only recyclable materials in mind. Designing
a product with recyclable materials can help reduce the environmental impact of the
product and increase its sustainability. By using recyclable materials, the product can be
easily disassembled and the materials can be reused or repurposed, reducing waste
and the need for new raw materials. Additionally, using recyclable materials can help
increase the product's longevity and reduce its overall environmental footprint. It is
important for designers to consider the entire lifecycle of a product, from its production
to its disposal, and to design with sustainability in mind.

* Can we incorporate in the design the ability to use a mobile phone to remotely control the movement of the product?

Yes, it is possible to incorporate mobile phone control into the design of a product. This
would involve integrating a wireless communication module such as Bluetooth or Wi-Fi
into the product's control system. Users could then download a mobile app that
communicates with the product via the wireless module, enabling them to remotely
control the product's movement.

But in our case, due to the time constrain, we didn't approach to this function.

* What are some examples of modules that can be interchanged within our design?

As for examples of interchangeable modules, some possibilities might include different types of sensors, actuators, or power sources. For example, if the product is designed for outdoor use, different power sources could be used depending on the availability of sunlight or other renewable energy sources. Alternatively, different sensors could be swapped in or out depending on the specific use case of the product.

* Does our actuator have to be connected to the sensor? Or can it only be connected with the microcontroller?

Regarding the actuator and sensor connection, it depends on the specific requirements of the product's design
But in our case, the actuator is not connect to the sensor, it only connect to the microcontroller.

* After collecting user requirements, we began to brainstorm and come up with a hundred design ideas based on these user requirements (See Design Ideation below).

## Design Ideation

* The role of each person in the group was to come up with 50 design ideas each that in total came up to 100 ideas that we can potentially use in our design concepts.

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230120_101953.png?raw=true)

* After coming up with the 100 ideas, we then came to together in person to brainstorm and decide which ideas were the best from the 100 ideas. We decided that brainstorming in person was more effective and successful then doing it virtually or seprately because we were able to come up with more ideas and better quality ideas.

* We then took the 100 ideas and came up with three design concepts that best fit the ideas that we had. Shown below is the three design concepts that we created based of the ideas that we came up with. 

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_082301.png?raw=true)

Abdulrizak Husein:

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230120_102516.png?raw=true)

This is our team's second concept. This concept includes a temperature sensor, an LED, a microcontroller, a motor, and a battery. This design will be connected to the user through WiFI and the user would be able to turn on the robot through a mobile device. When the user turns on the robot, the user will be able to turn the top piece to the direction of their choice. The LED will show if the system is on and reading the temperature sensor. 

Zhengbin Chen:

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_114244.png?raw=true)

This is our team's first design concept, which is a car-shaped patrol temperature monitoring robot, which has temperature sensors, LEDs, four wheels, motors, and gears. Based on this design, it can be connected to the user with WIFI, so that the user can see the temperature change anywhere. At the same time, we hope that the user can also use the mobile phone to remotely control the direction of the car, (this is also hoped for Use the gear to change the direction or use four motors to control different directions), so that users can remotely monitor where they want to monitor, and can go to any place they want to monitor. At the same time, we also hope that users can set the "alarm" temperature by themselves, so that once the temperature reaches the alarm temperature, the LED will flash to warn the user, and an alarm will also be displayed on the mobile phone.

Sivanee Naghichetty Prem Kumar:

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230122_043408.png?raw=true)

This is our team’s third design, The Box. Just like the previous designs, this design also consists of a temp sensor, a LED, a motor module, a microcontroller and an LED display. The main goal of this design is to make sure that the device is compatible and easy to carry. In this design you can see two different layers. On the outside, the LED, Temp sensor and the microcontroller is present. On the left side, you can see the LED display that displays the amount of temperature, read by the temp sensor and when we go deep inside, we can notice the motor module and the battery module. The battery module also works as a power bank, the can save up energy when charged to be used later. The battery is charged by the power module which is mentioned as a charging port in the diagram and present at the bottom of the device. In the right view, we can see different types of ports which are used to connect to any device to read the temperature. This design also has the feature of connecting to WIFI and bluetooth when needed.

:star:During the discussion, our team decided that since our idea is focused on reducing temperature, and that our motor should be linked to the temperature sensor. This made us to come to a conclusion of a fan like structure that is portabl. Whlie brainstroming our three designs, we tried to combine them and figured that the one with the highest interaction with temperature is our fan design. Whenever the surrounding temperature is higher than the room temperature, our fan will start to rotate to reduce the temperature. In the current design, the PCB will be inside the body of the fan and the motor will be at the top, connected to the fan propller and further, we also consider adding OLED to display the room temperature.

## Selected Design:

![image caption](https://github.com/egr314-team303/egr314-team303-asu.github.io/blob/main/Screenshot_20230120_102516.png?raw=true)

## Block Diagram
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Block%20Diagram-314.drawio.png?raw=true)

:star:The team 303 came togeather to discuss about the block diagram and first we determined the functions we need (motor driver, temperature sensor, WIFI module, ICSP), and then we find the pins we need according to the datasheet of the Microcontroller we choose. We splitted the subsystems among ourselfs and found that The subsystems meets all the product requirment. The motor driver meets the SPI and actuator reqiurment and the tempeture sensor meets the I2C requirment. The temperature and the motor subsystems are connnected to the microcontroller. When the temperature sensor reads the temperature, it sends signal to the motor driver which 
then adjusts the speed depending upon it. The motor driver is SPI and connected to external power supply. The temperature sensor is I2C and is connected to a 12V to 3.3V voltage regulator which is also connected to the wall supply. 
:star:We have Microcontroller to control WIFI Module, Temperature Sensor and Motor driver. Then there is ICSP pin interface to program through Cadence.

## Component Selection

<a href="Component Selection.pdf">Complete Component Selection</a>

## Voltage Regulator
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Voltage%20Rgulator.png?raw=true)

This Voltage Regulator has the lowest price and the highest availability. At the same time, it meets the requirements of our project, safe to use, can withstand severe temperature changes, stable 3.3V output and 1A safe current output.As well being surface mount.

## Power Supply
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Power%20Source.png?raw=true)

The team opted to use the AC/DC 12V power supply due to its ease of use and consistent 12V supply. The loss of portability is made up for by the convenience of not needing to replace batteries after repeated usage.

## Temperature Sensor
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Temperature%20Sensor.png?raw=true)

The reason for selecting this Temp. Sensor is that it is easier to use as are using it in class. It is also the cheapest option out of the three options. It also meets the I2C and surface mount requirements. 

## Motor Driver
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Motor%20Driver.png?raw=true)

This Motor driver is the better suite compare to other ones we viewed, due to its efficiency even when the cost is higher than the others. It also meets the SPI and Surface mount requirment.

## Mictocontroller
<a href="microcontroller-selection-table.docx (2).pdf">Complete microcontroller Selection is here</a>

This is the PIC that we choose:

![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/medium-PIC18F27Q10-SOIC-28.png?raw=true)

We compared three PICs, and after comparing the benefits, we finally decided to use this PIC because:

This is very practical, and the price is affordable, and the delivery time is very timely. At the same time, it also meets the needs of all course projects: with i2c communication, with UART, suitable for MPlab IDE, and suitable for MCC Melody. Also the In-System Programming Capability and Type is ICSP which fulfills the project requirement. There is also a complete programming tutorial for the temperature sensor, so our team thought this would be the best choice.



First of all, we have all of our electrical component be surface amount.

## Power Budget

![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Power%20budget.png?raw=true)

We found the required voltage and the required power consumption from the data sheets of the respective components, and then subtracted the voltage consumed by these components from our power source to roughly calculate whether our power source can support the voltage of these components consume.

Team 303 together worked on the component selection and came up with the best fit for our subsystems together. We first decided upon who is taking up which subsystem and split your component selection into three different sectors. Every individual in Team 303 worked seperately on their component selection at first and found the top three options based every single details, such as its voltage capacity, price, its power supply etc from the datasheet, compared all the three once again to finalise with one product. Later again when it was doe, we all met once again to discuss on the finalised product. 



## Final Hardware Implementation
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Schematic.png?raw=true)

Our Hardware design was split into 3 subsystems for each group member to work on. The subsytems that the members worked on include: Voltage regulater and PIC, Temperture Sensor, and Motor Driver and Motor. The power regulater subsystem The Regulator subsystem has a barrel jack connector input .  The 3A max power draw will never be met or exceeded in normal operating conditions, so a 3A fuse will help protect the circuit in a worst case scenario.  The 12V is stepped down and regulated to 3.3V for the PIC, sensor, motor controller, and motor to be powered by. The PIC is also wired with global tags to each other subsystem. The Temperature Sensor subsystem contains the temperature sensor and conditioning circuit. The Motor Subsystem contains both the motor and its motor controller. The motor is controlled by 4 inputs from the PIC via global tags. The motor and controller are powered off of 3.3V which is enough for the motor to turn at an acceptable speed for our intended use. It also has LEDs and Test point for debugging and a WiFi Module which is esp 32 so the user can connect to our device through Bluetooth and Monitor real-time temperature through mobile phone. We use ICSP pin for programming our pic. 

It satisfies the product requirements by having the tempeture sensor to be I2C and the motor driver to be SPI. It also satisfies it by being able to capture enviromental conditions.

And here is our Bill of Materials ● [See Appendix D](https://egr314-team303.github.io/#appendix-d)

Front side of our PCB in Cadence；
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Front%20side%20of%20PCB.png?raw=true)

Back side of our PCB in Cadence:
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/backside%20of%20pcb.png?raw=true)

Front side photo of our PCB:

![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/IMG_0491.jpg?raw=true)

Back side photo of our PCB:

![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/IMG_0492.jpg?raw=true)

## If we were to create a "Version 2.0" of our hardware design, here are few things we will definetely make sure:

1. We set the orientation of some components incorrectly, causing the pins to be connected wrongly, such as the ESP32. As a result, we could only complete the connection with jumper wires. This is the first mistake we will correct.

2. We will make the PCB larger because the small layout causes some pins to be unable to connect (they will touch other traces and cause a short circuit).

3. The through-hole size of our fuse was not set correctly, so it cannot be directly inserted and soldered. Instead, we have to use jumper wires. Therefore, if we have the opportunity next time, we will ensure that all pin sizes are set correctly.

4. If we have time, we will consider adding an OLED display because it will be an interesting feature.

## Final Software Implementation
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Software%20Proposal.drawio%20(3).png?raw=true)

Since we have used temperature sensors in class and are familiar with them, we chose them as our sensor. As it is related to temperature, we naturally thought of the function of cooling. Therefore, when the temperature rises, our motor starts to operate until the temperature drops below the user's setting.

We initialize the system first, then set up all hardware registers, and establish our communication (i2C for temperature sensor, spi for motor driver). All this is to make our function successful.

Our software is mainly to check whether a dangerous temperature has been set. Once the set temperature is reached, our motor will rotate with the fan blades (thus achieving a cooling effect).

The top 5 biggest changes are:

1. We added PWM to our motor to make it more efficient.
2. We put a limit on the temperature, as we cannot heat the temperature to very high levels.
3. We attempted to add an LCD display to show the current temperature.
4. We added a WiFi module.
5. We designed the system with energy efficiency and environmental sustainability in mind, minimizing energy consumption and reducing our impact on the environment.

If I were to create a "Version 2.0" of the software design, I would focus on improving the system's reliability, flexibility, and ease of use. Specifically, I would:

1. Improve the code structure: I would divide the code into smaller modules to make it more organized and easy to maintain. This would also make it easier to add new features in the future.

2. Implement error handling: In the current version, there is no error handling, which can make the system unstable. In the next version, I would implement error handling to detect and handle errors more effectively.

3. Create a more user-friendly interface: The current version does not have a user interface, which can make it difficult for users to interact with the system. In the next version, I would create a user-friendly interface that displays the current temperature and allows users to set temperature limits and control the motor.

4. Add support for multiple sensors: In the current version, only one sensor is supported. In the next version, I would add support for multiple sensors, allowing users to monitor temperatures in different locations.

5. Add support for remote monitoring: In the next version, I would add support for remote monitoring, which would allow users to monitor the system from their smartphones or other devices.

6. Improve the protocol design: In the next version, I would simplify and improve the protocol design to make it more efficient and reliable. This would help to ensure that the system can handle large amounts of data and communicate effectively with other devices.

7. Use more robust peripherals: In the next version, I would use more robust peripherals to make the system more stable and reliable. This would include using high-quality sensors and motors, as well as improving the cooling and power supply systems.

By making these improvements, the system would be more reliable, stable, and functional, which would make it more useful for a wider range of applications. Additionally, the system would be easier to use and maintain, which would reduce the time and effort required to operate it.

● [MQTT Topic Table](https://egr314-team303.github.io/#appendix-a)
● [C Code](https://egr314-team303.github.io/#appendix-b)
● [MCC Configuration](https://egr314-team303.github.io/#appendix-c)

## Lesson Learned

● Collaboration is necessary: Working collaboratively with team members is
necessary to ensure that the project meets all requirements and is successful.

● Attention to detail is crucial: In egr 314, small details can have a significant
impact on the success of a project, so attention to detail is crucial.

● Effective communication is key: Clear and consistent communication among
team members is essential to ensure that everyone is on the same page and
working towards the same goals.

● Planning and organization are critical: Developing a detailed project plan and
timeline is essential to ensuring that the project stays on track and deadlines are
met.

● Problem-solving is a valuable skill: Being able to identify and solve problems
quickly and efficiently is a critical skill in engineering projects.

● Flexibility is key: Plans and designs may need to be adapted or changed as the
project progresses, and being able to adapt to new challenges is essential.

● Thorough testing is essential: Testing is a critical part of the engineering process,
and it is important to conduct thorough testing to ensure that the product or
design functions as intended.

● Iteration is part of the process: Often, multiple iterations and revisions are
necessary to create a successful design or product.

● Documentation is important. Documenting the project thoroughly is necessary to
ensure that future team members can understand it and build on it.

● Continuous learning is valuable. This project will constantly evolve, and staying
up-to-date with new technologies and techniques is important to stay
competitive and produce high-quality work.

## Recommendations for future students

● Be proactive: Take the initiative to seek out additional resources if you're
struggling with the material. Ask your professor or TA for extra help, and don't
hesitate to form study groups with your classmates. Being proactive about your
learning can make a big difference in your success in the class.

● Stay organized: This class will likely require a lot of reading and writing
assignments, so it's essential to stay organized. Develop a system for keeping
track of due dates, notes, and other important information.

● Enhance your technical writing abilities: Writing technical reports and
presentations is a critical part of EGR 314. Improving your technical writing skills
will help you communicate your ideas more effectively in this class.

● Familiarize yourself with engineering software and tools commonly used in the
field, such as Cadence. Practice using these tools before the start of the course
to gain confidence and proficiency.

● Be curious and engaged in the subject matter, and don't be afraid to ask
questions and seek out additional resources to deepen your understanding.
Engage with your classmates and professors, and take advantage of
opportunities.

## Appendix A 
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/MQTT%20Table.png?raw=true)

## Appendix B
#include "mcc_generated_files/mcc.h"
//#include <stdio.h>
//#include <stdint.h>
//#include <stdbool.h>
#include "mcc_generated_files/examples/i2c2_master_example.h"
#include "mcc_generated_files/i2c2_master.h"

/*
                         Main application
 */
void main(void)
{
    SYSTEM_Initialize();
    SPI1_Initialize();
    INTERRUPT_GlobalInterruptEnable();

    // Enable the Peripheral Interrupts
    INTERRUPT_PeripheralInterruptEnable();

    uint8_t Temp;
    PWM4_Initialize();
    TMR2_Initialize();
    RA1_SetLow();

    // If using interrupts in PIC18 High/Low Priority Mode you need to enable the Global High and Low Interrupts
    // If using interrupts in PIC Mid-Range Compatibility Mode you need to enable the Global and Peripheral Interrupts
    // Use the following macros to:

    // Enable the Global Interrupts
    //INTERRUPT_GlobalInterruptEnable();

    // Disable the Global Interrupts
    //INTERRUPT_GlobalInterruptDisable();

    // Enable the Peripheral Interrupts
    //INTERRUPT_PeripheralInterruptEnable();

    // Disable the Peripheral Interrupts
    //INTERRUPT_PeripheralInterruptDisable();

    while (1)
    {
         PWM4_LoadDutyValue(0);
        if(EUSART1_is_tx_ready())
    {
      Temp = I2C2_Read1ByteRegister(0x4C, 0x00);

      printf("Temperature: %u C \n \r", Temp);
        }
      if(Temp>32)
      {
          PWM4_LoadDutyValue(1000);
          uint8_t dir1 = 0b11001111;
          uint8_t dir2 = 0b11001101;
           uint8_t receive;
   
     SPI1_Open(SPI1_DEFAULT);
      SS_pin_SetLow();

      receive = SPI1_ExchangeByte(dir1);
     SS_pin_SetHigh();
      SPI1_Close();

        __delay_ms(50);
     
      SPI1_Open(SPI1_DEFAULT);
      SS_pin_SetLow();


     receive = SPI1_ExchangeByte(dir2);

     SS_pin_SetHigh();
     SPI1_Close();
      __delay_ms(50);
         
    
        RA3_SetLow();
        __delay_ms(1000);
        
     RA1_SetHigh();
     __delay_ms(1000);
            
      }
    } 
    
}
## Appendix C
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/MCC%20Configuration.png?raw=true)

## Appendix D
![image caption](https://github.com/egr314-team303/egr314-team303.github.io/blob/main/Bill%20of%20Materials.png?raw=true)
