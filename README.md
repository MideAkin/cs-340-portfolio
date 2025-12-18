# Grazioso Salvare Rescue Dashboard

## Project Overview
The Grazioso Salvare Rescue Dashboard is an interactive web-based dashboard developed using Python and the Dash framework. The application allows users to analyze animal shelter outcome data to support rescue operations, including water rescue, mountain/wilderness rescue, and disaster/individual tracking.

The dashboard connects to a MongoDB database and provides real-time data filtering, visualization, and analysis tools to assist Grazioso Salvare in making data-driven decisions.

---

## Features
- Interactive data table with filtering and row selection
- Rescue-type filtering using radio buttons
- Geographic visualization of animal locations using a map
- Pie chart displaying the top 10 animal breeds based on current filters
- Integrated Grazioso Salvare branding with logo
- Secure database access using a dedicated MongoDB user

---

## Technologies Used
- **Python**
- **Dash / Plotly**
- **Pandas**
- **MongoDB**
- **JupyterDash**
- **HTML/CSS (via Dash components)**

These tools were selected to support interactive data visualization, efficient data handling, and seamless database integration.

---

## How to Run the Project
1. Ensure MongoDB is running and contains the AAC shelter data.
2. Verify the following files are located in the `code_files` directory:
   - `ProjectTwoDashboard.ipynb`
   - `CRUD_Python_Module.py`
3. Open `ProjectTwoDashboard.ipynb` in JupyterLab.
4. Restart the kernel and run all cells from top to bottom.
5. Open the Dash application using the provided Codio/Jupyter Dash tab.

---

## Project Structure
