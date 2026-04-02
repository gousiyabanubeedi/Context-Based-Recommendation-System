# Context-Based-Recommendation-System
A tourism destination recommendation places based on user input like state , city , keyword .it will Help tourists choose suitable destinations by combining ratings, and live weather data and 3 progressive models for smarter recommendations.

## 3 Models used in this
1.Keyword & Location Filtering Model - 
  Filters destinations based on user input like state, city, or keyword                                                                                                                                                    
2.Weather-Based Rule Filtering Model - 
  Fetches real-time weather using lat/longitude and eliminates destinations with unfavorable conditions                                                                                                                             
3.Optimized Weighted Scoring Model - 
  Ranks remaining destinations based on ratings, and weather suitability
  
## Technologies
Context-based filtering                                                                                                                                         
Rule-based filtering                                                                                                                                               
Weighted scoring optimization techniq

  
## 🚀 How to Run
1. Click the notebook file in this repo
2. Click "Open in Colab" button at the top
3. Download places.csv directly from this repo
4. Upload places.csv to colab by runing 
                                                                     
  from google.colab import files                                                                                                                                                                                                     
  uploaded = files.upload()   # select places.csv from your computer
  
5. Run all cells: Runtime → Run all
6. Notebook will automatically load the dataset

Note: If any library is missing, install via
!pip install [library name]

## Technologies 
Language: Python                                                                                                                                                            
Backend: Django                                                                                                                                                               
Libraries: Pandas, scikit-learn, NLTK                                                                                                                                                                             
Dataset: Kaggle tourism dataset                                                                                                                                                                                             
API: Open Meteo Weather API

