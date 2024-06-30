Here's the short README with the video embedded:

---

# Organ Donation and Procurement Management System (ODPMS)

## Introduction

The Organ Donation and Procurement Management System (ODPMS) is designed to streamline the complex process of organ donation, ensuring efficiency, transparency, and ethical standards.

## Key Features

- **Donor Registration**: Secure registration and storage of donor information.
- **Organ Procurement Coordination**: Facilitates coordination between hospitals, OPOs, and transplant centers.
- **Logistical Management**: Manages the logistics of organ transportation with real-time tracking.
- **Data Analytics and Reporting**: Generates reports and analytics to evaluate and improve organ donation programs.
- **Communication and Collaboration**: Enhances communication among healthcare professionals and agencies.

## Benefits

- **Improved Efficiency**: Automates processes, reducing administrative burden and speeding up transplantation.
- **Enhanced Transparency**: Provides real-time access to critical information.
- **Increased Donation Rates**: Simplifies registration and encourages organ donation.
- **Better Patient Outcomes**: Reduces wait times and improves the quality of life for recipients.

## Technologies Used

- **Backend**: Flask (Python)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript

## Installation and Setup

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-repository/odpms.git
   ```

2. **Navigate to the Project Directory**:
   ```sh
   cd odpms
   ```

3. **Set Up Virtual Environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

4. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

5. **Configure the Database**:
   - Open MySQL Workbench.
   - Create a new database.
   - Update `config.py` with your database credentials:
     ```python
     SQLALCHEMY_DATABASE_URI = 'mysql+pymysql://username:password@localhost/db_name'
     ```

6. **Run Database Migrations**:
   ```sh
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

7. **Run the Application**:
   ```sh
   flask run
   ```

## Usage

- Access the application at `http://localhost:5000`.
- Register as a donor, manage organ procurement and allocation, track logistics, and generate reports.

## Video Tutorial

Watch the video tutorial below:

<video width="600" controls>
  <source src="demovideo.mp4" type="video/mp4">
</video>

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

