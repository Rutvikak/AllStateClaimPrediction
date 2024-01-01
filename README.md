# AllState Claim Prediction <br>
Goal of this activity:<br>
To better predict Bodily Injury Liability Insurance claim payments based on the characteristics of the insured customer’s vehicle.

## Table of Contents
- [Introduction](#-Introduction)<br>
- [Data Dictionary](#-Data-Dictionary)
- [Training and Testing Datasets](#-Training-and-Testing-Datasets)

### Introduction:
- The training data consists of observations from years - 2005 to 2007.
- Data has 13184290 rows and 35 columns.

### Data Dictionary:
**Variables:**   

- `Row_ID:` Index column (numeric)
- `Household_ID:` Unique identifier for each household (numeric)
- `Vehicle:` Unique identifier for each vehicle within a household (numeric)
- `Calendar_Year:` Calendar year during which vehicle was insured (not blinded) (categorical)
- `Model_Year:` Model year of vehicle (not blinded) (categorical)
- `Blind_Make:` Vehicle make (example: ACME, coded A) (categorical)
- `Blind_Model:` Vehicle model (example: ACME Roadster, coded A.1) (categorical)
- `Blind_Submodel:` Vehicle submodel (example: ACME Roadster LS, coded A.1.1).  For the base model--e.g. no suffix after the model name--submodel is coded as 0   (categorical)
- `Cat1:` Categorical vehicle variable (categorical)
- `Cat2:` Categorical vehicle variable (categorical)
- `Cat3:` Categorical vehicle variable (categorical)
- `Cat4:` Categorical vehicle variable (categorical)
- `Cat5:` Categorical vehicle variable (categorical)
- `Cat6:` Categorical vehicle variable (categorical)
- `Cat7:` Categorical vehicle variable (categorical)
- `Cat8:` Categorical vehicle variable (categorical)
- `Cat9:` Categorical vehicle variable (categorical)
- `Cat10:` Categorical vehicle variable (categorical)
- `Cat11:` Categorical vehicle variable (categorical)
- `Cat12:` Categorical vehicle variable (categorical)
- `OrdCat:` Ordered categorical vehicle variable (categorical)
- `Var1:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var2:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var3:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var4:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var5:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var6:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var7:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `Var8:` Continuous vehicle variable, mean 0 stdev 1 (numeric)
- `NVCat:` Categorical non-vehicle variable (numeric)
- `NVVar1:` Continuous non-vehicle variable, mean 0 stdev 1 (numeric)
- `NVVar2:` Continuous non-vehicle variable, mean 0 stdev 1 (numeric)
- `NVVar3:` Continuous non-vehicle variable, mean 0 stdev 1 (numeric)
- `NVVar4:` Continuous non-vehicle variable, mean 0 stdev 1  (numeric)

**Target:**  
- `Claim_Amount`: Non-negative real number, 99% zeros on the training set (numeric)

### Training and Testing Datasets:
- For the testing and training the model, divided the existing dataset into Training (80%) and Testing(20%) datasets. 
- Training dataset contains 10547432 rows and 35 columns.
- Testing dataset contains 2636858 rows and 35 columns.
- Out of 35 columns 34 columns as independant and 1 column is dependent column. 

### Problem Statement:
- Using a training dataset, create a model to predict vehicle claim payments by providing information about damaged vehicles. 

### Solution: 
- The appropriate model type for predicting claim payments on the basis of characteristics of demaged vehicles is Linear regression.

### Steps for creating models:
- Check and remove NULL and duplicate values.
- Creation of dummy features for categorical features.
- 
