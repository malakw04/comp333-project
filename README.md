<h1>COMP 333 Project</h1>
<h2>Weather Rainfall Prediction</h2>

<hr/>

<h2>Team Information</h2>
<ul>
  <li><strong>Sean Goren</strong> — 40279199</li>
  <li><strong>Malak Abdelkafy</strong> — 40235257</li>
</ul>

<p>
  <strong>Course:</strong> COMP 333<br/>
  <strong>Instructor:</strong> Alexis Yanez<br/>
  <strong>Semester:</strong> Winter 2026
</p>

<hr/>

<h2>Project Overview</h2>
<p>
  This project analyzes U.S. weather data to address two primary tasks:
</p>

<h3>Supervised Learning</h3>
<p>Predict whether it will rain tomorrow.</p>

<h3>Unsupervised Learning</h3>
<p>Identify whether natural weather patterns form distinct clusters.</p>

<p>
  The dataset contains daily meteorological measurements collected from multiple weather stations across the United States.
</p>

<hr/>

<h2>Data Source</h2>
<p>
  <strong>Dataset:</strong> Weather Dataset (US)<br/>
  <strong>Author:</strong> Nachiket Kamod<br/>
  <strong>Kaggle Link:</strong>
  <a href="https://www.kaggle.com/datasets/nachiketkamod/weather-dataset-us">
    https://www.kaggle.com/datasets/nachiketkamod/weather-dataset-us
  </a>
</p>

<p>
  The original dataset (~8GB) was filtered during preprocessing to produce a reduced dataset (~2GB) used in this project.
</p>

<hr/>

<h2>Dataset Access</h2>
<p>
  Due to file size limitations, the filtered dataset (~2GB) is not included in this repository.
</p>

<p>
  <strong>Google Drive Link:</strong><br/>
  <em>https://drive.google.com/drive/folders/1AJH0xqVICqzKMqdQ5UzxKQAof5QCxodn?usp=sharing</em>
</p>

<p>
  After downloading, place the dataset file inside the same folder as the jupyter notebook.
</p>


<hr/>

<h2>Dependencies</h2>
<p>Install the required packages using:</p>

<pre><code>pip install polars pandas numpy scikit-learn matplotlib seaborn xgboost
</code></pre>

<p>or</p>

<pre><code>pip install -r requirements.txt
</code></pre>

<hr/>

<h2>Reproduction Instructions</h2>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/&lt;comp333-project&gt;.git
cd comp333-project
</code></pre>

<h3>2. Download and Place the Dataset</h3>
<p>
  Download the filtered dataset from the Google Drive link above and place it inside the <code>/data</code> directory.
</p>

<h3>3. Run the Notebook</h3>
<p>Open and run:</p>

<pre><code>Phase1_and_Phase2.ipynb
</code></pre>



