# [Pune Rent Predictor](https://rentwizardd.streamlit.app/)

This Streamlit web application predicts rental prices for properties in Pune, India, using a machine learning model. It provides an intuitive interface for users to input property details and receive estimated rental values.

## Features

-   **Rent Prediction:** Input property details like number of rooms, bathrooms, area, furnishing status, and availability to get an estimated monthly rent.
-   **Market Insights:** Visualize average rental prices in popular Pune localities and explore rental trends.
-   **How It Works:** Understand the machine learning model and the factors it considers for predictions.
-   **Contact & Insights Sidebar:** Access developer contact information and valuable Pune real estate insights.
-   **Interactive Visualizations:** Utilize Plotly for dynamic charts and graphs.
-   **User-Friendly Interface:** Clean and intuitive design with Streamlit.

## Technologies Used

-   **Python:** Programming language.
-   **Streamlit:** Web application framework.
-   **Scikit-learn:** Machine learning library.
-   **Pandas:** Data manipulation and analysis.
-   **NumPy:** Numerical computing.
-   **Pickle:** Serialization of Python objects.
-   **Plotly:** Interactive visualization library.

## Setup Instructions

1.  **Clone the Repository:**

    ```bash
    git clone [https://github.com/your-username/pune-rent-predictor.git](https://www.google.com/search?q=https://github.com/your-username/pune-rent-predictor.git)
    cd pune-rent-predictor
    ```

2.  **Create a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On macOS and Linux
    ```

3.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit Application:**

    ```bash
    streamlit run app.py
    ```

5.  **Access the Application:**

    Open your web browser and navigate to the URL displayed in the terminal (usually `http://localhost:8501`).

## Project Structure

```
pune-rent-predictor/
├── app.py           # Main Streamlit application file
├── Model.pkl        # Pre-trained machine learning model
├── requirements.txt # List of Python dependencies
├── img.png          # Project image
└── README.md        # Project documentation
```

## Usage

1.  **Rent Prediction Tab:**
    -   Enter the property details (number of rooms, bathrooms, area, furnishing status, availability).
    -   Click the "Calculate Rent" button to get the estimated monthly rent.
    -   View additional rental insights based on the prediction.

2.  **Market Insights Tab:**
    -   Explore the average monthly rent by popular Pune localities using interactive bar charts.
    -   View rental trends over the years.

3.  **How It Works Tab:**
    -   Learn about the machine learning model and the factors it considers for predictions.

4.  **Sidebar:**
    -   Access developer contact information.
    -   Read valuable Pune real estate insights.

## Model Training

The `Model.pkl` file contains a pre-trained Random Forest regression model. This model was trained on a dataset of Pune rental property listings. The dataset was preprocessed, encoded, and split into training and testing sets.

If you wish to retrain this model, you will need a separate python file. And the appropriate data set.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

## Author

-   **Vedant Kale**
    -   Email: [vedant.kale22@pccoepune.org](mailto:vedant.kale22@pccoepune.org)
    -   Phone: +91-8421204009
    -   LinkedIn: [https://www.linkedin.com/in/vedantkale106/](https://www.linkedin.com/in/vedantkale106/)


