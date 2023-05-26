# Data Science Capstone Project (IBM)

In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


![rocket](https://github.com/Zakia-M/SpaceX-Falcon-9-first-stage-Landing-Prediction/assets/76746908/dc2dd4a3-c02b-42bb-96cd-453e4457505d)



### Summary of methodologies:
- Data Collection using a RESTful API (SpaceX API)  and web scraping.
- Data wrangling, to explore the dataset and determine training labels.
- EDA, using SQL queries and some python libraries (pandas, matplotlib, and seaborn).
- Advanced exploration : Generate interactive maps using the Folium library. 
- Build an interactive dashboard with the Plotly Dash library.
- Using Machine learning models (classification techniques)  to predict if the first stage will land successfully.  

### Summary of results:
- The accuracy is almost the same for three classification models :  SVM, Logistic Regression and K Nearest Neighbours Classifier (83%).  Whereas the accuracy for the Decision Tree Model is very high (94%).
