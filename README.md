#Machine learning–based detection of cyber attacks in smart grid and SCADA network traffic.


## Problem Statement
Smart grid and SCADA networks rely on heterogeneous and resource-constrained
communication protocols such as MODBUS and DNP3. These protocols are often
vulnerable to cyber-attacks due to limited security mechanisms, which can
impact grid reliability and demand response programs.

Traditional rule-based security systems are insufficient to detect complex
and evolving attack patterns in cyber-physical systems.

## Objective
To design, implement, and evaluate machine learning and deep learning models
for detecting intrusions and anomalous behavior in smart grid and SCADA
network traffic.

## Approach
- Data preprocessing and feature engineering on real-world and benchmark datasets
- Supervised learning models: Random Forest, Decision Trees, Support Vector Machines
- Unsupervised learning models: k-means clustering
- Deep learning models: Feed-Forward Neural Networks, LSTM
- Comparative evaluation of models across multiple datasets and attack scenarios

## Datasets
- KDD Cup 99
- NSL-KDD
- MODBUS network traffic
- DNP3 network traffic
- Gas Pipeline dataset (Mississippi State University)

## Results
- Machine learning and deep learning models achieved improved detection
  performance compared to traditional baseline approaches
- LSTM models demonstrated strong capability in detecting sequential and
  time-dependent attack patterns
- Ensemble-based models provided robust performance across heterogeneous datasets

## Tech Stack
- Programming: Python
- ML/DL: Scikit-learn, TensorFlow / PyTorch
- Data Processing: Pandas, NumPy
- Environment: Linux, HPC environments

## Project Structure
data/        -> datasets  
src/         -> source code  
results/     -> experiment outputs  
assets/      -> figures and plots  

## Context
This project was developed as part of my PhD research in applied machine
learning and cybersecurity for cyber-physical systems (Smart Grid & SCADA).



## Reproducibility & Research Notes
- Experiments were conducted using publicly available and benchmark datasets
- Data preprocessing, feature extraction, and model training steps are documented
- Random seeds and model configurations are configurable for repeatability
- Results reported are based on multiple experimental runs

## How to Run
pip install -r requirements.txt  
python src/main.py  

## Research Context
This work was conducted as part of my PhD research in Computer Engineering,
focusing on applied machine learning for energy systems and cyber-physical
system security.

## Publications
Related work from this project has been published in peer-reviewed conferences
and journals in the areas of smart grids, cybersecurity, and applied machine learning.
Related peer-reviewed publications are listed in my CV.

## Skills Demonstrated
- Applied machine learning
- Cyber-physical system security
- Data preprocessing and feature engineering
- Experimental evaluation
- Reproducible research workflows

## Author
**Rajesh Manicavasagam**  
Machine Learning Engineer | PhD in Applied Machine Learning  
GitHub: https://github.com/rmanicav
