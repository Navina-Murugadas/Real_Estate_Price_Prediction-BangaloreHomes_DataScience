# REAL ESTATE PRICE PREDICTION (BANGALORE HOMES)
  This project is to implement  a  house  price prediction  model  of  Bangalore,  India.  It’s  a  Machine Learning  model  which  integrates  Data  Science  and  Web Development.  Housing  prices  fluctuate  on  a daily  basis  and  are  sometimes  exaggerated  rather  than based  on  worth.  The  major  focus  of  this  project  is  on predicting  home  prices  using  genuine  factors.  Here,  we intend to base an evaluation on every basic criterion that is taken into account  when establishing the pricing.  The goal of this project is to learn Python and get experience in Data Analytics, Machine Learning, and AI.

# Tools/Technologies used:
1. Jupyter Notebook
2. Flask
3. Python
4. HTML
5. CSS
6. JavaScript

# Steps to create model:
1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Feature Engineering
6. Dimensionality Reductions
7. Outlier Removal using Business Logic
8. Outlier Removal using Standard Deviation & Mean
9. Data Visualization
10. Building a Model
11. Test the Model for few properties
12. Export the tested model to a pickle file

# Methodology:
# 1. Data Collection
   The statistics were gathered from  Bangalore  home  prices dataset from Kaggle. The  information  includes  many  variables  such  as  area type, availability,  location, BHK, society,  total square feet, bathrooms, and balconies. 
# 2. Data Science:
   The first stage is standard data science work, in which  we take a data set named ‘Bengaluru House pricing data' from Kaggle.  We  will  do  significant  data  cleaning  on  it  to guarantee that it  provides  reliable predictions throughout prediction.  This  Jupyter notebook,  ‘Real Estate Price Prediction.ipynb,'  is  where  we  do  all  of  our data  science work.  Because  the  Jupyter notebook  is self-explanatory, we  will  only touch  on the  principles that  we have implemented  briefly.  In terms  of data  cleansing, our dataset needs a significant amount of effort. In fact, 70% of the  notebook  is  dedicated  to  data  cleaning,  in  which  we eliminate  empty  rows  and  remove  superfluous  columns that will not aid in prediction. The  process  of  obtaining  valuable  and  significant information from a dataset that will contribute the most to a successful prediction is the next stage. The  final  stage  is  to  deal with  outliers.  Outliers  are abnormalities  that  do  massive  damage  to  data  and prediction. There is a lot to comprehend conceptually from the  dataset  in  order  to  discover  and  eliminate  these outliers. Finally,  the  original  dataset  of  over 13000 rows  and  9 columns is reduced to about 7000 rows and 5 columns.
# 3. Machine Learning:
The resulting data is fed into a machine learning model. To find the optimal procedure and parameters for the model, we  will  mostly employ  K-fold  Cross-Validation  and  the GridSearchCV approach. It turns out that the linear regression model produces the best results for  our data,  with a  score of  more than  80%, which is not terrible. Now,  we  need  to  export  our  model  as  a  pickle  file (Real Estate Price Prediction.pickle),  which  transforms Python objects into  a character stream.  Also, in  order  to interact with  the locations(columns)  from  the  frontend,  we  must export them into a JSON (columns.json) file.
# 4. FrontEnd:
The  front  end  is  built  up  of  straightforward  HTML.  To receive an estimated pricing, the user may fill-up the form with  the  number  of  square  feet,  BHK,  bathrooms,  and location and click the  ‘ESTIMATE PRICE' button. We have used Flask Server and configured it  in python. It takes the form data  entered by the  user and  executes the  function, which  employs  the  prediction  model  to  calculate  the projected price in lakhs of rupees.

# Project architecture:
![Architecture](https://github.com/Navina-Murugadas/Real_Estate_Price_Prediction-BangaloreHomes_DataScience/assets/72821323/ab878f6a-0e88-47a3-8a6e-8d90d0683a27)

# Conclusion:
With  several  characteristics,  the  suggested  method predicts  the  property  price  in  Bangalore.  We experimented with  different Machine Learning algorithms to  get  the  best  model.  When  compared  to  all  other algorithms,  the  Decision  Tree  Algorithm  achieved  the lowest loss and the greatest R-squared. Flask was used to create the website.

# Real Estate Price Predictor:
![Price1](https://github.com/Navina-Murugadas/Real_Estate_Price_Prediction-BangaloreHomes_DataScience/assets/72821323/55a3a0b8-e94f-441b-80bc-60a5cc94c4a7)

![Price2](https://github.com/Navina-Murugadas/Real_Estate_Price_Prediction-BangaloreHomes_DataScience/assets/72821323/d4df08da-5135-4361-abb4-343572d26203)

![Price3](https://github.com/Navina-Murugadas/Real_Estate_Price_Prediction-BangaloreHomes_DataScience/assets/72821323/bdeefba9-88c9-41d8-9d88-41bdbd6e750c)
