# Data Science Portfolio

### Education
BSc Data Science,

James Cook University Singapore

### Technical Skills
Python, SQL, Java Script, R, Tensorflow, Keras, AWS, GoogleCloud, PowerBI, Tableau,

### Competition Experience
(2023)
[Ernst and Young Global Data Science Competition (with Microsoft and Cornell)](https://challenge.ey.com/challenges/past/level-1-crop-identification-global?id=637e2d535712cf0015c7691f)
- **Level 1: [Crop Identification](https://github.com/PaiHwai22/Ernst-and-Young-Data-Science-Challenge-2023/blob/main/EY%20Level%201%20Submission%20Final.pdf)**
  
  Placing 4th in Singapore Region, our 2 person team built a neural network to train radar images to classify if the crop was rice or non rice.
  Utilizing Sentinel-1 data given from the planetary computer API key, we accomplished in building AI Machine Learning Model with a high accuracy evaluation score of 96%.
  The model was built in python language utilizing tensorflow and Keras API Libraries. Led the preprocessing portion. 

- **Level 2: [Yield Estimation](https://github.com/PaiHwai22/Ernst-and-Young-Data-Science-Challenge-2023/blob/main/Level%202%20Submission.ipynb)**
  
  Placing 6th in Singapore Region, I led my team in building a one-tree regressor machine learning model to help scientists better understand the impact of climate change on crop
  yields. We used data from Microsoft Planetary Computer to access Sentinel-1 (radar), Sentinel-2 (optical), and Landsat data (optical). The model is purposed to forcast
  yield for any identified area of crop region. Applying feature engineering techinques and hyperparameter tuning, I improved the the 0.25 R2 baseline score to 0.64.
  
### Personal Projects 
(2023)
[Banking: Loan Default Prediction](https://github.com/PaiHwai22/LoanDefaultPrediction/blob/main/LDP_HistGradBoost_85%25.ipynb)
  
- Using a kaggle dataset for behavioral data and customer information, I built a predictor Histogram Gradient Boosting Classifier Model to predict if the customer will default on their
  loan. As the dataset had too many null values for important feature columns, I implemented the MICE imputation model and further improved accuracy outputs with feature engineering
  techniques to balance the targeted predictor. I optimized the hyperparameters with GridSearchCV to run all possible permutation combinations. The model is developed in Python
  language utilzing libraries such as Seaborn, Matlib, Pandas, Imputer, and NumPy. 

(2022)
[Conveyor Belt Operations: Real-Time Image Classification](https://github.com/PaiHwai22/CNN-for-Fruits-Classification)

- Convolutionary Neural Network for Realtime Image Classification
  
  I developed a Convolutional Neural Network for Image Classification on AWS SageMaker platform, utilizing keras and tensorflow API libraries. I applied Data Augmentation techniques
  with Keras' Image Data Generator and preprocessed the training data with feature engineering for RGB colors, normalization and scaling. The final model is evaluated at 91.45%
  accuracy when trained on 12 features on classfying images it has never seen before.
   
- VGG16 Transfer Model for Realtime Image Classification
  
  I developed a transfer learning model on AWS SageMaker utilizing SageBucket for data storage. I utilized splitfolder library to train the image data on the VGG16 transfer learning
  model. VGG16 Model was used because it has similar evaluation score to my own model at 92.7%. I freeze the top layers and train only on the last layers for the model to be optimized
  for my specific task. I add a fine tuning hyperparameter, ReduceLRonPlateau to reduce learning rate and achieve in finding the optimal learning rate. The model is evaulated at 86%
  accuracy. 

### Team Projects
(2022)
[NLP for Large Language Models: Topic and Text Analysis](https://github.com/PaiHwai22/NLP-Topic-and-Text-Analysis-for-Frequented-Websites)

- In a team of three, we built a machine learning model for topic modeling and text summerisation. The project involved webscrapping, topic selection, and topic summerisation. The project is deployed using Latent Dirichlet Method on a transformer based T5-Small model. The aim of the project is to give article summerisations to allow the user to decide if an article selected is worth diving deeper. The articles are retrieved based on keywords and ranked in by it's significance to the related key.
  
- I developed the webscrapping portion utilizing libraries such as Requests, BeautifulSoup, 'html'.parser, and Pandas. I led in the development of the main program which stores the extracted, parsed data into a collection of lists with three observations.

