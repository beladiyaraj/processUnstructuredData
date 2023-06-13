# Extracting Custom Entities from Documents with Amazon Textract and Amazon Comprehend

This repository provides code and resources to **extract custom entities** from documents using **Amazon Textract** and **Amazon Comprehend**.

## Overview

The project aims to demonstrate the integration of Amazon Textract and Amazon Comprehend for extracting custom entities from various types of documents. By combining the power of these services, it becomes possible to identify and extract *specific information* relevant to your use case.

## Requirements

- **AWS Account** with necessary permissions.
- **Python 3.x** installed.
- **Boto3** library installed.

## Usage

Follow these steps to extract custom entities from your documents:

1. **Set up AWS Services:** Start by setting up **Amazon Textract** and **Amazon Comprehend** services in your AWS account. Refer to the [blog post](https://aws.amazon.com/blogs/machine-learning/extracting-custom-entities-from-documents-with-amazon-textract-and-amazon-comprehend/) for detailed instructions.
2. **Clone the Repository:** Clone this repository to your local machine using `git clone`.
3. **Install Dependencies:** Install the required dependencies by running `pip install -r requirements.txt`.
4. **Configure AWS Credentials:** Configure your AWS credentials by either using the AWS CLI or setting environment variables.
5. **Update Configuration:** Open the Python script and update the necessary configurations, such as AWS region and bucket name.
6. **Run the Code:** Execute the Python script by running `python extract_entities.py`.
7. **Review the Results:** The extracted entities will be displayed in the console output.

## Contributing

Contributions are welcome! If you encounter issues or have suggestions, please open an issue or submit a pull request to the **GitHub repository**.
