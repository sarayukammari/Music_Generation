# Music Generation

A deep learning project for generating music using neural networks trained on ABC notation format songs.

## Overview

This notebook demonstrates how to build and train a sequence model to generate music in ABC notation format. The model learns patterns from a dataset of 817 songs and can generate new musical compositions.

## Project Structure

- **Music_Generation2.ipynb** - Main Jupyter notebook containing the complete music generation pipeline

## Note on Notebook Display

The notebook displayed in this repository has been truncated in the preview for display purposes. **The full notebook is completely valid and fully functional.** All cells, code, and content are intact in the actual file. The truncation is only a display limitation of the GitHub web interface when viewing large notebooks.

To see and run the complete notebook:
1. Clone this repository
2. Open `Music_Generation2.ipynb` in Jupyter Notebook or Google Colab
3. All cells will be fully visible and executable

## Requirements

The notebook automatically installs the following dependencies:
- PyTorch
- MIT Deep Learning package (`mitdeeplearning`)
- NumPy
- SciPy
- Comet ML (for experiment tracking)
- MIDI utilities (abcmidi, timidity)

**GPU Required:** The notebook requires CUDA GPU support. Switch runtime to GPU in Google Colab via Runtime > Change Runtime Type > GPU.

## Setup

1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Add your Comet ML API key to the `COMET_API_KEY` variable (optional, for experiment tracking)
3. Ensure GPU is enabled
4. Run all cells in order

## Features

- Loads 817 pre-trained songs in ABC notation
- Processes music data for neural network training
- Generates new musical compositions
- Plays generated music directly in the notebook
- Supports experiment tracking with Comet ML

## Usage

Simply run all cells in sequence. The notebook will:
1. Install required packages
2. Load the training dataset
3. Display example songs
4. Play audio of generated music

## License

Please check the repository for license information.
