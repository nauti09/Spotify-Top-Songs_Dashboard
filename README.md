# 📊 Spotify Top Songs 2023 - Power BI Dashboard  

## Overview  
This project presents an **interactive Power BI dashboard** that analyzes Spotify's top-streamed tracks from **2018 to 2023**. The dashboard provides insights into **streaming trends, track attributes, and artist performances** using a **refined dataset with album covers**.  

## Data Source  
📌 **Kaggle Dataset**: [Top Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023?resource=download)  

## Workflow  

1. **Data Acquisition**  
   - The raw dataset (`Spotify_2023.csv`) was obtained from **Kaggle**.  

2. **Data Enrichment**  
   - A Python script (`Getting_album_cover_script.ipynb`) was created to fetch **album cover URLs** for each track.  

3. **Data Cleaning & Transformation**  
   - The **updated dataset** (`updated_dataset_with_album_cover.csv`) was loaded into **Power BI**.  
   - Missing values were handled, and **necessary transformations** were applied.  

4. **Dashboard Development**  
   - A **visually appealing and interactive Power BI dashboard** was built to analyze:  
     - **Top streamed tracks & artists**  
     - **Annual & monthly streaming trends**  
     - **Track attributes (energy, danceability, valence, etc.)**  
     - **Track releases over time**  

## Dashboard Preview  
![Spotify Dashboard](Spotify_Dashboard.png)  

## Files & Structure  

| File Name | Description |
|-----------|------------|
| `Spotify_2023.csv` | Raw dataset from Kaggle |
| `Getting_album_cover_script.ipynb` | Python script to retrieve album cover URLs |
| `updated_dataset_with_album_cover.csv` | Enriched dataset with album covers |
| `Spotify.pbix` | Power BI report file |
| `Spotify_Dashboard.png` | Final dashboard screenshot |

## How to Use  

### **1. Power BI Dashboard**  
- Open `Spotify.pbix` in **Power BI Desktop**.  
- Ensure the dataset (`updated_dataset_with_album_cover.csv`) is loaded.  
- Explore insights with **interactive visualizations**.  

### **2. Running the Python Script**  
- Run `Getting_album_cover_script.ipynb` in **Jupyter Notebook**.  
- This script retrieves **album cover URLs** using APIs and updates the dataset.  

## Requirements  

### **Power BI**  
- **Power BI Desktop** (for visualizations)  

### **Python (for data processing)**  
- `pandas`
- `requests`
- `Jupyter Notebook`  

## Contribution  
Contributions are welcome! Feel free to enhance the **dashboard, data processing scripts, or visualizations**.  

## License  
📜 **MIT License** – Free to use and modify.  

---

🚀 **Discover Spotify's top songs and trends through interactive analytics!**  
