<img width="440" alt="image" src="https://github.com/user-attachments/assets/5d419921-cf4c-409c-9dd5-25d51b42816d">

# Prediction of Pharmaceutical Removal from Wastewater with Machine Learning
Jude Okolie (team lead), University of Oklahoma; Emmanuel Adeniyi, Louisiana State University; Faezeh Najafzadeh, University of Oklahoma; Jarely Mendez, Virginia Tech; Qianheng Zhang, University of Wisconsin, Madison; Samiha Nuzhat, Missouri State University; Siddiqur Rahman, University of Central Florida

## Background
The proposed project aims to address concerns related to the removal of pharmaceuticals pollutants from wastewater, a critical environmental challenge due to the increasing prevalence of these pollutants. 
Pharmaceuticals as emerging pollutants pose significant risks to both human health and the aquatic ecosystem. Their microscopic nature allows them to often go undetected, thereby complicating efforts to mitigate their impact.

Biochar produced waste materials could be used as a promising adsorbent for the remediation of pharmaceutical pollutants. 
The specific questions to be answered include: How effective is biochar, compared to other adsorbents in removing various pharmaceutical micropollutants from wastewater? 
What are the optimal conditions under which biochar can maximize the adsorption of these pollutants? 
Additionally, the research aims to understand the relationship between the properties of biochar and its efficiency in removing different types of pharmaceuticals. 
Furthermore, publicly available software will be developed for predicting biochar effectiveness in removing pharmaceuticals from wastewater.

The proposed problem is intrinsically linked to the theme of water security, a central focus of the Summer School 2024. 
Water security involves ensuring sustainable access to safe and clean water, a necessity that is compromised by the presence of pharmaceutical pollutants. 
The research into biochar as a cost-effective and eco-friendly adsorbent aligns with the goals of water security by providing a viable solution for clean water and waste valorization. 
It addresses the urgent need for innovative and sustainable technologies to mitigate water pollution, thereby safeguarding both environmental and public health.
The proposed project contributes to the broader goal of maintaining and improving water quality, a key aspect of water security.
## Project Motivations
1. Lack of understanding between Biochar properties & adsorption capacity
2. Difficulties in acquiring experimental data

## Project Objectives
1. Predict effectiveness of biochar in removing pharmaceuticals from wastewater
2. Determine optimal conditions to maximize pharmaceutical adsorption using biochar
3. Understand properties of biochar & its efficiency in removing pharmaceuticals

## Framing Project Within Social Science
### Environmental Justice and Equity
1. Intersectionality & health impacts
2. Disproportionate impacts on environment
3. Better prediction leads to safer water
4. Biochar production enhances equitable resource distribution
<img width="509" alt="image" src="https://github.com/user-attachments/assets/4354de24-1611-44be-8cb5-a2352431ee92">

## Experiment Workflow
1. Exploratory Data Analysis
2. Primary Model Performance Evaluation
3. Generation of Synthetic Data
4. Performance of Models on Augmented Dataset
<img width="444" alt="image" src="https://github.com/user-attachments/assets/8a15b200-32b7-4240-810c-458b6dd7bb18">

## Research Workflow
![project_workflow](https://github.com/user-attachments/assets/24c4a9ff-c4d4-4e46-ab4d-a7f905dd04f1)

## Exploratory Data Analysis Workflow
1. Gather data, and deal with missing data
2. Manage outliers
3. Heat map/Correlation Matrix
4. One Hot Encoding
5. Principal Component Analysis (PCA)

## Exploratory Data Analysis
### Heat Map
![heatmap](https://github.com/user-attachments/assets/f43bf051-2e8e-4f8a-82bb-4ebcf32acba5)
Figure shows correlation coefficient between each features and target variable used for this project.
### Principal Component Analysis
![PCA_plot](https://github.com/user-attachments/assets/1e4697b1-46e2-4316-9f71-9fbc26edd400)
### Boxplot
![Boxplot_original](https://github.com/user-attachments/assets/787e92cc-4078-4ba7-b16c-b72660a49c20)
Boxplots shows boxplot for each feature for the original dataset.
### Features
1. Pyrolysis temperature (TemP)
2. Time
3. Pore size (PS)
4. Brunauer–Emmett–Teller surface area (BET)
5. Pore volume (PV)
6. Carbon (C )
7. Hydrogen (H)
8. Nitrogen (N)
9. Oxygen (O)
### Target
Adsorption Capacity (Qm)
### Machine Learning Models
<img width="419" alt="image" src="https://github.com/user-attachments/assets/fa312ffe-a991-4687-b105-20ad879c4be7">

### Model Performance
<img width="406" alt="all_model_performance" src="https://github.com/user-attachments/assets/fea83621-1cb9-4589-9a07-db528c4b209e">

## Synthetic Data Generation
### GAN(Generative adversarial networks)
Dataset Size Matters
Filtered Authentic Data points: 80 rows times 24 columns
<img width="434" alt="image" src="https://github.com/user-attachments/assets/c4e00d8f-6f61-4aeb-9c12-79d034f62e16">
Synthesized Data points: 4371 rows times 24 columns
Augmented Data points: 4451 rows times 24 columns
### GAN Training Loss
<img width="294" alt="image" src="https://github.com/user-attachments/assets/84e823a8-228c-4f4c-98f6-a6ea52085a60">

### Synthetic Data Distribution
![boxplot_synthetic_data](https://github.com/user-attachments/assets/f8cc57fb-878e-4bd7-9240-13c85001f5c7)

### Synthetic and Original Data Distribution
![Boxplot_comparison_org_syn](https://github.com/user-attachments/assets/c4da89c8-ffb8-4873-8928-c29f2b1b5de2)

### Model Performance After Data Augmentation
<img width="406" alt="all_model_performance" src="https://github.com/user-attachments/assets/c4e420cc-71da-45fc-9d01-b5397f79e149">
Figure shows model performance of original data
<img width="355" alt="augmented_data_tuned" src="https://github.com/user-attachments/assets/d7f4415a-35c0-44fd-999f-d50cafffaad0">

Figure shows model performance for augmented data

## Ethics
<img width="472" alt="image" src="https://github.com/user-attachments/assets/078d2fd9-87cb-49e7-82b1-5bd0f62d8b6c">

## Graphical User Interface
![GUIpic](https://github.com/user-attachments/assets/9832d997-7a6f-419d-9775-94a51b934da8)

## Conclusions
1. ML models can be effective on environmental tasks by enhancing datasets and predicting results
2. Results provide insights and solutions for complex ecological tasks on multivariable relationships.
## Future Works
1. Improve GUI
2. In-depth Hyperparameter tuning on dataset and models
3. DEON Checklist.



###                                                    Team members:
![IMG_8282](https://github.com/user-attachments/assets/1cec9360-ee0c-4d76-86f0-79aa6492ee9d)



                       


