# GameAuth

How to start the GameAuth application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/gameauth-0.0.1-SNAPSHOT.jar server config.yml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`
******
Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a client that wanted to develop a web-based version of their game, "Draw It or Lose It." They required the software to support multiple teams and players, with unique game and team names, and only one instance of the game in memory at a given time.

What did you do particularly well in developing this documentation?
  One aspect I believe I did well in developing this documentation was ensuring clarity and completeness. I made sure to address all the client's requirements and provide detailed explanations of the design decisions made.

What about the process of working through a design document did you find helpful when developing the code?
  The design document served as a roadmap for developing the code. It helped in breaking down the requirements into manageable tasks and understanding the overall architecture of the software.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  One part I would revise is the section on security. While I mentioned encryption and secure communication protocols, I could have provided more detailed and specific security measures to protect user information.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  I interpreted the user's needs by focusing on usability and functionality. I designed the software to be user-friendly, with intuitive interfaces and smooth gameplay. Considering the user's needs is crucial because it     ensures that the software meets their expectations and provides a positive user experience.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
  I approached designing software by first understanding the requirements and then creating a high-level design that outlined the overall structure of the application. I then delved into the details of each component,       considering factors such as scalability, maintainability, and performance. In the future, I would continue to use similar techniques, but I would also focus more on modular design and testing to ensure the strength and    flexibility in the software.
