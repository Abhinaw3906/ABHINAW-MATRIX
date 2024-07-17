# ABHINAW-MATRIX
We propose a novel evaluation matrix for assessing text and typography in AI-generated images, addressing gaps in current benchmarking methods like CLIP SCORE and T2I-CompBench++. Our matrix uses automated tools for reproducible benchmarks, setting a new standard in text accuracy evaluation for AI image synthesis platforms.
Overview
Welcome to the Abhinaw Matrix project! This repository contains tools and instructions to evaluate the accuracy of text and typography in AI-generated images using our novel evaluation matrix.

Table of Contents
Getting Started
Prerequisites
Step-by-Step Guide
1. Generate Images
2. Use Abhinaw Matrix
3. Extract Data
4. Save Data
5. Gauge Exact Score
Contributing
License
Getting Started
To get started with the Abhinaw Matrix, follow the steps below to set up your environment and run the evaluation on your AI-generated images.

Prerequisites
Ensure you have the following installed:

Python 3.x
Required Python libraries (listed in requirements.txt)
Step-by-Step Guide
1. Generate Images
Generate images using your preferred AI text-to-image generation platform (e.g., MidJourney, DALL-E, Stable Diffusion).

2. Use Abhinaw Matrix
Use the Abhinaw Matrix tool available here to evaluate the generated images.


3. Extract Data
Extract the evaluation data in tabular format from the Abhinaw Matrix tool.

4. Save Data
Save the extracted data in CSV format.

bash
Copy code
# Save your data as abhinaw_matrix_output.csv
5. Gauge Exact Score
Use the provided Python code in this repository to gauge the exact score for your data.

Python Code
python
Copy code
import pandas as pd

# Load data
data = pd.read_csv('abhinaw_matrix_output.csv')

# Evaluate score using Abhinaw Matrix
def evaluate_text_accuracy(data):
    # Your evaluation logic here
    score = 0
    # Add evaluation details
    return score

score = evaluate_text_accuracy(data)
print(f"Text Accuracy Score: {score}")
Contributing
We welcome contributions! Please see the CONTRIBUTING.md for more details on how to contribute.

License
This project is licensed under the MIT License - see the LICENSE file for details.
