# Documentation for Trip Planner From Scratch

## Introduction
The "Trip Planner From Scratch" project is a Python-based application that allows users to plan and organize their travel itineraries. The application is built using the Flask web framework and aims to provide a user-friendly interface for creating, managing, and tracking trip details.

## Key Features
- Create and save trip plans with customizable details
- Add tasks and activities to each day of the trip
- Track task status (completed, in progress, etc.)
- Generate packing lists and budget estimates
- Receive safety tips and recommendations for the selected destinations

## Getting Started

### Prerequisites
- Python 3.7 or higher

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mayankchugh-learning/trip-planner-from-scratch.git
   ```
2. Navigate to the project directory:
   ```bash
   cd trip-planner-from-scratch
   ```
3. Install the dependencies using Poetry:
   ```bash
   poetry install --no-root
   ```

### Running the Application
1. Execution
   ```bash
   poetry main.py
   ```
2. Access the application in your web browser at `http://localhost:5000/`.

## Creating Agents
To build the trip planner application, the project uses a modular approach with different "agents" responsible for specific tasks. The agents work together to create the final trip plan. Here's a cheat sheet for creating the agents:

### Captain/Manager/Boss: Expert Travel Agent
- Responsible for overall trip planning and coordination
- Delegates tasks to other agents
- Ensures the team is working towards the goal

### Employees/Experts:
1. **City Selection Expert**
   - Researches and recommends the best destinations for the trip
   - Provides information on attractions, transportation, and accommodation

2. **Local Tour Guide**
   - Provides detailed information and recommendations for activities, local customs, and safety tips in the selected destinations

## Workflow
1. The Expert Travel Agent (Captain) defines the goal of creating a 7-day travel itinerary with detailed per-day plans, including budget, packing suggestions, and safety tips.
2. The Captain hires the City Selection Expert and Local Tour Guide to assist with the planning process.
3. The City Selection Expert researches and recommends the destinations for the trip.
4. The Local Tour Guide provides detailed information and recommendations for the selected destinations.
5. The Captain integrates the information from the experts, creates the trip itinerary, and manages the overall planning process.
6. The final trip plan is presented to the user, including the itinerary, budget, packing suggestions, and safety tips.

## Conclusion
The "Trip Planner From Scratch" project aims to provide a user-friendly tool for planning and organizing travel itineraries. By using a modular approach with specialized agents, the application can leverage the expertise of different domain experts to deliver a comprehensive trip planning experience.


https://github.com/joaomdmoura/crewAI-examples

https://github.com/bhancockio/crew-ai-crash-course


```bash
https://python-poetry.org/docs/#installing-with-the-official-installer
```

poetry --version

poetry new weather_api

poetry env list

poetry env use python

poetry env list

poetry add flask

poetry show

poetry run python   

poetry run python main.py

poetry run python app.py

export FLASK_APP=app.py

poetry run flask run

poetry add black

poetry remove black

poetry add black --group dev

pydantic = "^2.0.2"

poetry lock

poetry install

poetry export > requirement.txt

poetry install --no-root

which python

poetry shell

source "$( poetry env list --full-path | grep Activated | cut -d' ' -f1 )/bin/activate"

alias activate_poetry="source \"\$(poetry env list --full-path | grep Activated | cut -d' ' -f1 )/bin/activate\""