# ReverbLab

## Overview

Welcome to the ReverbLab! This repository is dedicated to the implementation and analysis of various digital reverb algorithms. The project aims to help students and researchers understand the different techniques used to create digital reverberation effects in audio processing.

## Project Structure

The project is divided into two main phases:

### Phase 1: Jupyter Notebook Implementations

- **Algorithms**: Various digital reverb algorithms are implemented in Python using Jupyter notebooks. Each algorithm includes detailed documentation and analysis.
  - Schroeder Reverb
  - Moorer Reverb
  - Convolution Reverb
  - Feedback Delay Network (FDN)
  - And more...

- **Documentation**: Each notebook contains in-depth explanations and visualizations of the algorithms. Graphs and plots illustrate the effect of different parameters on the reverb.
- **Example Audio Files**: A set of example audio files is provided for testing and demonstrating the algorithms.

### Phase 2: Windows Application

- **Implementation**: All the algorithms from Phase 1 will be wrapped into a Windows 11 application using C++ and the JUCE framework.
- **GUI Design**: The application will follow Microsoft's Fluent Design System to provide a modern and intuitive user interface.
- **Purpose**: The application aims to serve as a tool for students and researchers to experiment with and understand digital reverb algorithms.

## Getting Started

### Prerequisites

- **Python**: Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
- **Jupyter**: Install Jupyter Notebook by running `pip install notebook`.
- **Required Libraries**: Install the necessary Python libraries using `pip install librosa scipy matplotlib`.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/digital-reverb-algorithms.git
   cd digital-reverb-algorithms
