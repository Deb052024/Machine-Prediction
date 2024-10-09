**Goal of the Case Study**
The goal of this case study to design a machine Learning Model that can accurately predict price for mobile Phones based on its features.

To accomplish the above task following tasks have been performed

1. **Data Exploration** Loading and exploring the dataset to understand its structure, data types, and the range of values for each feature.it has got 540 rows and 12 columns / features as attributes for the data set
2. **Dimensionality Reduction** Based on the analysis of data set, the unnecessary column , features have been dropped, here its **Unnamed**
3. **Data PreProcessing** Handle any missing values, outliers, or inconsistencies in the dataset. Convert catergorical to numerical format through encoding. The data set does not contain any null values and Label Encoder has been used to convert categorical to numerical 
4. **Feature Extraction** Three different techniques have been Performed to extract features that are related to price , they were coorrelation-Heat Map, SelectKBest Method, ExtraTree classifier. Scores have been allocated to the features and they were plotted also. The key features come up are

   ![image](https://github.com/user-attachments/assets/ff375250-702c-478e-b792-ddec4d2c3998)

 
 a.  Based on High Degree of positive correlation – Key Features related to price are –Memory, RAM, Mobile Height
 b. Based on SelectKBest Method –Key Features are –  Model, Battery, Memory, Processor 
 c. Based on ExtraTree Classifier Method –Key Features are – Model, Battery, Mobile Height ,Processor 

5. **EDA and Visualtion** - Features with occurances above mean were plotted and less occurance features were seggregated as  **Lesser**

     **Some Interpretations from EDA were**
   
A. SAMSUNG Galaxy A145G, REDMI Note 12Pro 5G, VIVO Y16, realmeC55 have got maximum occurrences
B. Features- Maximum cell phones with 126GB Memory, 4 GB RAM and 16MP Front camera
C. 16.76 inch height handset are having maximum presence in the distribution
D. Qual Comm Snap Dragon Processors are mostly used in cell Phones
E. 5000mH battery is mostly present across cell phones 
![image](https://github.com/user-attachments/assets/4ca87b4f-b95e-4e4b-8f05-7ecf8b4e98cf)

7. **Model Building**- Split the dataset into training and testing sets. and Price was kept as a part of Dependent variable

    Different Machine Learning Regressor method was used to predict the price and different KPIS were used
    They were Linear , Logistic, Support Vector , Support Vector,  Decison Tree Regressor
   Apart from them couple of ensemble techniques were also applied
   They were Random Forest, XGBoost, AdaBoost

8. **Model Evaluation** - Each of the models were evaluated based on the following parameters
    a. Train and Test Accuracy Score
    b. R*2 , Mean Absolute Error and Mean Square Error
   ![image](https://github.com/user-attachments/assets/44755ef4-5391-4f23-af23-d6d2afca1557)


10. **Cross Validation**   - for each of the Regressor techniques , cross validations have been used and they were plottedfor R*2 . Support Vector R*2 has been least and more spread of R*2 score for the ensemble techniques
![cross validation score plot on bar](https://github.com/user-attachments/assets/474371ce-ef2c-490c-a632-7435befcfb7e)


    
10. **Recommendations** - Based on the Plotting and Machine Learnig KPI are

A. Top three brands with highest selling prices are Apple iPhone 14 Plus, Samsung Galaxy S23 5G and Google Pixel 7 


B.With 128GB Memory APPLE are the costliest with bigger heights compared to 256GB Memory of Samsung Cell Phones, Brand being the differentiator 

C. 12MegaPixel Front camera are costliest for Apple and Samsung but most cameras present are of 10 or 8 Mega Pixel, 

D.8GM RAM is the most sought after for Samsung - how ever the current distribution is having most cell phones with 4GB RAM 

E. Ensemble Techniques perform better in Model Accuracy than normal learning models 

F. XGBoost is having highest accuracy but bit overfit how ever AdaBoost is neither overfit nor under fit in price predictions

G. R*2 square with least MAE(Mean Absolute Error ) is present for XGBoost 


![image](https://github.com/user-attachments/assets/18226cd4-a25e-49f1-b677-1ab7318ac677)
**Histogram Plot For Price**
Inferences 
1. Above plot clearly depicts maximum cell phones present in market are in the range of 10k to 40k.
2. No cell phones at 70k Price range , opportunity for premimum players like Apple ,Samsung, Google, RealMe to bring products at the price Point


**THANK YOU**







