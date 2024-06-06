# IMBD-Replica : Movie Database UI - School Project

This contains the code for a school project aimed at developing a simple user interface (UI) to interact with a movie database. The UI allows users to execute and display results for various queries, providing an intuitive and user-friendly experience.

## Table of Contents

- [Project Overview](#project-overview)
- [UI Requirements](#ui-requirements)
  - [Basic Queries](#basic-queries)
- [Query Descriptions](#query-descriptions)
- [Getting Started](#getting-started)
- [Setup Instructions](#setup-instructions)

## Project Overview

This project is a school assignment designed to create a basic UI for interacting with a movie database. The UI should enable users to execute predefined queries and display the results in a user-friendly manner. 

## UI Requirements

The UI must meet the following basic requirements:

1. **Query Execution**: Users should be able to execute a list of queries through the UI. The required queries will be specified in the next deliverable.
   
2. **Basic Queries**:
   - **View All Movies**: A button that, when clicked, lists all movies and their details.
   - **View All Actors**: A button that, when clicked, lists all actors and their details.

3. **Query Execution via Front-End**: Queries should be executed by clicking on links or buttons. Parametrization can be done using textboxes, checkboxes, or option buttons. Simply providing a textbox for manual query entry is not acceptable.

4. **Results Display**: Query results should be displayed in a tabular format if the result includes multiple tuples and columns.

5. **User Interaction**: For features like "users liking movies", the UI should allow users to input their information and update the likes table when a user likes a movie.

Students are encouraged to improve the front-end design to meet these requirements. Assistance is available during office hours.

## Query Descriptions

Here is the list of queries to be implemented:

1. **List all tables in the database**.
2. **Search Motion Picture by name** (parameterized): Lists the movie name, rating, production, and budget.
3. **Find movies liked by a specific user** (parameterized by email): Lists the movie name, rating, production, and budget.
4. **Search Motion Pictures by shooting location country** (parameterized): Lists motion picture names without duplicates.
5. **List all directors who directed TV series in a specific zip code** (parameterized): Lists director name and TV series name without duplicates.
6. **Find people with more than "k" awards for a single motion picture in the same year** (parameterized): Lists person name, motion picture name, award year, and award count.
7. **Find the youngest and oldest actors to win at least one award**: Lists actor names and their age at the time of receiving the award.
8. **Find American producers with a box office collection ≥ "X" and budget ≤ "Y"** (parameterized): Lists producer name, movie name, box office collection, and budget.
9. **List people with multiple roles in a motion picture with rating > "X"** (parameterized): Lists person’s name, motion picture name, and role count.
10. **Find the top 2 rated thriller movies shot exclusively in Boston**: Lists movie names and ratings.
11. **Find movies with more than "X" likes by users aged < "Y"** (parameterized): Lists movie names and number of likes.
12. **Find actors in both "Marvel" and "Warner Bros" productions**: Lists actor names and motion picture names.
13. **Find motion pictures with higher rating than the average rating of all comedy movies**: Lists names and ratings in descending order.
14. **Find the top 5 movies with the highest number of people playing a role**: Lists movie name, people count, and role count.
15. **Find actors sharing the same birthday**: Lists actor names and their common birthday.

Parameterized queries should have text boxes for inputting the required parameters.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository.
2. Install necessary dependencies.
3. Run the application.

Detailed instructions for setup and running the application are provided below.

## Setup Instructions

Follow these steps to set up the project environment:

1. **Download the SQL database** provided in the GitHub repository.
2. **Import the SQL database** into phpMyAdmin.
3. **Find the installed location for XAMPP**: 
   - **Windows users**: The default location is usually `C:/Program Files/XAMPP/htdocs`.
4. **Create a directory structure**:
   - Create a folder named `COSI127B` under `C:/Program Files/XAMPP/htdocs`.
   - Within `COSI127B`, create a folder named `PA1.3`.
5. **Download and place the PHP files** found in the repository into the `PA1.3` folder.
6. Ensure your Apache web server is running.
7. Open your web browser and go to `http://localhost/COSI127B/PA1.3`.

This setup ensures that the PHP files are accessible through the local web server.

