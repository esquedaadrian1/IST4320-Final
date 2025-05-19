# IST4320-Final
Project Purpose
The goal was to develop a functional calculator app using Python and Tkinter, meeting my professor's requirements of GUI implementation, custom functions, input handling, and GitHub deployment. While a calculator is a simple concept, the challenge was in ensuring clean code structure, proper error handling, and intuitive UI design.

Development Process
Initially, I considered more complex ideas (e.g., a finance tracker or quiz app), but given time constraints, I opted for a calculator to focus on execution quality. The project evolved through several iterations:

First Attempt: A basic layout with buttons and a display, but no error handling. Pressing "=" with no input crashed the app.

Second Iteration: Added input validation and basic arithmetic operations, but the UI was inconsistent across different screen sizes.

Final Version: Implemented grid weight management for responsive sizing, added a history feature, and refined error messages.

What Worked Well
- Handles basic arithmetic (+, -, *, /) cleanly with proper operator precedence.
- Catches division by zero and invalid expressions without crashing.
- Successfully logs past calculations (though it’s currently in-memory only).
- Settled on a clean, minimalist design after testing different fonts and layouts.

Challenges & Limitations
- The app doesn’t gracefully handle leading operators (e.g., pressing "+" first). A future fix would involve input sanitization.
- Currently, history is lost on app close—integrating SQLite would solve this.
- While functional, the layout could be more dynamic for larger screens.

Key Takeaways
- Learned how grid() and pack() behave differently, and why consistent weight management matters.
- Simple input validation prevents most crashes—worth the extra effort.
- Initially wanted a scientific calculator mode, but prioritized robustness over scope creep.

Future Improvements
If continuing this project, I’d:
- Use SQLite or a JSON file to save calculations between sessions.
- Allow typing expressions directly for faster input.
- Separate UI and logic into modules for better maintainability.
- Implement pytest to catch regression issues early.

Final Thoughts
This project reinforced the importance of planning before coding—I wasted time fixing layout issues that could’ve been avoided with a wireframe. That said, the end result is a stable, functional app that meets all requirements. With more time, I’d focus on extensibility (Plugins for scientific functions) and polish (animations, themes).
