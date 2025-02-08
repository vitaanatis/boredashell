# Games Website

Welcome to the Games Website repository! This README.md file will give you all the information you need to start local hosting this games server!
If you don't intend on doing that, just use the websites made for this repository.

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- Flask library
- Webbrowser library
- Threading library

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Xi-v/Games-Website.git
   cd Games-Website
   ```

2. **Install the required dependencies:**

   If you don't have Flask installed, run:

   ```bash
   pip install flask webbrowser threading 
   ```

3. **Run the Flask server:**

   Inside the project directory, run:

   ```bash
   python local_hosting.py
   ```

   This will start the server locally.

4. **Access the website:**

   It will automatically open your browser and go to the website!

## Project Structure

- `static/` - Contains CSS, JavaScript, and image files.
- `templates/` - Holds HTML files rendered by Flask.
- `main.py` - The Flask application running the server.

## License
MIT License. See `LICENSE` for details.
