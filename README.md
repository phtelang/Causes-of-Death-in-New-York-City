## Causes of Death in New York City
In this project, I read the __[json data file](https://data.cityofnewyork.us/Health/New-York-City-Leading-Causes-of-Death/jb7j-dtam)__ which contains leading causes of death by sex and ethnicity in New York City in since 2007. This analysis can be used to understand the major causes of death and health practitioners can work on finding the root causes and advising people on how to prevent those diseases. Medical researchers can work on developing effective medicines or vaccinations. Year-wise trends can help to identify effects of particular medicine/vaccine it has had on the death rate. Race-wise deaths can lead to cultural patterns which might need changes.

I looked at the below questions:
1. Does the death count vary based on sex?
2. What are the major cause of deaths per sex?
3. What are the major causes of death race-wise?
4. What is the year-wise pattern of causes of death?
5. What are the major causes of death in young people?

### Summary of Results
1. There have been equal number of deaths from 2007 - 2016 (more than 25000 each year).
2. Most prominent causes of death are: Diseases of Heart, Malignant Neoplasms (Cancer). More number of deaths due to heart disease maybe due to improper lifestyle of junk food diet, lack of exercise and stress.
3. Assault, Parkinson's Disease are only affecting males.
4. Males have a higher chance of death due to :
    - Accidents Except Drug Poisoning,
    - Liver Disease and Cirrhosis,
    - HIV,
    - Intentional Self-Harm (Suicide),
    - Mental Disorders - Accidental Poisoning
5. Females have a higher chance of death due to :
   - Alzheimer's Disease,
    - Cerebrovascular Disease (Stroke),
    - Lower Respiratory Diseases,
    - Hypertension and Renal Diseases,
    - Influenza and Pneumonia,
    - Nephritis,
    - Septicemia
6. Causes of death vary for each race. For details, see information below.
7. Deaths due to Alzheimer's Disease, Cerebrovascular Disease, Liver Disease, Respiratory Diseases, Diabetes, Hypertension and Renal Diseases, Accidental Poisoning and Other Psychoactive Substance Use, Parkinson's Disease and Perinatal Conditions have increased over the years. More research on how to develop drugs to avoid or cure these diseases can be undertaken.
8. Deaths due to Assault, Congenital Malformations, HIV, Nephrotic Syndrome and Nephrisis, Viral Hepatitis have decreased over the years. This information can be useful to see if new drugs are effective in reducing the count.
9. Deaths from Alzheimer's disease, Hypertension and Renal Diseases have increased significantly from 2014-2017. Parkinson's disease has been the major cause of deaths in 2014-2017 bracket which did not cause death in earlier years. Urgent attention is needed for the cure of these diseases.
10. Across years, young Hispanic, Non-Hispanic Black and Asian males are dying due to diseases of heart.

To view the code and graphs accurately, please __[click on this link](https://nbviewer.jupyter.org/github/phtelang/Causes-of-Death-in-New-York-City/blob/master/Causes%20of%20Death%20in%20New%20York%20City.ipynb)__ as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the source JSON file on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
