# Predicting Dengue Hotspots in Malabon City through AI and Integrated Weather-Case Analysis

<p align="center">
  <strong>AI-Powered Dengue Hotspot Prediction and Geospatial Monitoring Dashboard</strong><br>
  <em>Capstone Project | Bachelor of Science in Information Technology | City of Malabon University</em>
</p>

<img src="assets/AI-dengue-hotspot-predictor-preview.png" alt="Dengue Hotspot Prediction System" width="900">

## Project Overview

**Predicting Dengue Hotspots in Malabon City through AI and Integrated Weather-Case Analysis** is a monolithic web application developed using **Python and Django** as a capstone project.

The system combines historical dengue case data with weather and environmental metrics to generate AI-assisted predictions of dengue transmission risk across barangays in **Malabon City**. Results are presented through an interactive dashboard and geospatial map, allowing users to visualize localized risk levels and identify areas that may require closer monitoring.

The project demonstrates practical experience in **full-stack web development, machine learning integration, API integration, data processing, database management, and geospatial visualization**.

## Objectives

- Predict potential dengue transmission risk using historical case and weather data.
- Analyze relationships between environmental conditions and localized dengue cases.
- Visualize predicted risk levels across Malabon City barangays.
- Integrate external weather data through an API.
- Provide a web-based dashboard for presenting AI-generated insights.
- Demonstrate the integration of machine learning into a full-stack web application.

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Random%20Forest-2E7D32?style=for-the-badge">
  <img src="https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/Open--Meteo-4B8BBE?style=for-the-badge">
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>

| Area | Technology |
|---|---|
| Programming Language | Python |
| Web Framework | Django |
| Machine Learning | Random Forest |
| Data Processing | Pandas |
| Database | SQLite / MySQL |
| Mapping & Visualization | Leaflet.js |
| Weather Data | Open-Meteo API |
| Version Control | Git / GitHub |

## Architecture

The application follows a **monolithic Django architecture**, with the web interface, server-side application logic, data processing, database operations, and machine learning integration maintained within the same application.

### High-Level Data Flow

```text
Historical Dengue Cases
          │
          ▼
   Data Preparation
          │
          ├───────────────┐
          │               │
          ▼               ▼
 Weather Data        Case Statistics
(Open-Meteo API)          │
          │               │
          └───────┬───────┘
                  ▼
          Data Processing
              (Pandas)
                  │
                  ▼
        Random Forest Model
                  │
                  ▼
        Risk Prediction Data
                  │
          ┌───────┴────────┐
          ▼                ▼
     Django Backend    SQLite / MySQL
          │
          ▼
      Web Dashboard
          │
          ▼
     Leaflet.js Map
          │
          ▼
   Barangay Risk Clusters
```

## Key Features

### AI-Based Dengue Risk Prediction

Implemented a machine learning pipeline using a **Random Forest model** to analyze historical dengue and environmental data and generate localized transmission-risk predictions.

### Weather and Case Data Integration

Integrated the **Open-Meteo API** to retrieve historical and weather-related metrics used as environmental variables for analysis.

The project involved handling API responses, converting JavaScript/JSON data into structures that Python could process, and preparing the resulting data for machine learning and database storage.

### Data Processing with Pandas

Used **Pandas** to clean, transform, organize, and prepare datasets before they were passed into the machine learning workflow.

### Geospatial Risk Visualization

Built an interactive **Leaflet.js** map that visualizes predicted dengue risk across Malabon City barangays.

The dashboard uses localized risk indicators to make geographically distributed prediction results easier to interpret.

### Django Web Application

Developed the application backend using **Django**, including server-side routing, application logic, database interaction, and integration of the prediction workflow into the web dashboard.

### Database Integration

Used **SQLite** during development for storing and managing application and prediction-related data, with MySQL also considered/supported as a database environment.

## My Role

**Lead Programmer | August – October 2025**

As the lead programmer, I was responsible for major parts of the application's development and technical integration, including:

- Developing the Django-based web application.
- Implementing the machine learning workflow using Random Forest and Pandas.
- Integrating weather data through the Open-Meteo API.
- Handling API response and JSON data conversion for Python-based processing.
- Connecting prediction-related data with the application database.
- Developing the interactive Leaflet.js geospatial dashboard.
- Implementing backend routing and server-side application logic.
- Troubleshooting integration issues between different technologies and data formats.

## Technical Challenges

### API and Data Conversion

One of the major technical challenges was integrating data originating from different technologies and formats.

The project required converting JavaScript/JSON-based data into structures that could be processed by Python and used by the machine learning pipeline. This included handling data from:

- **Leaflet.js** map coordinates and geospatial information.
- **Open-Meteo API** weather responses.
- Historical dengue case datasets.
- Database records used by the Django application.

This required independently troubleshooting data-format mismatches and designing a workable data flow between the frontend, API layer, Django backend, database, and machine learning components.

### Machine Learning Integration

Another challenge was integrating a machine learning model into a web application rather than treating the model as a standalone script.

The project connected the prediction pipeline with Django so that processed data could be used to generate results that were then presented through the web dashboard.

## Skills Demonstrated

This project provided practical experience in:

- Python development
- Django web development
- Full-stack application development
- Machine learning integration
- Random Forest modeling
- Data processing with Pandas
- REST/API data integration
- JSON data handling
- SQL and database management
- Geospatial visualization
- Leaflet.js
- Backend routing
- Technical troubleshooting
- Git and GitHub
- System architecture and integration

## Project Significance

This project demonstrates how a machine learning model can be integrated into a practical web-based information system instead of existing only as an isolated data science experiment.

It combines several areas of information technology into one application:

**Frontend → Backend → API → Database → Data Processing → Machine Learning → Geospatial Visualization**

The project was developed as an academic capstone and is intended as a **decision-support and visualization system**, not as a replacement for professional medical diagnosis, epidemiological surveillance, or public-health decision-making.

## Project Status

**Completed — Capstone Project**

**Role:** Lead Programmer  
**Development Period:** August – October 2025  
**Degree:** Bachelor of Science in Information Technology  
**University:** City of Malabon University  
**Batch:** 2026

## Author

**Ammaron C. Oliveros**

Information Technology graduate with a foundation in full-stack development, Python/Django development, database management, technical troubleshooting, and systems integration.

---

<p align="center">
  <sub>Built as a Bachelor of Science in Information Technology capstone project.</sub>
</p>
