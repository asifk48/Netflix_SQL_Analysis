<h1>Netflix_SQL_Analysis</h1>

<h2>Overview</h2>
<p>This project explores Netflix's rich dataset of movies and TV shows, utilizing SQL to extract and analyze key insights. The goal is to uncover trends in content, identify patterns in release years, and understand the geographical diversity of Netflix's offerings. Through SQL queries, the project reveals valuable details about how Netflix curates and evolves its content library. 🎬📊</p>

<h2>Goals</h2>
<ul>
    <li>📺 Analyze the balance between content types (Movies vs. TV Shows).</li>
    <li>⭐ Investigate popular ratings and classify content by genre.</li>
    <li>🌍 Examine release patterns and identify countries contributing the most content.</li>
    <li>🎥 Highlight unique content, such as the longest movies and top-rated directors.</li>
</ul>

<h2>Dataset</h2>
<p>The dataset contains extensive details about Netflix's content, including show ID, type (Movie/TV Show), title, director, cast, country of origin, date added to Netflix, release year, rating, duration, genres, and a brief description.</p>

<h3>Dataset Structure:</h3>
<pre>
CREATE TABLE netflix (
    show_id VARCHAR(5),
    type VARCHAR(10),
    title VARCHAR(250),
    director VARCHAR(550),
    casts VARCHAR(1050),
    country VARCHAR(550),
    date_added VARCHAR(55),
    release_year INT,
    rating VARCHAR(15),
    duration VARCHAR(15),
    listed_in VARCHAR(250),
    description VARCHAR(550)
);
</pre>

<h2>Insights Gained</h2>
<p>Using SQL queries, the project uncovers several insights, including:</p>
<ul>
    <li>📊 Comparison of the number of Movies and TV Shows on Netflix.</li>
    <li>⭐ Rating patterns and the distribution of different content types.</li>
    <li>🌍 Top countries contributing to Netflix's content library.</li>
    <li>📅 Trends in content release over the years.</li>
    <li>🎬 Unique categories like documentaries, long-duration movies, and noteworthy directors.</li>
</ul>

<h2>Key Findings</h2>
<ul>
    <li><strong>Diverse Library:</strong> Netflix offers a vast library catering to various genres and global audiences. 🌐</li>
    <li><strong>Rating Trends:</strong> Popular ratings reveal insights into audience preferences and age groups. 📈</li>
    <li><strong>Regional Contributions:</strong> Analysis highlights which countries are major contributors to Netflix's catalog. 🇮🇳</li>
    <li><strong>Content Evolution:</strong> Yearly trends show how Netflix has adapted its content strategy. 🔄</li>
    <li><strong>Unique Insights:</strong> Exploration of niche categories like documentaries and long-duration films enriches the analysis. 🎥</li>
</ul>

<h2>Conclusion</h2>
<p>This project showcases how SQL can unlock valuable insights from a large dataset like Netflix's. By analyzing the platform's diverse offerings, it provides a deeper understanding of content trends, audience preferences, and regional influences. The findings highlight Netflix's global strategy and continuous evolution. 📚</p>

<h2>Tools and Technologies</h2>
<ul>
    <li><strong>SQL:</strong> The primary language for data querying and analysis. 🛠️</li>
    <li><strong>PostgreSQL:</strong> Database management system used for storing and querying data. 💾</li>
    <li><strong>Microsoft Excel:</strong> Utilized for initial data exploration and cleaning. 📊</li>
</ul>

<h2>How to Use</h2>
<ol>
    <li>Clone this repository. 📥</li>
    <li>Import the dataset into your PostgreSQL database. 🗃️</li>
    <li>Run the provided SQL queries to gain insights. 🚀</li>
    <li>Modify queries to explore additional aspects of the data. 🔍</li>
</ol>

<h2>Acknowledgements</h2>
<p>Special thanks to Kaggle for providing the dataset and the SQL community for their invaluable resources. 🙏</p>
<p>Project developed by <a href="https://github.com/asifk48">Asif Khan</a>. 🤝</p>
