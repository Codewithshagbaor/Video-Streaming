# VideoChat Application

This is a simple video chat application built using Django and Channels. It allows users to engage in real-time video conversations using WebSocket communication.

## Features

- Real-time video chat using WebSocket communication.
- Support for handling regular HTTP requests alongside WebSocket connections.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- Python 3.x
- Redis Server

### Installation

1. Clone the repository:

   ```bash
   https://github.com/Codewithshagbaor/Video-Streaming.git
   ```

2. Navigate to the project directory:

   ```bash
   cd VideoChat
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

4. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start the Redis server:

   ```bash
   redis-server
   ```

6. Run the Django development server:

   ```bash
   python manage.py runserver
   ```

7. Access the application in your web browser at `http://localhost:8000`.

## Usage

- Open the application in your browser.
- Navigate to the video chat page.
- Enter your name and start a video chat session.
- Share the provided link with a friend to join the video chat.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```
