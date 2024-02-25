
# Pacman Ghostbusters Project

## Introduction
In this exciting chapter of Pacman's legacy, we delve into the era of Grandpac, Pacman's great grandfather, who once hunted ghosts for sport. Unlike Pacman's evasion strategies, Grandpac mastered the art of ghost hunting, guided solely by the cacophony of ghostly noises. This project challenges you to develop Pacman agents that utilize sensory data to locate and devour invisible ghosts, advancing from tracking stationary specters to pursuing packs of phantoms with unmatched precision.

### Key Features
- Development of agents capable of sensing and hunting invisible ghosts.
- Utilization of Bayes' Nets for ghost location inference through noisy sensor data.
- Implementation of exact and approximate inference techniques to handle single and multiple moving targets.

### Dependencies
- Python (version 3.x recommended). The project doesn't require additional dependencies beyond Python.

## Usage
The project includes an autograder for self-assessment, executable for individual questions or the entire suite:

```bash
python autograder.py
python autograder.py -q q2
```

For testing specific components, including graphical output:

```bash
python autograder.py -t test_cases/q2/0-small-tree --graphics
```

## Files and Directories
- **To Edit and Submit**:
  - `bustersAgents.py`: Your ghost-hunting agents.
  - `inference.py`: Inference mechanisms for ghost tracking.
  - `factorOperations.py`: Computational utilities for probability tables.
- **Core Components** (No need to edit):
  - `busters.py`: Main game entry, replacing `pacman.py`.
  - `bustersGhostAgents.py`: Ghost agents for this variant.
  - Other supporting files include AI logic (`game.py`, `ghostAgents.py`), graphical interfaces (`graphicsDisplay.py`, `graphicsUtils.py`, `keyboardAgents.py`), and utilities (`distanceCalculator.py`, `layout.py`, `util.py`).

## Ghostbusters and Bayes Nets
Embrace the role of a ghost-hunting Pacman equipped with sonar to detect invisible ghosts through noisy distance readings. Your task is to refine these readings into precise ghost locations using Bayes Nets, balancing exact and approximate inference methods to optimize hunting strategies.

## Advanced Ghost Tracking
From the foundations of ghost sensing, you'll progress to sophisticated inference algorithms. Starting with the construction of a Bayes Net for the ghost-hunting domain, you'll tackle exact inference through variable elimination, leveraging observations and time dynamics to pinpoint ghost locations. Approximate methods, including particle filtering, will further refine your agents' efficiency in diverse and complex scenarios.

## Contributing
While this project was primarily an academic exercise, contributions or suggestions for improvements are welcome. Please open an issue or a pull request if you have suggestions.

## License
This project is licensed under the MIT License - see the https://inst.eecs.berkeley.edu/~cs188/sp22/projects/ file for details.

## Acknowledgments
- Course staff and fellow students for their support and feedback.
- The original creators of Pacman for inspiring this educational project.
