# EDA_Book_sales
# 📊 Exploratory Data Analysis (EDA) on Book Sales Data

## 📂 Dataset Columns

`['index', 'Publishing Year', 'Book Name', 'Author', 'language_code', 'Author_Rating', 'Book_average_rating', 'Book_ratings_count', 'genre', 'gross sales', 'publisher revenue', 'sale price', 'sales rank', 'Publisher', 'units sold']`

---

## 🔍 Business Questions Answered

1️⃣ Trend of number of units sold over publishing year
2️⃣ Relationship between sale price & units sold
3️⃣ Relationship between average book rating & units sold
4️⃣ Relationship between average book rating & book ratings count
5️⃣ Distribution of units sold by genre
6️⃣ Composition of number of books by genre
7️⃣ Top 5 authors by average book rating
8️⃣ Bottom 5 authors by average book rating
9️⃣ Top 10 publishers with highest revenue
🔟 Distribution of units sold by genre & author rating

---

## 📈 Key Insights

* **Publishing Year vs Units Sold**:
  Most of the units (~59%) were sold after the year **2000**.

* **Sale Price vs Units Sold**:
  No significant relationship. Some books with lower prices sold <10,000 units, while others at the same price sold >30,000 units.

* **Average Rating vs Units Sold**:
  No strong relation observed. Books with lower ratings sometimes sold fewer than 10,000 units, while others with similar ratings sold over 30,000 units.

* **Average Rating vs Ratings Count**:
  A **direct relationship** – as the number of ratings increases, the average rating tends to rise.

* **Units Sold by Genre**:
  Children’s books show the **widest spread** in sales, ranging from **106 units to 50,112 units**.

* **Book Composition by Genre**:
  About **77%** of books belong to the **Fiction** genre.

* **Top Authors by Average Rating**:
  ⭐ **Bill Watterson** – Avg rating **4.65**

* **Bottom Authors by Average Rating**:
  ❌ **Sue Monk Kidd** – Avg rating **3.10**

* **Units Sold by Genre & Author Rating**:
  In the **Fiction** genre, more units are sold when authors have **Excellent** or **Intermediate** ratings. Very few sales are observed for books by **Novice** or less-known authors.

---

## 🚀 Takeaways

This analysis highlights how **genre and author reputation** impact book sales far more than **price or average rating**. Publishers and authors can leverage these insights to position their books strategically in the market.

