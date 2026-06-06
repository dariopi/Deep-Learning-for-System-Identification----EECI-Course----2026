# Deep Learning for System Identification 
This repository contains the material for the EECI course Deep Learning for System Identification, held in Milan from June 30 to July 4, 2025.

## Program
The Program of the course can be found in the document [Program.pdf](Program.pdf)

## Lessons
Slides of the lessons can be found in the folder [lessons](lessons)

## Exercises

Jupyter notebooks related to the exercise sessions can be found in the folder [exercises](exercises)

## Software Requirements

We recommend setting up a **Conda virtual environment** with Python and the required packages for this course.


1. **Install Anaconda**  
  Follow the official [Anaconda installation guide](https://www.anaconda.com/docs/getting-started/anaconda/install) for your operating system.

2. **Get the course repository**
  - If you have Git installed, clone the repository:
    ```bash
    git clone https://github.com/dariopi/dl-sysid-eeci2026
    ```
  - Alternatively, download it as a ZIP file from [this link](https://github.com/forgi86/dl-sysid-eeci2025/archive/refs/heads/main.zip) and extract it.

3. **Create and activate the Conda environment**  
  Open a terminal, navigate to the project's root directory, and run:
  ```bash
  conda create --name eeci python=3.13
  conda activate eeci
  pip install -r requirements.txt
 ```
This will create a virtual environment named eeci and install all the dependencies listed in [requirements.txt](requirements.txt).

4. **Run notebooks in jupyter**
All course examples are provided as Jupyter Notebooks. To launch the notebook interface, navigate to the folder containing the .ipynb file you wish to open, then run in a terminal:
```bash
conda activate eeci
jupyter notebook
```
Advanced user may opt for alternative setups such as venv, Docker, and different development environments like VSCode, PyCharm, etc., provided all required dependencies are installed and notebooks run as expected.

