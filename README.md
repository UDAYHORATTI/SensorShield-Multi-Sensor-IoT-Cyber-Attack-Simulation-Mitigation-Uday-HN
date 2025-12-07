# SensorShield-Multi-Sensor-IoT-Cyber-Attack-Simulation-Mitigation-Uday-HN
SensorShield is a virtual IoT security testbed simulating pulse and ultrasonic sensors to demonstrate real world cyberattacks like DoS, data injection, spoofing, and topic hijacking. It implements MQTT authentication, ACLs, and rate limiting to ensure secure, reliable IoT data communication.

 
Background

The Internet of Things (IoT) connects many lightweight devices and sensors that communicate automatically and continuously. Although this improves efficiency in sectors like healthcare, defense, and smart infrastructure, most IoT systems lack strong security. Lightweight protocols such as MQTT often operate without encryption or proper access control, making them vulnerable to attacks like data tampering, topic hijacking, and DoS. These weaknesses highlight the need for practical, low-cost IoT security frameworks.

Problem Statement

Many IoT environments transmit sensitive data without encryption and depend on weak communication protocols. As a result, attackers can alter sensor data, take control of devices, or disrupt services entirely. In mission-critical domains—such as healthcare monitoring or autonomous systems—false readings or system failures may lead to severe consequences. This project aims to study these vulnerabilities and design a controlled, secure testbed to analyze IoT attack behavior and mitigation strategies.

Project Motivation

Rapid IoT adoption in critical sectors inspired this work. Even a small misconfiguration in a medical sensor or an autonomous system can cause life-threatening failures. Classroom discussions and real-world cases highlighted how overlooked IoT weaknesses can escalate into major security incidents. This motivated the development of a virtual, safe environment to simulate attacks and evaluate defense mechanisms without relying on physical hardware.

Objectives

Build a virtual IoT model using Pulse and Ultrasonic sensors.

Simulate common IoT cyberattacks: MITM, topic hijacking, data injection, DoS, and spoofing.

Implement and test security measures including MQTT authentication, ACLs, and iptables-based rate limiting.

Visualize attack impact and improvements using a real-time Node-RED dashboard.

Strengthen understanding of IoT data integrity, availability, and secure communication.

Scope of the Project

The project uses Python-based virtual sensors and the Mosquitto MQTT broker to create a repeatable, hardware-free IoT security testbed. Four types of cyberattacks were simulated, and three defensive mechanisms were implemented. The Node-RED dashboard provides real-time monitoring to observe both normal operations and attack behavior. This safe environment allows hands-on testing of IoT threats and countermeasures.

Significance

This project provides a practical demonstration of how simple IoT systems can be exploited and how foundational security controls—authentication, ACLs, and rate limiting—can significantly improve resilience. It helps learners and professionals recognize IoT weaknesses, understand attack impact, and apply secure-by-design practices. The testbed offers a low-cost, reproducible model useful for research, education, and cybersecurity training.
