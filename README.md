# Nest Example

Cyber-intrusions and cyber-attacks are a serious concern, and as the number of devices connected to the internet has exponentially increased, so have these threats. Many homes are being connected using products like Nest, and Alexa. For these devices, convenience has overshadowed the need for robust security and detection against intrusions. We can provide machine-learning powered security to complement the convenience of these devices, and keep the user and their data secure. 

Analysis on the traffic of a Nest device has been performed, and this insight can be used to train complex models for the purpose of detecting anomalies *before* they reach the device.

For further information, read my report on my jupyter notebook: analysis.ipynb

## Overview

- Observations regarding dataset
- Feature engineering of nest dataset
- Hypothesis of useful models for detecting anomalies
- Client-side and server-side traffic visualized
- Examples of baseline models
- How these models may be implemented with current product architecture

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

