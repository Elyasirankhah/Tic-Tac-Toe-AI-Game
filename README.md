
# Tic-Tac-Toe AI Game
### An Interactive Educational Game for Introducing AI and Algorithmic Reasoning

## Overview

Tic-Tac-Toe AI Game is an interactive educational application designed to introduce children to fundamental concepts of artificial intelligence (AI), computational thinking, and algorithmic decision-making through gameplay.

Players compete against three AI opponents with different levels of strategic capability. By observing how each opponent responds to their moves, learners can explore how algorithms influence decision-making and game outcomes.

The game was developed as part of educational work investigating interactive approaches to introducing AI and machine learning concepts to elementary and middle school students.

## AI Opponents

The application features three AI opponents:

| Opponent | Difficulty | Decision-Making Strategy |
|----------|------------|--------------------------|
| Olivia | Easy | Randomly selects available moves |
| Emma | Medium | Combines random moves with strategic decisions |
| Chris | Advanced | Uses the Minimax algorithm to select optimal moves |

### Olivia — Easy
Olivia makes random valid moves without evaluating future outcomes, allowing beginners to explore the game and develop basic strategies.

### Emma — Medium
Emma combines random decisions with Minimax-based strategic moves. In the implementation, she selects an optimal move with a 70% probability and a random move otherwise.

### Chris — Advanced
Chris uses the Minimax algorithm to evaluate possible future game states and select optimal moves. Playing against Chris introduces learners to adversarial search, game trees, and strategic planning.

## Educational Objectives

The application aims to help learners:

- Understand how AI systems can use different algorithms to make decisions.
- Recognize differences between random and strategic decision-making.
- Explore fundamental concepts of search and reasoning.
- Develop problem-solving and computational thinking skills.
- Observe how algorithmic capabilities influence performance.

The educational design relates to the AI4K12 framework's Big Idea 2: **Representation and Reasoning**.

## Technologies

- Python
- Tkinter for the graphical interface
- Minimax algorithm for strategic decision-making
- Randomized decision-making
- Pillow for image handling
- Jupyter Notebook

## Getting Started

1. Clone the repository:

   `git clone https://github.com/Elyasirankhah/Tic-Tac-Toe-AI-Game.git`

2. Install the required Python packages, including Jupyter Notebook and Pillow.

3. Open `Tic Tac-Toe AI Game.ipynb` using Jupyter Notebook.

4. Run the notebook with `logo.png` available in the working directory.

5. Select an AI opponent and begin playing.

## Educational Research and Publications

The Tic-Tac-Toe application was included among five interactive AI and machine learning educational exhibits developed to introduce foundational AI concepts to children.

The exhibits were evaluated with 125 elementary and middle school students, aged 7–14. Within the broader study, 56 students interacted with the Tic-Tac-Toe exhibit and explored the different decision-making capabilities of its AI opponents.

This work is discussed in the following peer-reviewed ACM conference publications.

### 1. ACM SIGCSE 2024

**Perception, Trust, Attitudes, and Models: Introducing Children to AI and Machine Learning with Five Software Exhibits**

Martin, F., Vahedian Movahed, S., Dimino, J., Farrell, A., Irankhah, E., et al.

*Proceedings of the 55th ACM Technical Symposium on Computer Science Education (SIGCSE 2024), Volume 2*, pp. 1740–1741.

Published: March 15, 2024.

DOI: https://doi.org/10.1145/3626253.3635512

### 2. ACM CHI 2024

**Introducing Children to AI and ML with Five Software Exhibits**

Vahedian Movahed, S., Dimino, J., Farrell, A., Irankhah, E., et al.

*Extended Abstracts of the CHI Conference on Human Factors in Computing Systems (CHI EA 2024)*, Article 202, pp. 1–6.

Published: May 11, 2024.

DOI: https://doi.org/10.1145/3613905.3650991

## Screenshot

![Tic-Tac-Toe AI Game](https://user-images.githubusercontent.com/126001790/232905506-fc7e5aa5-b136-47d5-9583-f56c447608b7.png)


## Troubleshooting

- **Missing Pillow:** Install it using `pip install Pillow`.
- **Missing image file:** Ensure `logo.png` is in the same working directory as the notebook.
- **GUI not displaying:** Run the notebook in a local Python environment with Tkinter support.
- **Game not starting:** Make sure all required notebook cells have been executed.

