# Angular-Application-Internhsip
## Overview
This project was developed during a software development internship within the company's development department. The goal was to create a game similar to Candy Crush, utilizing the Angular framework. The project was structured into four key stages:

- Analysis: Defining essential game requirements and technical specifications.
- Design: Developing the game’s architecture and user interface.
- Implementation: Coding the game logic, interactions, and functionality in Angular.
- Testing: Ensuring the game operates seamlessly by debugging and optimizing.
The game features a dynamic 8x8 board where five distinct game elements are randomly generated, complete with a scoring system and a scoreboard to track progress across levels.
## Key Features
Functionalities
Game Board:
- An 8x8 grid with draggable elements.
- Match-3 mechanic to eliminate groups of at least three similar items.
- Dynamic falling and replacement of elements after matches.
  
Scoreboard:
- Displays player scores, time played, and levels achieved.
- Real-time updates for newly added scores.
- Integrated with an external API to fetch and post scores.
- API Integration

Testing Tools: Utilized Postman for API testing with POST and GET methods.

Endpoints:
- GET: Retrieve the scoreboard for specific levels.
- POST: Submit player scores, including name, points, time, and level.
- JSON Data Structure:
Example: { "player": "John", "score": 1200, "seconds": 300, "level": 2 }.
 
## Technical Highlights
Angular:
- Used directives like *ngFor for dynamic rendering.
- Created reusable components for modular development.
API:
- Implemented robust error handling for network calls.
- Ensured data validation and security during API communication.
Drag-and-Drop:
- Implemented drag-and-drop functionality for interactive gameplay.
- Verified valid moves and updated the board dynamically.
Scoring Logic:
- Calculated scores based on matched elements.
- Implemented cascading logic to handle multiple matches. 

Consult the [documentation](Doc.docx) for more details.
