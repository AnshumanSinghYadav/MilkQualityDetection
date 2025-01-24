# MilkQualityDetection

Milk being a perishable commodity that must be closely monitored to avoid financial losses and reduce the health risks associated with spoilage.

Python packages :

● Sklearn

● Pandas 

● Numpy 

● Matplotlib 

● Seaborn 

● Xgboost

# Dataset Features : 

pH: This feature defines pH of the milk, which is in the range of 3 to 9.5.

temperature: This feature defines the temperature of the milk, and its range is from 34'C to 90'C.

taste: This feature defines the taste of the milk and takes the possibles values: 1 (good) or 0 (bad).

odor: This feature defines the odor of the milk and takes the possibles values: 1 (good) or 0 (bad).

fat: This feature defines fat of the milk and takes the possibles values: 1 (good) or 0 (bad).

turbidity: This feature defines the turbidity of the milk and takes the possibles values: 1 (good) or 0 (bad).

colour: This feature defines the color of the milk, which is in the range of 240 to 255.

Preprocessing - The first step of preprocessing involved calculating the missing value in the data. It is found that there is not a single missing value for any of the features.

Since a computer cannot comprehend the value of the attribute in the problem, label encoding is used to convert the values in this case to category integer values. This dataset's "Grade" feature employs label encoding.

The final step is to scale the feature values. This is where the Min-Max scaling or z-score scaling is used. Scaling is typically employed to improves model convergence, and prevents certain features from overshadowing others based solely on their magnitude.

Temperature is right-skewed with 2.216739 and color is left-skewed with -1.024902.

We used PowerTransformer to get rid of skewness. PowerTransformer also has standardize argument. We can set it to True to accomplish our second task: scaling.

# Models Applied :

DECISION TREE

SUPPORT VECTOR MACHINE

ARTIFICIAL NEURAL NETWORK

RANDOM FOREST

GRADIENT BOOSTING CLASSIFIER

XGBOOST CLASSIFIER

ADABOOST CLASSIFIER

K-NEAREST NEIGHBOUR

USED GRIDSEARCHCV FOR MODEL TUNING.

Conclusion : A machine learning algorithm is used to predict milk quality based on influential factors, crucial for ensuring high-quality dairy products and preventing health risks. With increasing milk consumption and global production, efficient quality control becomes challenging. Machine learning offers a time-saving and labor-efficient solution. The study uses various metric evaluations for analysis. The Random Forest, XGBoost,K Nearest Neighbour, Adaboost models performs exceptionally great in achieving improved accuracy, enhancing quality assessment processes. With AdaBoost and other mentioned models, a 98.58% success rate is achieved using 1059 samples. The study concludes that machine learning algorithms offer high accuracy in assessing dairy product quality.
