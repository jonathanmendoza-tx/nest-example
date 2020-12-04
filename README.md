# Nest Example

Cyber-intrusions and cyber-attacks are a serious concern, and as the number of devices connected to the internet has exponentially increased, so have these threats. Many homes are being connected using products like Nest, and Alexa. For these devices, convenience has overshadowed the need for robust security and detection against intrusions. We can provide machine-learning powered security to complement the convenience of these devices, and keep the user and their data secure. 

I have performed a short analysis on the traffic of a Nest device, and this insight can be used to train more complex models for the purpose of detecting anomalies *before* they reach the device.

For further information, read my report on [jupyter notebook](https://github.com/jonathanmendoza-tx/nest-example/blob/master/analysis.ipynb)

## Overview

- Observations regarding dataset
    - Features to engineer, features I'd like to see captured
- Feature engineering of nest dataset
    - Create features based on observations
- Hypothesis of useful models for detecting anomalies
    - Supervised and unsupervised models
        - Neural networks
        - Decision trees
        - Time-series analysis
        - Facebook prophet
- Client-side and server-side traffic visualized
    - Shows all traffic broken down by client-side and server-side traffic
- Examples of baseline models
    - Using clustering and decision trees for an easy baseline
- How these models may be implemented with current product architecture
    - More training data
    - Validating efficacy of models
    - Capturing all traffic in real-time and routing it to a server where the model can analyze it

### Tech Stack

- Pandas
- Sklearn
- Matplotlib

### Models

Used IsolationForest and LocalOutlierFactor from sklearn to detect potential anomalies

### Data Sources

Nest dataset

### Feature Requests

I would love to hear from you about new features which would improve this analysis and further the aims of the project. Please provide as much detail and information as possible to show why you think your new feature should be implemented.

