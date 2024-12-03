<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>🎬 Fandango-Rating Mismatch Project</h1>
  <p><strong>Exposing the Truth Behind Movie Ratings</strong></p>

  <h2>📌 Project Overview</h2>
  <p>
    When it comes to deciding on a movie night out with friends and family, how much do you trust online reviews and ratings? This project explores this question, with a particular focus on the discrepancies between Fandango's ratings and those of other popular platforms like Rotten Tomatoes, IMDb, and Metacritic.
  </p>

  <h2>🔍 Key Findings</h2>
  <ul>
    <li>Fandango's ratings exhibited a consistent upward bias compared to other platforms.</li>
    <li>Movies rated highly on Fandango often scored lower on Rotten Tomatoes, IMDb, and Metacritic.</li>
    <li>Highlighted potential conflicts of interest, as Fandango is both a ticket seller and reviewer.</li>
  </ul>

  <h2>📂 Datasets</h2>
  <ul>
    <li><strong>fandango_scrape.csv:</strong> Contains movie ratings data scraped from Fandango.</li>
    <li><strong>all_sites_scores.csv:</strong> Contains aggregated ratings from multiple platforms, including Rotten Tomatoes, IMDb, and Metacritic.</li>
  </ul>

  <h2>📈 Visualizations</h2>
  <p>The analysis includes the following visualizations, which are implemented in <strong>Fandango-Rating Mismatch (1).ipynb</strong>:</p>
  <ul>
    <li><strong>Histplot:</strong> To visualize the distribution of ratings across platforms.</li>
    <li><strong>Scatterplot:</strong> To show relationships between Fandango ratings and other platforms.</li>
    <li><strong>Clustermap:</strong> To explore similarities and clustering among platforms based on their ratings.</li>
    <li><strong>KDE Plot:</strong> To examine the density of ratings for comparative analysis.</li>
  </ul>

  <h2>💻 How to Run the Project</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/SHUBHAMRAWAT-25/Fandango-Mismatch-Rating-Analysis.git
cd fandango-rating-mismatch
      </code></pre>
    </li>
    <li>Install the required libraries:
      <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Run the Jupyter Notebook:
      <pre><code>jupyter notebook "Fandango-Rating Mismatch (1).ipynb"</code></pre>
    </li>
    <li>Ensure the datasets (<strong>fandango_scrape.csv</strong> and <strong>all_sites_scores.csv</strong>) are in the same directory as the notebook.</li>
  </ol>

  <h2>🛠️ Tools Used</h2>
  <ul>
    <li><strong>Python Libraries:</strong> Pandas, Matplotlib, Seaborn, NumPy.</li>
    <li><strong>Jupyter Notebook:</strong> For analysis and visualization.</li>
  </ul>

  <h2>📜 License</h2>
  <p>
    This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
  </p>

  <h2>🤝 Contributors</h2>
  <p><strong>Shubham Rawat</strong></p>
  <p>Data Scientist in progress<br>Passionate about uncovering insights through data.</p>
</body>
</html>
