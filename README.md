# CS-230-Operating-Platforms
# Reflection
This repository contains my Software Design Document that I worked on throughout the entirety of CS 230.
## Summary of the Software Design Project
The assignement was based around the client looking to expand their exisiting game into a scalable web-based application. Their main requirement was to redesign the game so it could run across multiple platforms while maintaining consistency and performance. The system needed to support multiple teams, unique game instances, and give each game and player a unique identifier. 

## What I Did Well in the Design Document
One of the strongest parts of my documentation was the Operating Platform Evaluation. Comparing Mac, Linux, Windows, and mobile platforms helped me clearly understand how the system would perform in different environments. This section also helped connect business requirements to technical decisions, such as cost considerations, compatibility, and scalability. It made it easier to explain why certain platforms would be more suitable for deployment than others. 

## How the Design Document Helped During Development
Creating the Domain Model was especially helpful when moving into coding. Defining a shared based class for Game, Team, and Player made the Java implementation much more organized. Because the relationships and shared attributes were already planned, there could be more focus on wriiting logic instead of figuring out structure during development. 

## What I Would Revise
If I could revise one part, I would improve the System Architecture section. While the written explanantion is clear, adding a visual diagram of how the system components interact would also make it easier to understand. Particularly, showing how the web server communicates with client-side applications in a distributed setup would improve clarity.

## Interpreting User Needs & Importance of User Focus
I interpreted user needs by focusing on accessibility, usability, and data interity. The main goal was to have the game work smoothly across different devices without needing extra effort from the user. 

## Approach to Software Design
My approach to software design was based on using design patterns early to solve structural challeges. Patterns like Singleton and Iterator helped guide how the system should be built from the beginning. 
