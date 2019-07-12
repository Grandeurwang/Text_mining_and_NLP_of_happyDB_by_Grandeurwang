# Project 1: Text mining of HappyDB

![image](figs/title.jpeg)

### [Project Description](doc/Proj1_desc.md)
This is the first and only ***individual*** (as opposed to *team*) this semester. This project is finished by **Guanren Wang**

### Background
Nowadays, depression has been becoming a major threat for human being. Hoping to help them from a data-driven prospective, I did text mining on HappyDB, a corpus of 100,000 crowd-sourced happy moments. The goal is to advance the state of the art of understanding the causes of happiness that can be gleaned from text, which, furthermore, could be a reference for doctors.

### [Data Source](/data)

You may find the complete introduction of HappyDB here: [LInk](https://rit-public.github.io/HappyDB/)

### Project Summary:
+ cleaned unstructured data and transformed (tokenized and lemmatized) it into a well-formatted dataframe
+ used sentiment analysis method to explore the extent of happiness and found the extent of happiness across all age groups are almost same for male and female, but it differs for other genders
+ constructed relationship network between key words and discovered most probable causes of happiness such as job offer, video game and ride bike
+ discovered that Americans tend to gain happiness by themselves, while Indians are more likely to enjoy their life with family members or other relatives, after exploration of data using Latent Dirichlet Allocation 

### Complete Data Story: [Text mining of HappyDB](http://rpubs.com/Grandeur/Text_mining_and_NLP_of_happyDB)

### Examples of Visualizations

![image](figs/wordcloud.png)



![image](figs/relationships.png)


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
