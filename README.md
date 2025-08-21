# Netflix 1990s Movies — Exploratory Data Analysis

A compact, reproducible analysis of Netflix titles from the 1990s (1990–1999). We answer two business questions for a nostalgia-focused production company:

1. **What was the most frequent movie duration in the 1990s?**
2. **How many short *Action* movies (< 90 minutes) were released in the 1990s?**

> This repo is based on a DataCamp-style exercise. Feel free to fork and extend.

---

## Dataset

* **File:** `netflix_data.csv`
* **Source:** Provided with the exercise (place the file in the project root).
* **Schema:**

| Column         | Description                   |
| -------------- | ----------------------------- |
| `show_id`      | ID of the title               |
| `type`         | Type of title (Movie/TV Show) |
| `title`        | Title name                    |
| `director`     | Director(s)                   |
| `cast`         | Cast list                     |
| `country`      | Country of origin             |
| `date_added`   | Date added to Netflix         |
| `release_year` | Year of release               |
| `duration`     | Duration in minutes           |
| `description`  | Short synopsis                |
| `genre`        | Primary genre                 |

> **Note:** Some versions of the “Netflix titles” dataset store duration as strings (e.g., `"90 min"`). In this exercise, `duration` is already numeric minutes.

---

## Objectives (Business Questions)

1. **Most frequent 1990s duration:** Find the most common duration of movies released in the 1990s.
2. **Short Action count:** Count how many **Action** movies from the 1990s are **less than 90 minutes**.

---

## Tools & Libraries Used

* **Python 3**
* **pandas** → for data manipulation
* **numpy** → for logical filtering and calculations
* **matplotlib** → for optional visualization

---

## Insights & Learnings

* We practiced filtering data by year ranges (1990–1999).
* We explored **modes** in numerical data to find the most frequent duration.
* We worked with logical conditions to filter based on both **genre** and **duration**.
* The analysis gave insights into how 1990s movie runtimes clustered, and how many short action films were popular in that era.

---

## Possible Extensions

* Visualize the distribution of durations with histograms.
* Compare runtimes across genres (Action vs Drama vs Comedy).
* Explore country-level trends in 1990s movies.
* Identify prolific directors of the 1990s and their typical movie lengths.

---

## Acknowledgments

* Exercise inspired by **DataCamp**.
* Netflix dataset columns as specified in the exercise prompt.
