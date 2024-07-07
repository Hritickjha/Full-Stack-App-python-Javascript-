# Full-Stack App Tutorial - Python & JavaScript

## Overview
This repository contains a full-stack application built using Python for the backend and JavaScript for the frontend. The purpose of this project is to demonstrate a full-stack development workflow.

## Requirements

### Backend
- Python 3.8 or higher
- Flask
- SQLAlchemy
- Marshmallow
- Other dependencies specified in `backend/requirements.txt`

### Frontend
- Node.js 14.x or higher
- npm or yarn
- React
- Redux
- Other dependencies specified in `frontend/package.json`

### Virtual Environment
- venv

## Installation

### Backend Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/Hritickjha/Full-Stack-App-python-Javascript.git
    cd Full-Stack-App-python-Javascript/backend
    ```
2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

### Frontend Setup
1. Navigate to the frontend directory:
    ```sh
    cd ../frontend
    ```
2. Install the required dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

## Usage
1. Start the backend server:
    ```sh
    cd ../backend
    flask run
    ```
2. Start the frontend development server:
    ```sh
    cd ../frontend
    npm start
    # or
    yarn start
    ```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

