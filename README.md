# CountX

A command-line calorie tracking application built in C++ that helps users manage their daily nutritional intake through an intuitive account-based system.

## Overview

CountX is a lightweight meal management system designed to help users track their daily calorie consumption against personalized goals. The application features a pre-loaded database of common foods and meals, while also allowing manual calorie entry for maximum flexibility.

## Features

- **User Account Management**: Create, login, and manage multiple user accounts with individual calorie targets
- **Calorie Tracking**: Log daily calories either manually or by selecting from 20+ pre-loaded ingredients and meals
- **Historical Data**: View calorie logs by date and track progress against daily objectives
- **Data Persistence**: All user data and logs stored in CSV format for easy access and portability
- **Duplicate Prevention**: Built-in validation prevents duplicate ingredients and accounts

## Technical Stack

- **Language**: C++ (Standard Library)
- **Data Storage**: CSV files (`accounts.csv`, `logs.csv`)
- **Architecture**: Object-oriented design with separate classes for ingredients and management logic

## Getting Started

### Prerequisites
- C++ compiler (g++, clang, or MSVC)
- Standard C++ library support

### Compilation
```bash
g++ -o countx main.cpp
```

### Running
```bash
./countx
```

## Usage

Upon launch, users can:
1. Create a new account with a daily calorie objective (500-5000 calories)
2. Log in to an existing account
3. Track calories for specific dates
4. View progress against daily goals
5. Modify calorie objectives as needed


## Development Notes

This project was developed with AI assistance as part of demonstrating C++ proficiency, file I/O operations, and object-oriented design principles.

## Future Enhancements

Potential improvements include:
- Database integration (SQLite)
- GUI implementation
- Macronutrient tracking (protein, carbs, fats)
- Data visualization and reporting
- Import/export functionality

---

**If you find this project interesting, please consider giving it a star!**
