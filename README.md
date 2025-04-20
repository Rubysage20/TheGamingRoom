# Draw It or Lose It
Draw It or Lose It - Software Design Overview
About the Client
The Gaming Room is a game development company currently operating an Android-based game called Draw It or Lose It. The game is loosely inspired by Win, Lose or Draw and involves teams competing to guess what is being drawn from a library of stock images. The client’s goal is to expand the game into a web-based, cross-platform application that maintains performance, consistency, and scalability across desktop and mobile environments.

Software Requirements
The Gaming Room requested that the new system:

Support multiple platforms with synchronized game states

Use a singleton pattern for managing game instances

Assign unique identifiers and names to games, teams, and players

Implement security best practices to protect game data

Ensure the app is scalable to handle many concurrent users

Use object-oriented principles such as inheritance and encapsulation

Support real-time communication, ideally with WebSockets

Strengths in Documentation
One of the areas I did particularly well was clearly outlining the system’s architecture and design patterns. I effectively documented the class structure using a domain model and described how each class—like Game, Team, Player, and GameService—follows solid object-oriented design. I also emphasized how encapsulation and inheritance help maintain clean code and simplify object relationships. The document outlines each component’s purpose and behavior, providing a strong foundation for implementation.

Value of the Design Process
Working through the software design document helped significantly when it came time to write code. By defining the domain model, constraints, and class responsibilities beforehand, I had a clear roadmap to follow. It was especially helpful when implementing the singleton pattern and ensuring unique data constraints—because those elements were already well-thought-out during the design phase. It made translating design into code much faster and more efficient, and it prevented me from making major architectural changes later on.

What I Would Improve
If I could revise one part of my documentation, it would be the System Architecture View section. While not required for the assignment, fleshing it out would have added clarity on how the game logic, server, database, and client components interact across a distributed system. I would improve it by creating a simple diagram and a logical tier-based explanation, showing how client requests flow through the server and interact with game state management.

Understanding and Implementing User Needs
I interpreted the client’s needs by focusing on scalability, uniqueness, and performance—which were clearly outlined in the constraints. I implemented validation for name uniqueness and ensured data structures supported efficient retrieval and updates. Considering user needs was central to every decision: from real-time gameplay to secure authentication. It’s important to consider these needs because users expect software that is responsive, intuitive, and secure. Failing to meet those expectations often leads to poor adoption and negative feedback, regardless of how well the system is built technically.

Future Strategy
My approach to software design began with identifying core responsibilities for each class and defining how they relate to one another. I used UML modeling, object-oriented principles, and design patterns (like Singleton and Iterator) to keep the structure simple and scalable. In future projects, I would continue using these strategies but also add:

Early prototyping or wireframes to visualize the user experience

Architecture diagrams to map out server-client interactions

Agile design techniques like iterative refinement and user feedback cycles

These additions would help ensure the software is not only well-structured but also user-centered and ready to scale in real-world environments.
