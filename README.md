# 🎬 Movies Database - SQL Project

This is an SQL project that models a relational "Movies DB", including entities such as movies, directors, genres, languages, countries, and more. It serves as a practical example for database modeling, complex queries, and real-world data handling in a cinematic context.

---

## 📁 Database Structure

The database includes the following tables:

- `movie` – stores movie data
- `director` – stores movie directors
- `language` – language spoken in the movie
- `country` – country of origin
- `genre` – movie genre
- `movie_genre` – junction table for the many-to-many relation between movies and genres

### 🔗 Relationships:
- Each movie has **one** director, language, and country → many-to-one relationships
- A movie can have **multiple** genres → many-to-many relationship via `movie_genre`

---

## 📥 Data Insertion

The project includes sample insertions with fictional data:

- 10 movies
- 10 directors
- 10 genres
- 10 countries
- 10 languages
- Multiple movie–genre associations

---

## 📊 Useful SQL Queries

The project includes several useful queries such as:

1. 🎯 Movies with a budget higher than the average budget
2. 🌍 Number of movies produced per country
3. 🎞️ Genres with more than 5 movies
4. 💸 Top 10 highest-grossing movies
5. ⏱️ Top 5 shortest movies
6. 💰 Total box office revenue
7. 📏 Average movie duration
8. 💵 Most and least expensive movies
9. 🔠 Uppercase titles longer than 15 characters
10. 🔍 First 5 characters of each movie title
11. 📈 Total number of movies per genre (using `genre` and `movie_genre`)

---

## 🔧 Other Operations

- `UPDATE` for changing a country name
- `DELETE` to remove short movies (under 70 mins)
- Use of SQL functions like `AVG()`, `SUM()`, `UPPER()`, `LOWER()`, `SUBSTRING()`, `COUNT()`, and more

---

## 🧠 What I Practiced / Learned

- Creating a normalized relational database from scratch
- Handling one-to-many and many-to-many relationships
- Using aggregate functions and subqueries
- Data manipulation and filtering

---

## 🚀 How to Run This Project

1. Open your SQL client (e.g., MySQL Workbench)
2. Run the entire `.sql` file from top to bottom
3. You can freely modify, test, and expand the data or queries

---

## 👤 Author

**Robert Ștefan Popescu**  
📧 Contact: robert@example.com (or GitHub profile)

---

## 🏁 Project Status

✅ Completed  
🛠️ Future improvements:
- Add reviews & ratings
- Include actors and roles (extra many-to-many relation)
- Generate movie rankings by box office
