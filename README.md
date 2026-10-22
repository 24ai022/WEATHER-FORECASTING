# Weather Forecasting Using LSTM

## Project Description
This project predicts daily mean temperature using historical Delhi weather data and an LSTM neural network.

## Dataset
- File: `DailyDelhiClimateTrain.csv`
- Weather features: Mean temperature, humidity, wind speed, and mean pressure.
- Records: Approximately 1,462 daily records.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Google Colab

## Methodology
1. Load and clean the weather dataset.
2. Normalize the weather features.
3. Generate sequences using the previous seven days.
4. Train an LSTM model.
5. Evaluate using MAE and RMSE.
6. Plot actual versus predicted temperatures.
7. Demonstrate five future temperature predictions.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Upload `DailyDelhiClimateTrain.csv` to the Colab session.
3. Run the notebook cells in order.

## Evaluation
Model performance is measured using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
