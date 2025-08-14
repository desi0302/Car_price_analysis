
# Car price analysis

**Car price analysis** is a tool that examines how various factors influence vehicle pricing.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The dataset consists of 26 columns and 205 rows, providing detailed information about cars, including technical specifications, performance metrics, and pricing. This dataset allows for in-depth analysis of how brand, design, and mechanical features influence car prices.


## Business Requirements
* The primary business objective is to analyze and understand the factors that influence car prices in order to support data-driven decision-making in pricing, marketing, and product positioning.


## Hypothesis and how to validate?
* Market price distribution: Most cars may fall within a mid-range price, with fewer budget and luxury options. Validate with a histogram or density plot to assess distribution and skewness.
* Brand price positioning: Some brands may consistently command higher prices, reflecting premium strategies. Validate with grouped bar charts and boxplots comparing average prices by brand.
* Performance specs vs price: Features like horsepower, engine size, curb weight, and car width may drive higher prices, while fuel efficiency may lower them. Validate with correlation heatmaps and bar charts of feature-price relationships.
* Segment clustering: Premium cars may be heavier, more powerful, and less fuel-efficient, while economy cars are lighter and more efficient. Validate with bubble/multivariate scatter plots (curb weight, horsepower, highway MPG vs price).
* Price hierarchy: Price structures may follow a hierarchy across brand, model, and fuel type, with certain combinations targeting premium or economy markets. Validate with a sunburst plot visualizing pricing hierarchies and category averages.

## Project Plan
* Data is collected, cleaned, and organized for analysis.
* Key features are engineered and visualized to test business hypotheses.
* Data and analysis are managed in folders and Jupyter notebooks.
* Visual methods are used to reveal patterns and support decisions.

## The rationale to map the business requirements to the Data Visualisations
* Understand price distribution:
Rationale: A histogram/density plot reveals how car prices are spread across the market, helping identify common price ranges and outliers for inventory and marketing strategies.

* Identify premium brands and models:
Rationale: Grouped bar charts and boxplots compare average prices by brand/model, supporting decisions on product positioning and premium segment targeting.

* Analyze impact of technical features on price:
Rationale: Correlation heatmaps and bar charts show which specifications (e.g., horsepower, engine size, fuel efficiency) most influence price, guiding feature prioritization and pricing strategies.

* Segment the market by vehicle characteristics:
Rationale: Bubble/multivariate scatter plots visualize clusters of premium vs economy vehicles, informing segmentation and targeted marketing.

* Reveal hierarchical price structures:
Rationale: Sunburst plots illustrate how brand, model, and fuel type interact to form pricing hierarchies, supporting strategic product placement and market analysis.

## Analysis techniques used
* Data analysis methods: Descriptive statistics, correlation analysis, and a variety of visualizations including histograms, bar charts, scatter plots, and sunburst plot.
* Structure of techniques: The analysis progressed from general distribution insights (descriptive statistics, histograms) to exploring specific feature relationships (correlation analysis, scatter plots, sunburst plots), ensuring each step supported the business hypotheses and built on previous findings.
* Data limitations: None identified.
* Use of generative AI tools: Completing my first full-cycle data analytics project — from defining hypotheses through ETL, analysis, and visualization — in just 2 days was extremely challenging. The tight deadline required focusing on essentials and delivering a minimum viable product, which is why AI support proved highly valuable — primarily to refine hypotheses, guide analysis steps, and optimize code within the limited timeframe. 

## Visualisation Screenshots
Screenshot files are placed in the jupyter_notebooks folder to provide static visual references for some key plots. They were added because interactive visualizations created in Jupyter notebooks did not display correctly on GitHub.
Screenshots added:
- scr_bubble.png
- scr_fuel.png
- scr_sun1.png
- scr_sun2.png
- scr_sun3.png
- scr_sun4.png

## Unfixed Bugs
* No unresolved bugs; all issues that arose during the project were addressed and resolved.
* I first addressed gaps in project management and statistical knowledge, as these were key to progressing effectively. Even though I covered the necessary coding concepts and KPIs, I still do not feel fully confident in applying all the material I have learned. Even when I had a good idea, it took me time to develop a clear plan for how to present it. I found it useful to first explore the dataset, identify key findings, and then build hypotheses that I was able to prove — which is indeed a valid and practical approach in exploratory data analysis. Working on a real project and tackling actual issues has helped fill many of these gaps, which I found to be extremely valuable for my development.

## Development Roadmap
* One major challenge was managing the full cycle of my first data analytics project under tight time pressure. I also encountered gaps in statistical knowledge, coding confidence, and planning how to present insights effectively. To address these, I used AI tools to refine hypotheses, guide analysis steps, and optimize code. I supplemented this with resources from websites, YouTube channels, KPIs, and personal notes from classes to quickly fill knowledge gaps. An exploratory approach proved effective — beginning with dataset examination, identifying key findings, and then developing hypotheses to test.
* Some planned steps, such as encoding categorical variables and additional visualizations, were included in the preliminary blueprint of my project but were not performed due to time constraints. These can be considered for future work.
* Based on this project, I plan to strengthen my statistical analysis skills, improve Python coding efficiency, and develop more structured data storytelling techniques. I also intend to deepen my knowledge of visualization tools.


## Main Data Analysis Libraries
* Pandas – Used for data loading, cleaning, and manipulation.
Example: Reading the dataset into a DataFrame, handling missing values, and creating new calculated columns for analysis.
* NumPy – Used for numerical operations and statistical calculations.
Example: Performing array-based computations to support correlation and descriptive statistics.
* Matplotlib – Used for creating static visualizations.
Example: Plotting histograms to visualize the distribution of car prices.
* Seaborn – Used for creating aesthetically enhanced visualizations and statistical plots.
Example: Drawing correlation heatmaps to examine relationships between numerical features and price.
* Plotly – Used for interactive visualizations.
Example: Creating sunburst plots to visualize price hierarchy by brand, model, and fuel type.


## Credits 
* KPIs

* https://realpython.com/python-statistics/

* https://www.data-to-viz.com/#pca

* https://www.w3resource.com/python-exercises/pandas/pandas-detect-outliers-in-a-dataframe-using-the-iqr-method.php?utm_source=chatgpt.com

* https://www.geeksforgeeks.org/python/how-to-standardize-data-in-a-pandas-dataframe/

* AI

## Acknowledgements 
* Many thanks to Vasi, Mark, Roman, and Neil for all of their help and advice.