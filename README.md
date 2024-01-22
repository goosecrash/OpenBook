
# OpenBook Project

## Introduction
The OpenBook project is a Flask-based web application designed to manage and display book and author information from a SQLite database. It's an intuitive platform for book enthusiasts and researchers alike.

## Features
- Display book and author data from a SQLite database.
- Web interface for easy navigation and data viewing.
- Routes for accessing different types of data (e.g., books, authors).

## Installation

### Prerequisites
- Python 3
- Flask
- SQLite3

### Setting Up
1. Clone the repository:
   ```
   git clone https://github.com/goosecrash/OpenBook
   ```
2. Navigate to the project directory:
   ```
   cd OpenBook
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
To run the application:
```
python app.py
```
Access the web interface at `http://127.0.0.1:5000/`.

### Routes
- `/` - Home page displaying the main data.
- `/authors` - Page displaying authors' information.
- `/books` - Page displaying books' information.

## Contributing
Contributions to the OpenBook project are welcome. Please ensure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
