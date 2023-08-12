# End-to-end-Machine-Learning-project-with-MLflow

MLFLOW_TRACKING_URI=https://dagshub.com/vicdamilola29/End-to-end-Machine-Learning-project-with-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=vicdamilola29 \
MLFLOW_TRACKING_PASSWORD=17a0b2db7ef643c79ecdbfe63a2d6fbe9509e56d \
python script.py


Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/vicdamilola29/End-to-end-Machine-Learning-project-with-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=vicdamilola29 

export MLFLOW_TRACKING_PASSWORD=617a0b2db7ef643c79ecdbfe63a2d6fbe9509e56d


143553203054.dkr.ecr.us-east-1.amazonaws.com/ml_wineproj

Open EC2 and Install docker in EC2 Machine:
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

Configure EC2 as self-hosted runner:
setting>actions>runner>new self hosted runner> choose os> then run command one by one

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = ml_wineproj

webapp - 54.159.230.14:8080