# CodeFirstBasic1

Patika Code First Database Project
Overview
This project demonstrates how to create a database using the Code First approach in Entity Framework Core. It includes two independent tables: Movies and Games. These tables are automatically created based on the models defined in the application.

Requirements
Entity Framework Core is used to implement the Code First approach.
The following models are created:
Movie table with fields:
Id (int): Primary key, auto-incremented.
Title (string): Title of the movie.
Genre (string): Genre of the movie (e.g., Action, Comedy, Drama).
ReleaseYear (int): The release year of the movie.
Game table with fields:
Id (int): Primary key, auto-incremented.
Name (string): Name of the game.
Platform (string): Platform the game is played on (e.g., PC, PlayStation, Xbox).
Rating (decimal): The rating of the game (between 0 and 10).
Database Configuration
Context Class Name: PatikaFirstDbContext
Database Name: PatikaCodeFirstDb1
The database contains two tables:
Movies
Games
