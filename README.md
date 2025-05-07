# Pokémon Combat Prediction

> A machine-learning pipeline to predict the winner of Pokémon battle logs (combats.csv) using Pokémon stats (pokemon.csv).

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Environment & Dependencies](#environment--dependencies)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Exploratory Data Analysis](#exploratory-data-analysis)  
7. [Data Preprocessing](#data-preprocessing)  
8. [Feature Engineering](#feature-engineering)  
9. [Modeling](#modeling)  
10. [Evaluation & Results](#evaluation--results)  
11. [Future Work](#future-work)  
12. [Contributing](#contributing)  
13. [License](#license)  
14. [References](#references)  
15. [Contact](#contact)  

---

## Project Overview

- **Objective:** Predict which Pokémon wins a head-to-head combat based on their stats.  
- **Motivation:** Enhance player insights and explore ML applications in game analytics.  

## Dataset

- **pokemon.csv**  
  - Features: `#`, `Name`, `Type 1`, `Type 2`, `HP`, `Attack`, `Defense`, `Sp. Atk`, `Sp. Def`, `Speed`, `Generation`, `Legendary`.  
- **combats.csv**  
  - Records: `First_pokemon`, `Second_pokemon`, `Winner`.  
- Source: Kaggle (“Winner in Pokémon combat prediction”, Weedle’s Cave)  

## Environment & Dependencies

- **Language:** Python 3.x  
- **Libraries:**  
  - `pandas`, `numpy`  
  - `scikit-learn`  
  - `matplotlib`, `seaborn`  
  - `scipy`  

## Installation

# Clone the repository
git clone https://github.com/Parlynx1/AIM-5005-1_Pokemon_Combat_prediction.git
cd AIM-5005-1_Pokemon_Combat_prediction


# (Optional) create & activate virtual environment
python3 -m venv venv
source venv/bin/activate

