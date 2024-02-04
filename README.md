# ABOUT

This project aims to create a Data Pipeline using Anime Data from 2020 - 2023 using Jikan API: https://jikan.moe/

Jikan API is an open-source API that provides information from myanimelist.net.

The process starts from extracting the data from API followed by data cleaning and transformation before loaded into a Postgres DB.
All steps above are done using Airflow on Docker.
After that the data is analyzed using Metabase on Docker, the result is saved as a Dashboard.
