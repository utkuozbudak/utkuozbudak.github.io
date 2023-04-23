# Data Science portfolio by O. Utku Ozbudak

Welcome to my Data Science portfolio! My name is Osman Utku Ozbudak, and I am passionate about using data to solve complex problems. In this portfolio, you will find a collection of my data-driven projects, showcasing my skills in areas such as exploratory data analysis, data visualization, and machine learning. Enjoy exploring!

## Stand-alone Projects

### Facial Recognition

The face recognition task was accomplished in this project by implementing Siamese Networks, as proposed in the research paper "Siamese Neural Networks for One-shot Image Recognition" by Koch et al. Positive samples were obtained from my webcam, while negative samples were obtained from the LFW Face Database. The network was fed with anchor and validation images, which were then processed in the embedding layer using convolutions, and similarity (L1) was computed in the distance layer. Consequently, all anchor images were validated correctly. In addition, the network was able to correctly label the negative samples as false predictions. Therefore, the implementation of Siamese Networks not only accurately validated the positive anchor images, but also correctly identified the negative samples as unrelated to the validation set. To access the research paper and the project, refer to the GitHub repository of the project from below.

[GitHub](https://github.com/utkuozbudak/facial-recognition)

## Classification Problems

### Wine Quality Prediction

As a red wine enthusiast, I embarked on a quest to uncover the factors that contribute to a wine's quality. My Red Wine Quality Prediction project begins with exploratory data analysis, followed by the use of oversampling and SMOTE techniques to address class imbalance. I then trained and evaluated various models before selecting the best performer for further fine-tuning. Explore my process and findings in this exciting data-driven project from below links.

[Nb Viewer](https://nbviewer.org/github/utkuozbudak/wine_quality_prediction/blob/main/wine_quality.ipynb) [GitHub](https://github.com/utkuozbudak/wine_quality_prediction) [Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

## Regression Problems

### Graduate Admission
I recall being thrilled when I applied to TUM for my Master's degree. As a result, I decided to investigate which factors are significant in enhancing one's admission chances, utilizing the Graduate Admission dataset from Kaggle. Initially, I conducted data analysis, followed by training and evaluating numerous models to determine the most effective one. Subsequently, additional analyses were performed. You can examine my approach and discoveries in this project through the links below.

[NB Viewer](https://nbviewer.org/github/utkuozbudak/graduate_admission/blob/main/graduate_admission.ipynb) [GitHub](https://github.com/utkuozbudak/graduate_admission/blob/main/graduate_admission.ipynb) [Dataset](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)