Qlytics is a full-stack integrated AI Development Platform that integrated all of governments identified components as well as many more none defined with the RFI. Currently the Platform incorporates the following:

## Programming Languages

The Qlytics Platform is a secure python based solution deployed in a clients VPC using CloudFormation. The details of which are provided (https://github.com/qlyticsllc/platform-deployment). The Deployment leverages three EC2 instances that include a fronet-end server (Angular), Back-End Server (Django + Micro-services) and a Database Server. Additional instances are deployed through the platform using AMIs and Docker Containers

## Microservices and Containerized Services Platforms

The Qlytics Platform uses a Django framework to manage its microservices based architecture. AI Applications and AI Starter Kits are deployed using AMIs and Docker Containers.

## Message Streaming

Platform Message uses Amazon SQS and SNS, Django, sendgrid and Slack for message Streaming. 

## CI/CD Pipeline Automation

The Qlytics platform uses Ansible for environment provisioning and application deployment in a Continuous Integration/Continuous Delivery (CI/CD) process using a Jenkins Pipeline.

## AI/ML platforms and integration

The Qlytics Platform comes with a set of AMIs and Docker Containers that are auto deployed and launch Qlytics AI Apps and Starter Kits. Using Django Central Autehnication Services these Apps and Tools integrat into the platform with Single Sign On (SSO) and as custom Workflow management service within the Platform. 

The Qlytics Platform integrates EC2, ECS, EMR, S3, ECR, RDS, CloudFormation, CloudWatch, and AMI management into the only full-stack AI Development Platform.

## The Platform's current technical stack includes but is in no way limited to the following:

Postgres Database
Ansible
Jenkins
H20
Docker
Elasticsearch
Git
Jira
Keras
Maven
PostgreSQL
Apache Airflow
ReactJS / AngularJS / VueJS	Javascript Frameworks
Selenium
Spark
Scala
Hadoop

## Frameworks integrated into the Qlytics Platform include

TensorFlow
PyTorch
Caffe
Theano
Scikit-learn
Keras

## AI Tools and Frameworks delivered from the Qlytics platform incorporate more than 500 pre-scanned Open-Source Tools and Libraries.

For details on how the platform and the integrated applications work together to deliver a AI/ML driven workflow please review the platforms user guide and technical guide available at https://qlytics-demo.readthedocs-hosted.com/en/latest/index.html



