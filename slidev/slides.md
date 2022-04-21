---
theme: geist
layout: cover
lineNumbers: false
---

# A Brief History of Machine Learning

Haowen Zhang

<!--- page break -->

---
layout: two-cols
---

# what is machine learning?

#### 1949 Donald Hebb
- interaction pattern between neurons
#### 1950 Alan Turing & Turing Test
#### 1952 concept introduced by **Arthur Samuel**
- Ability to learn without being explicitly programmed

<img src="https://cs.stanford.edu/sites/default/files/Arthur%20Samuel%20picture.jpg" alt="drawing" width="80"/>
::right::
<br>
<img src="https://miro.medium.com/max/789/0*Q3PICBlib-932hhH.png" alt="drawing" width="500"/>


<!--- 
1949 – Donald Hebb published “The Organization of Behavior,” introducing theories on the interaction between neurons, which were later crucial in developing machine learning. He was considered the 'father of neuropsychology.' 

1950 – Alan Turing invented the Turing Test, or the imitation game, to determine if a computer can pass for a human-based on its written linguistic fluency.

1951 – Dean Edmonds and Marvin Minsky built the SNARC machine, the first machine with an artificial neural network, based on Hebb’s model.

1952 – Arthur Samuel developed a computer game of checkers; USC 
-->

---
layout: two-cols
---

## 1957-1974 The golden era

#### 1957 the perceptron
- designed by Frank Rosenblatt, The building block of Neural Network
<img src="https://953894.smushcdn.com/2611031/wp-content/uploads/2019/05/Perceptron1957.gif?lossy=0&strip=1&webp=1" alt="drawing" width="400"/>

::right::
<br><br><br><br><br><br><br><br><br><br>
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Perceptron/diagram-of-a-biological-neuron_1.jpg" alt="drawing" width="450"/>

<!--- page break -->
---
layout: image
image: https://inews.gtimg.com/newsapp_bt/0/14533715758/1000
---

<!--- page break -->
---
layout: iframe
url: https://gfycat.com/ifr/AnimatedVacantAldabratortoise
---

---
layout: default
---
# However, people under estimated it..

### 1957-1974  Golden era of machine learning
- Researchers came up with some great methods. (e.g KNN)
- Lots of funds, people were optimistic
- entry-level AI agent like chatting bot
- "machines can beat best human chess player with 10 years"

### 1974-1980  Dark winter
- promise not fulfilled
- This field was defunded


<!-- 
1967——「最近邻」算法（The nearest neighbor algorithm）出现
由此计算机可以进行简单的模式识别。它可以帮助旅行商制定旅游路线图，
即保证旅行商从任意城市出发，以最短的总路程遍历所有城市
The nearest neighbor algorithm was written for the first time this year. It allows computers to start using basic pattern recognition. This algorithm can be used to map a route for a traveling salesman that starts in a random city and ensures that the salesman passes by all the required cities in the shortest time. Today, the nearest neighbor algorithm called KNN is mostly used to classify a data point on the basis of how their neighbors are classified. KNN is used in retail applications that recognize patterns in credit card usage or for theft prevention when implemented in CCTV image recognition in retail stores
-->

---
layout: default
---
# Machine learning in 1980-1993

### 1980-1989  situation became better
- Expert system made some progress (e.g. medical diagnostic, tax services)
- Expert system = knowledge base + inference engine
- can it out-perform human? Yes and no

### 1989-1993  Second winter
- Expert system didn't achieve commercial success due to high cost
- Expert system requires heavy computing
- Computer was expensive at that time
- Hire a human expert cost way less money!

<!-- In artificial intelligence, an expert system is a computer system emulating the decision-making ability of a human expert. Expert systems are designed to solve complex problems by reasoning through bodies of knowledge, represented mainly as if–then rules rather than through conventional procedural code -->
---
layout: default
---
# No Deep learning? Not yet.

### 1993-2006  statistical machine learning
- learning from data instead of human knowledge

#### Symbolism: (like k-NN, decision tree, etc)
1. represents info through symbols and their relationships.
2. Specific algorithms are used to process these symbols to solve problem / deduce new knowledge
#### connectionism (like perceptron, Neural Network)
1. represents info in a distributed, less explicit form with a network
2. Biological processes underlying learning / problem solving

<!--- page break -->
---
layout: center
---

# Comparison
<img src="https://web.media.mit.edu/~minsky/papers/SymbolicVs.Connectionist_files/image012.png" width="800"/>

<!--- page break -->

---
layout: image-right
image: https://mozanunal.com/images/yoloroad.gif
---
## 2006-now Deep learning!

#### 2009 ImageNet: the largest labeled image database
- it focus on high quality training data rather than algorithm
#### 2012 AlexNet: the absolute winner in ImageNet Competition
- 10.8% less error rate than the runner up, which is a huge improvement
- this became a hot topic in computer vision community
#### 2014 DeepFace: 97.35% accuracy in face recognition by Facebook

<!--- page break -->

---
layout: default
---

# Since then, it become more and more data intensive

### 2020 GPT-3 A deep learning model to produce human-like text.
- It has 175 billion machine learning parameters
- It utilized all collectable human text on the internet to train itself
- Thanks to the rapid-growing computing power!

<br>

Let's play with it!
- **[GPT-3 Playground](https://beta.openai.com/playground)**


---
layout: center
---
# Well, GAN is even more interesting than GPT-3.


---
layout: iframe
url: https://creator.nightcafe.studio/
---

<!--- page break -->

---
layout: default
---
# Different deep-learning models
<img src="https://www.mathworks.com/discovery/reinforcement-learning/_jcr_content/mainParsys3/discoverysubsection/mainParsys/image.adapt.full.medium.png/1647932638418.png" width="700">

<!--
Supervised machine learning algorithms are able to apply what they have learned in the past to new data with the help of labeled examples. They do that to predict future events. Such algorithms begin with the analysis of the known training data set and then produce insights to make predictions about the output values. The system can provide targets for any new input after being exposed to sufficient training. The algorithm can also compare its results with the correct and intended output to find errors and modify the model accordingly.


Unsupervised machine learning algorithms are used when data fed to the algorithm is not labeled or classified in any way. Unsupervised learning is based on systems that analyze patterns in unlabeled data. The system doesn’t arrive at the output that can be just right or wrong, but rather it explores the data and draws inferences from data sets.

Reinforcement machine learning algorithms represent another type of learning method. This type of algorithm interacts with the environment by producing actions and then discovering errors or rewards. Delayed reward or trial and error searches are the key characteristics of reinforcement learning. The method allows machines to automatically determine the best behavior within a specific context to maximize their performance and get the best reward. They require to learn which actions work best – the so-called reinforcement signal. -->

---
layout: default
---
# Last but not least.. How can we use them in our life?
### Supervised learning: use labeled data to recognize/predict
- Classification problem: image recognition, face recognition
- Regression problem: House price prediction, lifespan prediction
### Unsupervised learning: use unlabeled data to recognize/predict
- Clustering problem: identify fake news, Spam filter
### Reinforcement learning: use data to make best decisions 
- self-driving cars, Hey Siri, Alpha Go, etc
<!--
Supervised machine learning algorithms are able to apply what they have learned in the past to new data with the help of labeled examples. They do that to predict future events. Such algorithms begin with the analysis of the known training data set and then produce insights to make predictions about the output values. The system can provide targets for any new input after being exposed to sufficient training. The algorithm can also compare its results with the correct and intended output to find errors and modify the model accordingly.


Unsupervised machine learning algorithms are used when data fed to the algorithm is not labeled or classified in any way. Unsupervised learning is based on systems that analyze patterns in unlabeled data. The system doesn’t arrive at the output that can be just right or wrong, but rather it explores the data and draws inferences from data sets.

Reinforcement machine learning algorithms represent another type of learning method. This type of algorithm interacts with the environment by producing actions and then discovering errors or rewards. Delayed reward or trial and error searches are the key characteristics of reinforcement learning. The method allows machines to automatically determine the best behavior within a specific context to maximize their performance and get the best reward. They require to learn which actions work best – the so-called reinforcement signal. -->

---
layout: end
class: text-center
---

# thanks! Any questions?
