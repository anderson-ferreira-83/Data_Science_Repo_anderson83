# First Data Challenge - Alura

![Badge in Development](http://img.shields.io/static/v1?label=STATUS&message=IN%20DEVELOPMENT&color=GREEN&style=for-the-badge)

<center>
  <img src="https://i.imgur.com/jn7km8o.png">
</center>

Alura Voz is a telecommunications company that hired us as data scientists on the sales team. In the first week, leadership informed us of the need to conduct a study on the company's churn. They explained that churn indicates whether a customer canceled or not their contract with the company, and that customer loss impacts revenue negatively.

Thus, we were informed that we have four weeks to seek an alternative to minimize customer loss and were provided a dataset containing various customer information, as well as indicating if they left the company.

We know that, before considering any alternative solutions, it’s essential to understand the provided information. After a brief meeting, we concluded that we would dedicate the first week to understanding the database, identifying data types, checking for incoherent values, and correcting them if necessary.

## Week 1 - Data Cleaning

### Data

Upon reviewing the [Alura Voz Database](https://github.com/sthemonica/alura-voz/blob/main/Dados/Telco-Customer-Churn.json), we found that the data is provided via an API in JSON format with multiple layers.

Along with the data, we were also provided the [data dictionary](https://github.com/sthemonica/alura-voz/blob/main/dicionario.md), which contains information on all database columns.

In addition to whether a customer left the company, it also includes:

<b>Customer:</b>
 
* `gender`: gender (male and female)
* `SeniorCitizen`: indicates if the customer is aged 65 or older
* `Partner`: if the customer has a partner or not
* `Dependents`: if the customer has dependents or not

<b>Telephone Service</b>

* `tenure`: months of customer’s contract
* `PhoneService`: subscription to telephone service
* `MultipleLines`: subscription to multiple phone lines

<b>Internet Service</b>

* `InternetService`: subscription to an internet provider
* `OnlineSecurity`: additional online security subscription
* `OnlineBackup`: additional online backup subscription
* `DeviceProtection`: additional device protection subscription
* `TechSupport`: additional technical support subscription with reduced wait time
* `StreamingTV`: cable TV subscription
* `StreamingMovies`: movie streaming subscription

<b>Contract</b>

* `Contract`: type of contract
* `PaperlessBilling`: if the customer prefers online billing
* `PaymentMethod`: payment method
* `Charges.Monthly`: total monthly charge for all services
* `Charges.Total`: total amount spent by the customer

Having this information allows us to understand our data and proceed to a more technical analysis, where we’ll understand the JSON structure, inspect the data, and clean it as needed.

All developments from our first week can be found in the [week 1 notebook](https://github.com/sthemonica/alura-voz/blob/main/1-Limpeza%20dos%20dados/limpeza.ipynb).

## Week 2 - Data Analysis

After recognizing and cleaning the data, we continued our work by analyzing it. Through discussion with the group, we concluded that a graphical analysis is necessary to understand which variables are related to churn so the sales team can get an overview of the current situation and so that we can develop hypotheses about the customer’s behavior.

We plan to conduct a **statistical analysis** of the data, check **data types**, create **distribution graphs for binary or categorical data**, produce **Boxplots** to detect outliers, and build a **correlation matrix**. Through these analyses, we can identify relationships between data and our target, spot incoherent and/or unnecessary values, and deepen our understanding of the data.

All development and analysis from our second week can be found in the [week 2 notebook](https://github.com/sthemonica/alura-voz/blob/main/2-%20An%C3%A1lise%20dos%20dados/analise.ipynb).

## Week 3 - Machine Learning Models

After discussing and reviewing all analyses from week 2, we concluded that a good option to minimize Alura Voz’s customer churn is to have a trained model that classifies customers as potential churn risks, enabling the sales team to act before they actually leave.

Therefore, we began preparing the data to feed the models. Through our studies in week 2, we identified irrelevant input variables, non-numeric categorical data that models cannot interpret directly, and an imbalanced target variable. We processed these data points accordingly.

The classification models we chose to address our problem are **SVC**, **Decision Tree**, and **Random Forest**. Since we couldn’t reach a consensus on which model would be best, we decided to develop and train all three models, so we could evaluate which one is most suitable in the final week.

All development and analysis from our third week can be found in the [week 3 model notebook](https://github.com/sthemonica/alura-voz/blob/main/3-Modelos%20de%20ML/modelos.ipynb) and [notebook for model improvement](https://github.com/sthemonica/alura-voz/blob/main/4-Melhorando%20o%20modelo/otimizacao.ipynb).

#alura #alurachallengedatascience1

## Meet the Team

#### Sthefanie Monica

<div align="left">
<img src="https://i.imgur.com/PPEmT1K.png" width="300px" />
</div>

Bachelor in Electrical Engineering from UTFPR, currently a Data Science instructor at Alura. During my undergraduate studies, I conducted research on neural networks and computer vision, including a research period at Hospital Israelita Albert Einstein. In my free time, I love playing games, both board games and video games, and I’m always planning my next trip.

<div>
<a href="https://www.linkedin.com/in/sthefanie-monica/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>

#### Ana Clara

<div align="left">
<img src="https://i.imgur.com/DAYE0yR.png" width="300px" />
</div>

Bachelor in Biomedical Informatics, currently pursuing a master’s in Bioengineering at USP. I work as a FAPESP researcher and instructor at Alura's Data School. I previously interned at the Hospital das Clínicas-FMRP, co-founded, and currently advise the Data Girls group. I am passionate about Data Science and AI applications in various fields. I also love books, series, games, and a good coffee.

<a href="https://www.linkedin.com/in/anaclara-amioto/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

#### Bruno Raphaell

<div align="left">
<img src="https://i.imgur.com/TpbGKvC.png" width="300px" />
</div>

Electrical Engineering student at UFPI and currently a Data Science scuba at Alura. Passionate about music, biographical films, and programming. In my free time, I try to rank up in League of Legends, play instruments, and watch movies and series.

<a href="https://www.linkedin.com/in/bruno-raphaell-alves-de-matos/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

#### João Miranda

<div align="left">
<img src="https://i.imgur.com/6evW05p.png" width="300px" />
</div>

Bachelor in Mathematics from UFMG, currently pursuing an MBA in Data Science and Analytics at USP/Esalq. I am a monitor at Alura's Data School. I enjoy reading, playing electronic and board games, and archery.

<a href="https://www.linkedin.com/in/joaovmiranda/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

#### Mirla Costa

<div align="left">
<img src="https://i.imgur.com/vrbN6ov.png" width="300px" />
</div>

Electrical Engineering student at UFPI with research focused on Machine Learning and Computational Intelligence. I work as a scuba in Alura's Data Science school. I love programming, teaching, and working with technology. In my free time, I enjoy playing with my pets, watching animations and series, and playing tabletop RPGs.

<a href="https://www.linkedin.com/in/mirla-costa/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
