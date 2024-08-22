# Title - DiagnoseMe: Personal Health Decoder

Introduction: People frequently struggle to recognize their health problems rapidly and accurately in today's fast-paced society. This may delay receiving the right medical attention and, in some situations, result in inaccurate self-diagnosis. Furthermore, it can be challenging for people to distinguish reliable sources from the rest due to the overwhelming amount of health information that is readily available online, some of which may be inaccurate

# This project seeks to provide a Personal Health Decoder application in recognition of these difficulties. 

For anyone looking to comprehend their health symptoms and possible underlying illnesses, this tool will act as an accessible, user-friendly resource.

The project is divided to three modules:
1.	Data Pre-Processing
2.	Data Visualization
3.	Disease Prediction

1. Data Pre-Processing
Data Pre-Processing is performed on the dataset in order to verify, check and make sure there are no missing values, noisy data, or inconsistent data before it is fed into the algorithm. For this we are importing python libraries numpy, pandas as shown in Figure 1.1

![image](https://github.com/user-attachments/assets/5fb6d8e8-6031-4cf6-9c6f-68ead0829474)

 We upload our dataset from our local as shown in Figure 1.2

 ![image](https://github.com/user-attachments/assets/c1257b5c-c6f4-49ea-bef2-95add2849adf)

![image](https://github.com/user-attachments/assets/b375f7f9-c737-4b98-a7ea-f1a40dc30e71)

Using the method “drop” we are removing the unwanted columns from the dataset as shown in Figure 1.4

![image](https://github.com/user-attachments/assets/40b587de-fd0e-41ee-981e-bb0bd174758b)

Using the methods isnull() and sum(), we are finding if our dataset has any null values present as shown in Figure 1.5

![image](https://github.com/user-attachments/assets/9b188d23-bf16-4cf9-8c15-38710707b9d8)

To get some more information about our dataset, we use the “info()” function of pandas which displays various information about our data such as the column names, no. of non-null values in each column(feature), type of each column, memory usage, etc. as shown in Figure 1.6

![image](https://github.com/user-attachments/assets/957b9f16-f07c-4a88-aa74-3faf0f2c21db)

![image](https://github.com/user-attachments/assets/59975a96-0105-45c3-8e08-977bbe5c6ab2)

![image](https://github.com/user-attachments/assets/d43af73d-ed4f-4966-a33e-81a9f979ea2d)

![image](https://github.com/user-attachments/assets/4f012484-65c1-4d00-8247-40757cb1f957)

![image](https://github.com/user-attachments/assets/e120f44e-77a2-4b8a-82ed-1d23a70d90e4)

![image](https://github.com/user-attachments/assets/ce5e17d4-6339-4664-af01-9d717880c61b)

![image](https://github.com/user-attachments/assets/bf967c43-ac89-48d1-8b05-5700253b4cdd)

![image](https://github.com/user-attachments/assets/5b9c6eb6-2b75-4a2e-a0a0-c6c6798a7d10)

![image](https://github.com/user-attachments/assets/0f370612-7719-4011-909b-997e56512fd1)

![image](https://github.com/user-attachments/assets/f99fcb4e-ed5b-4765-ac07-e5e4195ec2cb)


![image](https://github.com/user-attachments/assets/2e97e306-adf2-4a44-91ee-4886adae2843)

DISCUSSION : 
Python is a well-known programming language for developing machine learning models, and it includes a variety of tools and frameworks for predicting mental health. The first stage in developing a mental health prediction model is data gathering and preparation. The dataset from the Kaggle website is used for this project. The dataset is imported and text preparation is performed using pandas, pyplot, and numpy. The preprocessed data is then visualised using text patterns. The dataset is then used to train and test a machine learning classifier for text classification. Each model's performance is assessed.
The trained and proven model can be used to make disease diagnosis for a person. I attempted to keep the programme as basic as possible so that it could be understood and used as a reference in the future. I did face some challenges at the beginning, but I learned a lot from this class that I could use to this project, which made it easier for me to move forward.
CONCLUSION : 
To summarise, creating an automated symptoms checker and diagnostic system with Python is a significant and valuable endeavour. With the advent of healthcare digitalization and a doctor scarcity in many locations, such a system can increase access and give preliminary support to patients.
However, developing an accurate system is difficult, necessitating a huge dataset of symptoms and illnesses as well as the use of techniques such as machine learning and natural language processing. To minimise potentially hazardous misdiagnoses, thorough testing and validation are required prior to implementation.
An automated symptoms checker, if intelligently built with medical practitioner involvement, can assist triage patients, identify those in need of urgent care, and decrease load on healthcare systems. It may also encourage patients to seek timely in-person therapy when necessary. Such preventive care and early intervention.

