# Alchemy lab by Quy Vu
This is where crazy ideas are experimented. Lots of them didn't work, but some turned out to be interesting!

<b> About me</b>: 

- Machine learning, deep learning with Python, Matlab
- Extract data with SQL
- Cloud computing in the Azure ecosystem
- Present result with PowerBI, Data engineering with PySpark. 
- Version control with Git

Currently part of the Data and Analytics team at Mott MacDonald in London. Previously worked at PwC and KPMG in Vietnam as consultant. MSc in data science at City, University of London. 

Play Dota 2 and basketball in my free time. Worship dogs.

## Computer vision
### Face and character detection and recognition
- Processed group and individual photos, then extracted features for 3 ML algorithms and 
- Performed transfer learning (VGG-Net) to achive 99.25% accuracy.
- Wrote a program to detect and recognise faces in pictures and video. 
- Also detect and recognise any number shown in the picture

<b>[Report](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Face%20and%20digit%20recognition.pdf)</b>

### Optical character recognition
- Highlighted the main difference of CNN and MLP and compare their performances in OCR task.
- Messed up traning data labels to see how can the network learn - <b>THEY CAN!!!</b> Turned out to be one of the active research area!

<b>[Report](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Comparison%20of%20MLP%20and%20CNN%20in%20hand-written%20digit%20recognition.pdf)</b>

## Reinforcement learning
- Trained an agent to solve the Cliff Walking problem using Q-learning and SARSA
- Experimented different learning parameters such as exploration factor (epsilon), decay factor (lambda), learning policy, learning rate, discount factor.
- Concluded that the agent trained with only Q-learning is quite dumb ...

<b>[Report](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Reinforcement%20learning/Implementation%20of%20Q%20learning%20and%20SARSA%20in%20Cliff%20Walking%20Problem.pdf) | [Repo](https://github.com/quyvx/Alchemy/tree/master/City/Courseworks/Reinforcement%20learning)</b>

## Imbalance learning
### Credit card fraud detection
- Used PCA to identify important predictors. 
- My first machine learning project at City University. 
- As the main goal was to to understand more about the data, I selected logistic regression and decision tree. Obiviously could get better performance with more sophisticated models.
- Earned me a final interview at GoldmanSachs

<b>[Notebook](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Credit%20card%20fraud%20detection%20with%20Logistic%20Regression%20and%20Decision%20Tree/Submission.ipynb) | [Repo](https://github.com/quyvx/Alchemy/tree/master/City/Courseworks/Credit%20card%20fraud%20detection%20with%20Logistic%20Regression%20and%20Decision%20Tree)</b>

## Big data
### Natural Language Processing
#### Spam detection with Logistic Regression, Naive Bayes, Support Vector Machines + PySpark
- Experimented 3 ML algorithms to classify spam messages
- The bigger the hash vector, the better prediction, since differents words are less likely to be assigned to the same position. However, there was no improvement as the vector size exceeds 3,000: The topic may not be diversed.
- Normalizing samples to unit L1 or L2 norm limits SVM's accuracy to ~84%. Not normalising boosted SVM's accuracy to 90%. This can be regarded as an alternative to tunning SVM's kernel function.

<b> [Notebook](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Spam%20Detection%20with%20PySpark.ipynb)</b>

#### Sentiment classification of Amazon Reviews with PySpark
- Used Logistic Regression and Naive Bayes to classify 4 millions Amazon Reviews.
- Set up a PySpark pipeline to process data.
- TF-IDF gave similar result to word2vec, but took less time to run.
- TF-IDF length of 10,000 gave AUC score of 0.92, how about 100,000? No better. It turns out that 10,000 is enough for one single topic (which is product review)

<b>[Notebook](https://github.com/quyvx/Alchemy/blob/master/City/Courseworks/Sentiment%20classification%20with%20PySpark/Code.ipynb) | [Repo](https://github.com/quyvx/Alchemy/tree/master/City/Courseworks/Sentiment%20classification%20with%20PySpark) | 
  [Poster](https://camo.githubusercontent.com/fb353f672e97b343d66c00a656430b4294d6fb62/68747470733a2f2f692e696d6775722e636f6d2f5234636a6a71502e6a7067)</b>

Under construction ...

# Contact
 [LinkedIn](https://www.linkedin.com/in/quyvx/) 
 
 Email: quy.vu@city.ac.uk!
