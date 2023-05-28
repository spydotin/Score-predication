# IPL-Score-Predictor

- This is just another simple yet intresting project which can approximately predict an innings score based on the data from 2008-2017 IPL season.  
- I tried training three models:  
 1. Linear Regression  
 2. Lasso  
 3. Ridge  
- and out of these surprisingly Linear regression was giving more realistic results.  
- If you liked this project star this repo.  
- I made some improvisations in his code like I totally removed the result page and showed the results on the same page.  
- And also I took venue as a feature while training as I think that it ca really play a major role in predicting score.  
- Deployed using Flask.  
- Just run  app.py and go to localhost to see the results.  
- Thankyou,
- Surya Prakash Yadav


Sure! Here's an example README file for your code:

# IPL Score Prediction Web Application

This is a Flask web application that predicts the final score of an IPL (Indian Premier League) cricket match based on various input parameters. The application uses a trained regression model to make predictions.

## Getting Started

To run the application locally, follow the steps below:

1. Clone the repository:

   ```shell
   git clone <repository-url>
   ```

2. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   ```

3. Run the Flask application:

   ```shell
   python app.py
   ```

   The application will be available at `http://localhost:5000`.

## Usage

1. Open the application in a web browser.

2. On the home page, you will see a form where you can input the details for prediction.

3. Select the venue, batting team, and bowling team from the dropdown menus.

4. Enter the current number of overs, runs, wickets, runs scored in the previous 5 overs, and wickets taken in the previous 5 overs.

5. Click on the "Predict" button.

6. The predicted score range will be displayed on the page.

## Model and Data

- The regression model used for prediction is loaded from the file `iplmodel_ridge.sav`.

- The scaler object for preprocessing the input data is loaded from the pickled file `scaler.pkl`.

- The model and scaler should be placed in the same directory as the Flask application.

## Customization

If you want to add or modify the venues, batting teams, or bowling teams available for selection, you can update the corresponding code sections in `app.py`. Similarly, you can customize the prediction logic or the UI by modifying the Flask routes and the HTML templates in the `templates` directory.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Surya Prakash Yadav

Feel free to replace `<repository-url>` with the actual URL of your repository if you have it hosted online. You can also update the sections based on your specific requirements and any additional information you want to provide.