# MovieLens
This project includes both data exploration and preparation steps, primarily using Python libraries like `pandas`, `numpy`, `matplotlib.pyplot`, and `wordcloud`.
Key Highlights:
1. **Dataset Loading**:
   - The main MovieLens dataset (`movielens.csv`) is loaded into a DataFrame, and its dimensions are inspected using `data.shape`. 
   - Initial exploration is conducted with `data.head()` and `data.info()` to review the structure and content.

2. **Movies Analysis**:
   - Unique movie IDs are extracted, and their total count is calculated using `len(movies)`.
   - This helps understand the scale and uniqueness of the dataset.

3. **Ratings Data**:
   - A second dataset, `rating.csv`, is loaded to analyze user ratings.
   - The dataset's size, summary statistics, and rating range (minimum and maximum) are examined to provide an overview of the distribution.

4. **Visualization and Insights**:
   - The presence of libraries like `matplotlib` and `wordcloud` suggests that visualizations, such as histograms for rating distributions and word clouds for text-based features like genres or titles, are part of the analysis.

5. **Project Scope**:
   - This notebook is likely part of a larger capstone project, aiming to uncover insights from the MovieLens data through descriptive statistics, visualizations, and possibly preparation for advanced analysis or recommendation systems.
 
