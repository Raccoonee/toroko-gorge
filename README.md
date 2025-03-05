# Toroko Gorge

A procedural text generation project inspired by Nick Montfort's "Taroko Gorge" poetry generator. This project analyzes classic literature texts to create a weighted random text generator that produces new phrases based on word frequencies from the source texts.

## Project Overview

Toroko Gorge processes classic literature from Project Gutenberg, analyzes word frequencies, and uses this data to generate new text combinations. The project includes:

1. Text cleaning scripts to prepare the source material
2. Word frequency analysis of the cleaned texts
3. A web-based text generator that creates phrases using weighted random selection

## Text Sources

All source texts are from [Project Gutenberg](https://www.gutenberg.org/), a library of free eBooks consisting primarily of public domain works. The texts used in this project include:

- Alice in Wonderland by Lewis Carroll
- The Book of Ten Fishes
- Dracula by Bram Stoker
- Pegasus by Henry O. Dyar
- Pride and Prejudice by Jane Austen

Project Gutenberg texts include standard headers and footers with license information, which are removed during the cleaning process to focus on the literary content.

## Technology Used

### Python
- Used for text processing and cleaning (sample_cleaning.py)
- Removes Project Gutenberg headers and footers from the source texts
- Prepares clean versions of the texts for analysis

### Text Analysis
- Word frequency counting to identify the most common words in each text
- Categorization of words by part of speech (nouns, verbs, adjectives, etc.)
- Results stored in markdown files for reference

### Web Technologies
- HTML/CSS for the user interface
- JavaScript for the text generation logic
- Weighted random selection based on word frequencies from the source texts
- Pattern-based phrase construction

## How to Use

1. Open `toroko-remix.html` in a web browser
2. Click "Toggle Auto-Generate" to start automatic text generation
3. New phrases will appear every few seconds
4. Click "Clear All" to reset the output

## Project Structure

- `sample_cleaning.py`: Script to clean Project Gutenberg texts
- `toroko-remix.html`: Web-based text generator
- `text files/`: Directory containing:
  - Original source texts from Project Gutenberg
  - Cleaned versions of the texts
  - Word frequency analysis files

## Credits

- Original concept inspired by Nick Montfort's "Taroko Gorge"
- Source texts provided by Project Gutenberg
- Developed by Devin Dennis
