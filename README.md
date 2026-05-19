# CITASYA - Medical Appointment Management System

## Overview
CITASYA is a web-based medical appointment management system developed using Python and Flask. The platform provides a secure login and registration system with role-based dashboards. It allows patients to schedule medical appointments and review their appointment history, while doctors can view their daily schedule and upcoming appointments. The project uses SQLite as its database engine to store user accounts and appointment records.

## Features
### Authentication Module
- User registration with role assignment (Patient, Doctor, Administrator)
- Secure login system with session handling
- Logout functionality
- User data stored in an SQLite database

### Patient Dashboard
- Schedule a new medical appointment
- View pending appointments
- View appointment history

### Doctor Dashboard
- View today's appointments
- View upcoming appointments
- Organized schedule visualization

### Database Management
- SQLite database integration (`citasya.db`)
- Tables for user accounts and appointments
- Persistent storage of registered users and scheduled appointments

## Technologies Used
- Python 3
- Flask
- SQLite3
- HTML and CSS (embedded templates)

## Project Structure
This project is developed as a single-file Flask application:

- `app.py` (main application)
- `citasya.db` (SQLite database generated automatically)

## Installation and Setup

### Requirements
- Python 3.x installed
- pip package manager

### Install Dependencies
Run the following command to install Flask:

```bash
py -m pip install flask
