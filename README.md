# QuestionAnsweringBot
Build a powerful question answering bot with Amazon SageMaker, Amazon OpenSearch Service, Streamlit, and LangChain

# Source: AWS Blog: 
https://aws.amazon.com/blogs/machine-learning/build-a-powerful-question-answering-bot-with-amazon-sagemaker-amazon-opensearch-service-streamlit-and-langchain/

# Details:
## Prerequisite: 
The solution uses one instance each of ml.g5.12xlarge and ml.g5.24xlarge for SageMaker endpoint ; you can check the availability of these instances in your AWS account and request these instances as needed via a Sevice Quota increase.
<img width="772" alt="image" src="https://github.com/ConstantSun/QuestionAnsweringBot/assets/26327367/fd02e7fa-b829-4d26-b749-0c8a4d73c8f5">

## Solutions Architecture: 
<img width="710" alt="image" src="https://github.com/ConstantSun/QuestionAnsweringBot/assets/26327367/be8bf42c-32b5-4499-9c1a-b8c2a2d6be4a">

## How to run:
Choose your right Cloudformation region and deploy:
AWS Region 	Link


us-east-1   [Link](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=llm-apps-blog-rag&templateURL=https://aws-blogs-artifacts-public.s3.amazonaws.com/artifacts/ML-14328/template.yml)


us-west-2 	[Link](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=llm-apps-blog-rag&templateURL=https://aws-blogs-artifacts-public.s3.amazonaws.com/artifacts/ML-14328/template.yml)


eu-west-1 	[Link](https://console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/new?stackName=llm-apps-blog-rag&templateURL=https://aws-blogs-artifacts-public.s3.amazonaws.com/artifacts/ML-14328/template.yml)


ap-northeast-1 	[Link](https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#/stacks/new?stackName=llm-apps-blog-rag&templateURL=https://aws-blogs-artifacts-public.s3.amazonaws.com/artifacts/ML-14328/template.yml)

Follow : "Ingest the data into OpenSearch Service" Section in the AWS Blog to continue.
