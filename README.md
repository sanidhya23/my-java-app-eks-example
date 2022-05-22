# Application deployment Pipeline for my-java-app

Please follow the instructions to create the Jenkins job to run the pipeline:
- Create a new pipeline job
- <img width="1205" alt="image" src="https://user-images.githubusercontent.com/26666587/169715969-a0063ca0-90d5-408c-8734-ce780c9c485b.png">
- Specify the Jenkins file and Git repo
- <img width="573" alt="image" src="https://user-images.githubusercontent.com/26666587/169716055-1fdedf7b-c935-411b-8e43-72dfa430c147.png">
- Save and Apply the job

Please update the Cluster name, Region and Artifact URL 
- Edit the settings in ci-cd-files/Jenkinsfile
- Settings to be updated
-     environment {
        AWS_DEFAULT_REGION = 'ap-south-1'
        EKS_CLUSTER = 'cluster1'
        ...
    }


Run the Pipeline job to deploy the Application
- Click on build now and monitor the pipeline execution
- <img width="676" alt="image" src="https://user-images.githubusercontent.com/26666587/169716296-0b8bcab3-d5a7-4204-9dbc-72e6f168f101.png">
- On successful build, access the application by the URL http://sanidhya.link:8080/


Application Architecture:
![app-architecture](https://user-images.githubusercontent.com/26666587/169717065-ad5160b2-e947-4f75-a0da-6a2b9220d997.jpg)
