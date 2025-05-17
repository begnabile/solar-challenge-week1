echo "# Solar Challenge Week 1

## Environment Setup

1. Clone the repository:
  
   git clone https://github.com/your-username/solar-challenge-week1.git
   cd solar-challenge-week1

2. Set up virtual environment:
   - Using venv:
    
     python -m venv .venv
     source .venv/bin/activate  # On Windows: .venv\\Scripts\\activate
     

     

3. Install dependencies:
   
   pip install -r requirements.txt
   

## Project Structure


├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       ├── ci.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md

" > README.md
git add README.md
git commit -m "docs: add README with setup instructions"