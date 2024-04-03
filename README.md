# Abstract :

This project focuses on developing an electronics product recommendation system using collaborative filtering with neural networks (collabNN). We present a novel approach by incorporating a custom embedding module and implementing weight decay regularization to enhance the performance of the recommendation model. The dataset consists of user ratings, brands, and timestamps, providing a rich source of information for personalized recommendations. Our model leverages collaborative filtering techniques to predict user preferences based on historical interactions with electronic products. Through an iterative training process, the model learns to generate embeddings that capture latent features of both users and products, enabling accurate predictions. Experimental results demonstrate the effectiveness of our approach, as evidenced by the decreasing trend in both training and validation losses over multiple epochs. The achieved performance underscores the potential of our recommendation system in offering tailored suggestions to users, thereby enhancing their shopping experience in the realm of electronics.

# Objective:

The objective of this project is to create a user-friendly electronics product recommendation system using collaborative filtering and neural networks. We aim to accurately predict user preferences for electronic products, enhance model performance with a custom embedding module and weight decay, and improve user satisfaction by providing personalized recommendations. Through training and evaluation, we seek to optimize the system for accuracy and usability, ultimately enhancing the shopping experience for users in the electronics domain.

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
