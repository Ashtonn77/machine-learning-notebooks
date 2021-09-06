# Machine Learning
*A collection of study notes, notebooks, and resources*
<br/>
## What is Machine Learning?
  Oliver Theobald:
  <blockquote>
  Arthur Samuel introduces machine learning in his paper as a subfield of
  computer science that gives computers the ability to learn without being
  explicitly programmed. A key feature of machine learning is the concept of self-learning. This refers to the application of statistical modeling to detect           patterns and improve performance based on data and empirical information, all without direct programming commands.
  </blockquote>
  Machine learning algorithms find natural patterns in data that generate insight and help you make better decisions and predictions. They are used every day to make critical decisions in medical diagnosis, stock trading, energy load forecasting, and more. For example, media sites rely on machine learning to sift through millions of options to give you song or movie recommendations, retailers use it to gain insight into their customers’ purchasing behavior, etc.
  
## When Should You Use Machine Learning?
  <p>Consider using machine learning when you have a complex task or problem involving a large amount of data and lots of variables, but no existing formula or equation. For example, machine learning is a good option if you need to handle situations like these:</p>
<ol>
<li>Hand-written rules and equations are too complex—as in face recognition and speech recognition</li>
<li>The rules of a task are constantly changing—as in fraud detection from transaction records</li>
<li>The nature of the data keeps changing, and the program needs to adapt—as in automated trading, energy demand forecasting, and predicting shopping trends</li>  
</ol>

## How does it work?
  <p>Data is fed to the machine, an algorithm is selected, hyperparameters (settings) are configured and adjusted, and the machine is instructed to conduct its analysis. The machine proceeds to decipher patterns found in the data through the process of trial and error. The machine’s data model, formed from analyzing data patterns, can then be used to predict future values.</p>
  <p>The machine formulates decisions based on experience and mimicks the process of human-based decision-making.</p>

## Training and Testing
<p>In machine learning, data is split into training data and test data. The first split of data, i.e. the initial reserve of data you use to develop your model, provides the training data.</p>
<p>After you have successfully developed a model based on the training data and are satisfied with its accuracy, you can then test the model on the remaining data, known as the test data. Once you are satisfied with the results of both the training data and test data, the machine learning model is ready.</p>

## The three overarching categories of machine learning:
   1. Supervised Learning
   2. Unsupervised Learning
   3. Reinforcement Learning

<p><i>What are labels and features?</i></p>
  <span>feature is input & label is output</span>
<ul>
<li>feature: one column of the data in your input set. For instance, if you're trying to identify an object, your input features might include age, home region, family income, etc.</li>
  <li>labels: the final choice, such as dog, fish, iguana, rock, etc.</li>
</ul>

### Supervised Learning
  As the first branch of machine learning, supervised learning concentrates on learning patterns through connecting the relationship between variables and known outcomes and working with labeled datasets. Supervised learning works by feeding the machine sample data with various features (represented as “X”) and the correct value output of the data(represented as “y”). The fact that the output and feature values are known qualifies the dataset as “labeled.” The algorithm then deciphers patterns that exist in the data and creates a model that can reproduce the same underlying rules with new data.
  
### Unsupervised Learning
  In the case of unsupervised learning, not all variables and data patterns are classified. Instead, the machine must uncover hidden patterns and create labels through the use of unsupervised learning algorithms. Unsupervised learning algorithms typically group together data points that are found to possess similar features.
   
### Reinforcement Learning
  Reinforcement learning is the third and most advanced algorithm category among the three previously mentioned. Unlike supervised and unsupervised learning, reinforcement learning continuously improves its model by leveraging feedback from previous iterations. This is different to supervised and unsupervised learning, which both reach an indefinite endpoint after a model is formulated from the training and test data segments.
