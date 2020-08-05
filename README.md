[![Folasade](https://circleci.com/gh/Folasade/Machine-Learning-Microservice-API/tree/new_branch.svg?style=svg)](https://circleci.com/gh/Folasade/Machine-Learning-Microservice-API/tree/new_branch)

## Project Overview
**Operationalize a Machine Learning Microservice API**
Operationalizing a Python flask app, app.py. This serves out predictions(inference) about housing prices through API calls


### Project Tasks

The goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications.

* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested

---

## Setup the Environment

* A virtualenv was created and activated
* `make install` was run to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Docker setup and configured locally
* Kubernetes setup and configured locally
* Flask app created in Container
* Run via kubectl
