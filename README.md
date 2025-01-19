file 1 : Contains has preprocessing steps
  - it loads data
  - null value handling
  - outlier handling
  - out of 170+ columns , do feature engineering
  - then using PCA create 20 most important features
  - create transformed - Train, Test and unseen Datasets

    Class Information
    Class 1 : is for
    Class 2 : 

File 2 : contains model building classes 


File 3 : uses file 1 and 2 to do the training using different algorithms 
- calculates metrics
- display plots
- prints collated report of all the models. 
- make final prediction on unseen data

Models are saved in file and loaded on starting 
New models can be plugged in easily 
Information is readable and easily understandable. 
