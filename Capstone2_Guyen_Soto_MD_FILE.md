DS Average Salary Analysis
===============================

Using 3 different data sources, I created a tool to help local job seekers or a company's HR specialist find the average salary by state and the possible causes of its variation. I focused the analysis on Florida, but it could be applied to any state to draw conclusions. Using a variety of exploratory Supervised Machine Learning techniques, I developed a model to solve this problem.


├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── raw       	 <- The original, immutable data dump.
│   │    └── .csv		1_glassdoor1.csv
│   │				2_900_DS_jobs_US_raw.csv
│   │				3_DataScientist.csv
│   ├── intermediate     <- Intermediate data that has been transformed.
│   │    └── .csv		result_numer.csv
│   │
│   └── processed        <- The final, canonical data sets for modeling.
│       └── .csv		numer_data_step3_features
│
├── docs               <- A default  project; see .org for details
│
├───┐          		<- Jupyter notebooks. Naming convention is a number (for ordering),
│   ├── Capstone2_2_GS.ipynb
│   ├── Capstone2_3_EDA.ipynb
│   ├── Capstone2_4.ipynb
│   └── Capstone2_5.ipynb 
│
├── references          <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports             <- Generated analysis as HTML, PDF, LaTeX, etc.
│   ├── Capstone2_DS Average Salary_Guyen_Soto.pdf
│   ├── Capstone2_DS Average Salary_Guyen_Soto.pptx 
│   └──	Capstone2_Guyen_Soto_Features.txt
│                      
└── requirements.txt   <- The requirements file for 
