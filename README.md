# Heart-disease-Prediction-using-Python

The code is an implementation of logistic regression for predicting heart disease. The first section of the code imports necessary libraries like numpy, pandas, matplotlib, seaborn, scikit-learn, etc. and reads the data into a pandas DataFrame. The dataset contains 14 features including age, sex, chest pain type, resting blood pressure, serum cholestoral, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise induced angina, ST depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels, thal, and target, which is whether or not the patient has heart disease.

The second section explores the data using visualizations and statistical analysis. The target variable is binary, with values 1 for patients with heart disease and 0 for patients without heart disease. The count of the target variable is plotted using seaborn countplot. Further, the percentage of patients having heart disease and not having heart disease are calculated and printed. The count of sex is plotted using seaborn countplot, and the percentage of female and male patients are calculated and printed. The data is grouped by the target variable and mean of each feature is calculated and printed. Further, the frequency of heart disease is plotted against age and sex, maximum heart rate is plotted against age, the frequency of heart disease is plotted against slope, FBS, and chest pain type.

The last section creates dummy variables for categorical features like 'cp', 'thal', and 'slope'. The dummy variables are concatenated with the original dataset. The head of the new dataset is printed to verify the changes.

![image](https://user-images.githubusercontent.com/130720035/235516512-49b008bb-6ea9-483a-84ae-f8215c2166d9.png)

![image](https://user-images.githubusercontent.com/130720035/235516547-c05c7661-eab7-4912-96b1-807fe50d0c99.png)

![image](https://user-images.githubusercontent.com/130720035/235516596-e02b4e0c-f756-4426-8ed8-750a3b28c8b8.png)

![image](https://user-images.githubusercontent.com/130720035/235516629-798bac69-0161-4f64-a289-c1fe5ba80faa.png)

![image](https://user-images.githubusercontent.com/130720035/235516666-05d8c963-ef52-4f71-8e24-e8b343dfaa93.png)

![image](https://user-images.githubusercontent.com/130720035/235516849-a5627f86-fbf2-406b-a5dd-aea980eb68af.png)

![image](https://user-images.githubusercontent.com/130720035/235516892-51ed8e00-3594-409f-ae21-39a7f61b4c42.png)

![image](https://user-images.githubusercontent.com/130720035/235516932-b94261a6-e52a-469e-9d25-87754704a62d.png)

![image](https://user-images.githubusercontent.com/130720035/235516994-beb437fd-c24b-4afe-baf2-af5c366effe5.png)

![image](https://user-images.githubusercontent.com/130720035/235517082-fb08dda0-dda7-46b1-9296-07518ba301c5.png)

![image](https://user-images.githubusercontent.com/130720035/235517139-45bc8c23-532f-49af-ae26-4ad939d7d573.png)

![image](https://user-images.githubusercontent.com/130720035/235517264-6f9a1212-a711-4dd9-84a8-628c3fd06c2d.png)

![image](https://user-images.githubusercontent.com/130720035/235517339-7b55d73b-d632-43ac-9347-98398bceeb09.png)

![image](https://user-images.githubusercontent.com/130720035/235517373-f4f03268-3b69-46f6-b713-4ede4ecdcff5.png)
