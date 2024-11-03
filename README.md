# ETL_Weather_Airflow
ETL Weather Airflow
# Apache Airflow Weather ETL Project

This project is an ETL (Extract, Transform, Load) pipeline built with **Apache Airflow** for processing weather data. The environment is managed using **Astro CLI**, and **PostgreSQL** is used as the backend database for storing the extracted data. Docker Compose is used to orchestrate the setup.

## Project Overview

The ETL pipeline in this project is designed to:
- Extract weather data from a source API or data file.
- Transform the extracted data into a structured format.
- Load the data into a PostgreSQL database for further analysis or use.

## Prerequisites

Ensure you have the following installed:
- Docker & Docker Compose
- Astro CLI (for managing the Airflow environment)

## Installation and Setup





```
winget install -e --id Astronomer.Astro
```

Initialize the Astro project:
```
astro dev init

```


#Start the Astro and PostgreSQL services:

```
astro dev start
```

