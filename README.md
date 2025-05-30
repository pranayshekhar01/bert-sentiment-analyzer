# BERT Sentiment Analyzer 🎬

![BERT Sentiment Analyzer](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen?style=flat-square&logo=github)

Welcome to the BERT Sentiment Analyzer! This web application leverages the power of BERT (Bidirectional Encoder Representations from Transformers) to analyze the sentiment of movie reviews from IMDb. Built with Streamlit, this tool classifies reviews as either positive or negative with an impressive accuracy of 93%.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **High Accuracy**: Achieves 93% accuracy in classifying sentiments.
- **User-Friendly Interface**: Built with Streamlit for easy navigation.
- **Real-Time Analysis**: Get instant feedback on movie reviews.
- **Customizable**: Adapt the model to your specific needs.

## Technologies Used

- **BERT**: The backbone of our sentiment analysis.
- **Hugging Face Transformers**: For model implementation.
- **Streamlit**: For building the web application.
- **PyTorch**: Used for model training and inference.
- **IMDb Dataset**: For training the model.
- **Web Scraping**: To gather additional movie reviews.

## Installation

To set up the BERT Sentiment Analyzer on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pranayshekhar01/bert-sentiment-analyzer.git
   cd bert-sentiment-analyzer
   ```

2. **Install Required Packages**:
   Ensure you have Python installed. Then, run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Model**:
   You can download the latest release from the [Releases section](https://github.com/pranayshekhar01/bert-sentiment-analyzer/releases). Follow the instructions in the release notes to execute the model.

## Usage

To run the application:

1. **Start the Streamlit Server**:
   ```bash
   streamlit run app.py
   ```

2. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8501`.

3. **Input a Movie Review**:
   Type or paste your review in the text box and click the "Analyze" button.

4. **View Results**:
   The application will display whether the review is positive or negative.

## How It Works

### Data Collection

The application uses the IMDb dataset, which contains a vast collection of movie reviews. Web scraping techniques are also employed to gather additional reviews from the IMDb website, ensuring a comprehensive dataset for training.

### Model Training

The BERT model is fine-tuned on the dataset using PyTorch. The training process involves:

- **Tokenization**: Converting text into tokens that the model can understand.
- **Training**: Adjusting model weights based on the dataset.
- **Validation**: Testing the model on unseen data to check accuracy.

### Sentiment Analysis

Once trained, the model can classify new reviews. It analyzes the input text and predicts the sentiment based on learned patterns.

## Contributing

We welcome contributions to improve the BERT Sentiment Analyzer! If you would like to contribute, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**.
4. **Commit Your Changes**:
   ```bash
   git commit -m "Add Your Feature Description"
   ```
5. **Push to the Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [pranayshekhar01](https://github.com/pranayshekhar01)

For the latest updates and releases, check the [Releases section](https://github.com/pranayshekhar01/bert-sentiment-analyzer/releases).