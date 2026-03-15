<h1><sub><img src="https://github.com/RadhikaDeshpande1010/icon-library/blob/main/python-icon/python-icon.png" height="30" width="30"></sub> PySpark Movie Data Analytics </h1>

<img src="https://github.com/RadhikaDeshpande1010/PySpark-Movie-Data-Analytics/blob/main/PySpark%20RDD%20Movie%20Data%20Analytics.png">

## 📌 Project Overview
A practical PySpark project analyzing a movie dataset using RDD transformations and actions — covering map(), filter(), key-value pairs, and chained operations.

The notebook covers:
- Loading & parsing pipe-delimited data into RDDs
- 20 real-world operations using map() and filter()
- Extracting fields, type casting, string operations
- Key-value RDD pairs, range filters, and multi-condition queries

<h2>🗃️ Dataset</h2>

<p>
The dataset contains <b>20 movies</b> with the following fields:
</p>

<table>
  <tr>
    <th>Column Name</th>
    <th>Description</th>
  </tr>
  
  <tr>
    <td><code>movie_id</code></td>
    <td>Unique identifier for each movie</td>
  </tr>
  
  <tr>
    <td><code>movie_name</code></td>
    <td>Name of the movie</td>
  </tr>
  
  <tr>
    <td><code>genre</code></td>
    <td>Movie genre (Action, Drama, Comedy, etc.)</td>
  </tr>
  
  <tr>
    <td><code>release_year</code></td>
    <td>Year the movie was released</td>
  </tr>
  
  <tr>
    <td><code>duration_minutes</code></td>
    <td>Total runtime of the movie in minutes</td>
  </tr>
  
  <tr>
    <td><code>rating</code></td>
    <td>Movie rating score</td>
  </tr>
  
  <tr>
    <td><code>country</code></td>
    <td>Country where the movie was produced</td>
  </tr>
</table>

<h2>⚙️ Tech Stack</h2>

<table>
  <thead>
    <tr>
      <th align="left">Tool</th>
      <th align="left">Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>PySpark</td>
      <td>Distributed data processing</td>
    </tr>
    <tr>
      <td>RDD API</td>
      <td>Low-level Spark transformations</td>
    </tr>
    <tr>
      <td>Google Colab</td>
      <td>Execution environment</td>
    </tr>
  </tbody>
</table>

<h2>📁 Project Structure</h2>

<div style="background-color:#1e1e1e; padding:15px; border-radius:8px; font-family:monospace; color:#d4d4d4;">
<pre>
├── notebook/
│   └── pyspark_rdd_movie_data_analytics.ipynb
├── data/
│   └── movie_data.txt
└── README.md
</pre>
</div>

<h2>▶️ Run It</h2>

<pre><code class="language-bash">
pip install pyspark
</code></pre>

<p>
Or open directly in <b>Google Colab</b> — upload the notebook and 
<code>movie_data.txt</code> to <code>/content/sample_data/</code>.
</p>

<hr>

<p style="text-align:center; font-style:italic;">
Built by <b>Radhika Deshpande</b> · Exploring Big Data Engineering with PySpark
</p>
