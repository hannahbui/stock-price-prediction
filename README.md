# stock-price-prediction
Predict stock price using 12 variants of LSTM and GRU

### Results

![Results after training 12 variants](https://github.com/hannahbui/stock-price-prediction/blob/main/model_training_result.png)

![Result compared to traiditional methods using GRU or LSTM alone](https://github.com/hannahbui/stock-price-prediction/blob/main/result.png)

### Report and Presentation Slide
- [Report](https://github.com/hannahbui/stock-price-prediction/blob/main/COS30018_Group2_Report.pdf)
- [Presentation Slide](https://github.com/hannahbui/stock-price-prediction/blob/main/COS30018_Group2_PresentationSlide.pdf)

### Project Directory Structure
```
├── group2_code_submission <- Project Code Main Directory
│   ├── data <- data in different format
|   |   ├── processed <- The final, canonical data sets for modeling
|   |   ├── stock_indicators <- Add basic indicators related to stock (e.g. MDA)
|   |   ├── price_graph <- Add collective influence (ci) columns 
|   |   ├── raw <- The original, immutable data dump
|   ├── notebooks <- All the ipython notebooks used for the whole process
│   ├── demo_notebooks <- demo results when running different versions of models
│   ├── frontend <- API and streamlit web app code
```
