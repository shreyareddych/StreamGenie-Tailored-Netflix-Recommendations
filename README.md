# Netflix Recommendation System

A Streamlit-based movie recommendation system that suggests personalized movie titles based on user preferences. This project utilizes a dataset of Netflix titles and user data to deliver tailored recommendations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to provide personalized movie recommendations by analyzing user preferences and matching them with available Netflix titles. The application is built using Python and Streamlit, offering an interactive web interface for users to receive movie suggestions.

## Features

- Interactive web application using Streamlit
- Personalized movie recommendations based on user input
- Utilizes Netflix titles dataset for generating suggestions
- Simple and intuitive user interface

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sahasra24/netflix-recommendation-system.git
   cd netflix-recommendation-system
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Streamlit application:**

   ```bash
   streamlit run streamlit_app.py
   ```

2. **Access the application:**

   Open your web browser and navigate to `http://localhost:8501` to interact with the recommendation system.

## Project Structure

```
netflix-recommendation-system/
├── .devcontainer/
├── Netflix- Recommendation-System.pdf
├── Netflix.xlsx
├── Project Charter.pdf
├── Project Planner.mpp
├── README.md
├── requirements.txt
├── streamlit_app.py
└── user_data.csv
```

- `streamlit_app.py`: Main application script for the Streamlit interface.
- `requirements.txt`: List of Python dependencies.
- `Netflix.xlsx`: Dataset containing Netflix titles.
- `user_data.csv`: Sample user data for generating recommendations.
- `Netflix- Recommendation-System.pdf`: Project documentation.
- `Project Charter.pdf`: Project charter outlining objectives and scope.
- `Project Planner.mpp`: Project planning file.

