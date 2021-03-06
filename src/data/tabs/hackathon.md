<h3 style="color: #36874a">oneM2M Hackathon</h3>

SUPERVISOR: THIERRY MONTEIL

<p style="text-indent: 2%; text-align: justify;">
    Every year, the ISS students must participate in a Hackathon. This year, Mr. Monteil chose the International oneM2M Hackathon managed by the Korean Electronic Technology Institute (KETI) and the European Telecommunication Standards Institute (ETSI).
</p>

<details>
    <summary style="color: #36874a">Description</summary>
    <figure style="text-align: center">
        <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/hackathon_circuit.png?raw=true"
            title="Circuit"
            height="200">
        <figcaption>Our system</figcaption>
    </figure>
    <figure style="text-align: center">
        <img src="https://github.com/ALievre/5ISS_Portfolio/blob/main/public/images/hackathon_dashboard.png?raw=true"
            title="Dashboard"
            height="200">
        <figcaption>Our dashboard</figcaption>
    </figure>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
       This Hackathon had international participants from Korea, India, Spain, Germany, USA, and France. It lasted one month from the 30th of September to the 4th of November. The deliverables were a huckster.io project describing the IoT solution we produced and a short demo video. The subject of this event was to build and IoT solution helping citizens with social or environmental issues using the oneM2M standard. Thus, it was a project with a close link to the Middleware & Service module.
    </p>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        With a team of 4 students (2 from AE, 1 from GP and 1 from IR), we decided to create a Smart Crop Monitoring and Growth Management to reduce water consumption. As agriculture represents nearly 70% of the world’s water consumption, a lot of systems have been developed to optimize the watering method. However, plant growth is almost never considered.  Moreover, we noticed a significant lack of databases informing us about the parameters influencing the plant growth parameters. It is in this context that we wanted to develop an intelligent monitoring system to fill the gaps identified. The main functionalities of our system are the following:
    </p>
    <ul style="text-align: justify;">
        <li>Monitor the growth of the plant, water consumption and external parameters (luminosity, temperature, soil humidity, …).</li>
        <br>
        <li>Remotely control the watering or define some strategic rules to automate plant watering.</li>
        <br>
        <li>Predict the amount of water to deliver to the plant to achieve a certain growth rate over a given period for a given plant.</li>
    </ul>
    <p style="margin-left: 2%; text-align: justify;">
        You can find our Hackster.io project on the following link:
        <a style="color: #36874a" href="https://www.hackster.io/haka/keti-hackathon-smart-crop-monitoring-and-growth-management-877d14">Smart Crop Monitoring</a>
        <br>
        You can find our GitHub repository here:
        <a style="color: #36874a" href="https://github.com/ALievre/Hackathon">GitHub Repository Hackathon</a>
    </p>
</details>
<br>
<details>
    <summary style="color: #36874a">Technical challenges</summary>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        During this Hackathon, we encountered many challenges:
    </p>
    <ul style="text-align: justify;">
        <li>The sensors. As a matter of fact, we used several analogic sensors. Thus, we needed to use a multiplexer since the ESP8266 only has one analogic pin. It took us some time to operate it and we even had to change it. Finally, we succeeded thanks to the help of online documentation.</li>
        <br>
        <li>The valve. First, we had issues finding one, but we managed to get it one week before the deadline. Then, it was not working with our system and we had to buy hoses to guide the water flow into the valve. Moreover, to have enough pressure to use the valve, we used a cat water fountain motor. In the end, everything was working but it took us some time to understand what was missing and then to collect all the material.</li>
    </ul>
</details>
<br>
<details>
    <summary style="color: #36874a">Analysis</summary>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        This project was undoubtedly stimulating. It was nice to work on a big project, with all the equipment at our disposal and on a subject that we cared about. Once again, that is the kind of project I expected to have in ISS. Moreover, having a team composed of students from different background was very refreshing. Working on every aspect of an engineering project was very rewarding.
    </p>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        Coming from an Electronics background, I was in charge of the hardware parts of the project. In the end, I also participated in all the other parts. I made modifications in the gateway and deployed it on the Raspberry Pi. I also made the Node-RED dashboard, tested the whole system and participated in the making of the demo video. Since I worked on the whole project (on the hardware, on the gateway and oneM2M platform, and on the dashboard), I can say that I acquired all the skills corresponding to these parts. I think I apprehended all the technical implications. 
    </p>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        The only downside was the time allocated to do the project. The deadline was set by the organizers but not knowing early that we will have to participate in a Hackathon did not prepare us. In addition, being required to team with students with different background was a really good idea but it would have been better if we knew it ahead of time. In fact, we did not really know each other so we randomly formed the teams.
    </p>
    <p style="text-indent: 2%; margin-left: 2%; text-align: justify;">
        Overall, it was a very good experience but a little bit tarnished by the lack of time.
    </p>
    <p>
        I can summarize the skills I acquired with this module:
    </p>
    <ul>
        <li>Use the oneM2M platform</li>
        <li>Create a Node-RED dashboard</li>
        <li>Conceive a circuit with a lot of sensors</li>
        <li>Deploy a gateway on a Raspberry Pi</li>
        <li>Use the Fritzing software to design a circuit</li>
        <li>Use an ESP32 to control sensors and send data</li>
    </ul>
</details>

<p>-oneM2M Hackathon-</p>