# Product-Range-Analysis
Final project of TripleTen DA Course

1  Project Decomposition
Main goal:

We aim to analyze the product range in the e-commerce store, examining the diversity of available products, their pricing, popularity, categories, market trends, customer behavior, and product relationships. Our objective is to make data-driven decisions regarding the store's product assortment, pricing strategy, and further business developments.

1.1  Decomposition Plan:
Setting the appropriate environment

Importing libraries (pandas, numpy, seaborn, matplotlib, timedelta, scipy, math)

Data download

The file ecommerce_dataset_us.csv contains the following columns:

InvoiceNo — order identifier

StockCode — item identifier

Description — item name

Quantity

InvoiceDate — order date

UnitPrice — price per item

CustomerID

The dataset contains the transaction history of an online store that sells household goods.

**Data Preprocessing:**

- Convert the data to the appropriate types, such as datetime, to ensure accurate analysis.
- Check for missing values, carefully study them, and make decisions on whether to eliminate or replace them.
- Check for duplicates, thoroughly examine them, and remove any redundant entries.
- Examine the presence of negative date values, if any, and determine their quantity and nature.
- Determine whether non-numerical data requires categorization and add necessary columns.

**EDA - Product Range Analysis:**

- Study and visualize the timeframe of the given data to understand the data distribution and patterns.
- Identify and handle any abnormal data values by either removing or replacing them.
- Analyse categories.
- Analyse product sale trends.
- Analyze customer behavior, such as frequent buyers or those with large order sizes.

**Statistical Data Analysis:**

- Formulate hypotheses (H0 and H1) based on the research questions and objectives.
- Prepare data samples and perform statistical tests to evaluate the hypotheses.
- Interpret the results and make conclusions based on the findings.

**Visualization:**

- Create a PowerPoint presentation to effectively communicate the findings and analysis.
- Recommendations to the E-commerce Store for Product Range Improvements.
- Provide actionable recommendations to the e-commerce store based on the analysis conducted.
- Suggest strategies for enhancing the product range, optimizing pricing, and driving future business developments.

___List of Sources:___

1. Official documentation of relevant libraries and tools, such as Pandas, NumPy, Matplotlib, Seaborn, etc.
2. Google search - insights from open-source data and studies related to analogous e-commerce stores.
3. Resources and examples available on the Practicum online learning platform.
4. Online forums like Stack Overflow and W3Schools to seek guidance and solutions from the data analysis community.
5. Jupyter notebook archive (my previous projects with similar tasks and problem solving techniques).
