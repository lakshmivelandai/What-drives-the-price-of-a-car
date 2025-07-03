<style type="text/css">.rendered-markdown{font-size:14px} .rendered-markdown>*:first-child{margin-top:0!important} .rendered-markdown>*:last-child{margin-bottom:0!important} .rendered-markdown a{text-decoration:underline;color:#b75246} .rendered-markdown a:hover{color:#f36050} .rendered-markdown h1, .rendered-markdown h2, .rendered-markdown h3, .rendered-markdown h4, .rendered-markdown h5, .rendered-markdown h6{margin:24px 0 10px;padding:0;font-weight:bold;-webkit-font-smoothing:antialiased;cursor:text;position:relative} .rendered-markdown h1 tt, .rendered-markdown h1 code, .rendered-markdown h2 tt, .rendered-markdown h2 code, .rendered-markdown h3 tt, .rendered-markdown h3 code, .rendered-markdown h4 tt, .rendered-markdown h4 code, .rendered-markdown h5 tt, .rendered-markdown h5 code, .rendered-markdown h6 tt, .rendered-markdown h6 code{font-size:inherit} .rendered-markdown h1{font-size:28px;color:#000} .rendered-markdown h2{font-size:22px;border-bottom:1px solid #ccc;color:#000} .rendered-markdown h3{font-size:18px} .rendered-markdown h4{font-size:16px} .rendered-markdown h5{font-size:14px} .rendered-markdown h6{color:#777;font-size:14px} .rendered-markdown p, .rendered-markdown blockquote, .rendered-markdown ul, .rendered-markdown ol, .rendered-markdown dl, .rendered-markdown table, .rendered-markdown pre{margin:15px 0} .rendered-markdown hr{border:0 none;color:#ccc;height:4px;padding:0} .rendered-markdown>h2:first-child, .rendered-markdown>h1:first-child, .rendered-markdown>h1:first-child+h2, .rendered-markdown>h3:first-child, .rendered-markdown>h4:first-child, .rendered-markdown>h5:first-child, .rendered-markdown>h6:first-child{margin-top:0;padding-top:0} .rendered-markdown a:first-child h1, .rendered-markdown a:first-child h2, .rendered-markdown a:first-child h3, .rendered-markdown a:first-child h4, .rendered-markdown a:first-child h5, .rendered-markdown a:first-child h6{margin-top:0;padding-top:0} .rendered-markdown h1+p, .rendered-markdown h2+p, .rendered-markdown h3+p, .rendered-markdown h4+p, .rendered-markdown h5+p, .rendered-markdown h6+p{margin-top:0} .rendered-markdown ul, .rendered-markdown ol{padding-left:30px} .rendered-markdown ul li>:first-child, .rendered-markdown ul li ul:first-of-type, .rendered-markdown ol li>:first-child, .rendered-markdown ol li ul:first-of-type{margin-top:0} .rendered-markdown ul ul, .rendered-markdown ul ol, .rendered-markdown ol ol, .rendered-markdown ol ul{margin-bottom:0} .rendered-markdown dl{padding:0} .rendered-markdown dl dt{font-size:14px;font-weight:bold;font-style:italic;padding:0;margin:15px 0 5px} .rendered-markdown dl dt:first-child{padding:0} .rendered-markdown dl dt>:first-child{margin-top:0} .rendered-markdown dl dt>:last-child{margin-bottom:0} .rendered-markdown dl dd{margin:0 0 15px;padding:0 15px} .rendered-markdown dl dd>:first-child{margin-top:0} .rendered-markdown dl dd>:last-child{margin-bottom:0} .rendered-markdown blockquote{border-left:4px solid #DDD;padding:0 15px;color:#777} .rendered-markdown blockquote>:first-child{margin-top:0} .rendered-markdown blockquote>:last-child{margin-bottom:0} .rendered-markdown table th{font-weight:bold} .rendered-markdown table th, .rendered-markdown table td{border:1px solid #ccc;padding:6px 13px} .rendered-markdown table tr{border-top:1px solid #ccc;background-color:#fff} .rendered-markdown table tr:nth-child(2n){background-color:#f8f8f8} .rendered-markdown img{max-width:100%;-moz-box-sizing:border-box;box-sizing:border-box} .rendered-markdown code, .rendered-markdown tt{margin:0 2px;padding:0 5px;border:1px solid #eaeaea;background-color:#f8f8f8;border-radius:3px} .rendered-markdown code{white-space:nowrap} .rendered-markdown pre>code{margin:0;padding:0;white-space:pre;border:0;background:transparent} .rendered-markdown .highlight pre, .rendered-markdown pre{background-color:#f8f8f8;border:1px solid #ccc;font-size:13px;line-height:19px;overflow:auto;padding:6px 10px;border-radius:3px} .rendered-markdown pre code, .rendered-markdown pre tt{margin:0;padding:0;background-color:transparent;border:0}</style>
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
<li><strong>data/vehicles.csv</strong> - Dataset of 426K used car records</li>
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