# Machine Learning Image Classification for Agriculture Intelligence
This project was developed during the NSF-funded KANI DARE Summer Research Program, hosted by the University of Iowa. It focuses on building machine learning models to classify crop images using small datasets.
Objective
To develop image classification models capable of accurately identifying various crop types using limited training data. The project also explores data augmentation and generative techniques to expand the dataset and improve model performance.
## Models and Techniques
###	CNN-Based Classification
-	Binary and multiclass classification using custom CNN architectures
-	Fine-tuning with pretrained models: VGG16 and Xception
-	Best multiclass model accuracy: 74.19% with Xception + Fine Tuning + Data Augmentation
### Data Augmentation
-	Techniques used: random rotations, zoom, flips, etc.
-	Helped improve generalization with limited real-world data
### GAN-Based Image Generation
-	Trained a custom Generative Adversarial Network (GAN) on just 19 images of maize
-	Generated 150x150 images over 5000 epochs
-	Explored the challenges of synthetic image generation with extremely small datasets
## Results
Multiclass Model Accuracies:
- Multiclass Baseline CNN: 48.39%
- Multiclass with Data Augmentation: 41.94%
- Multiclass with VGG16 + Augmentation + Fine-Tuning: 67.74%
- Multiclass with Xception + Augmentation + Fine-Tuning: 74.19%
## Dataset
Source: Kaggle – Agricultural Crops Image Classification by MD Waquar Azam

Classes: Banana, Almond, Jute, Maize, Olives, Cherries

Small and imbalanced dataset with a focus on exploring generalization under constraints
## Team
- Tahsan Ul Alam (University of Iowa)
- Sam Akerman-Knopf (University of Iowa)
- Victoria Do (University of Arkansas)

For more information, please refer to the project poster.
