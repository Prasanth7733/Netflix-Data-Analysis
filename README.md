# **Netflix Data Exploratory Analysis**  

## **Overview**  
This project is an exploratory data analysis (EDA) of Netflix's extensive library of movies and TV shows, consisting of over 4,000 entries. The goal is to uncover meaningful patterns, trends, and insights related to content production, audience preferences, and genre popularity. By leveraging Python and data visualization tools, this project serves as a hands-on experience in data cleaning, feature engineering, and storytelling through data.  

---

## **Objectives**  
1. Perform data cleaning to handle missing values and inconsistencies.  
2. Analyze key attributes such as content type, release year, country of origin, and ratings.  
3. Engineer new features like:  
   - *Year Difference*: Time difference between release year and addition to Netflix.  
   - *Movie Category*: Classification of movies based on duration.  
   - *Age Suitability*: Categorization of content based on ratings.  
4. Visualize trends in genres, content types, and duration patterns.  
5. Provide actionable insights for stakeholders and content creators.  

---

## **Dataset**  

### **Source**  
The dataset used in this project is publicly available and contains the following attributes:  
- **Title**: Name of the movie or TV show.  
- **Content Type**: Indicates whether it is a movie or a TV show.  
- **Release Year**: The year the content was originally released.  
- **Country**: The country of origin for the content.  
- **Rating**: The content rating (e.g., PG, TV-MA).  
- **Duration**: The duration of the movie or number of seasons for TV shows.  
- **Listed Genres**: Genres the content is categorized under.  

The dataset was cleaned and preprocessed to handle missing and inconsistent data.  

---

## **Key Highlights**  

### **Insights Uncovered**  
- **Content Production by Country**:  
  - The United States leads in content production, with a significant contribution to Netflix’s library.  
  - India and Japan also have notable content representation.  

- **Genre Popularity**:  
  - *Stand-Up Comedy* emerged as the most popular genre in the U.S.  
  - *Documentaries* and *Dramas* are highly prevalent across global content.  

- **Content Type and Ratings**:  
  - Movies dominate Netflix’s library, accounting for 97.2% of the total content.  
  - Movies generally have more mature ratings (e.g., TV-MA, R) compared to TV shows, which cater to a broader audience.  

- **Duration Patterns**:  
  - The longest movie in the dataset exceeds 250 minutes.  
  - Older movies tend to have longer durations, whereas newer releases are often shorter and added to Netflix more quickly.  

- **Top Contributors**:  
  - **Directors**: Raul Campos and Alastair Fothergill are among the most featured directors.  
  - **Actors**: Anupam Kher, Shah Rukh Khan, and Naseeruddin Shah appear frequently in the content library.  

---

## **Feature Engineering**  
To derive deeper insights, the following features were engineered:  
1. **Year Difference**:  
   - Captures the gap between the release year and the year the content was added to Netflix.  
2. **Movie Categories**:  
   - Classified movies as short (< 60 mins), standard (60–120 mins), and long (> 120 mins).  
3. **Age Suitability**:  
   - Grouped ratings into categories such as *Kids*, *Teens*, and *Mature Audiences*.  

---

## **Visualizations**  
The project includes comprehensive visualizations to effectively communicate findings:  
- **Heatmaps**: To show correlations between attributes.  
- **Bar Charts**: For analyzing genre popularity, top actors, and content type distributions.  
- **Pie Charts**: To depict the proportion of movies versus TV shows.  
- **Scatter Plots**: To identify patterns in duration and year differences.  

---

## **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - **Pandas**: For data manipulation and cleaning.  
  - **NumPy**: For numerical computations.  
  - **Matplotlib** and **Seaborn**: For creating insightful visualizations.  
  - **Jupyter Notebook**: For an interactive coding environment.  

---

## **Steps to Run the Project**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/netflix-data-analysis.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd netflix-data-analysis  
   ```  
3. Install required Python libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  
4. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook netflix_analysis.ipynb  
   ```  
5. Run all cells in the notebook to replicate the analysis and visualizations.  

---

## **Key Learnings**  
- The project provided hands-on experience in:  
  - Handling real-world data with missing and inconsistent values.  
  - Engineering new features to derive deeper insights.  
  - Creating impactful visualizations to communicate findings effectively.  
- It reinforced the importance of storytelling with data, helping to uncover trends in the entertainment industry.  

---

## **Conclusion**  
This Netflix EDA project was a valuable exercise in understanding content trends and audience preferences. By analyzing real-world data, it provided meaningful insights that could benefit content creators and strategists in the entertainment industry. The findings also highlight the power of data science in uncovering hidden patterns and driving informed decision-making.  

---

## **Acknowledgments**  
Special thanks to my mentor, **Dixson Joy**, for his guidance and encouragement throughout this project.  
  
---

## **Connect With Me**  
Feel free to reach out with feedback, suggestions, or collaboration opportunities! 😊  
- **LinkedIn**: https://www.linkedin.com/in/prasanth-babu-493355278/  
  
Explore the project, and let’s connect to discuss more exciting data science projects! 🚀
