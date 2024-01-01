# All State Claim Prediction <br>
Goal of this activity:<br>
To better predict Bodily Injury Liability Insurance claim payments based on the characteristics of the insured customer’s vehicle.

## Table of Contents
- [Introduction](#-Introduction)<br>
- [Data Dictionary](#-Data-Dictionary)

### Introduction:
The training data consists of observations from years - 2005 to 2007.

### Data Dictionary:
**Variables:**   

- `Row_ID:` Index column
- `Household_ID:` Unique identifier for each household
- `Vehicle:` Unique identifier for each vehicle within a household
- `Calendar_Year:` Calendar year during which vehicle was insured (not blinded)
- `Model_Year:` Model year of vehicle (not blinded)
- `Blind_Make:` Vehicle make (example: ACME, coded A)
- `Blind_Model:` Vehicle model (example: ACME Roadster, coded A.1)
- `Blind_Submodel:` Vehicle submodel (example: ACME Roadster LS, coded A.1.1).  For the base model--e.g. no suffix after the model name--submodel is coded as 0
- `Cat1:` Categorical vehicle variable
- `Cat2:` Categorical vehicle variable
- `Cat3:` Categorical vehicle variable
- `Cat4:` Categorical vehicle variable
- `Cat5:` Categorical vehicle variable
- `Cat6:` Categorical vehicle variable
- `Cat7:` Categorical vehicle variable
- `Cat8:` Categorical vehicle variable
- `Cat9:` Categorical vehicle variable
- `Cat10:` Categorical vehicle variable
- `Cat11:` Categorical vehicle variable
- `Cat12:` Categorical vehicle variable
- `OrdCat:` Ordered categorical vehicle variable
- `Var1:` Continuous vehicle variable, mean 0 stdev 1
- `Var2:` Continuous vehicle variable, mean 0 stdev 1
- `Var3:` Continuous vehicle variable, mean 0 stdev 1
- `Var4:` Continuous vehicle variable, mean 0 stdev 1
- `Var5:` Continuous vehicle variable, mean 0 stdev 1
- `Var6:` Continuous vehicle variable, mean 0 stdev 1
- `Var7:` Continuous vehicle variable, mean 0 stdev 1
- `Var8:` Continuous vehicle variable, mean 0 stdev 1
- `NVCat:` Categorical non-vehicle variable
- `NVVar1:` Continuous non-vehicle variable, mean 0 stdev 1
- `NVVar2:` Continuous non-vehicle variable, mean 0 stdev 1
- `NVVar3:` Continuous non-vehicle variable, mean 0 stdev 1
- `NVVar4:` Continuous non-vehicle variable, mean 0 stdev 1 

**Target:**  
- `Claim_Amount`: Non-negative real number, 99% zeros on the training set

### EDA

