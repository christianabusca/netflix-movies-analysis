# 🎬 Investigating Netflix Movies
A data analysis project exploring Netflix movie trends, durations, and patterns using Python, pandas, and matplotlib.

## 📋 Project Overview
This project started as a guided DataCamp exercise and has been expanded to enhance my Python data analysis skills. The analysis focuses on understanding movie duration trends, genre distributions, and content patterns in the Netflix catalog.

## 🎯 Objectives
- Analyze movie duration trends across different decades
- Explore genre distributions and patterns
- Investigate relationships between release years, countries, and movie characteristics
- Practice data manipulation, analysis, and visualization techniques

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **Jupyter Notebook** / Python scripts

## 📊 Dataset
The dataset (`netflix_data.csv`) contains information about Netflix content including:
- Show ID and type (Movie/TV Show)
- Title and director
- Cast and country of origin
- Release year and date added to Netflix
- Duration and genre
- Description

**Source:** This dataset originates from a DataCamp project exercise.

## 🔍 Analysis Performed

### Phase 1: Initial Exploration
- Filtered movie data from the 1990s (1990-1999)
- Created histogram visualizing movie duration distribution
- Analyzed short Action movies (< 90 minutes)

### Phase 2: Extended Analysis ✅ COMPLETED

#### Task 1: Genre Deep Dive ✅
- Analyzed genre distribution for 1990s Netflix movies
- Identified top 5 most popular genres
- Created horizontal bar chart visualization
- Calculated percentage representation of the #1 genre

#### Task 2: The Duration Detective ✅
- Compared movie lengths across 3 selected genres
- Calculated average, shortest, and longest duration for each genre
- Created box plot comparing duration distributions
- Analyzed genre consistency in movie lengths

#### Task 3: Time Traveler's Analysis ✅
- Grouped movies by decade (1990s, 2000s, 2010s)
- Calculated average movie duration per decade
- Created line plot showing duration trends over time
- Added overall average duration reference line
- Interpreted findings on movie length evolution

#### Task 4: The Country Comparison ✅
- Compared content patterns between two major producing countries
- Analyzed most common genres per country
- Calculated average durations and total movie counts
- Created side-by-side comparison visualizations
- Filtered for post-2010 content to identify recent trends

#### Final Boss Task: Netflix Report ✅
- Generated comprehensive multi-visualization dashboard
- Used subplots to display 3-4 key visualizations together
- Added proper titles and labels to all charts
- Compiled 3-5 key findings with text output
- Created clear, interpretable insights for general audiences

## 📁 Project Structure
```
netflix-movies-analysis/
│
├── netflix_data.csv          # Dataset
├── netflix.py               # Main analysis script
├── netflix.ipynb               # Jupyter notebooks (if applicable)
├── visualizations/           # Saved plots and charts
└── README.md                 # Project documentation
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib
```

### Running the Analysis
```python
python netflix.py
```

Or open the Jupyter notebook:
```bash
jupyter notebook
```

## 📈 Key Findings

### 1990s Movie Analysis
- Identified dominant genres in the 1990s Netflix catalog
- Action, Drama, and Comedy being dominant

### Duration Trends Across Decades
- Tracked how average movie lengths evolved from 1990s through 2010s
- Discovered patterns in movie length changes over time

### Genre Characteristics
- Different genres show distinct duration patterns
- Some genres maintain consistent lengths while others vary widely

### Country-Based Patterns
- United States and India are 2 countries that produced a lot of content
- United States having the higher average movie produced
- India having the higher average movie duration

## 🎓 Learning Goals
This project helps me develop skills in:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Statistical analysis and interpretation
- Data visualization best practices
- Python programming and pandas operations
- Drawing insights from real-world datasets
- Multi-faceted data storytelling

## 📝 Notes
This is a learning project where I'm continuously expanding my analysis based on new questions and curiosities about the data. Phase 2 represents a significant expansion including genre analysis, temporal trends, and cross-country comparisons with comprehensive visualizations.

## 🙏 Acknowledgments
- **DataCamp** for providing the initial project structure and dataset
- The data analysis community for inspiration and best practices

## 📫 Contact
Feel free to reach out if you have suggestions or questions about this analysis!

---
*Last Updated: December 2025*
*Phase 2 Completed: December 2025*
