<h1 align="center">
<b>𝐌𝐞𝐫𝐜𝐚𝐝𝐨_𝐏𝐚𝐥𝐨_𝐌𝐞𝐱𝐄𝐄𝟒𝟎𝟐_𝐂𝐚𝐬𝐞𝐒𝐭𝐮𝐝𝐲</b>
</h1> 

<h1 align="center">
<b>𝐌𝐞𝐱𝐄𝐄 𝟒𝟎𝟐: 𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠 𝐂𝐚𝐬𝐞 𝐒𝐭𝐮𝐝𝐲</b>
</h1> 

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## 𝐌𝐞𝐦𝐛𝐞𝐫𝐬

| Name | Student Number | Section |
|---|---|---|
| Mercado, Christian |22-03089 |Mexe - 4103 |
| Palo, Yiestene | 22-04486 | Mexe - 4103 |

## 𝐍𝐨𝐭𝐞𝐛𝐨𝐨𝐤 𝐥𝐢𝐧𝐤𝐬

| Chapter | Mercado, Christian | Member 2 |
|---|---|---|
| Ch1_2_3 | [link]() | https://colab.research.google.com/drive/1CwPB3wUb3k4n09dz6jncVc5an9by-VGZ#scrollTo=R2-n79fV82uk |
| Ch4 | [link]() | https://colab.research.google.com/drive/1kKW6SMR9tP7P9B2ZX9Z0vY5o665xlEcT |
| Ch5 | [link]() | https://colab.research.google.com/drive/1GZvGgKPqXEqGkX_t6BdvwUf16uOjNeZU |
| Ch6 | https://colab.research.google.com/drive/1mHUySbNGVrnncpXGaCgQud3Y2I5LgEww?usp=sharing | [link]() |
| Ch7 | https://colab.research.google.com/drive/1Xgv-4IfFOBhqsLEZiLaqDmwZ7ie5YKf4?usp=sharing | [link]() |
| Ch8 | https://colab.research.google.com/drive/11iFJWV1vmR2Jk0GOPxjNruIAu_HAzsKe?usp=sharing | [link]() |
| Ch9 | https://colab.research.google.com/drive/1LIQEpbuax5XyN5RFucoSy4H_ZHXC19yz?usp=sharing | [link]() |

<h1 align="center">
<b>𝐖𝐡𝐚𝐭 𝐰𝐞 𝐥𝐞𝐚𝐫𝐧𝐞𝐝</b>
</h1> 
One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught
you and what surprised you. Not what the library does, but what you understood.






## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 1_2_3

These chapter taught us that data preprocessing is necessary to do before applying the data to any model to ensure that we will have clean data and all the issues we found are addressed. We also learned that there are different ways to handle the missing values. What surprised us the most was when there are missing values you can choose between two options whether to delete the row or imputation and what's really surprising is the imputation wherein you can compute for the average and that is the data we can use to fill in for the missing data so we don't have to delete them. Also one more thing, cleaning the data is just a few simple steps to make the messy raw data more accurate and ready to use for any model.

## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 4

This chapter taught us that feature engineering means that creating or changing columns so the data will show patterns more clearly, like binning the temperatures or making ratios such as lemonade per degree. The part we understood the best was when choosing what encoding to use, ordinal encoding when they have a natural order, like Little, Medium and Lots while, one-hot encoding when the categories have no order like Sunny, Cloudy and Rainy. What surprised us the most was that we can make new useful information just by combining the columns that we already have, like dividing the lemonade sold by temperature. This showed us that the way we prepare the data is as important as the data itself.

## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 5

This chapter taught us that data scaling makes the features on a similar scale so that the model can treat them equally. In the student example, Grades had much bigger numbers than the Study Hours, so without data scaling the model will favor only the grades because it has larger values even if it is both equally important. We learned two ways to fix this, StandardScaler which will change each column so the mean will be 0 and standard deviation to 1 and MinMaxScaler, which changes the values to fit between 0 and 1. What surprised us the most was that a feature can dominate a model because of its higher value not because it is more important than the other.

## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 𝟔

In Chapter 6, we learned that outliers are not simply data points that should be removed immediately, but values that need to be carefully examined because they can affect the accuracy and interpretation of an analysis. We learned how to use the Z-score and IQR methods to identify values that significantly differ from the majority of the data. What surprised us most was that the value 100 was clearly different from the other values, yet its Z-score was only approximately 2.53, which did not exceed the ±3 cutoff. This helped us understand that different methods can produce different results and that we should not rely on only one method when analyzing data. Overall, the chapter taught us the importance of careful analysis and proper judgment when handling outliers to produce more reliable and meaningful results.

## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 𝟕

This chapter taught us that feature selection is an important part of data preprocessing because not every piece of information in a dataset is equally useful for prediction. We understood that selecting relevant features can make a model simpler, more efficient, and easier to interpret, while unnecessary features may affect its performance. What surprised us was that different feature selection methods, such as the Filter method, RFECV, and LassoCV, can choose different features even when they are applied to the same dataset. This helped us realize that feature selection is not simply about choosing the features with the highest values, but about understanding how each method evaluates the importance of the data. Overall, the chapter gave us a better understanding of how carefully selected features can contribute to building a more effective machine learning model.

## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 𝟖

In Chapter 8, we learned how a preprocessing pipeline helps organize and standardize the preparation of data for machine learning. We understood that a pipeline works like a conveyor belt, where data passes through a series of steps, such as handling missing values and scaling features, before it is ready for analysis. We also gained a better understanding of how `SimpleImputer`, `StandardScaler`, and `ColumnTransformer` work together when processing the `Age` and `Fare` features of the Titanic dataset. What surprised us most was how a pipeline can reduce manual work and minimize the possibility of errors while keeping the preprocessing steps consistent. Overall, this chapter helped us realize that proper data preparation is just as important as building the machine learning model itself.


## 𝐂𝐡𝐚𝐩𝐭𝐞𝐫 𝟗

Chapter 9 taught us that data preprocessing is an important step in making raw data reliable and meaningful for analysis. We understood that handling missing values, transforming numerical features, encoding categorical data, reducing unnecessary information, and grouping values into meaningful categories can greatly improve the quality of a dataset. What surprised us most was that preprocessing is not simply a one-time process; it may need to be reviewed and adjusted depending on what we discover from the data and visualizations. We also realized that plots are useful not only for presenting results but also for helping us understand patterns and relationships that may not be obvious from the raw data. Overall, this chapter helped us appreciate that careful preparation of data is essential before using it for further analysis or machine learning.


<h1 align="center">
<b>𝐄𝐫𝐫𝐨𝐫𝐬 𝐰𝐞 𝐟𝐨𝐮𝐧𝐝</b>
</h1> 


List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

<h1 align="center">
<b>𝐍𝐨𝐭𝐞 𝐨𝐧 𝐀𝐈 𝐭𝐨𝐨𝐥𝐬</b>
</h1> 


Say whether you used an AI tool, and what for. This is not a penalty.
Hiding it is.

<h1 align="center">
<b>𝐑𝐞𝐟𝐞𝐫𝐞𝐧𝐜𝐞𝐬</b>
</h1> 


McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
```
