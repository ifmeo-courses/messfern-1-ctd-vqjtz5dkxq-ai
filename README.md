[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Ho6soczG)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23984452)
# Exercise 1: CTD Profile Plotting

## Overview

This exercise teaches you to work with real oceanographic CTD (Conductivity, Temperature, Depth) data. You'll learn to process Sea-Bird sensor data, calculate TEOS-10 parameters, and create professional oceanographic plots including Temperature-Salinity diagrams.

## Getting Started

### Option 1: Local Python Environment (Recommended)
```bash
# Clone your repository
git clone <your-repo-url>
cd <your-repo-name>

# Create environment and install packages
pip install -r requirements.txt

# Open Jupyter
jupyter lab src/assignment.ipynb
```

### Option 2: GitHub Codespaces (Backup Option)
If you have trouble with local Python setup:

1. **Click the green "Code" button** in your repository
2. **Go to the "Codespaces" tab**
3. **Click "Create codespace on main"**
4. **In the setup screen:**
   - **Machine type:** 2-core (default is fine)
   - **Dev container:** Choose **"Python 3.11"** (NOT Python 3.14 or other versions)
   - **✅ Tick the checkbox** for "Install requirements.txt dependencies"
5. **Click "Create codespace"**

**⏰ Important:** The first time setup will take **5-10 minutes**. This is normal! The system is installing all oceanographic packages.

**💡 Tip:** If the notebook shows raw JSON instead of cells, right-click `assignment.ipynb` and select **"Open With → Jupyter"**.

## Assignment Structure

- **`src/assignment.ipynb`** - Main assignment notebook with YOUR CODE HERE sections
- **`tests/test_exercise.py`** - Automated tests (run automatically when you push)
- **`requirements.txt`** - Required Python packages

## Learning Objectives

You will learn to:
- Convert Sea-Bird CNV data to netCDF format using seasenselib
- Calculate TEOS-10 oceanographic parameters (Absolute Salinity, Conservative Temperature)
- Create professional oceanographic profile plots
- Generate Temperature-Salinity diagrams with density contours
- Analyze real research data from the North Atlantic Ocean

## Required Outputs

Generate these four figures:
- `ex1fig1-YourName-Messfern.png` - Temperature and practical salinity profiles
- `ex1fig2-YourName-Messfern.png` - Conservative temperature and absolute salinity profiles  
- `ex1fig3-YourName-Messfern.png` - Basic T-S diagram
- `ex1fig4-YourName-Messfern.png` - Enhanced T-S diagram focused on dense water

## Tips for Success

1. **Replace placeholder names** - Change "YourName" to your actual name in figure filenames
2. **Complete all YOUR CODE HERE sections** - These are required for full credit
3. **Run tests locally** - Use `python -m pytest tests/ -v` to check your work
4. **Answer analysis questions** - Demonstrate your understanding of the data

**Total Points: 22**
