# Shoes-Image-Classification 

Classification of Shoes using Deep Learning via Transfer Learning.

### Problem Statement:
Classifying goods using the correct commodity code is the most important step in import management. These codes tell customs officials what is being imported, if the goods are admissible, and what taxes, if any, are due. 

Any importer who gets the classification wrong is violating import laws. As a result, the importer is vulnerable to delayed cycle times, confiscated shipments, and fines. Around 52% of companies lack the headcount to perform all their import operations, according to Deloitte, managing importation requirements can cause unexpected business pain and disruption.

Here i pick a particular niche "Shoes" where I try to implement Deep Learning models using Transfer Learning which can aid companies and officials to solve this problem. 


### Objective
To build a model which would help in solving this niche problem. Thus enabling
- Consumers to choose and search for the specific type of shoe they are looking for.
- Retailers can use it to organise and Classify Inventory
- Manufacturers can use this for improving their production and design processes.
- Helping in preventing fraud and evasion of taxes and duties.


### Dataset Used
The link to the dataset
[https://www.kaggle.com/datasets/utkarshsaxenadn/shoes-classification-dataset-13k-images]

The dataset consists of 5 classes
- Ballet Flat
- Boat
- Brogue
- Clog
- Sneaker

consisting of images of type .jpeg

The directory structure of the dataset
```
Shoes Dataset/
    Train/
        class1/
            img1.jpeg
            ...
        class2/
            imga.jpeg
            ...
    Valid/
        class1/
            img2.jpeg
            ...
        class2/
            imgb.jpeg
            ...
    Test/
        class1/
            img3.jpeg
            ...
        class2/
            imgc.jpeg
            ...
```

However Validation Folder isnt entirely needed if would like to like specify another dataset.
The model takes in validation dataset from the training dataset itself.
