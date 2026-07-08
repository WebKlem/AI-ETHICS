# Phase 1: Build Foundation (you first)

    Next, I designed a simple scenario with six devices to practice applying these concepts. The devices are Router A, Router B, Router C, Laptop 1, Laptop 2, and a Printer. In this design, Router A connects to both Router B and Router C. Router B connects to Laptop 1, while Router C connects to Laptop 2 and the Printer. This small network allows me to visualize how data would flow between devices and how routers communicate to determine the best paths.

    For this scenario, I chose to use RIP, a distance vector protocol, because the network is small and simplicity is sufficient. RIP allows each router to share information about the number of hops to each destination, which is easy to manage in a small network like this. However, I recognize that if the network grows or if faster convergence is needed when a link fails, OSPF, a link state protocol, would be more appropriate because it can calculate the most efficient paths using a complete network map and reacts quickly to topology changes.

    After designing the scenario and justifying my choice, I plan to use AI to probe deeper. I can ask AI to evaluate my design, suggest improvements, and explain in detail why another protocol might perform better under different conditions. By doing this, I combine my initial understanding with AI-assisted analysis, which helps me learn the technical topic more effectively while practicing the “right way” to use AI for learning.


# Phase 2: Strategic AI Use

    Test your understanding, explore edge cases with targeted questions, then validate.

        Here’s a revised version in sentences using your perspective:

        First, I tested my understanding by asking myself targeted questions about my network design and the routing protocols I chose. I asked, “What happens if Router B fails? Can Laptop 1 still communicate with Laptop 2?” and “How does RIP handle loops in this small network?” These questions helped me explore possible edge cases and check my understanding.

        Next, I explored unusual scenarios by asking, “What happens if I suddenly add five more routers? Will RIP still converge correctly?” and “What happens if the link between Router C and Laptop 2 goes down temporarily? How fast can OSPF recover compared to RIP?” These edge cases made me think critically about limitations and failure points in my design.

        Finally, I validated my answers by reasoning through them first and then asking AI to check my conclusions. I asked, “In my six-device network using RIP, what happens if Router B fails? Would OSPF handle this better?” This helped me confirm my reasoning, identify gaps, and deepen my understanding without letting AI do the work for me.

        By testing my understanding, exploring edge cases, and validating with AI, I actively learned the topic, anticipated potential problems, and used AI responsibly to strengthen my technical knowledge.


# Phase 3: Real Application

    Design a small smart-city network (1,000 IoT sensors, 50 traffic lights, 10 emergency vehicles). Decide protocols, justify choices, list failure points, then refine with AI feedback.

        From my point of view, I would design the small smart-city network by choosing communication protocols based on the needs of each device.

        For the 1,000 IoT sensors, I would use MQTT because it is lightweight and efficient for sending small amounts of data like temperature or air quality readings.

        For the 50 traffic lights, I would use HTTP since it is simple, reliable, and suitable for sending control commands such as changing signal colors.

        For the 10 emergency vehicles, I would combine MQTT with 5G because 5G provides fast and low-latency communication, which is important when traffic lights need to change quickly during emergencies.

        I would include a central control server to collect sensor data and manage traffic light operations.

        I believe the main failure points could be server crashes, internet outages, power failures, 5G network disruption, and cyberattacks.

        To reduce these risks, I would add backup servers, local offline control for traffic lights, battery support, and strong security measures like encryption and authentication.


# Reflection:

    % human judgment vs. AI contribution

        From my point of view, the smart-city system should be about 60% human judgment and 40% AI contribution.
        Humans should make critical and ethical decisions, while AI handles data analysis, traffic prediction, and automatic adjustments.
        AI supports the system, but humans should remain in control for safety and oversight.


    Could you defend decisions without AI?

         i can in my own understanding.



    What will you still remember in 6 months? 

            i can remember most of my quest.



    Did AI make you sharper, or think for you?
         
         AI makes me sharper and think deep.

