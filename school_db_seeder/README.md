# School DB Seeder

A Python script for seeding a school database with realistic fake data using `Faker`.  
The project creates tables for students, teachers, grades and groups, and populates them with random data.  
Perfect for generating test data for development or database exercises.

## 🚀 Features

- Creates database tables:
    - Students
    - Teachers
    - Grades
    - (Optionally) Groups
- Random data generation using `Faker`
- Populates database with:
    - 50 students
    - Teachers assigned to subjects
    - Random grades (2-5) per student per subject
- Uses SQLite for easy local development

## 🏗️ Technologies

- Python 3.8+
- SQLite3 (Python standard library)
- Faker
- Random (Python standard library)

## 📦 Installation

1. Clone this repository:

```bash
git clone https://github.com/pawl455/school_db_seeder.git
cd school_db_seeder
