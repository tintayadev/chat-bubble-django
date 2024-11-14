# Chat Bubble - Django with Tailwind CSS

This is a simple Django web application that demonstrates the integration of Tailwind CSS for styling. The app features a chat interface with chat bubbles and a dark mode.

## Features

- Chat interface with receiver and sender chat bubbles
- Dark mode support
- Integration of Tailwind CSS for styling
- Use of the `flyonui` library for additional UI components

## Getting Started

### Prerequisites

- Python 3.x
- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chat-bubble.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-bubble
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate
   ```

4. Install the Python dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Install the Node.js dependencies:

   ```bash
   npm install
   ```

6. Compile the Tailwind CSS:

   ```bash
   npm run watch:css
   ```

   This will start watching the `static/css/main.css` file and automatically compile the Tailwind CSS.

7. Start the Django development server:

   ```bash
   python manage.py runserver
   ```

8. Open your browser and go to `http://localhost:8000` to see the chat app.
