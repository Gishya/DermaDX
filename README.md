# DermaDX

A mobile and web application designed to identify skin diseases using machine learning. This tool provides a preliminary analysis to help users decide if they should consult a healthcare professional.

## About The Project

Skin diseases are a common health concern globally. While many are not fatal, they can significantly impact an individual's quality of life. Diagnosis is often delayed because people are unaware of their condition or are deterred by the high cost and limited availability of dermatologists.

**DermaDX** is a cost-effective and user-friendly application designed to provide a preliminary analysis of potential skin conditions, making initial screening more accessible.

### Built With

- **Frontend:** [Flutter](https://flutter.dev/)
- **Backend & Machine Learning:** [Python](https://www.python.org/)
- **ML Framework:** [TensorFlow](https://www.tensorflow.org/) / [PyTorch](https://pytorch.org/)

## How It Works

DermaDX offers a simple way for users to get an initial assessment:

1.  **Upload Image:** Use the mobile or web app to upload a clear image of the affected skin area.
2.  **AI Analysis:** The machine learning model analyzes the image against a dataset of skin conditions.
3.  **Get Results:** Receive a preliminary analysis, including the potential condition and a recommendation on whether to consult a doctor.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need the following software installed on your machine:

- Flutter SDK
- Python 3.8+
- Pip

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/Induranga-kawishwara/DermaDX.git
    ```
2.  Install backend Python packages
    ```sh
    pip install -r requirements.txt
    ```
3.  Install frontend Flutter packages
    ```sh
    cd frontend && flutter pub get
    ```
4.  Run the application

    ```sh
    # To run the backend server (from the root directory)
    # python app.py or flask run

    # To run the Flutter app (from the frontend directory)
    cd frontend && flutter run
    ```

## Usage

Use this space to show useful examples of how the project can be used. Additional screenshots, code examples, and demos work well in this space.

## Disclaimer

**Important:** DermaDX is an informational tool and **not** a substitute for a professional medical diagnosis. It is intended for preliminary screening purposes only. Always consult a qualified healthcare provider for any health concerns or before making any medical decisions.
