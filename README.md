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
  This project implements a complete end-to-end data analytics pipeline on U.S. daily 
  weather data, addressing two research questions:
</p>
</p>
  As apart of Phase 3, instead of including multiple markdown cells inside our jupyter notebook, we wanted to explain and show our results, findings, etc. in a more structured format.     We created a written document that includes a proper overview of our project, complete with explanations, results, tables, graphs, etc.
  The report will be included as apart of our project submission, titled "COMP 333 Project Summary".
</p>
<h3>Supervised Learning</h3>
<p>Can we predict whether it will rain tomorrow?</p>
<h3>Unsupervised Learning</h3>
<p>Can we identify weather patterns that lead to distinct meteorological events?</p>
<p>
  The dataset contains daily meteorological measurements (TMAX, TMIN, PRCP, and station 
  geographic data) collected from weather stations across the United States between 
  1992 and 2021.
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
  The original dataset (~8.37 GB) was filtered during preprocessing. Stations with less 
  than 98% non-null values across TMAX, TMIN, and PRCP were removed, producing a 
  filtered dataset (~2.90 GB) used throughout this project.
</p>
<hr/>

<h2>Dataset Access</h2>
<p>
  The dataset is retrieved programmatically via the Kaggle API. To enable this, add your 
  Kaggle API token to the notebook where indicated:
</p>
<pre><code>os.environ['KAGGLE_API_TOKEN'] = 'your_token_here'</code></pre>
<hr/>

<h2>Dependencies</h2>
<p>Install the required packages using:</p>
<pre><code>pip install polars pandas numpy scikit-learn matplotlib seaborn xgboost kaggle
</code></pre>
<p>or</p>
<pre><code>pip install -r requirements.txt
</code></pre>
<hr/>

<h2>Reproduction Instructions</h2>
<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/malakw04/comp333-project.git
cd comp333-project
</code></pre>

<h3>2. Download the Dataset</h3>
<p>
  Add your Kaggle API token to the notebook and let the pipeline download the 
  dataset automatically.
</p>

<h3>3. Run the Notebook</h3>
<p>Open and run all cells in:</p>
<pre><code>phase_3_final.ipynb</code></pre>
<p>
  Cells must be run in order as later cells depend on variables defined earlier in the pipeline.
</p>
