# Data Science portfolio by O. Utku Ozbudak

Welcome to my Data Science portfolio! My name is Osman Utku Ozbudak, and I am passionate about using data to solve complex problems. In this portfolio, you will find a collection of my data-driven projects, showcasing my skills in areas such as exploratory data analysis, data visualization, and machine learning. Enjoy exploring!

## Stand-alone Projects

### Facial Recognition

The face recognition task was accomplished in this project by implementing Siamese Networks, as proposed in the research paper "Siamese Neural Networks for One-shot Image Recognition" by Koch et al. Positive samples were obtained from my webcam, while negative samples were obtained from the LFW Face Database. The network was fed with anchor and validation images, which were then processed in the embedding layer using convolutions, and similarity (L1) was computed in the distance layer. Consequently, all anchor images were validated correctly. In addition, the network was able to correctly label the negative samples as false predictions. Therefore, the implementation of Siamese Networks not only accurately validated the positive anchor images, but also correctly identified the negative samples as unrelated to the validation set. To access the research paper and the project, refer to the GitHub repository of the project from below.

[GitHub](https://github.com/utkuozbudak/facial-recognition)

## Clustering Problems

### Customer Personality Analysis

I am always thrilled to extract business strategies by analyzing customer data. In this project, I conducted a comprehensive exploratory data analysis using customer data to delve into various problems, such as why customers file complaints and what strategies can be employed to address them. Additionally, I employed clustering techniques to segment the customers into different clusters based on their characteristics. Using these clusters, I generated various marketing strategies that are tailored to the unique features of each group. Discover the process from below links (NbViewer is recommended for 3D plots).

[Nb Viewer](https://nbviewer.org/github/utkuozbudak/customer_personality_analysis/blob/main/customer_analysis.ipynb) [GitHub](https://nbviewer.org/github/utkuozbudak/customer_personality_analysis/blob/main/customer_analysis.ipynb) [Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
## Classification Problems

### Wine Quality Prediction

As a red wine enthusiast, I embarked on a quest to uncover the factors that contribute to a wine's quality. My Red Wine Quality Prediction project begins with exploratory data analysis, followed by the use of oversampling and SMOTE techniques to address class imbalance. I then trained and evaluated various models before selecting the best performer for further fine-tuning. Explore my process and findings in this exciting data-driven project from below links.

[Nb Viewer](https://nbviewer.org/github/utkuozbudak/wine_quality_prediction/blob/main/wine_quality.ipynb) [GitHub](https://github.com/utkuozbudak/wine_quality_prediction) [Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

## Regression Problems

### Graduate Admission
I recall being thrilled when I applied to TUM for my Master's degree. As a result, I decided to investigate which factors are significant in enhancing one's admission chances, utilizing the Graduate Admission dataset from Kaggle. Initially, I conducted data analysis, followed by training and evaluating numerous models to determine the most effective one. Subsequently, additional analyses were performed. You can examine my approach and discoveries in this project through the links below.

[NB Viewer](https://nbviewer.org/github/utkuozbudak/graduate_admission/blob/main/graduate_admission.ipynb) [GitHub](https://github.com/utkuozbudak/graduate_admission) [Dataset](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)

### Medical Cost Analysis
We all value affordable health insurance costs and strive to maintain good health. My goal in this project was to investigate the factors that influence the cost of insurance for individuals. Initially, I conducted an exploratory data analysis to extract valuable insights that cannot be easily discerned from the raw data. Subsequently, I trained and fine-tuned multiple regression models. Consequently, I achieved an R-squared value of 88%. Please refer to the following links for a detailed overview of my methodology and approach in this project.

[Nb Viewer](https://nbviewer.org/github/utkuozbudak/insurance_forecast/blob/main/insurance_forecast.ipynb) [GitHub](https://github.com/utkuozbudak/insurance_forecast) [Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance?datasetId=13720&sortBy=voteCount)

