Expense Management System

The Expense Management System is a comprehensive solution designed to track and manage expenses efficiently. It features a Streamlit-based frontend and a FastAPI-powered backend, ensuring a seamless and interactive user experience.

Project Structure

frontend/ – Contains the Streamlit application code for the user interface.

backend/ – Includes the FastAPI backend server code, handling data processing and API endpoints.

tests/ – Provides unit tests for both frontend and backend components to ensure reliability.

requirements.txt – Lists the necessary Python dependencies for the project.

README.md – Offers an overview of the project along with setup instructions.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
