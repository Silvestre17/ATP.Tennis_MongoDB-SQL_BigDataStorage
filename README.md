# 🛠️ Database Administration Project: From Relational Prowess to NoSQL Versatility 🗄️

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/3f/ATP_Tour_logo.svg/1200px-ATP_Tour_logo.svg.png" alt="Database Administration Project Banner" width="200">
</p>

<p align="center">
    <!-- Project Links -->
    <a href="https://github.com/Silvestre17/ATP.Tennis_MongoDB-SQL_BigDataStorage"><img src="https://img.shields.io/badge/Project_Repo-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

## 📝 Description

This project focuses on building, managing, and optimizing a database system using both relational (**SQL**) and non-relational (**NoSQL**) database models. The project aims to demonstrate proficiency in database design, implementation, data migration, and performance tuning within different database paradigms.

## ✨ Objective

The primary objective is to build a robust data management solution by:
*   Designing and implementing a normalized relational database schema.
*   Efficiently migrating data from MySQL to a MongoDB collection.
*   Implementing performance optimizations, including proper indexing.
*   Demonstrating a practical understanding of when and how to use different database models.

## 🎓 Project Context

This project was developed for the **Armazenamento para Big Data** (*Storage for Big Data*) course, as part of the **[Licenciatura em Ciência de Dados](https://www.iscte-iul.pt/degree/code/0322/bachelor-degree-in-data-science)** (*Bachelor Degree in Data Science*) at **ISCTE-IUL**. The work was completed during the 2022/2023 academic year in 1st Semester in 2nd year.

## 🛠️ Technologies Used

The project was implemented using a standard stack for relational and NoSQL database management.

<p align="center">
    <a href="https://www.mongodb.com/">
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    </a>
    <a href="https://www.mysql.com/">
        <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
    </a>
    <a href="https://www.phpmyadmin.net/">
        <img src="https://img.shields.io/badge/phpMyAdmin-F27319?style=for-the-badge&logo=phpmyadmin&logoColor=white" alt="phpMyAdmin" />
    </a>
</p>

## 📝 Data Source

*   **Dataset:** `ATP Players` - A complete database of the TOP500 ATP men's professional tennis players, data taken from the [official ATP website](https://www.atptour.com/en/stats/individual-game-stats?factType=Aces&year=career&surface=all&country=all&sortBy=percentage&sortDirection=desc) via webscrapping in 2022.
*   **Origin:** The initial data was provided in `.json` format, which was then processed and structured for data analysis.

## ⚙️ Project Workflow & Key Steps

1.  **Data Ingestion & Initial Analysis (NoSQL):** 🔍
    *   The raw data was first imported from a `.json` file into a **MongoDB** collection using `mongoimport`. This allowed for flexible initial exploration of the semi-structured data.

2.  **Relational Database Design (SQL):** 📐
    *   Analyzed the entities (Players, Tournaments, Games) and their relationships.
    *   Designed a normalized relational schema with three main tables: `Players`, `Tournaments`, and `Games`, linked by primary and foreign keys.

3.  **Implementation & Data Loading (SQL):** 💻
    *   Exported the data from MongoDB to a `.csv` file.
    *   Created the tables in **MySQL** and imported the structured data from the CSV.
    *   Cleaned and standardized the data within SQL, handling inconsistencies in player names, locations, and other attributes.

4.  **Optimization:** ⚡
    *   Applied indexes to key columns (like `Player_Name` and foreign keys) to significantly improve query performance for data retrieval and joins.

## 🔗 Relational Database Schema

The final relational model was designed to ensure data integrity and minimize redundancy.

<p align="center">
    <img src="./img/Esboço da BD Relacional_Com Oponente Nome.png" alt="Relational Database Schema"/>
</p>

---


## 🚀 How to Run the Code

To replicate this project, you will need **MongoDB** and **MySQL** (preferably managed via a tool like **phpMyAdmin** or MySQL Workbench).

#### 1. Initial Data Load into MongoDB

1.  Start your MongoDB server.
2.  Use the `mongoimport` command line tool to load the initial JSON data.
    ```bash
    mongoimport --db atp --collection players --drop --file atpplayers.json
    ```
    *(Note: The `--drop` option will remove the existing collection before importing new data to avoid duplicates. Make sure to adjust the file path as necessary.)*

#### 2. Data Export to CSV

1.  Use `mongoexport` to create a CSV file that can be imported into MySQL.
    ```bash
    mongoexport --db atp --collection players --type=csv --fields PlayerName,Born,Height,Hand,LinkPlayer,Tournament,Location,Date,Ground,Prize,GameRound,GameRank,Oponent,WL,Score --out atp.csv
    ```
    *(Note: You need to adjust the file path and fields according to your MongoDB collection structure.)*

#### 3. Setup and Data Loading in MySQL

1.  Create a new database (e.g., `atp_relational`) in your MySQL server.
2.  Run the SQL script provided in this repository (`schema_and_load.sql`). This script will:
    *   `CREATE` all the necessary tables (`Players`, `Tournaments`, `Games`).
    *   `LOAD DATA INFILE` to import the data from `atp.csv`.
    *   Run all the `UPDATE` and `ALTER TABLE` commands for data cleaning, normalization, and index creation.

## 👥 Team Members (Group 8)

*   **André Silvestre** (Nº104532)
*   **Diogo Catarino** (Nº104745)
*   **Francisco Gomes** (Nº104944)
*   **Rita Matos** (Nº104936)


## 🇵🇹 Note

This project was developed using Portuguese from Portugal 🇵🇹.
