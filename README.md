## Data Visualization Learning Hub 📊📈

### Description

Welcome to the Data Visualization Learning Hub! This repository is a comprehensive guide aimed at beginners who want to learn data visualization using Python. The repository contains five core modules that take you through the entire process, from understanding your data to crafting insightful visualizations. It's the perfect playground for those getting started in machine learning and data science.

### Libraries Used
- Pandas: For data manipulation and analysis
- Seaborn: For statistical data visualization
- Matplotlib: For plotting and visualization

### Data Setup 📁

The notebooks in this repository read data from CSV files. **These files must be downloaded first, and are available in the `data/` folder of this repository.**

Once downloaded, you have two options for making them accessible in Google Colab:

1. **Download and Use Your Drive**: After downloading the CSV files from the `data/` folder, upload them to your own Google Drive. You'll then need to change the file paths in the notebooks to match where you've stored the files. Example code in the notebooks using this approach:

    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    df_tips = pd.read_csv('/content/drive/My Drive/Your Folder Path Here/tips.csv')
    ```

2. **Download and Upload Directly to Colab**: Alternatively, after downloading the CSV files, you can upload them directly into your Google Colab environment using the file upload utility (`Files` tab -> `Upload`). Once uploaded, you'll need to adjust the file paths in the notebooks. Example code:

    ```python
    df_tips = pd.read_csv('tips.csv')
    ```

### What You'll Learn

#### A. Knowing Your Data
- How to load a dataset using Pandas
- Exploratory data analysis techniques to understand the shape and nature of your data

#### B. Filtering and Sorting
- How to filter and sort data based on various conditions
- Using Boolean indexing for filtering

#### C. Grouping
- Grouping data for aggregate analysis
- Utilizing Pandas' `groupby` function to summarize data

#### D. Apply
- Learn how to use the `apply` function for more complex data manipulation
- Using custom functions for data transformation

#### E. Visualization with Seaborn and Matplotlib
- Plotting basic graphs and charts to represent your data
- Crafting complex visualizations to extract insights

### How to Use

1. Clone this repository to your local machine.
2. Open the notebooks using Jupyter Notebook or any compatible IDE.
3. Start with the `a_knowing_your_data.ipynb` notebook and proceed in the order of the modules.

### Contact

If you have any questions or need further clarifications, feel free to contact me:

📧 Email: lital.h.ben.baruch@gmail.com  
🌐 LinkedIn: [https://www.linkedin.com/in/lital-ben-baruch](https://www.linkedin.com/in/lital-ben-baruch)

Happy Learning!
