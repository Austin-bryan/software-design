# CS-230 – Software Design Reflection: The Gaming Room

## 1. Briefly summarize The Gaming Room client and their software requirements.
The Gaming Room is a client who originally developed an Android only game called *Draw It or Lose It*. They hired us to design a web-based version of the game that is scalable, supports multiple platforms, and uses a clean architecture. They required the game to allow for multiple teams and players, ensure unique names for each, and maintain only one instance of the game in memory.

## 2. What did you do particularly well in developing this documentation?
I clearly mapped out the relationship between classes using object-oriented principles and explained my design decisions using plain language that a non-technical client could understand. I also gave detailed platform comparisons and design constraints to support real-world deployment.

## 3. What about the process of working through a design document did you find helpful when developing the code?
Breaking the project into components early helped me think more clearly about how classes would interact. The UML and design constraints kept me focused on fulfilling the requirements logically.

## 4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would refine the language in the evaluation table to more explicitly label answers to each rubric question. I’d also revise the executive summary to be a bit more concise and client-friendly.

## 5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I interpreted the client’s needs through the lens of platform support, scalability, and usability. By focusing on platform compatibility, RESTful communication, and clear class structures, I ensured that the application would meet both functional and technical requirements. Considering user needs ensures the end product is not only functional but also maintainable and accessible to its intended audience.

## 6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I started with high-level architecture (client-server), then identified reusable patterns (singleton, iterator) and enforced consistency with inheritance. In the future, I’d continue using UML diagrams, constraint analysis, and platform evaluations to guide both planning and implementation phases.
