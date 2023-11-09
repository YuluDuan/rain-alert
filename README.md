# Rain Alert Python Project

This Python project provides a rain alert system that notifies users about upcoming rain based on predefined settings and a chosen location by sending SMS messages.
## Project Overview

The rain alert system is built using Python and utilizes weather data from an API to send notifications when rain is forecasted for a specified location. The core functionalities of the project include:

- Fetching weather data for a specified location.
- Analyzing the weather forecast to detect rain.
- Sending alerts to users through their preferred communication channel.

## Getting Started

### Prerequisites

Ensure you have Python installed on your machine. If not, you can download and install Python from the [official Python website](https://www.python.org/).

### Installation

1. Clone the repository:
 
 ```bash
git clone https://github.com/YuluDuan/flowfairy.git
```

2. Install the required dependencies:
   
 ```bash
pip install -r requirements.txt
```

### Usage

1. Set up your API keys:
- Obtain API keys from [OpenWeatherMap](https://openweathermap.org/api/one-call-api) and set them in the configuration file.
- Obtain API tokens and Virtual phone number from [Twilio](https://www.twilio.com/try-twilio)

2. Run the script:

```bash
python rain_alert.py
```

## Using PythonAnywhere to Automate the Script

[PythonAnywhere](https://www.pythonanywhere.com/) is a platform that allows you to run Python scripts in the cloud, making it a convenient option for automating tasks.

### Steps to Automate the Rain Alert Script on PythonAnywhere

1. **Sign Up/Log In:**
Sign up or log in to your [PythonAnywhere](https://www.pythonanywhere.com/) account.

3. **Upload Your Project:**
Upload your `rain_alert` project to PythonAnywhere

5. **Create a New Task:**
- Go to the Dashboard and navigate to the "Tasks" tab.
- Click on "Create a new task."
- Select the Python version and set the task to run the `rain_alert.py` script.
- Set run command to `export OWN_API_KEY=YOUR_OWN_API_KEY; export AUTH_TOKEN=YOUR_TWILIO_TOKEN; python3 main.py`

5. **Set the Schedule:**
- Set the desired schedule for the task to run periodically (Daily for this project).
- Save the task.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the guidelines in `CONTRIBUTING.md`.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

