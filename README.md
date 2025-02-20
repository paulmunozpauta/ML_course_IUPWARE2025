<h1>Machine Learning Hydrological Forecasting</h1>

<p>This repository provides hands-on Jupyter Notebooks for building machine learning models for hydrological forecasting. The project is designed to run seamlessly on <strong>Google Colab</strong>, with setup instructions provided inside the notebooks.</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
ml-hydrological-forecasting/
├── notebooks/              # Jupyter notebooks
│   ├── example_notebook.ipynb
├── pyproject.toml          # Poetry dependency file
├── poetry.lock             # Poetry lock file (auto-generated)
├── README.md               # Project documentation
</pre>

<hr>

<h2>🚀 Running the Project</h2>

<p>This project is designed to be run on <strong>Google Colab</strong>. Follow the instructions provided in the notebooks to set up and install dependencies automatically.</p>

<hr>

<h2>📊 Jupyter Notebooks Available</h2>
<p>The repository includes the following Jupyter Notebooks:</p>
<ul>
  <li><code>1_Satellite_precipitation.ipynb</code>: Working with satellite precipitation data, including preprocessing and visualization.</li>
  <li><code>2_ML_modelling.ipynb</code>: Advanced Machine Learning for hydrological modelling/forecasting, including model training and evaluation.</li>
</ul>

<hr>

<h2>⚙️ Project Dependencies</h2>
<p>The environment is managed using Poetry, ensuring consistency and ease of dependency management. The main dependencies used in this project are:</p>

<ul>
  <li><code>scikit-learn ^1.3.0</code>: Machine learning algorithms</li>
  <li><code>numpy ^1.25.0</code>: Numerical computations</li>
  <li><code>pandas ^2.0.3</code>: Data manipulation</li>
  <li><code>matplotlib ^3.8.0</code>: Data visualization</li>
  <li><code>jupyter ^1.0.0</code>: Interactive notebooks</li>
  <li><code>seaborn ^0.12.2</code>: Statistical data visualization</li>
  <li><code>openpyxl ^3.1.2</code>: Excel file handling</li>
  <li><code>descartes ^1.1.0</code>: Geometric data visualization</li>
  <li><code>shapely ^2.0.1</code>: Geometric objects and operations</li>
  <li><code>geopandas ^0.14.1</code>: Geospatial data manipulation</li>
  <li><code>rasterio ^1.3.9</code>: Raster data handling</li>
  <li><code>rioxarray ^0.15.0</code>: Raster data manipulation with xarray</li>
  <li><code>xarray ^2023.6.0</code>: Multidimensional arrays</li>
  <li><code>h5py ^3.10.0</code>: HDF5 file handling</li>
</ul>

<p>All dependencies are listed in the <code>pyproject.toml</code> file.</p>

<hr>

<h2>📜 License</h2>
<p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>
