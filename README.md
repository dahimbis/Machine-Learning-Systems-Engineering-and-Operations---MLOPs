# Machine Learning Systems Engineering and Operations (MLOps)
Building deployable, reliable, and scalable machine learning systems involves a lot more than just training a model.

## Topics Covered
- Challenges and basic principles of ML systems
- Large Data Systems
- Model Training at Scale -GPUs
- Continuous Monitoring and Tracing
- CI/CD (Continuous Integration/Continuous Delivery/Deployment)
- Safeguarding ML systems
- Cloud Computing
- DevOps
- AI Agents and Model Context Protocol (MCP)
- Data, Training, and Serving
- MFLOW VS AIRFLOW
- Use PostgreSQL to store core application state for users, images, comments, and flags.

## Cloud Computing Service Providers
- Chameleon
- Amazon Web Services (AWS)
- Google Cloud Computing
- Microsoft Azure
- Snowflake
- Oracle Cloud

## Main Cloud Computing Models
- **IaaS** - Infrastructure as a Service
- **CaaS** - Container as a Service
- **PaaS** - Platform as a Service
- **FaaS** - Function as a Service
- **SaaS** - Software as a Service
- **AaaS** - Anything as a Service

**Core Cloud Services:** Compute, Network, Databases, and Storage

## Tools & Technologies
- Jupyter Notebook
- Linux Terminal
- Docker
- Kubernetes
- Cloud Computing Platforms

## Key Skills & Lessons Learned
- Deploying a Kubernetes cluster on Chameleon instances
- Model Deployment and Life Cycle Management
- CI/CD Pipelines
- Experiment Tracking and Monitoring
- Containerization (Docker, Kubernetes installation)
- Cloud Platform Configuration
  - Network and Network Groups
  - Lease and Reservation
  - VM Instances Creation

## Core DevOps principles
- Version Control
- IaC/CaC - Infrastructure as Code/Configuration as Code
- CI/CD - Continuous Integration / Continuous Development
- Monitoring and Logging

We also have Code as an Infrastructure, as well as configuration as a service

## Data
Types of Data
- Structure
- Unstructured

## Acquiring training data
- Source training
- Legal and ethical obligations
- Matching Business Context
- Fairness and Bias

## Sources of Data
- Synthetic Data Source
- Internal source
- External source

* Use Redpanda, Redis, and Iceberg alongside PostgreSQL for real-time features and durable training data
* Train models incrementally with partial_fit and track exact data snapshots using Iceberg snapshot_id

## weekly labs
- Data
- Large Scale Training


## Large Model Training 
Backpropagation - neural networks use backpropagation as a computational graph with one input, one hidden unit, and no bias. Forward Pass and Backward Pass

## Training MLs at scale
- Test for training code
- Experiment tracking
- Scheduling and Resource Allocation
- Hyperparameter tuning
- Monitoring, faulty tolerance, and recovery
- Resource Sizing and Cost Control

## Test Types
- unit test
- failure mode tests
- Canary training tests

## What to track
Parameters (Hyperparameters) -> metrics, artifacts, intent

## Scheduling Jobs
- FIFO (First In First Out)
- Backfill scheduling
- Fairshare scheduling
- Prememption Scheduling
- Time-slicing scheduling
- Gange Scheduling




**Instructor:** Fund Fraida
