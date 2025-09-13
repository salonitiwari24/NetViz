# 📺 Netflix Dataset Visualization

## 📂 Dataset
- Source: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows) from Kaggle  
- Format: CSV (~8,800 rows, 12 columns)  

The dataset includes metadata about Netflix Movies and TV Shows such as:
- Type (Movie/TV Show)
- Title
- Director, Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)

---

## 📊 Visualizations
We used **Seaborn and Matplotlib** to explore the dataset.  

## 📌 Plots
### Count of Movies vs TV Shows
![Movies vs TV Shows]("Screenshots\Count_of_Movies_vs_TV_Shows.png")

### Distribution of Release Years
![Distribution of Release Years]("Screenshots\Distribution_of_Release_Years.png")

### Ratings Distribution
![Ratings Distribution]("Screenshots\Ratings_Distribution.png")

### Top 10 Countries by Content
![Countries by Content]("Screenshots\Top_10_Countries_by_Content.png")

### Release Year vs Type
![Release Year vs Type]("Screenshots\Release_Year_vs_Type.png")

### Violin Plot: Release Year by Type
![Release Year by Type]("Screenshots\Violin_Plot_Release_Year_by_Type.png")

### Scatter Plot: Release Year vs Duration (Movies only, numeric duration)
![Release Year vs Duration]("Screenshots\Scatter_Plot_Release_Year_vs_Duration.png)

### Bar Plot: Average Duration by Rating (Movies only)
![Average Duration by Rating]("Screenshots\Bar_Plot_Average_Duration_by_Rating.png")

### Heatmap: Correlation (only numerical fields)
![Correlation]("Screenshots\Heatmap_Correlation.png)

### Pair Plot: Release Year & Duration
![Release Year & Duration]("Screenshots\Pair_Plot_Release_Year_&_Duration.png")

### Pie Chart: Distribution of Content Type
![Distribution of Content Type]("Screenshots\Pie_Chart_Distribution_of_Content_Type.png")
 
---

## 📝 Insights
- Netflix library is dominated by **Movies (~70%)**.  
- The most frequent ratings are **TV-MA** and **TV-14**, showing that content targets teens and adults.  
- Content production surged **after 2015**.  
- **US and India** are the top-producing countries.  
- Most movies last **80–120 minutes**.  

---

## ⚙️ Tech Stack
- Python 3  
- Jupyter Notebook  
- Pandas, Numpy  
- Seaborn, Matplotlib  

---

## 📌 Files in this Repository
- `Plots.ipynb` → Jupyter Notebook with code + analysis  
- `netflix_titles.csv` → Dataset file  
- `README.md` → Project description, screenshots, insights  
