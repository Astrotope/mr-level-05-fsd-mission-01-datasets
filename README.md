# AI Vehicle Identification Datasets

## Dataset Folder Structure

```
/train
  /cab
  /convertible
  /coupe
  /hatchback
  /minivan
  /Negative
  /sedan
  /suv
  /truck
  /van
  /wagon
/val
  /cab
  /convertible
  /coupe
  /hatchback
  /minivan
  /Negative
  /sedan
  /suv
  /truck
  /van
  /wagon  
 
```

Note: A 'cab' is short for 'cabin', and it is what we call a Ute (Utility) in New Zealand.

## Dataset Contents

* Image counts in train folders:
	
	* sedan: 1907
	* van: 291
	* suv: 1437
	* Negative: 200
	* truck: 347
	* cab: 719
	* hatchback: 554
	* coupe: 1054
	* minivan: 250
	* convertible: 1036
	* wagon: 253
	
* Image counts in validation folders:
	
	* sedan: 1880
	* van: 287
	* suv: 1418
	* Negative: 79
	* truck: 240
	* cab: 711
	* hatchback: 549
	* coupe: 1042
	* minivan: 248
	* convertible: 1022
	* wagon: 250

## Download Dataset

* Dataset Archive [Google Drive - ai-vehicle-id-dataset.zip](https://drive.google.com/file/d/1o8ZxFqylNY37aoDljaFLhQDxv_iu9PdI/view?usp=drive_link)
* Browse Dataset [Google Drive - folder - ai-vehicle-id-dataset](https://drive.google.com/drive/folders/1BKlVwcp2yWBfIMbXleIblvZ8fywM70RF?usp=drive_link)

## The images were sourced from the following datasets:

* Car Images - Stanford Cars Dataset
	* Image Files - Download via KaggleHub - Dataset Name: jutrera/stanford-car-dataset-by-classes-folder

		```
		import kagglehub
		
		# Download latest version
		path = kagglehub.dataset_download("jutrera/stanford-car-dataset-by-classes-folder")
		
		print("Path to dataset files:", path)
		```

	* Dataset Description [Stanford Cars Dataset](https://www.kaggle.com/datasets/jutrera/stanford-car-dataset-by-classes-folder/data)
	* License [ImageNet License](https://www.image-net.org/download.php)
* Truck Images - Images.CV - Trucks Dataset
	* Image Files [Images.CV Trucks Dataset](https://images.cv/dataset/truck-image-classification-dataset) 
	* License [Various Licenses - No Specific License Specified](https://images.cv/datasets-licenses)
* Negative Images - BG-20K Datset of Backgrounds
	* Image Files [BG-20K Google Drive](https://drive.google.com/drive/folders/1ZBaMJxZtUNHIuGj8D8v3B9Adn8dbHwSS)
	* Dataset Description [BG-20K GitHub](https://github.com/JizhiziLi/GFM?tab=readme-ov-file#bg-20k)
	* Usage Agreement [Dataset Agreement](https://jizhizili.github.io/files/gfm_datasets_agreements/BG-20k_Dataset_Release_Agreement.pdf)
	* License [MIT License](https://github.com/JizhiziLi/GFM/blob/master/LICENSE)

## Explore Dataset in Google Colab

* Colab Notebook to Load and Explore Dataset [Google Colab](https://colab.research.google.com/drive/1apzmMH28lyQxR0PqjXztb4hIESP98XYV?usp=sharing)

