---
# Sun Position Tracker

The Sun Position Tracker is a Python program that continuously tracks the position of the sun at regular intervals and calculates its azimuth and altitude for a given location.

## Features

- Calculates the sun's position (azimuth and altitude) based on the provided date and location.
- Provides continuous tracking of the sun's position at a specified interval.
- Includes an example usage for Victoria Square in Belfast, UK.

## Prerequisites

To run the Sun Position Tracker program, ensure you have the following:

- Python 3.x installed on your system.
- The `ephem` library installed. You can install it using the command `pip install ephem`.

## Usage

Follow these steps to use the Sun Position Tracker:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/your-username/sun-position-tracker.git
   ```

2. Navigate to the project directory:

   ```shell
   cd sun-position-tracker
   ```

3. Run the program:

   ```shell
   python sun_position_tracker.py
   ```

4. Adjust the latitude, longitude, start date, and duration in the `sun_position_tracker.py` file according to your requirements.

## Configuration

In the `sun_position_tracker.py` file, you can configure the following parameters:

- Latitude: The latitude coordinate of your desired location.
- Longitude: The longitude coordinate of your desired location.
- Start Date: The date and time from which you want to start tracking the sun's position.
- Duration: The duration (in seconds) for which you want to track the sun's position.

## Example

```python
latitude = 54.59829051999089
longitude = -5.925160675531965
start_date = ephem.Date('2023-06-21 12:00:00')
duration = 60 * 60

# Rest of the code...
```

You can modify the values of latitude, longitude, start date, and duration in the example code snippet according to your specific requirements.

## Contributing

Contributions to improve the functionality or add new features to the Sun Position Tracker are welcome! If you find any bugs or have suggestions for enhancements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

