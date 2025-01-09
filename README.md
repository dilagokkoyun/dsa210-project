
# Spotify Listenings & University Exam Schedule Analysis  

## Project Overview  
This project investigates the relationship between Spotify listening behaviors (e.g., music genres, timestamps) and university exam schedules. By analyzing patterns in listening habits, the goal is to determine whether students' music preferences correlate with exam stress periods and explore insights for stress management strategies.

### Key Questions:  
1. How do listening habits (genre preferences, listening times, etc.) correlate with exam schedules?  
2. Does the frequency of certain genres increase or decrease near exam periods?  

---

## Notebook Outline  
1. **Data Import & Merging**  
2. **Data Cleaning & Preprocessing**  
3. **Exploratory Data Analysis (EDA)**  
4. **Visualization**  
5. **Fetching Additional Metadata (Genre) from Spotify’s API**  
6. **Simple Machine Learning Approach**  
7. **Limitations & Future Work**  

---

## Libraries Used  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `sklearn`  
- `requests`  
- `json`  
- `spotipy`  

---

## Functions Implemented  
- `chunker`: A helper function for dividing data into manageable chunks for efficient processing.

---

## Findings  

### What You Learned  
- Skills in analyzing and visualizing data using Python libraries like `pandas`, `matplotlib`, and `seaborn`.  
- Experience working with APIs, specifically the Spotify API, to fetch and integrate additional metadata.  
- Improved data cleaning and preprocessing techniques.  
- Implemented a simple machine learning model to make predictions based on the data.  

### Limitations  
- Dataset was limited to a specific time period and may not reflect broader trends.  
- Mock data was used for demonstration purposes, potentially reducing real-world applicability.  
- Machine learning model (logistic regression) may not be the most suitable for the dataset.  

### Future Work  
- Analyze a larger and more diverse dataset for comprehensive insights.  
- Explore advanced machine learning models for improved accuracy.  
- Incorporate additional metadata from the Spotify API.  
- Examine the relationship between listening habits and exam schedules in greater detail.  
- Develop a user-friendly dashboard for visualizing insights.
