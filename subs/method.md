<a name=top>

[<img width=100% src="../pictures/head.png?raw=yes">](../README.md) 
&nbsp;&nbsp;&nbsp;[HOME](../README.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[ABSTRACT](aim.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[METHODS](method.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[CITATION](cite.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[DEMO](demo.md#top) &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp;[CONTACT-US](contact.md#top) &nbsp;&nbsp;&nbsp;

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


<!-- 01/10/2021 &nbsp;&nbsp;&nbsp;|
&nbsp;&nbsp;&nbsp; This is the very beginning of the [hil-se](https://github.com/hil-se/hil-se/blob/main/README.md) lab. Hooray! -->
