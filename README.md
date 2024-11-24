# Airflow ETL Pipeline for Weather Data

This project demonstrates an ETL (Extract, Transform, Load) pipeline built using [Apache Airflow](https://airflow.apache.org/) with the Astro platform. The pipeline processes weather data fetched from [Open-Meteo](https://open-meteo.com/), transforms it, and stores it in a PostgreSQL database using Docker containers for orchestration.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)

---

## Project Overview
The goal of this project is to implement a reliable and scalable ETL pipeline that:
1. Extracts weather data from the Open-Meteo API.
2. Transforms the data into a format suitable for analysis and storage.
3. Loads the transformed data into a PostgreSQL database for further processing or visualization.

---

## Features
- **ETL Workflow Orchestration**: Managed using Airflow DAGs.
- **Weather Data Source**: Data is fetched in real-time from Open-Meteo API.
- **Database Storage**: PostgreSQL is used for storing transformed data.
- **Containerized Environment**: Uses Docker for seamless deployment and scalability.

---

## Technologies Used
- **Astro Airflow**: For building and scheduling DAGs.
- **PostgreSQL**: For database storage.
- **Open-Meteo API**: For weather data extraction.
- **Docker**: For containerizing the application.
- **Python**: For scripting ETL logic and Airflow DAGs.

---

## Setup and Installation

### Prerequisites
1. Docker and Docker Compose installed on your system.
2. An Open-Meteo API key (if required for access).
3. Python installed for testing and development.

Clone the repository:
   ```bash
   git clone https://github.com/HiyaJain22/Airflow_ETLWeather.git
   cd Airflow_ETLWeather

