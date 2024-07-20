# PRODIGY_GA_03
Implementing a simple text generation algorithm using Markov chains.This task involves creating a statistical model that predicts the probability of a character or word based on the previous ones.

# Simple Text Generation using Markov Chains

## Overview
This project involves implementing a simple text generation algorithm using Markov chains. The algorithm builds a statistical model that predicts the probability of a character or word based on the preceding ones.

## Features
- **Markov Chain Construction**: Build Markov chains from input text data.
- **Text Generation**: Generate text based on the constructed Markov chain model.
- **Configurable Parameters**: Adjust parameters such as the order of the Markov chain and the length of generated text.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/markov-text-generator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd markov-text-generator
    ```
3. Install required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Prepare your input text file.
2. Run the script with the desired parameters:
    ```sh
    python generate_text.py --input_file path/to/input.txt --order 2 --length 100
    ```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
