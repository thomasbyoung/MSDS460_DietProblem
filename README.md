# Diet Problem || Assignment 1

## Diet Problem Overview

The program solves two variations of the same nutritional optimization problem:

1.) Basic optimization allowing zero servings of items
2.) Modified optimization requiring minimum one serving of each item

## Problem Description

The optimization considers five food items:

Cheese
Salad
Chicken
Salmon
Oatmeal

### Each food item has associated:

Nutritional values (sodium, energy, protein, vitamin D, calcium, iron, potassium)

### Cost per serving

The program aims to minimize the total cost while meeting minimum nutritional requirements and not exceeding maximum limits.

### Requirements

Python 3.x
PuLP library (pip install pulp)

### Output

The program outputs:
Optimal number of servings for each food item

### Total minimum cost

Comparison between allowing zero servings vs requiring minimum one serving

### Technical Details

_Constraints_

Sodium: ≤ 35,000 mg
Energy: ≥ 14,000 cal
Protein: ≥ 350,000 g
Vitamin D: ≥ 140 mcg
Calcium: ≥ 9,100 mg
Iron: ≥ 126 mg
Potassium: ≥ 32,900 mg

### Variables

All food quantities are non-negative in the first version, and ≥ 1 in the second version.

### License

MIT License

# Nutrition Optimization GUI Application

A simple desktop application built with Python, Tkinter, and PuLP for optimizing daily nutritional intake while minimizing cost.
Features

- Add/Edit/Delete food items with their nutritional values
- Save food data to JSON file
- Calculate optimal servings while meeting nutritional requirements
- Display results in a user-friendly interface

## How to Run It

### Step 1: Install Python dependencies

Shocking, but you'll need Python > 3.6, plus install:

_pip install pulp_

Step 2: Run the App

In the directory where the script is saved run:

_python main.py_
