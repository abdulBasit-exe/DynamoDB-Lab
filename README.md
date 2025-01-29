# DynamoDB Lab - Data Engineering on AWS

This repository contains my work from the **"Introduction to Data Engineering on AWS: Data Sourcing and Storage"** course. In this lab, I practiced interacting with **AWS DynamoDB** using Python and **boto3**. I used **Google Colab** for coding and performing operations on DynamoDB tables.

### **Lab Overview**

The lab focuses on performing basic operations on **DynamoDB** including:

- **Creating a Table** in DynamoDB
- **Loading Data** into DynamoDB both manually and using a JSON file
- **Querying Data** from DynamoDB
- **Deleting a Table** from DynamoDB

### **Files Included:**
1. **CreateTable.ipynb**  
   This notebook contains the code to **create a DynamoDB table**. The table has the schema:  
![Screenshot from 2025-01-29 13-23-41](https://github.com/user-attachments/assets/f9366395-b11f-4bc3-9e8e-ab22e90f617f)

2. **LoadData.ipynb**  
   This notebook contains the code to **load data** into the DynamoDB table.  
   - Data is loaded both manually using a DataFrame and through a JSON file.
   - ![Screenshot from 2025-01-29 14-59-25](https://github.com/user-attachments/assets/fc6b83aa-3cd5-462e-933c-5022db50d2c2)

   -![Screenshot from 2025-01-29 14-34-31](https://github.com/user-attachments/assets/cad327ca-2980-48ab-a201-cf2c0a304dea)

3. **QueryData.ipynb**  
   This notebook contains the code to **query data** from the DynamoDB table.
![Screenshot from 2025-01-29 14-58-39](https://github.com/user-attachments/assets/9c8957ec-f42c-4462-87b9-36f7c81ba7f8)

4. **DeleteTable.ipynb**  
   This notebook contains the code to **delete the DynamoDB table**.
![Screenshot from 2025-01-29 13-25-16](https://github.com/user-attachments/assets/2d081eb6-3378-4272-9256-3c11b07d0412)


### **Tools and Technologies:**
- **AWS DynamoDB**  
- **boto3** (AWS SDK for Python)
- **Google Colab** (for coding and running Python)
- **IAM User** (for authentication with AWS DynamoDB)

### **Steps Performed:**
- Created a **DynamoDB table** with the required schema.
- Loaded data into the table using **Pandas DataFrame** and a **JSON file**.
- Queried the table to retrieve data based on the schema.
- Deleted the table after completing the operations.

### **Authentication:**
To interact with AWS DynamoDB, I created an **IAM user** with appropriate permissions and used the user’s **Access Key ID** and **Secret Access Key** for authentication. These credentials were set up using environment variables.


### **Important Notes:**
- **Security Warning:** Make sure to **remove your credentials** from the code before pushing it to any public repository.
- **Dependencies:** Ensure that `boto3` is installed in your environment:
  ```bash
  pip install boto3
