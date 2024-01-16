
# Match Momentum Predictor

## Overview

Match Momentum Predictor is a machine learning project designed to predict the win and loss probability of IPL teams during a cricket match. By utilizing features such as batting team, bowling team, host city, target for the second innings, current score of the chasing team, current over, and wickets out, the model aims to provide insights into the potential outcome of an IPL match.

## Dataset

To train the model, we have used a dataset sourced from Kaggle. The dataset can be found [here](https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set). It contains comprehensive information about various IPL matches, including team performance, match details, and player statistics.

## Getting Started

### Prerequisites

Make sure you have Python installed. You can download it from [python.org](https://www.python.org/).

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/sampritibanerjee/Match-Momentum-Predictor.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Match-Momentum-Predictor
    ```

3. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

    The following libraries will be installed:
    - streamlit
    - pandas
    - numpy
    - scikit-learn (sklearn)

### Usage

1. Download the dataset from the provided Kaggle link and place it in the `data` directory.

2. Run the Jupyter notebook or Python script to train the model:

3. Once the model is trained, you can use it to predict win and loss probabilities for specific match scenarios.

## Model Details

The model is built using machine learning techniques and supervised learning. It takes into account historical IPL match data to learn patterns and make predictions based on the input features.

## Contributors

-  [Sampriti Banerjee](https://github.com/sampritibanerjee)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Kaggle and the dataset contributor [ramjidoolla](https://www.kaggle.com/ramjidoolla) for providing the IPL dataset.

Feel free to customize this README file based on your specific project details and preferences.
