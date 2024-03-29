## About
This step is about analyzing the dataset & using machine learning skills to solve real world problems.
<br/>In this project, I have built an deep learning models for multitask classification (*biotic stress and severity*)  estimation of coffee leaf biotic stress using Pytorch. The models has been trained on over 1740 images.

## Dataset
All images collected to build the datasets used in this work are public available at the following link:

[Coffee datasets](https://drive.google.com/open?id=15YHebAGrx1Vhv8-naave-R5o3Uo70jsm).

To give context the data represents a total of 1747 images of coffee entire leaves, including healthy leaves and diseased leaves, affected by one or more types of biotic stresses.

The dataset contains the following stresses:
  <br/> -> leaf miner,
  <br/> -> rust,
  <br/> -> brown leaf spot and 
  <br/> -> cercospora leaf spot. 

The images were labeled in relation to the predominant biotic stress of each leaf and its severity.

Severity is mapped in the csv file as follows:
	<br/> 1- Healthy : 0
 	<br/> 2- Very low : 1
 	<br/> 3- Low : 2
 	<br/> 4- High : 3
 	<br/> 5- Very high : 4


Your task is to train a model that is capable of identifying:
	<br/> 1- The stresses present
	<br/> 2- The severity of the predominant stress
	
We are expecting you to submit the following:
	<br/> 1- Your Notebook Code
	<br/> 2- csv file involves image name, stresses present and the severity

## Some Results
* Usin [RESNET50](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html)

<img
	  src="https://github.com/ahmadaking/Coffee-Leaves/blob/master/results/leaf_multitask/RESNET50_dis.png"
	  alt="to edit"
	  title="RESNET50_dis"
	  style="display: inline-block; margin: 0 auto; "
	  width=325px
	  height=325px
	><img
	  src="https://github.com/ahmadaking/Coffee-Leaves/blob/master/results/leaf_multitask/RESNET50_sev.png"
	  alt="to edit"
	  title="RESNET50_sev"
	  style="display: inline-block; margin: 0 auto; "
	  width=325px
	  height=325px
	>
* Using [GOOGLENET](https://pytorch.org/hub/pytorch_vision_googlenet/) with defualt setting (*t01_fold1_adm*)

<img
	  src="https://github.com/ahmadaking/Coffee-Leaves/blob/master/results/leaf_multitask/googlenet_t01_fold1_adm_standard_dis.png"
	  alt="to edit"
	  title="standard_dis"
	  style="display: inline-block; margin: 0 auto; "
	  width=325px
	  height=325px
	><img
	  src="https://github.com/ahmadaking/Coffee-Leaves/blob/master/results/leaf_multitask/googlenet_t01_fold1_adm_standard_sev.png"
	  alt="to edit"
	  title="standard_sev"
	  style="display: inline-block; margin: 0 auto; "
	  width=325px
	  height=325px
	>

