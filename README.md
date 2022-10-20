# uninova-visualisation-and-reporting-engine

This repository contains the VesselAI Visualisation and Reporting Engine, which is based on the latest version of Apache Superset.

It is recommended that the VesselAI Visualisation and Reporting Engine is deployed on a Debian Linux distribution with Docker and Docker Compose installed. The Engine can also be deployed in a Kubernetes cluster, by converting the docker-compose file into a Kubernetes Pods deployment.

## Installation

1. Clone this repository.

2. Run the following line in an Linux Bash terminal:

    `docker-compose -f docker-compose-non-dev.yml up`


3. Wait until the `superset-init` container to exit with code 0;

4. Open the link <http://localhost:8088> on a browser;

5. Login as an Administrator (username: admin, password: admin);

6. For security purposes, create a new Administrator user, logout the default admin, login with the new one, and erase the default admin's account.

7. To change any Superset configuration varable, please update the `.env-non-dev` file. 

## User Guide

For a complete User Guide, please visit the following link: <https://superset.apache.org/docs/intro/>
