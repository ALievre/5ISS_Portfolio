<h3 style="color: #56b6c2">Smart Devices</h3>

SUPERVISOR: JÉRÉMIE GRISOLIA

<p style="text-indent: 2%; text-align: justify;">
    Smart devices based on sensors are an important part of all the devices surrounding us. In this course, we participated in the whole creation process of a gas sensor, from the nano-particle deposition to the signal acquisition on a microcontroller.
</p>

<details>
    <summary style="color: #56b6c2">Description</summary>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        This project is part of the 5ISS year formation at INSA Toulouse. We created a nanoparticle gas sensor in the AIME laboratory at INSA Toulouse. Then, we designed the PCB and the code to use the sensor with a LoraWAN protocol and display its data on a dashboard. The Smart Devices module gathers four classes that go over the different steps of production of a nanoparticle-based gas sensor. I summarized them in the table below. Then, I focused on the most relevant experiences: the nano-particle deposition to create the sensor and the M&OSH project.
    </p>
    <table style="border-collapse: collapse; border: 1px #56b6c2 solid; text-align: center; margin-left: 2%;">
    <tr style="border: 1px #56b6c2 solid; background-color: #56b6c2; color: #282c34; font-weight: bold;text-align: center; padding: 10px;">
       <th style="border: 1px #56b6c2 solid;">Class name</th>
       <th style="border: 1px #56b6c2 solid;">Context & Mission</th>
    </tr>
    <tr>
       <td style="border: 1px #56b6c2 solid; font-weight: bold;">Microcontrollers & Open-Source Hardware, Embedded IA (M&OSH)</td>
       <td style="border: 1px #56b6c2 solid;">Project developed in groups of two using the gas sensor we built. We used our sensor with an ESP32, creating a PCB board using KiCad and adding a Lora communication module to turn our sensor into a smart sensor sending data to The Things Network's cloud.</td>
    </tr>
    <tr>
       <td style="border: 1px #56b6c2 solid; font-weight: bold;">CAD, Manufacturing & Integration of Nano-Technology Sensors (AIME)</td>
       <td style="border: 1px #56b6c2 solid;">Internship at the AIME lab to follow and realize the process of creating the gas sensor with a nano-particles deposition on a silicium board.</td>
    </tr>
    <tr>
       <td style="border: 1px #56b6c2 solid; font-weight: bold;">Sensors Introduction</td>
       <td style="border: 1px #56b6c2 solid;">Theoretical lectures and practical works about the physical concepts of different types of sensors and how to create a sensor datasheet.</td>
    </tr>
    <tr>
       <td style="border: 1px #56b6c2 solid; font-weight: bold;">Analog Electronics Labs</td>
       <td style="border: 1px #56b6c2 solid;">Practical works destined to help us design the analog circuit that would transform the output value of our sensor (in the form of a resistance variation) to a usable signal going from 1V to 5V.</td>
    </tr>
    </table>
    <br>
    <details style="text-indent: 10%;">
        <summary style="color: #56b6c2">AIME Internship</summary>
        <figure style="text-align: center">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_AIME_GSWO3_4.jpg?raw=true"
                title="Gas sensor"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_AIME_GSWO3_1.jpg?raw=true"
                title="Gas sensor"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_AIME_GSWO3_3.jpg?raw=true"
                title="Nano-particles deposition"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_AIME_GSWO3_8.jpg?raw=true"
                title="Nano-particles deposition"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_AIME_GSWO3_9.jpg?raw=true"
                title="Finished gas sensor"
                height="100">
            <figcaption>Our gas sensor</figcaption>
        </figure>
        <p style="text-indent: 10%; margin-left: 10%; text-align: justify;">
            The first experience we had in the Smart Devices module was the internship in the AIME cleanroom. It lasted for a week, consisting in different half-day modules where we could oversee and manipulate the different processes involved in the manufacturing of a nano-particle sensor. The end goal was to make a gas sensor from Tungsten nano-particles, that expresses a variation of resistance when detecting specific gases (in our case Ethanol & Ammonia).
        </p>
        <p style="text-indent: 10%; margin-left: 10%; text-align: justify;">
            I describe the different steps we followed to make the sensor below: <br><br>
            1. &emsp; <b>Exposing the sensor circuit by photolithography:</b> without going into too much detail about the process of photolithography, we used it to engrave based on a mask on a silicium wafer. It is a pretty complex mask containing a heating resistance, a temperature sensor, and two interdigitated combs where we will make the deposition. <br><br>
            2. &emsp; <b>Making and deposing the nano-particles:</b> the next step was to create the Tungstene nano-particles and deposit them on the engraved wafer. To do so, we followed an extremely precise chemical process, using equipment having a 0.05 milliliter precision.
            Once we obtained the particles, we deposited them using a process called Dielectrophoresis. What we did was we put a drop of our very diluted solution containing the nano-particles on the entire sensor circuit, and then put an electrical field only on the intergititated combs part. This resulsted in the particles only "sticking" to the desired part when we rinced the solution in water. <br><br>
            3. &emsp; <b>Caraterising the sensor for the datasheet:</b> now that we had our sensor, we tried to caracterise it by generating some I/V curves, so that all the groups could use their data to create a datasheet. <br><br> 
        </p>
        <p style="text-indent: 10%; margin-left: 10%; text-align: justify;">
            Once the AIME internship was finished for all the groups and using the concepts we learned during the "Introduction to sensors" class, we were able to redact a datasheet that tries to be as close as possible to the ones you can find in the industry, made by professional mnufacturers. You can find the datasheet made by my group in the following link:
            <a style="color: #56b6c2" href="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/files/sdev_datasheet.pdf">Datasheet</a>
        </p>
    </details>
    <br>
    <details style="text-indent: 10%;">
        <summary style="color: #56b6c2">M&OSH Project</summary>
        <figure style="text-align: center">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_ARDUINO.jpg?raw=true"
                title="Arduino system"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_Schematic_PCB.PNG?raw=true"
                title="Circuit"
                height="200">
        </figure>
        <figure style="text-align: center">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_PCB.PNG?raw=true"
                title="PCB Board"
                height="200">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_PCB_3D.PNG?raw=true"
                title="3D PCB Board"
                height="200">
        </figure>
        <figure style="text-align: center">
            <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/sdev_NODERED_dashboard_ok.PNG?raw=true"
                title="Dashboard"
                height="200">
            <figcaption>M&OSH Project</figcaption>
        </figure>
        <p style="text-indent: 10%; margin-left: 10%; text-align: justify;">
            In this course, we had a lot of freedom to choose what direction we wanted to take: to follow proposed labs or to start a project directly related to our gas sensor. With my project partner, Assia Nguyen, we chose to start the porject to allow us to go further in the development of our sensor. It was a great follow-through since we can now use it with a shield, connect it to The Things Network and see the data on a Node-RED dashboard. The Arduino code used to retrieve and process the data was adapted for both the AIME gaz sensor and the industrial grove sensor given to us. We used a ESP32 as a microcontroller. I was very excited to start working on this project since its a culmination of what we did during the AIME internship and it showed me the complete process of making a sensor. 
        </p>
        <p style="margin-left: 15%;">
            Our work was divided into different steps:<br><br>
            1. &emsp; To test the LoRa connexion<br><br>
            2. &emsp; To implement a code that retrieves and sends data to The Things Network with LoRaWAN<br><br>
            3. &emsp; To conceive a PCB shield with KiCad<br><br>
            4. &emsp; To create a Node-RED dashboard to display the data and the controls of the sensor<br><br>
        </p>
        <p style="text-indent: 10%; margin-left: 10%; text-align: justify;">
            As a delierable for the project, we redacted a quick report in the form of a README file, follow the link to consult it:
            <a style="color: #56b6c2" href="https://github.com/MOSH-Insa-Toulouse/2021_2022_LIEVRE_NGUYEN">M&OSH Project</a>
        </p>
    </details>
</details>
<br>
<details>
    <summary style="color: #56b6c2">Technical challenges</summary>
    <br>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">Microcontroller and Open Source Hardware (M&OSH)</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            Because it involved many different skillsets, the M&OSH mini-project had different challenges:
        </p>
        <ul style="text-align: justify;">
            <li>Since we never used LoRa communication before, it took us some time to understand how to implement it. We were able to find multiple examples of code online so it helped us do this part faster.</li>
            <br>
            <li>Another difficulty was to connect our device to The Things Network. In fact, we never used it before. We did not know the process to create a TTN application and to connect our device to it took us some time to figure it out.</li>
            <br>
            <li>I also had difficulties to connect our TTN application to our Node-RED dashboard. Normally, there is a Node-RED node specifically design to receive datat from TTN. But, for unknown reasons, it is not working anymore. So, I had to use a MQTT node. It took me some time to configure it. Moreover, since TTN is not always working properly, I thought for a long time that my configuration was wrong when it was just the website not responding correctly.</li>
        </ul>
    </details>
    <br>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">CAD, Manufacturing & Integration of Nano-Technology Sensors (AIME)</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            We had difficulties obtaining good results when we tested our sensor. As a matter of fact, we had problems integrating the Tungsten nano-particles into the sensor. When we looked in the microscope to see our particles, we observed that there was a low concentration of nano-particles. Thus, we tried increasing the concentration of nano-particles by heating it to evaporate more water. Then, we tried once again to integrate the solution into our sensor but it was still not enough. Since we were running out of time, we used sensors made by last year students. It was so sad to see our work not functionning.
        </p>
    </details>
    <br>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">Sensors introduction</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            I chose to group the technical challenges of the last two classes together, because they served a similar purpose. In the introduction to sensors class, we had some theoretical lectures about the general physics principles of sensors, along with some physics practicals that brought back notions. It also gave us critical notions on how to design a good datasheet, what metrics to use and what errors to avoid.
        </p>
    </details>
    <br>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">Analog Electronics Labs</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            The Analog electronics labs were here to help us design the analog signal treatment part to exploit the values coming from our gas sensor. As said previously, the sensor's output is a resistance variation, which can be expressed as a current variation by imposing V (the tension). However, this current is really small, at about 100 nA, and we cannot measure it directly. So, we had to create a signal processing circuit to move the signal in a tension 1.1V to 5V, which corresponds to the range of the ADC of the Arduino Uno.
            Designing the circuit was pretty challenging, involving signal processing notions and filters that we had not used in a long time. Fortunately, we used the tool LTSpice, an electronics circuits simulator, to help us iterate over prototypes and test our results.
        </p>
    </details>
</details>
<br>
<details>
    <summary style="color: #56b6c2">Analysis</summary>
    <p>
        You can find explications on how to read the skills matrix by clicking on the table icon in the left bar.
    </p>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">Self-evaluation with the skills matrix</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            This module was one of my favorite one. It required the widest array of skills in electronics, signal processing, physics, and programming. I really feel that I acquired the skills expected.
        </p>
        <br>
        <table style="border-collapse: collapse; border: 1px #56b6c2 solid; text-align: center; margin-left: 2%;">
            <tr>
                <th style="border: 1px #56b6c2 solid; background-color: #56b6c2; color: #282c34; font-weight: bold;text-align: center; padding: 10px;" colspan="4">Introduction to sensors</td>
            </tr>
            <tr style="border: 1px #abb2bf solid; background-color: #abb2bf; color: #282c34">
                <td style="border: 1px #56b6c2 solid;">Skill</th>
                <td style="border: 1px #56b6c2 solid;">Required level</th>
                <td style="border: 1px #56b6c2 solid;">Self-evaluation</th>
                <td style="border: 1px #56b6c2 solid;">Learning mode</th>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Understand basic notions of sensors, data acquisition: physics, electronics and metrology point of view</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to manufacture a nano-particles sensor using micro-electronics tools: chemical synthesis, assembly, testing</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to design the datasheet of the sensor manufactured</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT + PE</td>
            </tr>   
        </table>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            For the Introduction to Sensors skillset, my background in Electronics really helped me understand what was expected of me. The cleanroom sessions were well explained so we could understand every step of the process. The datasheet was more challenging to write but coming from AE helped me since I already knew how to read a datasheet. Teamwork was also a big part of this training and helped me overcome the challenges I faced.
        </p>
        <table style="border-collapse: collapse; border: 1px #56b6c2 solid; text-align: center; margin-left: 2%;">
            <tr>
                <th style="border: 1px #56b6c2 solid; background-color: #56b6c2; color: #282c34; font-weight: bold;text-align: center; padding: 10px;" colspan="4">Microcontrollers and Open Source Hardware</td>
            </tr>
            <tr style="border: 1px #abb2bf solid; background-color: #abb2bf; color: #282c34">
                <td style="border: 1px #56b6c2 solid;">Skill</th>
                <td style="border: 1px #56b6c2 solid;">Required level</th>
                <td style="border: 1px #56b6c2 solid;">Self-evaluation</th>
                <td style="border: 1px #56b6c2 solid;">Learning mode</th>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Understand microcontroller archictecture and how to use them</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT + ST</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to design data acquisition system (sensor, conditioner, microcontroller) with respect to the application</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT + ST</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to design the electronic circuit of a sensor’s signal conditioner (design + simulation)</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT + PE</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to design a shield to accommodate the gas sensor</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be abe to design the sofware to use the gas sensor and its HMI</td>
                <td style="border: 1px #56b6c2 solid;">3</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT + ST</td>
            </tr>
            <tr>
                <td style="border: 1px #56b6c2 solid;">Be able to combine all of the above mentioned components into a smart device</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">4</td>
                <td style="border: 1px #56b6c2 solid;">IT</td>
            </tr>
        </table>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            As for the M&OSH skillset, I really felt invested because that is the type of project I really like. Coming from AE and from personal projects, I already had previous experience to help me with this project. Since this module had more AE notions, I already had some skills about circuits, PCB board, Arduino microcontroller and ESP32. The lectures were a good reminder of electronics, physics and programming notions.
        </p>
        <p>
            I can summarize the skills I acquired with this module:
        </p>
        <ul>
            <li>Conceive a nan-particles based sensor in a cleanroom</li>
            <li>Establish communication between a sensor and a gateway with LoRaWAN</li>
            <li>Display the data with a Node-RED dashboard</li>
            <li>Write a datasheet</li>
            <li>Program an ESP32</li>
            <li>Use LTSpice to conceive a circuit</li>
            <li>Use KiCad to design a PCB board</li>
        </ul>
    </details>
    <br>
    <details style="text-indent: 2%;">
        <summary style="color: #56b6c2">General review and feedback on the course</summary>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            As I already said, this module was one of my favorites of the year. Participating in the entire creation process of a sensor was nice, from the creation in a cleanroom to the implementation of the sensor in a real project. I think that this module was what I expected when I chose to study ISS. I really sensed that I was acquiring or strengthening many skills during this project. I also really liked the freedom we had to choose what we wanted to do. It showed that the professors really tried to adapt this module to every different backgrounds.
        </p>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            I am happy to have chosen the project. I think that all the complementary classes really helped with the main project. I really felt that every classes had a purpose and were useful to carry out the project.
        </p>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            However, I think that the scheduling of this module was not perfect. For example, we directly did the AIME lab sessions before having the Introduction to Sensors class. We also did not have time to print the PCB boards and I wad a little bit disappointed by that. As a matter of fact, I was really enthusiast about fully creating a PCB board. I really invested myself into designing the board. So, it was sad not to have the final product and not being able to use the sensor we manufactured. That being said, it was still a really good experience that I loved doing.  
        </p>
        <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
            To conclude, I feel that this module was the embodiment of what I wanted to do in ISS. It is one the modules where I was the most invested in. I can positively say that I learn a lot and that I had a lot of fun doing it.
        </p>
        <br>
    </details>
</details>

<p>-Smart devices courses-</p>