# Building-and-Deploying-Model-on-Amazon-SageMaker
Here, you'll find a  Jupyter Notebook files (.ipynb) showcasing the end-to-end process of creating and deploying machine learning models using Amazon SageMaker. From data preprocessing and model training to deployment configuration and endpoint creation, each notebook provides step-by-step guidance and code examples to help you leverage the power of SageMaker for your own projects. Whether you're new to SageMaker or looking to enhance your deployment skills, these notebooks offer practical insights and hands-on experience in building scalable and production-ready machine learning solutions on AWS.
Credits: Analytics Vidya

Steps Followed :
1. Prepare Your Model:
Train your machine learning model using a supported framework (e.g., TensorFlow, PyTorch, scikit-learn) and save the trained model artifacts.
2. Prepare Your Data:
Ensure your input data is in a suitable format for inference and preprocess it if necessary.
3. Upload Model Artifacts to Amazon S3:
Upload your trained model artifacts (e.g., model files, scripts, dependencies) to an Amazon S3 bucket.
4.Create a SageMaker Model:
In the SageMaker console, navigate to the "Models" section and click "Create model."
Provide a name for your model and specify the location of your model artifacts in Amazon S3.
5.Create an Endpoint Configuration:
In the SageMaker console, navigate to the "Endpoint configurations" section and click "Create endpoint configuration."
Configure settings such as instance type, instance count, and model variant for your deployment endpoint.
6.Deploy the Model:
Navigate to the "Endpoints" section in the SageMaker console and click "Create endpoint."
Choose the endpoint configuration you created in the previous step.
Specify a name for your endpoint and select the VPC (Virtual Private Cloud) settings if required.
Review the configuration and click "Create endpoint" to deploy your model.
7.Test the Endpoint:
Once the deployment is complete, you can test the endpoint by sending sample requests to it.
Use the SageMaker SDK or AWS CLI to invoke the endpoint with input data and observe the output predictions.
8. Monitor and Manage the Endpoint:
Monitor the endpoint's performance, latency, and usage metrics using Amazon CloudWatch and SageMaker's built-in monitoring capabilities.
You can update the endpoint configuration, deploy new model versions, or delete the endpoint as needed to maintain and manage your deployment.
