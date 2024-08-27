## AWS Amplify React+Vite Starter Template

This repository provides a starter template for creating applications using React+Vite and AWS Amplify, emphasizing easy setup for authentication, API, and database capabilities.

## Overview

This template equips you with a foundational React application integrated with AWS Amplify, streamlined for scalability and performance. It is ideal for developers looking to jumpstart their project with pre-configured AWS services like Cognito, AppSync, and DynamoDB.

## Features

- **Authentication**: Setup with Amazon Cognito for secure user authentication.
- **API**: Ready-to-use GraphQL endpoint with AWS AppSync.
- **Database**: Real-time database powered by Amazon DynamoDB.

## Deploying to AWS

For detailed instructions on deploying your application, refer to the [deployment section](https://docs.amplify.aws/react/start/quickstart/#deploy-a-fullstack-app-to-aws) of our documentation.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

amplify gen2の試行
https://docs.amplify.aws/react/start/quickstart/

作成されたIAMロール11個
TodoIAMRolecfd440-pbqje3xj7zhn7izkjblxoswpqq-NONE AWS のサービス: appsync  
amplify-d16rku8chyqko6-ma-AmplifyTableWaiterStateMa-5QzDpeCkuYGG AWS のサービス: states  
amplify-d16rku8chyqko6-ma-AmplifyManagedTableOnEven-VYCJ9Q4rhkeg AWS のサービス: lambda  
amplify-d16rku8chyqko6-ma-AmplifyManagedTableIsComp-SLmz8RRnWfbw AWS のサービス: lambda  
amplify-d16rku8chyqko6-ma-CustomS3AutoDeleteObjects-qbqqTaBklr8I AWS のサービス: lambda  
amplify-d16rku8chyqko6-ma-CustomCDKBucketDeployment-OwtrUd6BsWHA AWS のサービス: lambda  
amplify-d16rku8chyqko6-ma-amplifyAuthunauthenticate-BWUXhcADDWXe ID プロバイダー: cognito-identity.amazonaws.com  
amplify-d16rku8chyqko6-ma-amplifyAuthauthenticatedU-vIfSPpmivOXJ　ID プロバイダー: cognito-identity.amazonaws.com  
amplify-d16rku8chyqko6-ma-AmplifyBranchLinkerCustom-fVGDBca5cBL7 AWS のサービス: lambda  
amplify-d16rku8chyqko6-ma-AmplifyBranchLinkerCustom-3Yf5mE2d2wZ9　AWS のサービス: lambda  
AmplifySSRLoggingRole-9092be20-dcca-4312-ae81-8eb34ed360e5　AWS のサービス: amplify  

```
git clone https://github.com/amaya690221/amplify-vite-react-template.git
cd amplify-vite-react-template && npm install
アカウントは
amaya@bau-haus.com
古い通例大文字@
```
クラウドサンドボックスの作成
```
npx ampx sandbox
```
コマンドnpx ampx sandboxは と同時に実行されるはずですnpm run dev。クラウド サンドボックスは、「アプリ バックエンドの localhost に相当するもの」と考えることができます。

うーんとうまく動いていんのかどうなのか・・・