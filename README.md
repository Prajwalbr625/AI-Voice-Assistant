# AI Voice Assistant

This repository contains a pipeline that takes a voice query command, converts it into text, uses a Large Language Model (LLM) to generate a response, and then converts the output text back into speech. The system should have low latency, Voice Activity Detection (VAD), restrict the output to 2 sentences, and allow for tunable parameters such as pitch, male/female voice, and speed.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Prajwalbr625/AI-Voice-Assistant.git
   cd ai-voice-assistant
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter notebook:**

   ```bash
   jupyter notebook
   ```

   Open the `AI Voice Assistant.ipynb` file in Jupyter Notebook to explore and run the project.

## Usage

This project can be used as a base for developing a custom AI Voice Assistant. The notebook provides step-by-step implementation details, making it easy to understand the workflow and adapt it to your needs.

To execute the assistant, run all cells in the notebook and interact with the assistant via voice commands.

## Project Structure

- **`AI Voice Assistant.ipynb`:** The main notebook containing all code and explanations.
- **`requirements.txt`:** A file listing all the dependencies required to run the project.
