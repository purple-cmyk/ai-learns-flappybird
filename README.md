# Flappy Bird AI using NEAT

A Flappy Bird implementation where AI agents learn to play the game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. Neural networks evolve over generations, gradually improving their ability to navigate obstacles and achieve higher scores.

## Features

* Flappy Bird game built with Pygame
* AI training using NEAT
* Automatic neural network evolution
* Fitness-based selection and mutation
* Training statistics and visualization
* Configurable NEAT parameters

## Project Structure

```text
project/
│
├── main.py                    # Game and training logic
├── visualize.py               # Visualization utilities
├── config-feedforward.txt     # NEAT configuration
├── requirements.txt           # Dependencies
│
├── imgs/
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── base.png
│   └── bg.png
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <project-directory>
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

```bash
# Linux / macOS
source venv/bin/activate

# Windows
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

## How It Works

Each bird is controlled by a neural network. The network receives information about the bird and the upcoming pipe and decides whether to jump.

Over multiple generations:

1. Birds play the game.
2. Fitness scores are assigned.
3. The best genomes reproduce.
4. Mutations create new variations.
5. Performance improves through evolution.

## Configuration

NEAT parameters can be modified in:

```text
config-feedforward.txt
```

This includes population size, mutation rates, fitness thresholds, and network settings.

## Visualization

Training and network visualization utilities are available in:

```text
visualize.py
```
