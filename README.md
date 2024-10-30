# HHA504_assignment_nosql_dbs
The objective of this assignment is to be introduce to managed database services in Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor database-related services, including BigQuery and MySQL.

## Fake dataset to use: 
- data set url: [https://raw.githubusercontent.com/hantswilliams/HHA-504-2024/refs/heads/main/other/module8/module8_nosql_hw.csv](https://raw.githubusercontent.com/hantswilliams/HHA-504-2024/refs/heads/main/other/module8/module8_nosql_hw.csv)

```csv
PatientID,Name,Age,Gender,DiagnosisCode,VisitDate,Hospital,TreatmentPlan,FollowUpDate
1,John Doe,45,M,M54.5,2024-09-10,Stony Brook Hospital,Physical Therapy,2024-09-20
2,Jane Smith,29,F,E11.9,2024-08-15,Stony Brook Hospital,Insulin,2024-09-15
3,Bob Johnson,65,M,I10,2024-10-01,Long Island Clinic,Hypertension Medication,2024-11-01
4,Alice Williams,50,F,J45.909,2024-07-22,Southampton Hospital,Bronchodilators,2024-08-22
5,Michael Brown,37,M,G43.909,2024-06-12,Stony Brook Hospital,Triptans,
6,Susan Davis,54,F,I25.10,2024-05-10,Stony Brook Hospital,Statins,2024-06-10
```

- Dataset Explanation
  - *PatientID*: Unique identifier for each patient (integer).
  - *Name*: Patient's full name (string).
  - *Age*: Age of the patient (integer).
  - *Gender*: Gender of the patient (string: M or F).
  - *DiagnosisCode*: ICD-10 code representing the patient’s diagnosis (string).
  - *VisitDate*: Date of the hospital visit (YYYY-MM-DD format).
  - *Hospital*: Name of the hospital or clinic where the visit took place (string).
  - *TreatmentPlan*: The prescribed treatment plan for the patient (string).
  - *FollowUpDate*: Date for a follow-up visit, if applicable (YYYY-MM-DD format).

### 1. Start and Configure Databases
- **Google BigQuery (GCP):**
![dataset_table](https://github.com/user-attachments/assets/7b605b89-991b-4890-9522-1b106a91bcb3)
- **MongoDB Atlas (Cloud):**
![mongoDB_atlas](https://github.com/user-attachments/assets/02b969a5-b49c-43a9-b688-20009bba9221)
### 2. Explore BigQuery (GCP)
- **BigQuery:**
![BigQuery_explore](https://github.com/user-attachments/assets/25fecf77-ad69-42ba-8830-d25101a3828a)
### 3. Modify and Explore the Data in MongoDB Atlas and Redis Cloud
- **MongoDB Atlas**:
  Key features include: A multi-cloud deployment which allows databases from AWS, Azure, and google cloud.
  Automated Operations which allows for high performance and availabity. Consist of a Unified Query API which can work with different types of data structures. Their integrated data services include full-text search, real time analytics, and data visualization. Lastly they have a robust security measure which include an end to end encryption.
  Their interface is very user-friendly with Atlas UI. Their key features include data explorer which allows managing of databases and collection of documents at ease. In addition they have aggregation pipline builder which can create and run aggretation piplines to process and analyze data. Lastly, they have real time analytics and visualization which build charts for better view of the dataset. 
- **Redis Cloud**:
  Key features include: Fully managed service which include scaling, backups, and maintenance. Offer high availability and have multicloud flexability which enables multicloud deployments provigind a unifed data layer. Lastly it has advacned data capabilities which includes features like auto tiering and advanced query and search capabilities to simplify the tech stack.
  The interface include a dashbaord overview which provides a view of the database and displau metrics and health indicators. They enable easy database management which include configuration and scaling of databases. In addition they offer real-time performance monitoring that includes metrics to help identify potential issues quickly. Lastly, it allows management of user roles and permission so that the database is more secure. 
### 4. Describe Your Experience
After using all three cloud platforms there are many positives and negatives to all three of them. For Redis cloud, it offers streamline interface deployment and provides minimal database creation, scaling, and monitoring tools. They are best used for developers to build real time, high performance application and data storage. For google cloud, it is a more general cloud platform as it offers services other then databases so finding the database is a bit harder compared to the other two cloud platforms. Lastly, MongoDS Atlis, is easy for familiarizing with nosql database as it provides a graphic user interface and allows for quick creation and management of clusters, collections, and queries. Overall, I believe that all three platforms are pretty user friendly. 
