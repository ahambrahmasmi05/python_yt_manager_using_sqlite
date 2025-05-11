# YouTube Manager with SQLite

This project is a simple Python application that allows users to manage their YouTube video database using SQLite. It provides basic functionalities such as adding, listing, updating, and deleting video entries. The database stores video information, including the video name and time.

## Features

- **List Videos**: View all videos in the database.
- **Add Video**: Add a new video to the database.
- **Update Video**: Update the name or time of an existing video.
- **Delete Video**: Remove a video from the database.
- **Exit**: Exit the application.

## Requirements

- Python 3.x
- SQLite (SQLite comes built-in with Python, so no extra installation is required)

## Setup and Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ahambrahmasmi05/python_yt_manager_using_sqlite.git
    ```

2. Navigate to the project directory:
    ```bash
    cd python_yt_manager_using_sqlite
    ```

3. Ensure that the SQLite database file `youtube_manager.db` is present in the project directory. If not, the program will automatically create it upon the first run.

## Usage

1. Run the Python script to launch the application:
    ```bash
    python youtube_manager_db.py
    ```

2. Follow the on-screen prompts to manage your YouTube video database:
    - **1**: List all videos.
    - **2**: Add a new video.
    - **3**: Update an existing video.
    - **4**: Delete a video.
    - **5**: Exit the application.

## Code Overview

- **youtube_manager_db.py**: Main Python file that connects to the SQLite database, creates the necessary table (`videos`), and provides functionalities to add, list, update, and delete video records.
- **youtube_manager.db**: SQLite database file used to store video information. This file is automatically created when the program runs for the first time.

## Example of Usage

1. **List Videos**:
    ```
    1. List videos
    2. Add video
    3. Update video
    4. Delete video
    5. Exit
    Enter your choice: 1
    (1, 'Video 1', '10:00')
    (2, 'Video 2', '12:30')
    ```

2. **Add Video**:
    ```
    Enter video name: New Video
    Enter video time: 15:45
    ```

3. **Update Video**:
    ```
    Enter video ID to update: 1
    Enter video name: Updated Video
    Enter video time: 20:00
    ```

4. **Delete Video**:
    ```
    Enter video ID to delete: 2
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
