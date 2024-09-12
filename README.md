# MedData Manager

MedData Manager is a web-based application for managing various health-related data tables using PostgreSQL. The application provides a user-friendly interface built with Streamlit for performing CRUD operations (Create, Read, Update, Delete) on tables such as `disease_type`, `disease`, `country`, `doctor`, `users`, and more.

## Features

- View, add, update, and delete records for multiple tables.
- Streamlined database management for health-related data.
- PostgreSQL as the backend database.
- Built with SQLAlchemy for database operations and Streamlit for the user interface.

## Tables

- **disease_type**: Manages different types of diseases.
- **disease**: Manages disease records with descriptions and pathogens.
- **country**: Stores country information with population data.
- **doctor**: Manages doctor records with associated degrees.
- **users**: Manages user records with salaries and contact information.
- **public_servant**: Tracks public servants working in health departments.
- **specialize**: Records the specialization of doctors in diseases.
- **record**: Keeps track of disease statistics in countries.
- **discover**: Stores disease discovery dates in specific countries.

## Installation

To set up and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MedData-Manager.git
