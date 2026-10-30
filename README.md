# Moods and Stresses

This repository is the starting point for a two-part full-stack exercise. This README contains **Part 1 only**. Your interviewer will send you Part 2 after the application below is running.

## Part 1: Build the Data Pipeline

Build a small full-stack application that reads the three CSV files in this repository and makes their data available to a user interface through a backend.

You may use any languages, frameworks, libraries, database, or in-memory data structures you prefer. Choose tools that let you work comfortably and move quickly; production-grade styling, authentication, and deployment are not required.

### AI use

You are encouraged to use AI tools during Part 1. You may use them to scaffold the application, select or install dependencies, parse the files, build the API and UI, debug errors, or complete any other Part 1 work.

Do not attempt to predict or solve Part 2. When the application meets the completion criteria below, tell your interviewer. They will provide the next prompt and explain the tool-use rules for that part.

### The data

- [users.csv](users.csv): `user_id`, `user_name`, `full_name`
- [moods.csv](moods.csv): `user_id`, `date`, `mood`
- [stress.csv](stress.csv): `user_id`, `date`, `stress`

The mood and stress files contain daily readings associated with the people in the users file. Some readings may be missing. You do not need to analyze, combine, or interpret the readings in Part 1.

### Completion criteria

Your Part 1 application is ready when:

- It has both a backend and a user interface.
- The backend reads all three CSV files.
- The user interface makes at least one request to the backend and displays data returned by it.
- The displayed result demonstrates that data from each of the three files is available. A few sample records, record counts, or another simple representation is sufficient.
- You can explain the path the data takes from the CSV files to the screen.

Keep the implementation simple. You will build on it in Part 2, so favor a structure you can understand and change easily.

Once these criteria are met, stop and let your interviewer know you are ready for Part 2.
