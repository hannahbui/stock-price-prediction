# stock-price-prediction
Predict stock price using 12 variants of LSTM and GRU

### Project Directory Structure
```
├── stock-price-prediction <- Project Main Directory
│   ├── data <- data in different format
|   |   ├── processed <- The final, canonical data sets for modeling
|   |   ├── stock_indicators <- Add basic indicators related to stock (e.g. MDA)
|   |   ├── price_graph <- Add collective influence (ci) columns 
|   |   ├── raw <- The original, immutable data dump
|   ├── notebooks <- All the ipython notebooks used for the whole process
│   ├── demo_notebooks <- demo results when running different versions of models
│   ├── frontend <- API and streamlit web app code
```