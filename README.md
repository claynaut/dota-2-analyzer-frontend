# Dota 2 Analyzer Frontend
> Author: J.S. Pescasio

## What Is It?
Frontend code of a CS180 (Intro to Software Engineering) project. 

In this project, my group and I developed a web application that analyzed data from a ["Dota 2 Matches" database from kaggle](https://www.kaggle.com/devinanzelmo/dota-2-matches). I developed the frontend while the other group members developed the backend.

## Original Project Specifications
> Original frontend developer: J.S. Pescasio

> Original backend developers: Tinh La, Wyland Lau, Sky Wu, Hsiang-Yin (Sean) Hsieh

This was a team project (5 students per team). The goal was to build an **in-memory data store** with a **layered client-server architecture** from scratch. The data store provides predefined data analytics for gaining insights from the data. Initially, the data store can be populated with some public dataset in CSV format.

## Dataset Used
The public dataset we chose was the ["Dota 2 Matches" database from kaggle](https://www.kaggle.com/devinanzelmo/dota-2-matches).

## Original Features
### Search Feature
> Each search feature displays either 25, 50, or 100 search results (determined by the user).
- Search Heroes
- Search Abilities
- Search Players
- Search Matches by First Blood Time
- Search Matches by Cluster Region
- Search Matches by Likes

### Insert/Update/Delete, Backup/Import Features
> These features originally work with the API server and backend code (not included in this codebase). The insert/update/delete features would update the dataset to be displayed in the GUI.
- For Heroes
- For Abilities
- For Players
- For Matches

*Side note: The admin password to update an ability is "1234"*

### Analytics
- **Search Top Upgraded Abilities:** gets abilities in order of number of upgrades
- **Get a Hero's Win Rate Over Time in Matches:** gets a hero's win rate over time (represented in a line chart)
- **Compare a Hero's Win Rate Against Other Heroes:** gets the win rate ratio in comparison to other heroes (repesented in a bar chart)
- **Compare a Hero's Average XP and Gold in Matches:** gets the hero's average XP and gold accumulated over a number of matches (represented in a bar chart)
- **Get a Match's Win Rates for First Blood:** gets a match's win rates for different win types for first blood (represented in a bar chart)

## Tech Stack
- **[React](https://reactjs.org/):** frontend framework used for this project
- **[Axios](https://github.com/axios/axios):** used to make GET/POST requests to an API server
- **[Express](https://expressjs.com/):** web framework used for the API server to connect the backend to the frontend

## 3rd Party Packages
- **[Chart.js](https://www.chartjs.org/):** used to display the data through charts
