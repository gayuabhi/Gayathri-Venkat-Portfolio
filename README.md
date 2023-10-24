# Data Scientist

### Education
Masters of Science in Data Science, The University of Texas At Austin

### Work Experience
#### Data Scientist @ Tensor Data Scientists
- Key projects 
    - Customer segmentation model.
    - Recommendation systems.
    - Customer churn prediction.

#### Solutions Engineer  @ Sonline  LLC 

# Projects

###  [Ice Hockey Tournament](../blob/master/LICENSE)

In this project, I built a SuperTuxKart ice hockey agent based on supervised learning approach. In this game, our hocket agent plays against an AI agent with a game session of two minutes per round.  To win the game our agent have to score more goals than the opponent AI agent within two minutes. Explored two approaches: 1. Dagger based imitation learning; 2. Supervised learning approach based on vision and control. Final implementation was using the supervised learning approach because it gave better results compared to the Dagger method. I trained a deep network, with an average score 2-0 against the AI agent accorss different difficulty levels (Simple,Medium,Hard).
  
###  [Self Driving Go-Kart Racer](../blob/master/LICENSE) 

![](https://github.com/gayathri0905/gayathri-portfolio/blob/main/Images/go_kart_racer.gif)

In this project, I built a racer kart that uses computer vision to drive in different terrains. This game was developed in the SuperTuxKart game environment.  This kart uses ONLY the camera screen images as its input to predict its trajectory of motion. I developed a fully convolutional network using a encoder-decoder structure with  batch normalization to process the input image and predicted an 'aim point'. This aim point is value which had x and y co-ordinate of the kart position to which the kart was supposed to drive, inorder to complete the race. And, I also implemented a controller which handled the steering, acceleration, braking and drifting of the kart based  on the predicted aim point.  

[Question Answering System](../blob/master/LICENSE)

Developed an question answering model that answers  questions based  on passages from Wikipedia. This is my final project where I modified an existing neural question answering system and proposed an  improved model which was able to identify answers better than the baseline model. I was given three main  datasets:  SQuAD (Rajpurkar et al., 2016), NewsQA (Trischler et al., 2017), and BioASQ (Tsatsaronis et al.,2015) to work with. SQuAD asks questions about Wikipedia articles, NewsQA about news articles, and BioASQ about biomedical text.Furthermore, I also tested my model against the adversarial SQuAD data from Jia and Liang (2017). This data
adds sentences which look like the question but contain nonsense entities, and easily fool many pre-trained
SQuAD models. I implemeted a single model Bi-LSTM and trained it on the SQuAD dataset. The model showed between 5-6% improvement in performance on  both the SQuAD and Adversial SQuAD datasets. And, I did two minor changes to the baseline models:  1.Repositioning the attention  layers and 2. Fine tuning the hyperparameters.  






