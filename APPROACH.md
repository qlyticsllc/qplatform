# APPROACH

Qlytics approach is to deliver the government a complete full-stack AI development platform that includes advanced security, reporting and operational monitoring. A self-healing, fault tolerant Machine and Deep Learning solution that is designed to streamline AI Development and deliver a structure, managed, secure operational model for operationalizing AI/Machine Learning.

![alt text](https://github.com/qlyticsllc/qplatform/blob/master/past-performance/images/Qlytics%20Platform%20Architecture.png)

# Q-AUTH
A single sign-on (SSO) and single log-out (SLO) microservice that provides user management and secure token-based access to Q-Platform microservices, applications, resources, BOTs and datasets. Q-Auth allows users to simply log-in once and use all applications and resources to which they have been granted access. Centralized role based permissioning and IAM (Identity and Access Management) provides granular controls of provisioning and deprovisioning of resources. Real-time reporting and advanced analytics ensures compliance with enterprise standards, SOC2, GDPR, HIPPA and others.

![alt text](https://github.com/qlyticsllc/qplatform/blob/master/past-performance/images/Auth.jpg)

# Q-GATEWAY
Q-Gateway is an end-to-end API Management microservice that leverages a custom REST Framework (DRF) for designing, implementing, securing, managing, monitoring, and publishing APIs. The Q-Gateway manages access of authenticated users to resources, to monitor and analyze traffic, to log and report on all transactions and to apply runtime policies to enforce governance like rate limiting, throttling and caching. The Q-Gateway securely connects authorized front-end API requests to backend Qlytics System.

# Q-MANAGER
An easy to navigate browser-based User Interface (UI) that provides secure role-based access, management and reporting of Q-Platform components and services. Q-Auth authenticated Users can leverage the Q-Manager’s UI to manage – Projects, Talent, Data, Subscriptions, Applications, BOTs, Cloud Resources, and AI development resources. The Q-Manager provides users the ability to take actions based on their Role, Subscriptions and provisioned services.

# AI TALENTHUB
A standalone microservice that links 5,000+ Qlytics certified AI Talent / Developers to the Q-Manager, enabling users to search for and invite talent to instantly and securely linked to an AI enablement projects being developed and deployed on the Q-Platform. Qlytics provides organizations the ability to create a Private AI Talent Hub and to add employees and contractors to a secure and searchable Local Talent database for talent management and project collaboration.

# TIMETRACKER
A secure browser-based client, the Qlytics TimeTracker is a component of the AI Talent Hub microservice that helps organizations manage and track developer and project team members work and productivity. A simple user interface enables users of the TimeTracker to select projects and tasks to work on. Screen capture preview and approval enables users to protect data and work. Leveraging a JIRA API, Qlytics TimeTracker enables organizations to assign and track activities in real-time. Integrated screen capture functionality provides compliance and oversight of work being done at a task level.

# DATA EXCHANGE
A standalone microservice that provides users the ability to programmatically search, access, subscribe to, and link to core, alternative or training datasets. The Q-Platform makes it easy for Organizations to create, manage, update and automatically publish subscription-based datasets that can be linked via API to systems, applications, or AI development projects. Authorized clients have the ability to manage user subscriptions, set and track API calls and with an integrated Payment Gateway quickly create, publish and even monetize data.

# Q-DEEP-NLP
Capable of replacing most human intensive document-based workflows, Q-Deep-NLP automatically preprocesses documents using a combination of Statistical and Deep-Learning approaches. Multiple engines featuring OCR and statistical segmentation are available for dealing with a wide range of formats, from scanned images to PDFs with complex tables. . Once pre-processed, the application converts the unstructured document to a database-like representation to enable further understanding and knowledge extraction using the DQL scripting capability.

# Q-DEEP-VISION
A powerful Deep-Learning based computer vision application that combines a convolutional neural network, a framework for supervised learning and a user friendly interface to deliver the ability to detect, track and report on objects and actions within images and videos. With over 80 pre-trained object detection datasets and an embedded Annotation tool (Q-Annotator) to create custom trained models, Q-Deep-Vision trains the Q-Platform to replace most human intensive image-based workflows.

# AI STARTER KITS
A set of four Dockerized functional tool kits each comprised of a standard set of 100+ python tools, open-source libraries, apps and frameworks. Automatically launched and accessed from the Q-Platform with two mouse clicks, the AI Starter kits have been scanned for potential viruses, possible nefarious code and potential compatibility issues. Additionally all open-source libraries are reviewed for any potential license compliance issues. Once scanned and reviewed the Starter Kits are packages to ensure security and compliance for clients and developers looking to leverage open-source tools.

# BOT STORE
A marketplace of API accessible machine and deep learning models, algorithms and bots. Available for use within Q-Apps or as API accessible algorithms the Bots store enables users to streamline the addition of AI driven features and functions to a project or workflow.
