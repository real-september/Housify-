Setup Instructions: 
  1. Clone the repository
     git clone https://github.com/real-september/Housify-.git
     cd Housify-
  
  2. Create a virtual environment
     python -m venv venv
     source venv/bin/activate (for mac)
     venv\Scripts\activate (for windows)

  3. Install dependencies
     pip install -r requirements.txt

  4. Run the Application
     python main.py

  5. Open your browser and navigate to http://localhost:5000

PROJECT Structure
Housify-/
├── __init__.py          # App initialization
├── auth.py              # Authentication routes
├── models.py            # Database models
├── views.py             # Main application routes
├── main.py              # Application entry point
└── templates/
    ├── base.html        # Base template
    ├── home.html        # Home page
    ├── login.html       # Login page
    └── sign_up.html     # Registration page
