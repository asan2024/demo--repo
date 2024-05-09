# Demo
Some description!

Jose Manuel Troya
:headphones:  hace < 1 minuto
# InfluxDB Deployment Automation
This repository contains files and scripts for automating the deployment of InfluxDB, a time-series database, across different environments. The resources available help simplify the configuration, installation, and maintenance of InfluxDB.
## Repository Contents
- **Dockerfiles**: Scripts to build Docker containers for InfluxDB.
- **Configurations**: Example and template configuration files for various usage scenarios.
- **Automation Scripts**: Tools and scripts to automate the deployment and management of InfluxDB.
## Prerequisites
Before proceeding with installation and configuration, ensure that you have installed:
- Docker (for container-based deployments)
- Git (for repository cloning)
## Installation
To utilize the resources in this repository, follow these steps to run locally:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/influxdb-deployment.git
   cd influxdb-deployment
2. **Execute the influxdb container:**
   ```bash
   sh run-local.sh
3. **Verify connection**
   ```bash
   curl -G 'http://myuser:password@localhost:8086/query' --data-urlencode "db=mydatabase" --data-urlencode "q=SELECT * FROM my_measurement"


## LOcal development
1.Open index.html in you browser1