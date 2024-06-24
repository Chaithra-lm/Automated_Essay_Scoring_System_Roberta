# Automatic Essay Scoring System using RoBERTa

This repository contains the code and resources for our Automatic Essay Scoring (AES) system using the RoBERTa model. Our system achieved a Cohen Kappa score of 0.51, demonstrating a reasonable level of agreement with human raters. The repository also includes a demo video embedded in the PowerPoint presentation shared in this repository.

## Contents

- `README.md`: This file.

## Dataset

We used the dataset from the [Kaggle Learning Agency Lab Automated Essay Scoring 2 competition](https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2). Please note that you need to agree to the competition's rules to download the dataset.

## Requirements


flask==2.0.1
werkzeug==2.0.1
torch
transformers
tqdm
pandas


## Usage

1. Prepare the dataset:
    - Download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2) and place it in the `data/` directory. Ensure it follows the required format as specified in the code.


## Results

Our AES system achieved a Cohen Kappa score of 0.51. Detailed results and analysis can be found in the ipynb files.

## Demo

A demo video showcasing the functionality of our AES system is included in the `demo/` directory within the PowerPoint presentation (`AES_Demo.pptx`).

## Contributing

We welcome contributions to enhance the system. Please fork the repository and create a pull request with your changes.


## Acknowledgments

- Hugging Face's Transformers library for providing the RoBERTa model.
- The Kaggle Learning Agency Lab Automated Essay Scoring 2 competition for the dataset.
- The dataset providers and the community for their support.

## Contact

For any questions or inquiries, please contact chaithralm17@gmail.com.

