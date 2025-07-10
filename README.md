# Project description:
This project is about building a machine learning model to predict house prices in Mashhad.<br>
We used the GradientBoostingRegressor to build the model.

---

## What programming language is this project written in?
<img src = "https://img.shields.io/badge/Python-f39f37" />

### Libraries used in this project:
<img src = "https://img.shields.io/badge/Numpy-f39f37" /> <img src = "https://img.shields.io/badge/Pandas-f39f37" /> <img src = "https://img.shields.io/badge/Seaborn-f39f37" /> <img src = "https://img.shields.io/badge/Matplotlib-f39f37" /> <img src = "https://img.shields.io/badge/Scikitlearn-f39f37" />

---

# Model evaluation:
|Data|MAPE|R2|MRR_Mean|MAE|
|:---:|:------:|:------:|:---:|:---:|
|Test|0.133637|81.94248|0.907731|86.450633|7.331749e+08|
|Train|0.076234|92.26256|0.953803|93.339793|4.490000e+08|

---

<h2 style="line-height:200%;font-family:vazir;color:#0099cc">
<font color="#0099cc">
Introduction to the dataset:
</font>
</h2>

<p>
<font size=3>
The data set contains 48121 rows, the description of each column is given in the table below
</font>
</p>

<center>
<div>
<font size=3>
    
|Column|Description|
|:------:|:---:|
|type|It identifies two types of villas and apartments|
|area|Area of house or land|
|neighborhood|Specifies the area, neighborhood, and street|
|description|The description the seller wrote for the house|
|Lat|The latitude of the traded house|
|Lng|Longitude of the traded house|
|age|Shows the year of manufacture|
|floor|Indicates the floor|
|bedrooms|Number of bedrooms|
|price|Price in Tomans|