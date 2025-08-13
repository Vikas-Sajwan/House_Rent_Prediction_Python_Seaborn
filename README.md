## 🏠 House Rent Dataset Analysis

This repository contains a comprehensive exploratory data analysis (EDA) of a house rent dataset. The project's goal is to uncover key insights and trends within the Indian rental market using a variety of data cleaning, manipulation, and visualization techniques.

***

### 📊 Dataset

The analysis is based on the **`House_Rent_Dataset.csv`** file, which contains rental listings from several major Indian cities. The dataset includes detailed information on properties, such as:

* `Posted On`: The date the listing was posted.
* `BHK`: Number of bedrooms.
* `Rent`: The monthly rent in Indian Rupees.
* `Size`: The area of the property in square feet.
* `City`: The city where the property is located.
* `Furnishing Status`: Whether the property is furnished, semi-furnished, or unfurnished.
* `Tenant Preferred`: The preferred tenant type (e.g., Bachelors, Family).

***

### 🚀 Methodology

This project follows a standard data analysis pipeline:

1.  **Data Cleaning and Preprocessing**: The raw dataset was loaded and cleaned to ensure data quality. This involved:
    * Handling missing values and removing duplicate entries.
    * Converting the `Posted On` column to a proper datetime format.
    * Extracting a numerical floor number from the `Floor` column.
    * The cleaned data is saved as **`Cleaned_Dataset.csv`**.

2.  **Exploratory Data Analysis (EDA)**: A series of 20 professional-level questions were posed and answered to explore the relationships between different variables.

3.  **Visualization**: All insights are visualized using **`seaborn`** and **`matplotlib`** with a custom, professional color palette to effectively communicate findings.

***

### 📈 Key Findings

The analysis notebook reveals several interesting insights into the rental market:

* **Rent Distribution**: There is a wide distribution of rent prices across cities, with significant variation in average rent per square foot.
* **Correlation**: A strong positive correlation exists between a property's **`Rent`** and its **`Size`**, a fundamental relationship in real estate.
* **BHK and Bathrooms**: A clear relationship was found between the number of bedrooms (`BHK`), bathrooms, and the average rent.
* **Market Trends**: The analysis also provides insights into the most common tenant preferences and the distribution of property types across different cities.

***

### 💻 Technologies Used

* **`pandas`**: For data manipulation and analysis.
* **`numpy`**: For numerical operations.
* **`seaborn`**: For creating aesthetically pleasing statistical visualizations.
* **`matplotlib`**: For basic plotting and plot customization.

***

### 📝 How to Use

To replicate this analysis, simply:

1.  Clone this repository to your local machine.
2.  Ensure you have a Python environment with the required libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`) installed.
3.  Open the **`Analysis_Notebook.ipynb`** file in Jupyter Notebook or JupyterLab.
4.  Run the cells sequentially to see the data cleaning, analysis, and visualizations in action.
