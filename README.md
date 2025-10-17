# Weber's Law Auditory Time Perception Experiment

This repository accompanies the project "Establishing Weber's Law for Time Perception using Auditory Interval Discrimination", conducted at Indian Institute of Science.

## Overview

This project investigates Weber's Law in the context of human time perception using an online psychophysics experiment (adaptive staircase) and rigorous analysis. The codebase includes:

- Experiment UI for data collection (task website)
- Example participant data
- Full Python/Jupyter analysis pipeline and plotting scripts

Key findings replicate classic Weber's law for temporal interval discrimination, quantify just noticeable differences (JNDs) and Weber fractions, and explore individual differences and reaction time patterns.

## Repository Structure

- **/UI-code/** — Source files and design for the online auditory discrimination experiment
- **/Data/** — Sample datasets (trial-by-trial responses per subject)
- **/Result.ipynb** — Cleaned Jupyter notebook for data analysis, threshold calculation, visualization, and statistical testing

## Live Links

- **Raw Experimental Data:**  
  [Google Sheets Dataset](https://docs.google.com/spreadsheets/d/1llkrzHlXf2ex6RKVSfD0Bteo5CvndS9lzRVMnnp2ZZ4/edit?gid=0)
- **Online Task UI Demo:**  
  [Task website](https://midnight-koffee.github.io/weber-law-experiment/)
- **Analysis Code:**  
  [Python/Jupyter notebook](https://github.com/midnight-koffee/weber-law-experiment/blob/main/Result.ipynb)

## How to Run

1. Clone or download this repository.
2. Open `Result.ipynb` and run in [Google Colab](https://colab.research.google.com/) or locally in Jupyter Lab.
3. Download or point to your dataset as needed (`weber_final_data.csv`).
4. Execute cells to reproduce threshold calculation, plots, and statistics.

## Data & Code Accessibility

All data and code in this repo are fully open for non-commercial reuse and replication. Citing this repo and/or the linked publication is appreciated.

## Acknowledgments

- Much of the code in this repository was developed with the assistance of AI coding tools (e.g., OpenAI GPT), then verified and adapted by the author.
- Core experimental questions are based on "Sensation & Perception Assignment 1" by S.P. Arun (IISc).
- Background references:  
  - [Wikipedia: Weber–Fechner law](https://en.wikipedia.org/wiki/Weber%E2%80%93Fechner_law)  
  - [NYU S&P Handout](https://www.cns.nyu.edu/~msl/courses/0044/handouts/Weber.pdf)

---

For questions, collaborations, or data reuse, contact: [your email here]
