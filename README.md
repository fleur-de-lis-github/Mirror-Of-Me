# Mirror Of Me
## Problem Scenario
Personality of a person encircles every aspect of life. It
describes the pattern of thinking, feeling and characteristics
that predict and describe an individual’s behaviour and also
influences daily life activities including emotions, preference,
motives and health .
The increasing use of Social Networking Sites, such as
Twitter and Facebook have propelled the online community to
share ideas, sentiments, opinions, and emotions with each
other; reflecting their attitude, behaviour and personality.
Obviously, a solid connection exists between individual’s
temperament and the behaviour they show on social networks
in the form of comments or tweets [2].
Nowadays personality recognition from social networking
sites has attracted the attention of researchers for developing
automatic personality recognition systems.

## Our Approach
![alt](https://i.gifer.com/Gi1m.gif)
However, the
major issue associated with the aforementioned studies is the
skewness of the datasets, i.e. presence of imbalanced classes
with respect to different personality traits. This issue mainly
contributes to the performance degradation of personality
recognition system.
To address the aforementioned issue different techniques
are available for minimizing the skewness of the dataset, like
Over-sampling, Under-sampling and hybrid-sampling [9].
Such techniques, when applied on the imbalanced datasets in
different domain, have shown promising performance in terms
of improved accuracy, recall, precision, and F1-score
## Potential Client
## Tools Used
We also utilize the Natural Language Toolkit (NLTK) library for much of our text preprocessing, Numpy
for matrix computations, sk-learn for conventional learning
algorithms, and PyTorch for deep learning.
## Data Description
![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+)We obtained our data from the (MBTI) Myers-Briggs Personality Type Dataset from Kaggle. It provides the text of the 45-50 most recent social media posts for 8,600 users along with the user’s MBTI personality type. 

>This gives us 422,845 total labeled points in the form (post text, MBTI type). The posts are drawn from the PersonalityCafe online forum, a platform for all kinds of >conversations and discussions, and they obtain the labels by allowing the user to input MBTI type as account info. Data in this dataset was collected from an Internet forum and >after analysing the content of the dataset. 

![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+)Non-uniform representation of MBTI types in the dataset that is not commensurate with the actual proportions of MBTI types in the general population was the most important reason for this. 

>It was determined that this is because the data was collected from an Internet forum created for discussion about personality type and MBTI types were repeated too many times in >the posts. This may also affect the accuracy of the model. As a result, NLTK was used to remove the MBTI types from the dataset.
## Citation
- https://ieeexplore.ieee.org/document/9578983
- https://www.researchgate.net/publication/314100144_Social_media_user_personality_classification_using_computational_linguistic
- https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00459-1
