# Machine_Learning

These are project for Udacity's Machine Learning Specialization Nanodegree program. 

## Supervised Learnig
- **titanic_survival_exploration**: Predicting the survival of a Titanic passenger based on the RMS Titanic passenger manifest.

![titanic_sinking_image](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/titanic.jpg)


- **boston_housing**: Predicting selling prices for Boston Housing based on data collected from various suburbs in Boston, Massachusetts.

![histogram](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/housesbanner.png)

- **finding_donors**: Applying supervised learning techniques on data collected from the U.S. census to predict possible donors to help CharityML (a fictitious organization).

![histogram](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/fgdonors.png)

## Unsupervised Learnig
- **customer_segments**:
  - Analyzing a dataset containing data on various customers' annual spending amounts of diverse product categories.
  - Describing the variations in the different types of customers that a wholesale distributor interacts with.
  - Applying the appropriate features scaling, transformations and applying Gaussian Mixture Model (GMM) clustering algorithm to identify the various customer segments hidden in the data.
  
![customer_clusters](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/cusseg.png)

## Reinforcment Learnig
- **smartcab**:
  - Constructing an optimized Q-Learning driving agent that navigates a smart cab through its simulated environment towards its destination.
  - The driving agent is evaluated on two metrics: Safety and Reliability.
  - The result: Agent committed no traffic violations, and always chose the correct action. And it reached the destination on time for at least 90% of trips, rendering it safe and reliable

![smartcab](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/smartcap.PNG)


## Deep Learnig
- **dog_breed**: 
  - Using OpenCV's implementation of Haar feature-based cascade classifiers to detect human faces in images.  
  -> Sensitivity: ~100%
  - Using a pre-trained ResNet-50 model to detect dogs in images.  
  -> Sensitivity: ~100%
  - Creating a CNN to Classify Dog Breeds ( from scratch)
  - Creating a CNN to Classify Dog Breeds ( Using transfer learning: VGG19, InceptionV3)
  - Final Dog Breeds classifier -> accuracy: ~ 72%
  - Final Algorithm:
    - if a dog is detected in the image, the predicted breed is returned.
    - if a human is detected in the image, the resembling dog breed is returned.
    - if neither is detected in the image, output indicates an error.
 
![dogs](https://github.com/youssef-ahmed/Machine_Learning_Nanodegree/blob/master/snapshots/dog_breed.PNG) 

## Capestone Project
## Statoil: Icberge Classification Problem:  

### Problem Statement:
Drifting icebergs present threats to navigation and activities in areas such as offshore of the East Coast of Canada. Currently, many institutions and companies use aerial reconnaissance and shore-based support to monitor environmental conditions and assess risks from icebergs. However, in remote areas with particularly harsh weather, these methods are not feasible, and the only viable monitoring option is via satellite.  

The challenged is to build an algorithm that automatically identifies if a remotely sensed target is a ship or iceberg from satellite imagery. Improvements made will help drive the costs down for maintaining safe working conditions.

### Results:

Accuracy: 92%.
Kaggle Leaderboard score: 0.267.

