# Python-Code-Generation-with-Amazon-Bedrock-and-SageMakerAI
Automating Python Code Generation with Amazon Bedrock's Claude Model using SagemakerAI

As a Machine Learning Engineer at Valtara, you are tasked with automating code generation using AI models. You will leverage Amazon Bedrock's Claude model to generate Python code for analyzing sales data from a CSV file. The goal is to create a system that automates code generation, ensuring the generated code is syntactically correct, optimized, and functional, reducing manual coding efforts and improving efficiency in developing data analysis scripts.

Amazon Bedrock In SDLC

<img width="813" alt="Screenshot 2025-01-11 at 17 00 40" src="https://github.com/user-attachments/assets/ff1b398c-c18d-47df-8787-ebc079651b07" />



# Activity Guide: Automating Python Code Generation with Amazon Bedrock's Claude Model Using SageMaker

1. Set Up Prerequisites
AWS Account:
Ensure you have an active AWS account with access to Amazon SageMaker and Bedrock services.
- Enable Foundation Model:
Deploy the Anthropic Claude v2 model in the same region where SageMaker Studio is set up (e.g., us-west-2).
- Install Required Tools:
Familiarize yourself with basic Linux commands such as unzip, cp, ls, and vi.
Follow the guide to set up a Jupyter Notebook environment in SageMaker Studio.

2. Clone the GitHub Repository

- Access SageMaker Studio:
Open SageMaker Studio and launch a terminal.
- Clone the Repository:
Run the following command to clone the stated GitHub repository within the lab:
- Navigate to the Folder:
Enter the cloned directory for further setup.

3. Execute Code for Bedrock Model Integration

- Open the Jupyter Notebook:
Open the relevant .ipynb file in SageMaker Studio.
- Run Cells:
Sequentially execute the cells in the notebook:
Configure Bedrock client using boto3.
Define a prompt to generate Python code for analyzing a sales dataset.
Invoke the Claude model to process the prompt and generate Python code.
Validate the generated code and run analysis tasks such as calculating revenue or visualizing sales.

4. Test the Generated Python Code
- Prepare Sample Data:
Create a CSV file named sales.csv containing sales data for testing (e.g., product, revenue, and monthly sales).
- Analyze Results:
Use the generated Python code to perform operations such as:
Calculating total revenue.
Identifying the product with the highest revenue.
Visualizing sales trends using bar charts.

5. Clean Up Resources
- Delete Jupyter Space:
Stop and delete the Jupyter notebook instance in SageMaker Studio.
Remove associated domain users and delete the SageMaker domain.
- Delete S3 Bucket:
Locate and delete the S3 bucket created for storing datasets and results.
Verify Resource Deletion:
Ensure all resources have been deleted to avoid incurring unnecessary costs.

7. Troubleshooting Common Issues
- Error: AccessDeniedException:
Ensure the Claude Foundation Model is deployed in the correct region.
- Data Transfer or API Errors:
Confirm proper IAM roles and permissions for Bedrock and SageMaker services.
