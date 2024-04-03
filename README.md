# Deep Learning for Collaborative Filtering with Custom Neural Networks using PyTorch 

## Objective:

The objective of this project is to develop a highly effective product recommendation system using deep learning techniques within the collaborative filtering framework. Key goals include:

1. Designing and implementing a custom neural network architecture in PyTorch to process user interactions and item embeddings for personalized recommendations.
2. Leveraging Fastai libraries for efficient training and evaluation of the recommendation model, aiming to achieve notable improvements in both training and validation performance.
3. Integrating tailored embeddings and advanced neural network structures to enhance the accuracy and relevance of product recommendations.
4. Evaluating the effectiveness of the recommendation system through extensive testing and validation, with a focus on enhancing user satisfaction and engagement within e-commerce platforms.

# Abstract :

This project presents the development of a sophisticated product recommendation system leveraging deep learning techniques within the collaborative filtering paradigm. Utilizing PyTorch and Fastai libraries, we engineered a custom neural network architecture capable of processing user interactions and item embeddings to deliver personalized product recommendations. By concatenating embedding activations and applying nonlinear transformations, the model effectively captures user preferences and item features. Through extensive training and evaluation, notable improvements in both training and validation performance were achieved, affirming the system's effectiveness in refining product recommendations. The integration of tailored embeddings and advanced neural network structures underscores the project's contribution to enhancing user satisfaction and engagement within e-commerce platforms.


## Exploratory Data Analysis (EDA)

### Gender Distribution in Purchases

- **Bar Chart Analysis:**
  - Analyzed the gender distribution among customers based on purchasing behavior.
  - Observed that females tend to make more purchases compared to males, as indicated by the bar chart visualization.

![Image](https://github.com/Aravinth-Megnath/Product-Recommendations/assets/120720408/91ac74c5-be5a-4213-8c41-85a87118abff)

### Popular Product Categories

- **Bar Chart Analysis:**
  - Investigated the distribution of purchases across different product categories.
  - Found that "Headphones," "Computer Accessories," and "Camera/Photo" are the top-selling categories, based on the bar chart visualization.


![Image](https://github.com/Aravinth-Megnath/Product-Recommendations/assets/120720408/ba7e2eec-cfb1-4f8b-98f2-fc40ff70bd8f)

### Ratings by Gender and Product Category

- **Boxplot Analysis:**
  - Conducted a boxplot analysis to examine the distribution of ratings by gender across various product categories.
  - Observed that males tend to rate "Security and Surveillance" products higher, while females rate "Home Audio" products higher.
  - Additionally, both genders rate "Accessories and Supplies" similarly.


![Image](https://github.com/Aravinth-Megnath/Product-Recommendations/assets/120720408/2ae24915-e0c9-4208-a18b-3fb36e7e7354)

### Ratings Over the Years

- **Boxplot Analysis:**
  - Investigated the distribution of ratings over the years using a boxplot.
  - Found that the ratings were consistently high (near 5) around the year 2002, but decreased significantly after 2007, with most ratings falling below 4.



![Image](https://github.com/Aravinth-Megnath/Product-Recommendations/assets/120720408/22476758-ab54-44a1-ae22-71f7757d7fb2)

# Conclusion


![Image](https://github.com/Aravinth-Megnath/Product-Recommendations/assets/120720408/07e215d9-dcd1-408f-a8e4-369fea2b6d2d)


In conclusion, the decreasing trend in both training and validation losses suggests that the model is learning and improving over the training epochs. This indicates that our product recommendation system is effectively capturing patterns in user behavior and making better predictions. However, the slight fluctuations in validation loss indicate that there may be room for further optimization to enhance the system's performance. Overall, these results are promising and provide a solid foundation for refining and optimizing our recommendation system to better serve users and enhance their shopping experience.
