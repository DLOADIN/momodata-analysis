# MoMo Data Analysis Project
A full-stack application designed to process, analyze, and visualize SMS transaction data in XML format. The project provides an interactive dashboard for data analysis with a clean, responsive user interface.

## Features

- XML data processing and cleaning
- Relational database storage using SQLite
- Interactive dashboard with data visualization
- Search and filter functionality
- Responsive design
- Data visualization using Chart.js
- Pagination for large datasets

## Technology Stack

- **Frontend**:
  - HTML
  - CSS
  - JavaScript
  - Chart.js for data visualization

- **Backend**:
  - Python
  - Django
  - SQLite database
  - xml.etree.ElementTree for XML processing

### Prerequisites
Ensure you have the following installed on your system:
- Python 3 or Python

## Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/DLOADIN/momodata-Analysis.git
cd momo-Analysis
```

2. Set up a Python virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install django(Required):
```bash
pip install django sqlalchemy
```

4. Change the directory:
```bash terminal
cd MOMO_DASHBOARD
```

5. Then Start the development server:
```bash terminal
python manage.py runserver
```
/!\: Make sure your are current working directory has manage.py

6. Go to http://127.0.0.1:8000/momo:
  ``` bash terminal
  http://127.0.0.1:8000/momo
  ```
   Now you can use and navigate our beautiful\_\_ app.

7. For accessing our simple api
```
[http://127.0.0.1:8000/momo](http://127.0.0.1:8000/momo/api/transaction-data/)
```

8. For accessing our simple api
Go to:
```
- http://127.0.0.1:8000/momo/api/transaction-data/
```

9. For accessing my demo video
Go to:
```
- https://vimeo.com/1091293185?share=copy
```

## Project Structure

- Frontend CSS files are organized in a dedicated folder with separate files for:
  - Tables
  - Charts
  - Component-specific styles


- Backend structured with Django's MVT architecture
  - Data processing modules
  - Database models
  - View logic
  - URL routing

## Key Features Implementation

### Dashboard

- Interactive search and filter options
- Data visualization using Chart.js
- Responsive design for various screen sizes
- Paginated data tables

### Data Processing

- XML data cleaning and structuring
- Validation of SMS message fields
- Standardized data processing pipeline

### Database

- Optimized schema design
- Efficient query handling
- Data integrity constraints
- Django ORM integration

## Challenges Addressed

- Resolved merge conflicts in CSS implementation
- Handled data inconsistencies in SMS messages
- Optimized parsing of varied XML structures
- Implemented efficient database queries for large datasets
- Ensured smooth frontend rendering of large data sets

## Future Improvements

- Enhanced database performance optimization
- Additional data analysis filters
- Advanced dashboard visualizations
- Improved data processing efficiency

## Documentation & References

- [Project Repository](https://github.com/DLOADIN/momodata-analysis)
- [Python XML Parsing Documentation](https://docs.python.org/3/library/xml.etree.elementtree.html)
- [SQLite Documentation](https://www.sqlite.org/docs.html)
- [Django Documentation](https://docs.djangoproject.com/)
- [Chart.js Documentation](https://www.chartjs.org/)

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request