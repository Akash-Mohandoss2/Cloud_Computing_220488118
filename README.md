# Cloud_Computing_220488118
# ---------------------------->Performance evaluation of Terapixel rendering Cloud(Super) Computing<---------------------------

# ---------------------------------------------------->Description<----------------------------------------------------

1. This project performs Exploratory Data Analysis for the given datasets.
2. The programming language used is Python.
3. The code is executed in Jupyter Notebook.

# ---------------------------------------------------->Datasets required<----------------------------------------------------

1. application-checkpoints.csv -file contains application checkpoint events throughout the execution of the render job
2. gpu.csv-This file contains metrics that were output regarding the status of the GPU on the virtual machine.
3. task-x-y.csv -This file contains the x,y co-ordinates of which part the image was being rendered for each task.

# ---------------------------------------------------->Files Included<----------------------------------------------------

1. Abstract_Cloud Computing(CSC8634) -> Containing the overview of the report
2. Report_Cloud Computing (CSC8634) -> project report containing the brief Data analysis of the Datasets
3. Code_Cloud_Computing.ipynb -> jupyter notebook executable file containing data analysis code.
4. Code_Cloud_Computing.pdf -> PDF format of the executable code file

:
# ---------------------------------------------------->Step to be followed<----------------------------------------------------

1. Download the datasets from the university website link and place the file in an appropriate workplace in a folder.

2. Datasets downlink - 

https://newcastle-my.sharepoint.com/personal/nmf47_newcastle_ac_uk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnmf47%5Fnewcastle%5Fac%5Fuk%2FDocuments%2FTeraScope&ga=1

3. Open the file in the code workbook by inputting the correct path of the dataset files.

For instance,

My Dataset file paths - C:/Users/Akash/OneDrive/Desktop/Cloud Computing/application-checkpoints.csv
Then my code will be written as,

chk_pt=pd.read_csv('C:/Users/Akash/OneDrive/Desktop/Cloud Computing/application-checkpoints.csv')

4. Once the step3 is executed then Go to Cell->Run All.

5. The entire file gets executed and the outputs will be displayed below the respective cell where the code is being executed.
