# North-90-Task-3

This repository contains two AWS Lambda functions:

1. **Add Two Numbers Lambda Function**: A simple Lambda function that adds two numbers and returns the result.
2. **Upload File to S3 Lambda Function**: A Lambda function that uploads a file to an S3 bucket.

This repository also contains two test files to run and test these functions:

1. **test-numbers.js**: Change the values of `number1` and `number2` to check the function. It contains the link to `add-numbers.js`.
2. **test-upload.js**: Change the `filename` and `fileContentBase64` according to the file you want to upload. It contains the link to `upload-file.js`.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- [AWS CLI](https://aws.amazon.com/cli/) installed and configured with your AWS credentials (for deploying Lambda functions).
- An active AWS account with permissions to create Lambda functions and S3 buckets.
- [Visual Studio Code](https://code.visualstudio.com/) installed for code editing.

## Steps to Run the Lambda Functions Locally in VS Code

1. Open the terminal in the folder where the files are located.

2. To test the **Add Two Numbers Lambda Function**, run the following command:

   ```bash
   node test-numbers.js
3. To test the **Upload File to S3 Lambda Function**, run the following command:

   ```bash
   node test-upload.js
