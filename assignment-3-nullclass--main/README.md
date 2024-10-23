# Task 3: Create a feature to translate the language from French to Tamil and it should predict if the french word has only five letter if the french word has more than five letters or less than five letters the model should not translate the word 


## Overview
This task involves translating French words to Tamil, but only if the French word is exactly five letters long. Words with a different length are not translated.

## Model
- The model uses a sequential architecture to handle the translation.
- Constraints are applied to check word length before translation.

## Data
- Data consists of French-Tamil translation pairs.
- Sentences are preprocessed and tokenized.

## Files
- `task3.ipynb`: Contains the translation model and constraints.
- `gui.py`: GUI script to interact with the model.

## Setup
1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd <repo_name>