# Django CSV Visualizer

A simple Django-based web application to visualize and explore CSV data from Excel files. This tool allows users to upload Excel files, which are converted to CSV format and displayed in an interactive table. Users can filter, sort, and visualize data using various graphing techniques.

## Features

- **Upload Excel Files**: Accepts `.xls`, `.xlsx` formats.
- **CSV Conversion**: Automatically converts Excel data into CSV format for processing.
- **Data Visualization**: Provides graphical representation of data using charts (e.g., bar, line, scatter plots).
- **Data Filtering & Sorting**: Users can filter and sort data directly in the web interface.
- **Pagination Support**: Handles large datasets with paginated tables.

## Prerequisites

Make sure you have the following installed on your system:

- Python 3.x
- Django 4.x
- Pandas
- Openpyxl (for reading Excel files)
- Matplotlib or Plotly (for visualizations)

You can install the required Python libraries using:

```bash
pip install django pandas openpyxl matplotlib

'''
 



