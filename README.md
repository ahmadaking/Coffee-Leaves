# About
This step is about analyzing the dataset & using machine learning skills to solve real world problems.
In this project, I have built an deep learning models for classification health and severity estimation of coffee leaf biotic stress using Pytorch. The models has been trained on over 1740 images.

# Dataset
To give context the data represents a total of 1747 images of coffee entire leaves, including healthy leaves and diseased leaves, affected by one or more types of biotic stresses.

The dataset contains the following stresses:
  -> leaf miner,
  -> rust,
  -> brown leaf spot and 
  -> cercospora leaf spot. 

The images were labeled in relation to the predominant biotic stress of each leaf and its severity.

Severity is mapped in the csv file as follows:
	<br/>1- Healthy : 0
 	2- Very low : 1
 	3- Low : 2
 	4- High : 3
 	5- Very high : 4


Your task is to train a model that is capable of identifying:
	1- The stresses present
	2- The severity of the predominant stress
	
We are expecting you to submit the following:
	1- Your Notebook Code
	2- csv file involves image name, stresses present and the severity