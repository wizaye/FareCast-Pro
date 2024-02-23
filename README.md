# Flight Fare Prediction Web App

This is a web application built with Flask that predicts flight fares based on various input parameters such as departure date, arrival date, source, destination, number of stops, and airline using a RandomForest Regressor model.

## Installation

To run this web application locally, you need to have Python installed on your system. Follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/wizaye/flight-fare-prediction-web-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flight-fare-prediction-web-app
    ```

3. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

5. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Once the dependencies are installed, you can run the Flask app:

    ```bash
    python app.py
    ```

2. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the web application.

3. Fill in the input fields with the required information (departure date, arrival date, source, destination, number of stops, and airline) and click on the "Submit" button to get the predicted flight fare.

## Model Training

The RandomForest Regressor model used in this web application is trained on flight data. To retrain the model or update it with new data, you can follow these steps:

1. Prepare your dataset with flight information, including features and target (fare).

2. Train the RandomForest Regressor model using Python. You can use tools like scikit-learn.

3. Save the trained model to a file using joblib or pickle.

4. Replace the existing model file (`model.pkl`) in the `models` directory with your newly trained model.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
