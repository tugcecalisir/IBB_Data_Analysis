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

<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/223101419-36866e82-21a5-4193-bd21-68bb590f238a.PNG">

<img width="800" height="400" src="https://user-images.githubusercontent.com/58370511/229122870-deaf07b5-e3f4-48cd-8aeb-bebc27ea057c.gif?raw=true">

Then, using the dataset at this <a href = "https://github.com/sukruburakcetin/veri-analizi_parklar-ve-yesil-alanlar/blob/main/Data/Non-GIS%20data/raw/park_location.csv"> link </a> green areas and parks were categorized.

<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229128101-78dbefaa-2729-446e-a320-0a2211c75f1a.PNG"><br>
<sub><b>Types of Green Spaces </b> </sub><br>

<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229131170-903f09c6-99ae-44a9-9ea3-ffd67b4d0017.PNG"><br>
<sub><b>Types of Parks</b></sub><br>

Using the <a href ="https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/Datasets/cocuk_nufus.csv" > Child Population</a> dataset, a ratio was made between the children's parks in the districts and the sum of the '0-4' and '5-9' age population columns. The graphics below show the ratio of playgrounds per 1000 children. According to the graph, there is no children's park for children in Kartal; It is seen that this rate is very low in Esenler and Sultanbeyli districts. It is seen that the Adalar district has the highest ratio of children's parks for children.

<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229132433-ab2c0d4e-63c7-43b1-a784-be2912066b77.PNG">
<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229132463-c70a1d51-8f6a-40ff-8bb3-ee4466b948f6.PNG">

Using the <a href ="https://github.com/tugcecalisir/IBB_Data_Analysis/blob/main/Datasets/nufus.csv" > Population</a> dataset, the districts with the highest and least population in Istanbul are shown in the graphs below. While Esenyurt is the most populated district in Istanbul, Adalar is the least populated district.
<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229140000-d4269910-d298-4847-bf50-9cb2a8cbace2.png">

With the population dataset, a ratio was made between the total number of green areas and parks in the districts. The rate of green areas and parks per 1000 people was found. In the final, it is seen that the Silivri district has the green spaces and parks ratio the most. Şile is the district that has the least.
<img width="900" height="300" src="https://user-images.githubusercontent.com/58370511/229143626-db0d4c40-ebe2-4e84-b5ea-04a5453465a8.png">
