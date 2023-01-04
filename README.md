<a name="readme-top"></a>

#  Project Name
As part of the Big Data and AI Engineering Onsite Bootcamp, we are asked to deliver a solution for the MENA market that can be solved by Big Data and AI tools. The project has to have an impact and deliver a solution for a real-world problem using MENA datasets. 



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-overview">Project Overview</a></li>
    <li>
    <a href="#business-objective">Business Objective</a>
      <ul>
        <li><a href="#methods-used">Methods Used</a></li>
        <li><a href="#technologies">Technologies</a></li>
      </ul>
    </li>
    <li><a href="#dataset-overview">Dataset Overview</a></li>
    <li><a href="#preprocessing-overview">Preprocessing Overview</a></li>
    <li><a href="#visualization">Visualization</a></li>
    <li><a href="#modeling-results">Modeling Results</a></li>
    <li><a href="#contributing-members-contact">Contributing Members Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

##
## Project Overview

This is the overview of the project's structure and files for easier navigation.

```
├── README.md
├── dashboard.pdf
├── presentation.pdf
├── Notebooks
│   ├── preprocessing.ipynb 
|   ├── EDA.ipynb
│   └── ML.ipynb
└── Datasets
    ├── 1st_DS.csv (output of the pre-preprocessing notebook) 
    └── 2nd_DS.csv (used for the EDA, Dashboard, and Machine Learning models)
```


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Business Objective
The goal of this project is to forecast if a student can enroll in one of the public institutions in Egypt based on his current major and a few extracted attributes using data from a third-year secondary school dataset that was web scraped from the standardized tests in Egypt.


### Methods Used
* Preprocessing 
* Feature Engineering
* Feature Selection
* Labeling and classifying the data
* Exploratory Data Analysis
* Data Visualization
* Machine Learning
* Oversampling

### Technologies
* Python, Jupyter
* Pandas
* Plotly
* Power BI
* Pig (Big Data tool)
* PySpark Machine Learning (Big Data tool)



<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Dataset Overview
This dataset provides Egyptian student’s public results information. Including the student’s unique desk identifier number during the exam (this is unique for all students across Egypt), their gender and school name, the administration and the city their school belongs to, and how many test attempts they had. Lastly, for each attempt, it lists all the courses they can take depending on their branch and what score they have achieved for each course. Most of the courses will be calculated in the total score except for three courses; religion, national education, and economics Statistics. The dataset consists of 45 features and 683k records, which were taken for one year only; 2022. 

However, the problem has challenges because all the helpful features to our target can be found in the grades which can't be taken because it will create a data leakge in our model. In order to create a solid prediction, we need to extract more features from the existing columns, i.e. the school name.


At the beginning of our analysis, we raised some questions that we intend to answer using our EDA, dashboard visualization, and modeling. The questions are:
1. How many branches? Do grades differ based on the branch?
2. Has Egypt achieved the perfect normal distribution for the grading curve? 
3. Were there any unusual cases that happened to students during their exams?
4. What exactly happens if a student fails or misses their exam? Are they given another chance? And does their score improve once they get a second chance? 
5. For people with disabilities, What's their gender? How many can join the university? What are their grades? Do they have more second attempts? for unusual cases? 
6. For Egypt and Saudi, Do we have the same schooling system? How do schools handle disabled students?
7. Do we have gender equality in our schools?


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Preprocessing Overview 

Preprocessing is the essence of this project. In this README file, we will be listing the overview of each step. However, for a more detailed description, visit our [Medium Blog Post]


Preprocessing steps:

![image](https://user-images.githubusercontent.com/53378171/210471797-13d3ea08-9d78-43fe-8151-b9212a996044.png)


Feature engineering steps:


## Visualization


1st dashboard:


2nd dashboard:


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Modeling Results

All of these models were evaluted in order to choose the best one of them.



Model results:


Baseline Distribution:


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing Members Contact

**Team Leadear: Reema Alaswad** ([Reema's LinkedIn](https://www.linkedin.com/in/reema-alaswad-2002a3188/))

#### Other Members:

|Name     |  LinkedIn   | 
|---------|-----------------|
| Raghad Aleisa | [Raghad's LinkedIn](https://www.linkedin.com/in/rghde)  |
| AlJohara Alkanhal | [AlJohara's LinkedIn](https://www.linkedin.com/in/joharaalkanhal/) |
| Maha AlHazzani | [Maha's LinkedIn](https://www.linkedin.com/in/mahazzani/)  |
| Eman Aldosari | [Eman's LinkedIn](https://www.linkedin.com/in/eman-aldosari-51215a204/)  |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments
* [Readme Template 1](https://github.com/sfbrigade/data-science-wg/blob/master/dswg_project_resources/Project-README-template.md)
* [Readme Template 2](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
