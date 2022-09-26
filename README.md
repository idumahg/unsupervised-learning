# Project: Identify Customer Segments

In this project, I apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that I use has been provided by AZ Direct and Arvato Finance Solution, and represents a real-life data science task.

Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. In this notebook, I use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I also needed to assess and clean the data in order to convert the data into a usable form.

-------
## Data description
As a result of an agreement with the providers of the data. I cannot share the data in a public doamin. However, I provide a brief description of the data.

- Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Detailed information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

----------

## Task undertaken
The following effort was put into the project:

- Data Preprocessing - data cleaning, dealing with missing data, feature selection and re-encoding.
- Feature transformation - applying feature scaling, dimesionality reduction using PCA, interpreting principal components.
- Clustering - applying Kmeans to general population, inverse transform to compare customer data to demographics data.
- Interpretation - infering where the strongest customer base for the company is.

