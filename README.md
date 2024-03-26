# Welcome! 2 Exploratory Data Analysis projects are available here 🩵

 * **Dating Experiment project** with ipynb: **"v10_tinder.ipynb"** : based on a famous dating app with a flame 🔥
 * **Big Data project** with data Databricks: **"Click_Project_Links_3PARTS.txt"** : based on Video Plateform analysis 🎮

 - 👇🏽 *Down here you have the full description of both projects from Jedha, hope you enjoy them as did making them* 👇🏽

--- 

# Dating Experiment Project ❤️‍🔥

![Tinder](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Tinder-Symbole.png =100x200)

## Company's description 📇

<a href="https://tinder.com/" target="_blank">Tinder</a> is an online dating and geosocial networking application. In Tinder, users "swipe right" to like or "swipe left" to dislike other users' profiles, which include their photos, a short bio, and a list of their interests.

Tinder was launched by Sean Rad at a hackathon held at the Hatch Labs incubator in West Hollywood in 2012.

As of 2021, Tinder has recorded more than 65 billion matches worldwide.


## Project 🚧

The marketing team needs help on a new project. They are experiencing a decrease in the number of matches, and they are trying to find a way to understand **what makes people interested into each other**. 

They decided to run a speed dating experiment with people who had to give Tinder lots of informations about themselves that could ultimately reflect on ther dating profile on the app.

Tinder then gathered the data from this experiment. Each row in the dataset represents one speed date between two people, and indicates wether each of them secretly agreed to go on a second date with the other person.


## Goals 🎯

Use the dataset to understand what makes people interested into each other to go on a second date together:
* You may use descriptive statistics
* You may use visualisations



## Scope of this project 🖼️

Data was gathered from participants in experimental speed dating events from 2002-2004. During the events, the attendees would have a four minute "first date" with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests.

The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information. See the Speed Dating Data Key document below for details.

[Dataset](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data.csv)
[Dataset Description](https://full-stack-assets.s3.eu-west-3.amazonaws.com/M03-EDA/Speed+Dating+Data+Key.doc)


## Helpers 🦮

To help you achieve this project, here are a few tips that should help youbest destinations on a map

Data Exploration Ideas :
* What are the least desirable attributes in a male partner? Does this differ for female partners?
* How important do people think attractiveness is in potential mate selection vs. its real impact?
* Are shared interests more important than a shared racial background?
* Can people accurately predict their own perceived value in the dating market?
* In terms of getting a second date, is it better to be someone's first speed date of the night or their last?


## Deliverable 📬

To complete this project, your team should deliver:

A notebook with:
* descriptive statistics
* visualisations
* captions and interpretations on how the stats and visualisations are relevant to why people agree to a second date

--- 
--- 

# Steam's videogames platform 👾


👉🏽 *Here are the links from projects made on Databricks, follow the order please* 👈🏼
* **PART 1** : https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5823139237603888/925461032928614/3521016135925631/latest.html 

* **PART 2** : https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5823139237603888/3853032301986325/3521016135925631/latest.html

* **PART 3** : https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5823139237603888/2966921541288243/3521016135925631/latest.html 


## Company's description 📇
Steam is a video game digital distribution service and storefront from Valve. It was launched as a software client in September 2003 to provide game updates automatically for Valve's games, and expanded to distributing third-party titles in late 2005. Steam offers various features, like digital rights management (DRM), game server matchmaking with Valve Anti-Cheat measures, social networking, and game streaming services. Steam client's functions include game update automation, cloud storage for game progress, and community features such as direct messaging, in-game overlay functions and a virtual collectable marketplace.

## Project 🚧
You're working for Ubisoft, a French video game publisher. They'd like to release a new revolutionary videogame! They asked you conduct a global analysis of the games available on Steam's marketplace in order to better understand the videogames ecosystem and today's trends.


## Goals 🎯

The ultimate goal of this project is to understand what factors affect the popularity or sales of a video game. But your boss asked you to take advantage of this opportunity to analyze the video game market globally.
To carry out this project, you will have to adopt different levels of analysis. 
You're free to follow these guidelines, or to choose a different angle of analysis, as long as your analysis reveals relevant and useful information. 🤓

## Scope of this project 🖼️
You'll have to use Databricks and PySpark to conduct this EDA. Particularly, you'll have to use Databrick's visualisation tool to create the visualizations.

The dataset is available in our S3 bucket at the following url: s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json.

## Helpers 🦮

To help you achieve this project, here are a few tips that should help you:
To adopt different levels of analysis, it might be useful to create different dataframes.
As the dataset is semi-structured with a nested schema, Pyspark's methods such as getField() and explode() may help you.
There are some text and date fields in this dataset: Pyspark offers utilitary functions to manipulate these types of data efficiently 💡
You can use agregate functions and groupBy to conduct segmented analysis.

## Deliverable 📬

To complete this project, you should deliver:

* One or several notebooks including data manipulation with PySpark and data visualization with Databrick's dashboarding tool.
* To make sure the jury can view all the visualizations, please use the "publish" button on Databricks notebooks to create a public url where a copy of your notebook will be available.
* While using the "publish" button, Databricks may tell you that your notebook's size exceeds the maximal size allowed. If this happens, just split your notebook in several notebooks.
* Please copy-paste the link(s) to your published notebooks into your Github repo such that the jury can access it easily. 😌
