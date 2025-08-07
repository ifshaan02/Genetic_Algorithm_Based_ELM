Project Description: 

This project aims to find an accurate machine-learning model for calculating the air quality 
index. This project includes Linear Regression, Logistic Regression, Support Vector Regression, 
and Genetic-Algorithm based Extreme Learning Machine (GA-ELM). The system takes input 
from the user and provides RMSE-based performance comparisons. 


System Requirements: 
Anaconda Navigator (with Python 3) 
Jupyter Notebook 


Required Python Libraries: 
Numpy 
Pandas 
Scikit-learn 
Matplotlib 
Seaborn 
Tkinter 


Setup Instructions: 
Step 1: Open Anaconda Navigator 
1. Click on the Start Menu (Windows) or use Spotlight Search (Mac). 
2. Type “Anaconda Navigator” and open the application. 
3. Wait for the interface to load — it may take a few seconds. 


Step 2: Launch Jupyter Notebook 
1. In the Anaconda Navigator window, locate the “Jupyter Notebook” tile. 
2. Click the Launch button. 
3. A new browser window will automatically open, showing the Jupyter Notebook interface 
(usually at http://localhost:8888). 
Note: If it doesn’t open automatically, copy the link shown in the Anaconda Navigator terminal 
output and paste it into your browser.


Step 3: Open the Notebook File 
1. In the Jupyter file browser, navigate to the folder where you have saved your project files. 
Example path: Documents/Projects/AirQuality/ 
2. Look for the notebook file named AirQuality.ipynb. 
3. Click on the filename to open it. 
Note: This will open the notebook in a new tab where you can read, edit, and execute each code 
cell interactively.


Step 4: Verify the Dataset File 
1. Before running the notebook, ensure that the dataset file AirQualityUCI.csv is located in 
the same directory as the notebook. 
This is important because the notebook reads the data file using a relative path. 
2. If it is located elsewhere: 
Move the dataset into the notebook's folder. 
Or update the file path in the notebook code to reflect the correct location. 
Note: If the file is not found, you'll get a FileNotFoundError when the notebook tries to load the 
dataset. 

Step 5: Run the Notebook 
1. In the notebook tab, click on the first cell. 
2. Press Shift + Enter to execute it. 
3. Continue running each cell one by one using Shift + Enter. 
This will initialize variables, load the dataset, train models, and generate outputs. 
4. Some cells may prompt you to input or use default input data. 
5. When you run the final cell, the GUI window is popped up. Enter the input values. Later 
press the button “Calculate AQI” for the result.

 
7. Final outputs will include: 
o RMSE values for each algorithm (Linear, Logistic, SVM, GA-ELM) 
o Graph comparing the models 
Note: To run all cells at once: Go to the top menu → Click Cell → Select Run All.
