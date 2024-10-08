[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/VuODydzp)
# FIFA Players Dataset Analysis

## Project Overview
This project processes and analyzes FIFA player datasets across multiple years for both male and female players. It includes data from 2016 to 2022. The data is loaded, processed, and stored in a PostgreSQL database for further analysis.

## Dataset Features
The dataset contains the following key features:
- **Player Information**: `sofifa_id`, `player_url`, `short_name`, `long_name`, `player_positions`, `overall`, `potential`
- **Financial Attributes**: `value_eur`, `wage_eur`, `release_clause_eur`
- **Personal Information**: `age`, `dob`, `height_cm`, `weight_kg`, `preferred_foot`, `weak_foot`, `skill_moves`, `international_reputation`, `work_rate`, `body_type`, `real_face`
- **Club Information**: `club_team_id`, `club_name`, `league_name`, `league_level`, `club_position`, `club_jersey_number`, `club_loaned_from`, `club_joined`, `club_contract_valid_until`
- **National Team Information**: `nationality_id`, `nationality_name`, `nation_team_id`, `nation_position`, `nation_jersey_number`
- **Skill Attributes**: Attributes such as `pace`, `shooting`, `passing`, `dribbling`, `defending`, `physic`, and detailed attacking, skill, movement, power, mentality, and defending attributes.
- **Goalkeeping Attributes**: `goalkeeping_diving`, `goalkeeping_handling`, `goalkeeping_kicking`, `goalkeeping_positioning`, `goalkeeping_reflexes`
- **Positional Attributes**: Specific ratings for various positions such as `ls`, `st`, `rs`, `lw`, `lf`, `cf`, etc.
- **Images**: URLs to player face images, club logos, and national flags.

## Benefits of Using PostgreSQL Compared to NoSQL Database
Using a PostgreSQL relational database for this project provides several advantages over a NoSQL database:

1. **Structured Data with Relationships**: PostgreSQL is ideal for storing structured data with complex relationships, such as player attributes linked to clubs and national teams. It provides ACID compliance, which ensures data integrity across transactions.

2. **Data Integrity and Consistency**: PostgreSQL offers strong data typing and schema enforcement, which helps maintain data consistency and avoid discrepancies that can occur in NoSQL databases.

3. **SQL Querying Capabilities**: PostgreSQL supports SQL, making it easier to perform complex queries, aggregations, and data analysis directly within the database. This is highly beneficial for analytics-heavy tasks, which require complex joins and data transformations.

4. **Advanced Features**: PostgreSQL supports advanced features like indexing, full-text search, and window functions, which are useful for data processing and enhancing query performance.

In this case, PostgreSQL offers a robust, reliable, and well-supported platform that aligns with the need to analyze large datasets with structured attributes, while also ensuring data accuracy and efficient querying capabilities.
