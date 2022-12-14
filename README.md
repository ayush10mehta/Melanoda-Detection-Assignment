# Melanoda-Detection-Assignmen

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Create a CNN-based model that accurately detects melanoma. If melanoma is not found in its early stages, it can be fatal. It is responsible for 75% of skin cancer fatalities. A system that can analyse photos and notify dermatologists of the existence of melanoma might potentially eliminate the need for a lot of manual diagnosis work.

## Flow Diagram
![Flow chart](https://github.com/ayush10mehta/Melanoda-Detection-Assignmen/blob/main/CNN.drawio.png?raw=true)

### About the Data
- The dataset, which was created by the International Skin Imaging Collaboration, has 2357 photos of cancers, both malignant and benign (ISIC). With the exception of melanomas and moles, whose photos have a minor predominance, all images were sorted according to the categorization determined with ISIC, and all subgroups were divided into the same number of images.


## Conclusions
1. For Model 1 - The model is overfitting. We can see from the training vs. validation accuracy graph above that the discrepancy between training accuracy and validation accuracy grows as the epoch size increases.
2. For Model 2 - Overfitting is less of a problem after applying dropout layer and data augmentation and model performance has not improved at all. I'll look at how the classes are distributed in the training set to see if there are any class imbalances.
3. For Model 3 - The training accuracy and validation accuracy both rise with the final model (model3), problem of model overfitting is resolved and class rebalancing helps in enhancement and the greatest possible training and validation accuracy.
4. For Model 4 - Used Augmentor Library and the augmentation technique but haven't got good accuray using Model 4.
5. Also tried 2 more models
- Used Model 1 with Augmentor and got good accuracy.
- Used Model 3 with 45 epoch and got accuracy = 90% and validation accuracy = 84%.
 

## Technologies Used
- numpy version - 1.22.3
- pandas version - 1.4.2
- matplotlib version - 3.3.2
- seaborn version - 0.11.2
- missingno version - 0.4.2
- plotly version - 5.1.0
- scikit-learn - 0.24.1
- category-encoders - 2.2.2
- statsmodels - 0.14.0

## Acknowledgements
- We have taken the references of data computation methods from some of the python libraries.
1. Numpy: https://numpy.org
2. Pandas: https://pandas.pydata.org
- We have taken the references of data visualization from some of the python libraries.
1. Plotly: https://plotly.com
2. Seaborn: https://seaborn.pydata.org
3. Matplotlib: https://matplotlib.org
- We have taken the references of data modeling from some of the python libraries.
1. Keras - https://keras.io
2. Tensorflow - https://www.tensorflow.org/?gclid=Cj0KCQiAsdKbBhDHARIsANJ6-jd2UyztpB8oWAtfI-SHs2gOHEIUWP3JyQ43ueTIXKc-_40NVftEdfAaAnxhEALw_wcB
3. Augmentor - https://augmentor.readthedocs.io/en/stable/


## Contact
Created by [@ayush10mehta] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
