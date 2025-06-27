# Draw-It-or-Lose-It-Software-Design-Template

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room is a client that currently has an Android-only game called Draw It or Lose It. The client wanted a web-based version of the game that could work across multiple platforms, including mobile and desktop. The software needed to support multiple teams and players, use unique names for games and teams, and ensure only one instance of a game is active in memory at a time. They also required the game to be scalable, secure, and real-time.

2. What did you do particularly well in developing this documentation?
I think I did particularly well in clearly organizing the software requirements and translating them into a design that makes sense from both a technical and user perspective. I also feel good about the way I explained system architecture and used object-oriented principles, like inheritance and the Singleton pattern, to support the game’s functionality.

3. What about the process of working through a design document did you find helpful when developing the code?
Working through the design document helped me think ahead about how the code should be structured. It made me consider things like how data would flow through the system, how components like Game, Team, and Player would interact, and what kind of backend services were needed. Having a clear blueprint before coding made the development process a lot smoother..

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part, I’d improve the System Architecture View section by adding a visual diagram or flowchart. While I explained the architecture in words, a visual would help communicate the structure and flow between components more clearly.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I interpreted the user’s needs by focusing on the game’s real-time nature and the requirement to work across platforms. That’s why I chose technologies like WebSockets and used responsive design. Considering the user’s needs is important because it ensures the final product is actually usable and enjoyable. If the software doesn’t meet the user's expectations or platform needs, it doesn’t matter how well it’s built.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the design by breaking the game down into components and identifying how they would interact, using object-oriented programming and design patterns. In the future, I would continue using this modular approach, and also include more user flow diagrams, state diagrams, and mockups earlier in the process to better visualize how users will interact with the system before writing any code.
