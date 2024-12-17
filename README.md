# Shri Shrinivasa Medical Shop Inventory Management System

## Description
This is a Flask-based inventory management system for a medical shop. It allows users to manage stock, customers, and invoices efficiently.

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/Sripad09/medical>
   cd <medical>
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Set up the environment variables in a `.env` file.
2. Run the application:
   ```bash
   flask run
   ```
3. Access the application at `http://127.0.0.1:5000`.

## Deployment on Heroku
1. Create a new Heroku app:
   ```bash
   heroku create <app-name>
   ```
2. Push the code to Heroku:
   ```bash
   git push heroku main
   ```
3. Open the app in your browser:
   ```bash
   heroku open
   ```

## License
This project is licensed under the MIT License.
