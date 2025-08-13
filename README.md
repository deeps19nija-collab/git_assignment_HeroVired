# CalculatorPlus

CalculatorPlus is a simple Python application that performs basic arithmetic operations and includes a square root feature.  
This project demonstrates Git branching, bug fixing, feature development, and release versioning.

## Features
- Addition
- Subtraction
- Multiplication
- Division (with divide-by-zero check)
- Square root calculation


## Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/git_assignment_HeroVired.git
cd git_assignment_HeroVired
```

### 2. Run the Application
```bash
python calculator.py
```
## Branch Workflow Used
- **main** - Stable production-ready branch.
- **dev** - Active development branch.
- **feature/sqrt** - Feature branch for square root functionality.

## Git Workflow for This Project

### 1. Initial Setup
- Create Repository: git_assignment_HeroVired
- Add initial code to dev branch
- Merge to main → **Release v1.0**

### 2. Feature Implementation
- Create feature/sqrt from dev
- Implement square_root method
- Merge dev bug fix (divide-by-zero check) into feature/sqrt

### 3. Pull Request & Review
- Create PR from feature/sqrt → main
- Request review and address feedback
- Merge feature/sqrt into dev
- Merge dev into main → **Release v2.0**

## Version History
- **v1.0** – Basic calculator with add, subtract, multiply, divide.
- **v2.0** – Added square root feature and divide-by-zero fix.

## Example Output
16 + 4 = 20  
16 - 4 = 12  
16 * 4 = 64  
16 / 4 = 4.0  
The square root of 25 = 5.0  










