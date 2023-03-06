# Overview of Istanbul

This repository consists of two main projects. 
1. The analysis of Green Spaces and Parks in Istanbul and Their Relation to the Population 
<a href = "https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/%C4%B0BB_Green_Space_Analysis_and_Visualization.ipynb" > İBB_Green_Space_Analysis_and_Visualization </a>
2. Prediction of the Population of Istanbul Using ML Models 
<a href = "https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/Istanbul's_Population_Analysis_By_Regression.ipynb" > Istanbul's_Population_Analysis_By_Regression </a>


## 1. The analysis of Green Spaces and Parks in Istanbul and Their Relation to the Population

This project handles Green Spaces and Parks located in Istanbul. While dealing with green spaces and parks in Istanbul, the number, names, locations, categories, and types of them are considered district by district. Besides the population of Istanbul, and the population rate according to the number of green spaces and parks is	examined district by district. Finally, the number of events that the municipality of Istanbul organized and their relation with the number of green spaces and parks are considered.


### Parks and Green Spaces

In this section, <a href = "https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/Datasets/Istanbul%20Park%20and%20Green%20Area%20Coordinates.csv" > Istanbul Park and Green Area Coordinates </a> dataset is used. This dataset is taken from <a href = "https://data.ibb.gov.tr/dataset/parklar-ve-yesil-alanlar/resource/d588f256-2982-43d2-b372-c38978d7200b" > İBB AÇIK VERİ PORTAL </a>. 
This dataset includes the name, longitude, latitude, neighborhood, and district of parks and green spaces in Istanbul. In the project, preprocessing and cleaning procedures were applied to the dataset. In the end, it is seen that the EYÜPSULTAN and ÜSKÜDAR districts have the green spaces and parks the most. In contrast, ADALAR is the district that has them the least. 

In the graph below, the parks and green spaces numbers in all districts in Istanbul are shown.
![image](https://user-images.githubusercontent.com/103861412/222979480-d5b488cc-79fa-4b24-abee-d04c95ae0a7c.png)

Thanks to the longitude and latitude information of the parks and green spaces in the dataset, the total number of parks and green spaces was visualized one by one and district by district. Each park and green space was visualized one by one using MapBox and Choropleth Map. The link JSON file that is used <a href = "https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/istanbul-districts.json" > Istanbul Districts </a>. 
![Adsız tasarım (2)](https://user-images.githubusercontent.com/103861412/222981291-82981c4e-51e6-42d9-80d3-e7ecad0bff3d.gif)
![choropleth map1 gif](https://user-images.githubusercontent.com/103861412/222980218-072fa4b3-9d41-42f9-8fae-9703414b275b.gif)
