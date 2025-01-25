# Grocery Tracker

## Introduction

**Project Overview**:  
The Grocery Tracker is a Python application designed to manage grocery purchases, track spending, and suggest meals based on available ingredients.

**Objectives**:  
- Track individual grocery items and their attributes.
- Analyze spending on groceries over time (monthly, weekly, per meal).
- Suggest meal options based on current kitchen inventory.

**Target Audience**:  
Individuals interested in managing their grocery expenses and meal planning.

## Program Description

### Main Menu

The main interface includes:

- **Functionality 1: Price Tracking**
  - **Description**: Collect data on grocery purchases to provide spending analysis.
  - **Features**:
    - Record purchases with detailed item attributes.
    - Generate reports on spending by time period (month, week, meal).

- **Functionality 2: Menu Builder**
  - **Description**: Use inventory data to suggest meal combinations.
  - **Features**:
    - Track pantry items in real-time.
    - Suggest simple meal options based on available food categories (protein, fruit, vegetable, carbohydrate).

### System Architecture

**Components**:
- **Database**: Initially, a text file for item storage, with potential for SQL upgrade.
- **UI**: Command-line interface with plans for GUI expansion.

**Flow**: 
- User inputs data via command-line menu.
- Data is written to the text file for storage.
- Data is read back into memory for generating reports or meal suggestions.

### User Interface

**Interface Design**:
- Command-line menu with numbered options for:
  - Adding new items
  - Viewing reports
  - Building menus
- Potential shorthand codes for quicker interaction.

### Technical Requirements

**Software**: 
- Python (latest stable version)
- Libraries: TBD, updates will be reflected here.

**Hardware**: 
- Any standard computer capable of running Python.

## Class Structure (Object-Oriented Approach)

**Main Food Item Class**: 
- Attributes: `name`, `category`, `price`, `quantity`, etc.
  
**Inherited Classes**: 
- **Snack** - Example attributes: `flavor`, `size`
- **Vegetable**, **Fruit**, **Protein**, **Carbohydrate** - Specific attributes based on category.

## Conclusion

This document outlines the initial design for the Grocery Tracker. Future enhancements include:

- Transition to a graphical user interface
- More sophisticated menu builder with varied meal options
- Expansion of food categories and item attributes
- Enhanced data analysis capabilities (e.g., nutritional tracking, budget forecasting)

## Links

- [Code Repository](https://github.com/FranklinWoodard/Grocery-Tracker.git)
