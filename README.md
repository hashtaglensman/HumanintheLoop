 <a name=top>

[<img width=100% src="pictures/head.png?raw=yes">](README.md) 
&nbsp;&nbsp;&nbsp;[HOME](#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[ABSTRACT](subs/aim.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[METHODS](subs/method.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[CITATION](subs/cite.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[DEMO](subs/demo.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[CONTACT-US](subs/contact.md#top) &nbsp;&nbsp;&nbsp;

<!-- [<img src="https://github.com/hil-se/hil-se/blob/main/img/collaborate.png?raw=yes">](https://www.vodafone-institut.de/aiandi/five-things-that-demonstrate-that-ai-and-human-collaboration-is-the-future/)  -->

## Abstract

Facial attribute classification algorithms frequently manifest demographic biases, disproportionately impacting specific gender and racial groups. Existing bias mitigation techniques often lack generalizability, require demographically annotated training sets, exhibit application-specific limitations, and entail a trade-off between fairness and classification accuracy. This trade-off implies that achieving fairness often results in diminished classification accuracy for the most proficient demographic sub-group. In this paper, we propose a continual learning framework designed to mitigate bias in facial attribute classification algorithms by integrating human-machine partnership, especially during the deployment stage. Our methodology harnesses the expertise of human annotators to label uncertain data samples, subsequently used to fine-tune a deep neural network over a time period. Through iterative refinement of the network's predictions with human guidance, we seek to enhance the accuracy and fairness of facial attribute classification. Extensive experimentation on gender and smile attribute classification tasks validates the efficacy of our approach, supported by empirical results from four datasets. The outcomes consistently demonstrate accuracy improvements and reduced bias across both classification tasks.
<!-- We believe that "human AND AI" is much more powerful than "human OR AI" ([some external evidence](https://www.theatlantic.com/sponsored/deloitte-consulting-2017/cognitive-collaboration-why-humans-and-computers-think-better-together/1196/)). 

The hil-se lab explores and provides machine learning solutions to assist humans in various software engineering tasks. These tasks include but are not limited to:
 - Retrieving relevant information.
 - Detecting and reducing ethical bias in human decisions.
 - Identifying certain software artifacts, e.g. security vulnerabilities, defects, tech debts, actionable static warnings.
 - Predicting for trace links between different software artifacts. -->
### Contribution


## Methods
### Gender Classification
| Method     | Acceptance | Accuracy | Standard deviation |
| ---        | ---       |  ---     | ---               |
| Shannon's Entropy   | `         |    s      |       d            |
| Dirichlet's Uncertainty Estimation       | \|        |          |                    |
| Boundary Proximity Confidence-based Outlier Detection   | `         |    s      |       d            |
| Ensemble-based Outlier Detection | \|        |          |                    |
| Multiview Disagreemen     | \|        |          |                    |

### Smile Attribute Classification


We discussed two methods in the paper
### Method 1:
For this method, we defined the uncertain data as the test data which was misclassified with high confidence score. To order to capture the definition, we proposed the following,
The data is called to be uncertain when,
#### the feature of the test data is equvidistant from the feature space of the training data and,
#### the high ratio of the confidence score,

### Method 2:
If there is a disagreement between two scores obtained from the main classifier model, and the combination of different pruned and quantized models, then the data is considered as uncertain.

### Method 3: 
Data points are considered as uncertain when it lies close to the decision boundary.


<!-- 08/25/2021 &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp; Two new PhD students [Monoshiz Mahbub Khan](https://github.com/hil-se/hil-se/blob/main/people/people.md#monoshiz-mahbub-khan) and [Xiaoyin Xi](https://github.com/hil-se/hil-se/blob/main/people/people.md#Xiaoyin-Xi) have joined the lab as graduate research assistants!
 
01/22/2021 &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp; A new Master of Data Science student [Nishant Nair](https://github.com/hil-se/hil-se/blob/main/people/people.md#nishant-nair) has joined the lab as a graduate assistant! -->


## Citation

## Demo


## Contact Us
### Anoop Krishnan

### Ajita Rattani
<!-- [<img align="left" width=100 src="https://github.com/hil-se/hil-se/blob/main/people/headshot/Monoshiz_Mahbub_Khan.jpg?raw=yes">](https://github.com/hil-se/hil-se/blob/main/people/people.md#monoshiz-mahbub-khan)
 
[<img width=100 src="https://github.com/hil-se/hil-se/blob/main/people/headshot/Xiaoyin Xi.jpg?raw=yes">](https://github.com/hil-se/hil-se/blob/main/people/people.md#Xiaoyin-Xi) -->
