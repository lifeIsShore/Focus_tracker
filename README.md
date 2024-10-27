# Focus Time Tracker

A Python application for tracking focus sessions using Tkinter. The app allows users to start a session, record laps (individual time intervals within a session), and terminate the session. The focus session data is saved in a JSON file for easy tracking and analysis.

## Features

- **Start a Focus Session**: Begins a focus session, capturing the start date, day, and time.
- **Record Lap Times**: During a session, the user can record multiple laps to log different intervals within the session.
- **Terminate Session**: Ends the current focus session and saves data, including the end time, into a JSON file for later review.
- **Persistent Data Storage**: Focus session data is stored in a JSON file, enabling session history review.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/FocusTimeTracker.git
   cd FocusTimeTracker
   ```

2. **Requirements**: This project requires Python and Tkinter (usually pre-installed with Python). Additionally, ensure that `pandas` and `json` libraries are available:
   ```bash
   pip install pandas
   ```

## Usage

1. **Run the Application**:
   ```bash
   python focus_tracker.py
   ```
![image](https://github.com/user-attachments/assets/39447537-534c-48f1-9497-854d9d7d8e99)

2. **Starting a Session**: Click the "Start Focusing" button to initiate a new focus session. The application will log the current date, day, and time.

3. **Recording Laps**: During the session, click the "Lap" button to record laps. Each lap logs the current time as an individual interval within the session.

4. **Terminating a Session**: Click "Terminate the Session" to end the session. This will log the end time and save all session data in a JSON file.

![image](https://github.com/user-attachments/assets/9625ddf4-44f4-4881-866a-39aad498305b)

## File Structure

- **focus_tracker.py**: Main script to run the application.
- **focus_sessions_v3.json**: JSON file that stores focus session data. The default location for this file is `C:\Users\ahmty\Desktop\Python\focus_tracker\Focus_tracker\database\focus_sessions_v3.json`. Modify this path in the script if needed.

## JSON Data Format

Each session is stored in the JSON file in the following format:
```json
[
    {
        "Day": "Monday",
        "Start Time": "23-Oct-24",
        "Start DateTime": "13:45:32",
        "Lap #1": "13:50:10",
        "Lap #2": "13:55:20",
        "End Time": "14:00:45"
    }
]
```

## Contributing

Feel free to fork this project, create new branches, and submit pull requests. Any contributions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to customize the content to match your needs or to specify any additional requirements.
