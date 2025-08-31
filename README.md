# GCP_Cloud_Pub_Sub_Real_Time_Streaming_Project
This repo contains details about implementation of the real time streaming using GCP Cloud Pub/Sub Service leveraging sample datasets and using Python code. Thanks

**Project Details:**

1. In this project, I have worked on creating a sample datasets to get experience with GCP Pub/Sub functionality and work on how data flows in real time manner
2. Once GCP Project is ready, proper permissions needs to be provided to the service account leveraging in the project
3. Make sure you install Gcloud CLI and linked your GCP project from local machine
4. Before running GCP Pub code, make sure to install required Python packages
5. Once a topic is created in the UI, run the Producer code and try to pull the messages to see producer code is working as expected
6. Once producer code is working as expected, Prepare a new topic and update the topic in both pub/sub python code and run the code parallely and see how data is consuming
7. If needed, to chekc the Balancing of the data in the consumers, please run consumer code in another terminal parallely to see how GCP Sub handles parallelism i..e we are running same code with another instances but for same topic  - Verify that ACK IDs are completely different. you can repeat to run multiple instances of the consumer code
8. Once data is pulled, Please do check the monitoring tab in the Pub/Sub UI to make sure data flow is accurate and check to see for any errors
9. GCP Service Account roles needed: Storage Admin, Pub/Sub Subscriber,  Pub/Sub Publisher and Admin
10. Python Packages/Libraries: pip3 install google-cloud-pubsub, JSON, random, time
    
