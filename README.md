# Voice Assistant App

## Description
This is a basic voice assistant application that listens to your voice commands and performs predefined tasks, including:
- Conducting web searches
- Retrieving weather information
- Telling the current time
- Setting reminders or opening applications

This project is ideal for beginners in Python and voice recognition. It leverages simple APIs and libraries to perform tasks with a hands-free approach.

## Requirements

To get started, ensure the following dependencies are installed. You may follow the installation commands based on your operating system.

### Required Libraries
- `requests`
- `pyttsx3`
- `SpeechRecognition`
- `webbrowser`

### Setup Commands

#### Windows
1. Make sure Python is installed (preferably version 3.6+). You can download it from [python.org](https://www.python.org/).
2. Open Command Prompt and run:
   ```bash
   pip install requests pyttsx3 SpeechRecognition
3. Ensure your microphone is set up and working correctly.
   
#### Linux
1. Install Python (if not already installed):
    ```bash
    sudo apt update
    sudo apt install python3 python3-pip
2. Install the required libraries:
    ```bash
    pip3 install requests pyttsx3 SpeechRecognition
3. Ensure your microphone is configured properly on your Linux distribution.

## Usage
1. Replace the placeholders in  `get_weather()` function:
  - Add your API key from OpenWeatherMap `(YOUR_OPENWEATHERMAP_API_KEY)`.
  - Set your preferred city name `(YOUR_CITY)`.
    
2. Run the application by executing:
    ```bash
    python Voice_assist_app.py
    
  (or python3 Voice_assist_app.py on Linux).

3. The assistant will greet you and start listening for commands. You can say commands like:
  - "Hello"
  - "What is the time?"
  - "What's the weather like?"
  - "Open a web" (for opening a webpage)
  - "Open app" (to open a specific application)
  - "Goodbye" or "Bye" (to end the assistant)

### Features
  - **Web Search**: Perform basic web searches.
  - **Weather Information**: Retrieve and announce real-time weather data.
  - **Time Announcement**: Tell the current time.
  - **Open Applications and Webpages**: Launch websites or applications with voice commands.
  - **Reminders**: Set reminders or alarms (future expansion possibility).

### Troubleshooting
  - If the assistant does not recognize your commands, ensure your microphone is working and try adjusting ambient noise settings.
  - For API errors with weather data, verify your API key and network connection.

#### Notes
  - This application uses Google’s Speech Recognition service, so an active internet connection is required.
  - Replace `YOUR_OPENWEATHERMAP_API_KEY` and `YOUR_CITY` in the `get_weather()` function before running.

This `README.md` file includes all necessary setup instructions, usage examples, and troubleshooting 
