# Explaining Demand Forecasts in Capacity Planning

This project implements a deep learning approach to forecast supply chain demand using Long Short-Term Memory (LSTM) networks. To ensure model transparency, the project applies Explainable AI (XAI) techniques: Integrated Gradients (IG) and DeepSHAP to interpret feature importance in time-series data. 

Ensure you have Python 3.8+ installed. You can install the required dependencies using pip: 

````bash
pip install torch captum scikit-learn matplotlib pandas numpy
````

Next, simply run all the cells in the notebook. Training the LSTM should only take roughly 30-60 minutes depending on your hardware. The last cells contain the code for the explainable methods and their plots.

Lastly, make sure the .csv file is inside the same folder as the Jupyter Notebook.
