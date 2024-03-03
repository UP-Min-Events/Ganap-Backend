# Ganap

An event management application. Under heavy development.

#### Tech Stack

-   Next.js
-   Tailwind CSS
-   AWS Cognito
-   AWS DynamoDB
-   Serverless Framework

## Getting Started

The following instructions will guide you on how to setup serverless framework on your machine.

### Setup AWS CLI

1. **Download and install the AWS CLI from [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)**
2. **Setup AWS Profile:**
    ```
    aws configure --profile ganap
    ```
3. **Enter the following details:**
    ```
    AWS Access Key
    AWS Secret Access Key
    ```
    - The details above will be provided by the project owner.
    - Input `ap-southeast-1` as the default region.
    - Leave the default output format as blank.

### Setup Serverless Framework

1. **Pre-requisite**
    - Ensure that you have Node.js version 20.x or later installed.
2. **Install Serverless Framework:**
    ```
    npm install -g serverless
    ```
3. **Install Serverless Plugins:**
    ```
    npm install
    ```
4. **Deploy the application:**
    ```
    sls deploy --stage 'dev' --aws-profile 'ganap' --verbose
    ```
