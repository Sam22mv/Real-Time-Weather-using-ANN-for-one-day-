# Real-Time-Weather-using-ANN-for-one-day

This project predicts future temperatures using real-time weather data and historical weather records. The system utilizes an Artificial Neural Network (ANN) built with TensorFlow and Keras to forecast future weather conditions based on input features such as temperature, humidity, wind gust speed, and pressure. The real-time data is fetched from the OpenWeatherMap API, and historical data is used to train the ANN model for temperature prediction.

## Features
1. Fetches real-time weather data from the OpenWeatherMap API.
2. Prepares historical weather data for training the ANN model.
3. Scales input features using MinMaxScaler for improved model performance.
4. Builds and trains an ANN model using TensorFlow and Keras.
5. Predicts future temperatures based on current weather conditions.

## Functions
1. get_current_weather(city): Fetches current weather data for the specified city from OpenWeatherMap.
2. read_historical_data(filename): Reads and preprocesses historical weather data from a CSV file.
3. prepare_data_for_ann(data): Prepares data for training by scaling features and separating the target variable.
4. build_ann_model(input_dim): Constructs an ANN model with specified input dimensions.
5. train_ann_model(X, y): Trains the ANN model using the prepared data.
6. predict_future_temp(model, current_data): Predicts future temperature based on the trained model and current data.
7. weather_view(): Main function to execute the weather prediction process and print results.

