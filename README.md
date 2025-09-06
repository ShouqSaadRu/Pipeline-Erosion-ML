# Prediction of Erosion Rate in Pipelines Using Machine Learning

---

## Purpose of the Project

In computational fluid research (CFR) and industrial pipeline monitoring, calculating erosion rates manually is time-consuming and complex. Machine learning offers a faster, reproducible alternative that can generalize across varying conditions once trained.  

In oil and gas pipelines, especially at bends and elbows, erosion from solid particles such as sand can cause severe damage. Predicting this erosion helps minimize failures, maintenance costs, and unplanned shutdowns.  

This project applies **machine learning techniques** to structured experimental data to predict erosion rates. It builds upon a previous study ([Zahedi et al., 2018](https://doi.org/10.1016/j.powtec.2018.07.055)) that used Random Forests and another models. We extended their approach by adding preprocessing, and testing multiple ML models.  

The purpose of this project is to design a **proof-of-concept machine learning framework** for predicting erosion rates in pipelines, with the goal of supporting engineers and researchers in:  

- **Understanding erosion patterns** in gas-sand and multiphase flow conditions.  
- **Reducing maintenance costs and risks** by anticipating erosion-prone scenarios.  
- **Exploring how ML methods** can complement or replace manual calculations and simulations.  

**Note:** This project was developed using **limited data (202 rows)** due to **privacy and confidentiality restrictions**. The dataset cannot be provided here, but you can find it in the reference paper [Zahedi et al., 2018](https://doi.org/10.1016/j.powtec.2018.07.055). As such, the models require further validation on larger, more diverse datasets to be considered production-ready.   

---

## Project Report PDF

- **Project Report PDF:** [`docs/erosion report.pdf`](docs/erosionReport.pdf)

---



## Development Note

This project was completed within **two weeks** during my training period:  

- **Week 1** Reading the research paper, trying to understand the problem, and contacting the requestor (a non-technical stakeholder) to clarify requirements.
- **Week 2** Building the ML pipeline, preprocessing data, training models, and writing the report.  

---



## Conclusion

This project demonstrates the potential of **ML models (Gradient Boosting, Random Forest)** to predict erosion in pipelines using structured experimental data. Despite dataset limitations and inconsistencies, results show these methods can provide accurate, scalable alternatives to manual calculations.  

**Future Work:**
- Use larger, cleaner datasets.  
- Explore cross-validation and adjusted R².  
- Apply feature engineering to improve results. 
- Experiment with additional models
