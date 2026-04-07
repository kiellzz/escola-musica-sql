# 🎼 Music School — Database

<p align="center">
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/Relational%20Database-000000?style=for-the-badge" />
</p>

---

## 🧠 About the Project

Relational database designed as an **academic project (2nd semester)** to manage orchestras, musicians, symphonies, and performances.

The project focuses on data modeling, relationships, and complex queries using SQL.

---

## 🏗️ Database Structure

- **orchestra**: id, name, city, country, creation_date, continent  
- **symphony**: id, name, composer, date, country  
- **musician**: id, name, identity, nationality, birth_date, gender, city, instrument, orchestra, continent  
- **instrument**: id, name  
- **role**: id, name  
- **performance**: id, date, orchestra, symphony  
- **musician_role_performance**: links musicians, roles, instruments, and performances  

---

## 📊 Sample Data

- Orchestras: Vienna Philharmonic, Brazilian Symphony Orchestra  
- Symphonies: Symphony No. 5 (Beethoven), Symphonie Fantastique (Berlioz)  
- Musicians: João Silva, Anna Müller, Yuki Tanaka  
- Instruments: Violin, Viola, Piano  
- Roles: Violinist, Pianist, Flautist  

---

## 🔍 Main Queries

- Brazilian vs foreign musicians  
- Musicians by continent  
- Musician with instrument and orchestra  
- Youngest and oldest musician  
- Orchestra performing the oldest / newest symphony  

---

## 🧩 Views

- view_brazilian_musicians / view_foreign_musicians  
- view_south_american_musicians / view_non_south_american_musicians  
- view_male_musicians / view_female_musicians  
- view_musician_instrument / view_musician_orchestra  
- view_youngest_musician / view_oldest_musician  
- view_european_orchestras / view_non_european_orchestras  

---

## 🎯 Purpose

This project was created to:

- Practice relational database modeling  
- Work with SQL queries and views  
- Understand real-world data relationships  

