
<div class="rendered-markdown"><h1>Used Car Price Analysis</h1>
<h2>Problem Statement</h2>
<p>A used car dealership needs to understand what factors make a car more or less expensive to provide clear recommendations on what consumers value in a used car. The goal is to analyze a dataset of 426,880 used cars and build a predictive model to identify the key drivers of used car pricing.</p>
<p><strong>Business Question</strong>: What factors drive the price of a used car, and how can a dealership optimize their inventory and pricing strategy?</p>
<h2>Summary of Findings</h2>
<h3>Model Performance</h3>
<ul>
<li><strong>Best Model</strong>: Ridge Regression</li>
<li><strong>Accuracy</strong>: 72.3% (R² Score) - explains 72% of price variance</li>
<li><strong>Average Prediction Error</strong>: $2,255</li>
<li><strong>Median Error</strong>: $598</li>
</ul>
<h3>Top 5 Price Drivers</h3>
<ol>
<li><strong>Vehicle Model</strong> (45.5% importance) - Specific make/model combination is the strongest predictor</li>
<li><strong>Vehicle Mileage</strong> (25.8% importance) - Higher mileage significantly reduces value</li>
<li><strong>Vehicle Age</strong> (7.8% importance) - Older vehicles depreciate consistently</li>
<li><strong>Model Year</strong> (5.8% importance) - Newer model years command premium</li>
<li><strong>Brand/Manufacturer</strong> (5.0% importance) - Brand reputation affects pricing</li>
</ol>
<h3>Key Business Insights</h3>
<ul>
<li><strong>Model matters most</strong>: Focus inventory on popular models (F-150, Camry, Silverado)</li>
<li><strong>Sweet spot</strong>: Vehicles 3-7 years old with &lt;75K miles offer best value</li>
<li><strong>Mileage impact</strong>: Every 10K miles reduces value by approximately $1,200</li>
<li><strong>Brand strategy</strong>: Maintain mix of 60% mainstream, 25% domestic, 15% luxury brands</li>
<li><strong>Vehicle types</strong>: SUVs and trucks command higher prices</li>
</ul>
<h3>Business Impact</h3>
<ul>
<li><strong>Potential Annual Value</strong>: $800K - $1.8M improvement opportunity</li>
<li><strong>ROI</strong>: 3x return on investment from better pricing strategies</li>
<li><strong>Implementation</strong>: Ready for deployment as decision support tool</li>
</ul>
<h3>Data Processing Results</h3>
<ul>
<li><strong>Original Dataset</strong>: 426,880 records</li>
<li><strong>Final Clean Dataset</strong>: 379,771 records (89% retention rate)</li>
<li><strong>Features</strong>: Engineered from 18 original to 9 key predictive features</li>
<li><strong>Missing Data</strong>: Successfully handled through imputation and strategic removal</li>
</ul>
<h2>Repository Contents</h2>
<ul>
<li><strong><a href="prompt_II.ipynb">prompt_II.ipynb</a></strong> - Complete analysis notebook with detailed methodology, visualizations, and results</li>
<li><strong>data.zip</strong> - Unzip the <a href="https://github.com/lakshmivelandai/What-drives-the-price-of-a-car/blob/main/data.zip" data </a> data file. </li> Ensure you have structure of data/vehicles.csv which is the Dataset of 426K used car records</li>
<li><strong>images/</strong> - Supporting visualizations and diagrams</li>
</ul>
<h2>Methodology</h2>
<p>This analysis follows the CRISP-DM framework:</p>
<ol>
<li><strong>Business Understanding</strong> - Define pricing optimization goals</li>
<li><strong>Data Understanding</strong> - Explore 426K vehicle records</li>
<li><strong>Data Preparation</strong> - Clean and engineer features</li>
<li><strong>Modeling</strong> - Train and compare multiple algorithms</li>
<li><strong>Evaluation</strong> - Assess performance and business value</li>
<li><strong>Deployment</strong> - Provide implementation recommendations</li>
</ol>
<hr />
<p><strong>For detailed analysis, methodology, and visualizations, see the <a href="prompt_II.ipynb">complete Jupyter notebook</a>.</strong></p>
</div>
