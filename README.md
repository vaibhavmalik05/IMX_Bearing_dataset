# IMX_bearing_dataset

This repo contains two ipynb files

**1. bearing_data_preprocessing.ipynb**
      In this file, the various time stamped sensor recordings are postprocessed into a single dataframe (1 dataframe per experiment).
      the following parameters are extracted for each time signal
      Min, Max, Range, Mean, Standard Deviation, Skewness, Kurtosis, Crest factor, Form factor
      Each of the files are exported for saving

**2. bearing_ml_model.ipynb**
      In this file, the ML model is generated.
      Here random forest classifier is employed
      the model developed 
        **training accuracy : 0.98  
        testing accuracy : 0.92**
        
        
 Along with the python notebooks (ipynb) i have also placed the Test1.csv, Test2.csv and Test3.csv which are the dataframes of compiled experiments.
 
 References: 
 1. https://www.youtube.com/watch?v=WJ7JEwBoF8c (NPTEL prognostics course)
 2. https://www.youtube.com/watch?v=WCjR9vuir8s (approach to the problem)
