# Netflix Data Analysis using Python

![image](https://github.com/user-attachments/assets/ca6c0297-5688-4ae8-8898-84bafeb8c57b)


# Overview
This project focuses on analyzing Netflix data to gain insights into trends, patterns, and user behavior. The analysis is performed using Python and various data visualization libraries.

# Dataset
The dataset used in this project is sourced from Kaggle Netflix Movies and TV Shows. It contains information about various Netflix titles, including:

  Title
- Director
- Cast
- Country
- Release year
- Rating
- Duration
- Type (Movie/TV Show)
- Genre
  
# Installation
To run this project, you'll need to install the required dependencies. Use the following command to install them:

```
pip install -r requirements.txt
```

# Usage
1. Clone the repository:
```
git clone https://github.com/Neha-9008/Data-Science-projects.git
cd Data-Science-projects/Netflix%20Data%20Analysis
```

2. Open the Jupyter Notebook:
```
jupyter notebook Netflix_Data_Analysis_using_Python.ipynb
```

3. Run the cells in the notebook to perform the analysis.
Analysis
Loading Data
The dataset is loaded into a Pandas DataFrame for analysis.
```
import pandas as pd
df = pd.read_csv('data/netflix_titles.csv')
```

# Data Cleaning
Missing values are handled, and unnecessary columns are removed to clean the dataset.

# Exploratory Data Analysis
EDA is performed to understand the distribution and relationships within the data.

# Visualization
Data visualization is done using libraries such as Matplotlib and Seaborn to create insightful plots.

# Conclusion
The analysis reveals various insights into Netflix content, including trends in genres, release years, and more. These insights can help in understanding viewer preferences and guiding content strategy.

# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

# License
This project is licensed under the MIT License.
