# Hotel-Rate-Tracking-Tool

Hotel-Rate-Tracking-Tool is a web application that scrapes hotel pricing data from various sources and provides tools for tracking and analyzing rate fluctuations. This tool is designed to help hotel managers optimize their pricing strategies by providing comprehensive data and visualization.

## Features

- **Web Scraping**: Scrapes hotel pricing data from multiple sources.
- **Data Visualization**: Provides charts and graphs to visualize rate trends.
- **User Interface**: Easy-to-use interface for interacting with the tool.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation

### Backend (Python)

1. Clone the repository:
    ```bash
    git clone https://github.com/bramsubic/Hotel-Rate-Tracking-Tool.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Hotel-Rate-Tracking-Tool
    ```
3. Set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Frontend (React)

1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```
2. Install the necessary dependencies:
    ```bash
    npm install
    ```

## Usage

### Run the Scraper

1. Navigate to the project directory:
    ```bash
    cd Hotel-Rate-Tracking-Tool
    ```
2. Run the scraper to collect pricing data:
    ```bash
    python src/scraper.py
    ```

### Start the Backend Server

1. Navigate to the project directory (if not already there):
    ```bash
    cd Hotel-Rate-Tracking-Tool
    ```
2. Start the Flask backend server:
    ```bash
    python src/app.py
    ```

### Start the Frontend Server

1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```
2. Start the React frontend server:
    ```bash
    npm start
    ```
3. Open your browser and navigate to `http://localhost:3000`.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request.
