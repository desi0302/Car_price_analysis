# Car price analysis

**Car price analysis** is a tool that examines how various factors influence vehicle pricing.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The dataset consists of 26 columns and 205 rows, providing detailed information about cars, including technical specifications, performance metrics, and pricing. This dataset allows for in-depth analysis of how brand, design, and mechanical features influence car prices.


## Business Requirements
* The primary business objective is to analyze and understand the factors that influence car prices in order to support data-driven decision-making in pricing, marketing, and product positioning.


## Hypothesis and how to validate?
* Market price distribution: Histogram/density plot to assess price concentration and skewness.
 - Hypothesis: The car market may have a concentration of models within a specific price range, with fewer budget and luxury options, which could impact market targeting and inventory planning. Use a histogram or density plot of car prices to visually assess the distribution shape and identify skewness.
* Brand price positioning: Grouped bar charts/boxplots to compare average prices across brands.
 - Certain brands may consistently position their vehicles at higher price points, reflecting premium market strategies and brand equity. Compare average prices across brands using grouped bar charts and boxplots to visually identify price differences.
* Performance specs vs price: Correlation heatmap/bar chart to explore relationships between features and price.
 - Performance-related specifications (horsepower, engine size, curb weight, car width) may drive higher pricing, while higher fuel efficiency could be associated with more budget-friendly segments. Use a correlation heatmap and bar chart of correlation coefficients to explore relationships between numerical features and price.
* Segment clustering: Bubble/multivariate scatter plots to visualize premium vs economy clusters.
 - Heavier, more powerful, and less fuel-efficient vehicles may dominate the premium segment, while lighter, fuel-efficient cars may compete in the economy segment. Create bubble/multivariate scatter plots with curb weight, horsepower (bubble size), and highway MPG (color) against price to observe clustering patterns.
* Price hierarchy: Sunburst plot to show hierarchical price structures by brand, model, and fuel type. 
 - Price structures may follow a hierarchy across brand, model, and fuel type, where certain combinations are strategically positioned to target premium or economy markets. Build a sunburst plot to visualize pricing hierarchies and compare category averages visually.

## Project Plan
Project Plan
* Data is collected, cleaned, and organized for analysis.
* Key features are engineered and visualized to test business hypotheses.
* Data is managed in structured folders and processed in Jupyter notebooks for reproducibility.
* Visual, exploratory methods are chosen for their clarity and effectiveness in revealing patterns and supporting business decisions.

## The rationale to map the business requirements to the Data Visualisations
* Understand price distribution:
Rationale: A histogram/density plot reveals how car prices are spread across the market, helping identify common price ranges and outliers for inventory and marketing strategies.

* Identify premium brands and models:
Rationale: Grouped bar charts and boxplots compare average prices by brand/model, supporting decisions on product positioning and premium segment targeting.

* Analyze impact of technical features on price:
Rationale: Correlation heatmaps and bar charts show which specifications (e.g., horsepower, engine size, fuel efficiency) most influence price, guiding feature prioritization and pricing strategies.

* Segment the market by vehicle characteristics:
Rationale: Bubble/multivariate scatter plots visualize clusters of premium vs economy vehicles, informing segmentation and targeted marketing.

*Reveal hierarchical price structures:
Rationale: Sunburst plots illustrate how brand, model, and fuel type interact to form pricing hierarchies, supporting strategic product placement and market analysis.

## Analysis techniques used
* Data analysis methods: Descriptive statistics, correlation analysis, and a variety of visualizations including histograms, bar charts, scatter plots, and sunburst plot.
* Structure of techniques: The analysis progressed from general distribution insights (descriptive statistics, histograms) to exploring specific feature relationships (correlation analysis, scatter plots, sunburst plots), ensuring each step supported the business hypotheses and built on previous findings.
* Data limitations: None identified.
* Use of generative AI tools: Completing my first full-cycle data analytics project — from defining hypotheses through ETL, analysis, and visualization — in just 2 days was extremely challenging. The tight deadline required focusing on essentials and delivering a minimum viable product, which is why AI support proved highly valuable — primarily to refine hypotheses, guide analysis steps, and optimize code within the limited timeframe.

## Ethical considerations
* No ethical considerations

## Unfixed Bugs
* No unresolved bugs; all issues that arose during the project were addressed and resolved.
* I first addressed gaps in project management and statistical knowledge, as these were key to progressing effectively. Even though I covered the necessary coding concepts and KPIs, I still do not feel fully confident in applying all the material I have learned. Even when I had a good idea, it took me time to develop a clear plan for how to present it. I found it useful to first explore the dataset, identify key findings, and then build hypotheses that I was able to prove — which is indeed a valid and practical approach in exploratory data analysis. Working on a real project and tackling actual issues has helped fill many of these gaps, which I found to be extremely valuable for my development.

## Development Roadmap
* One major challenge was managing the full cycle of my first data analytics project under tight time pressure. I also encountered gaps in statistical knowledge, coding confidence, and planning how to present insights effectively. To address these, I used AI tools to refine hypotheses, guide analysis steps, and optimize code. I supplemented this with resources from websites, YouTube channels, KPIs, and personal notes from classes to quickly fill knowledge gaps. An exploratory approach proved effective — beginning with dataset examination, identifying key findings, and then developing hypotheses to test.
* Based on this project, I plan to strengthen my statistical analysis skills, improve Python coding efficiency, and develop more structured data storytelling techniques. I also intend to deepen my knowledge of visualization tools to create more impactful and interactive dashboards. 


## Main Data Analysis Libraries
* Pandas – Used for data loading, cleaning, and manipulation.
Example: Reading the dataset into a DataFrame, handling missing values, and creating new calculated columns for analysis.
* NumPy – Used for numerical operations and statistical calculations.
Example: Performing array-based computations to support correlation and descriptive statistics.
* Matplotlib – Used for creating static visualizations.
Example: Plotting histograms to visualize the distribution of car prices.
*Seaborn – Used for creating aesthetically enhanced visualizations and statistical plots.
Example: Drawing correlation heatmaps to examine relationships between numerical features and price.
* Plotly – Used for interactive visualizations.
Example: Creating sunburst plots to visualize price hierarchy by brand, model, and fuel type.


## Credits 
* KPIs

* https://realpython.com/python-statistics/

* https://www.data-to-viz.com/#pca

* https://www.w3resource.com/python-exercises/pandas/pandas-detect-outliers-in-a-dataframe-using-the-iqr-method.php?utm_source=chatgpt.com

* https://www.geeksforgeeks.org/python/how-to-standardize-data-in-a-pandas-dataframe/

* ChatGPT & Copilot

## Acknowledgements 
* A big thank you to Vasi, Mark, Roman, and Neil for all the support and guidance along the way