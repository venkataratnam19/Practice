# Practice
This repository is for deploying an single index.html file as docker image.

Step1: Clone this repo(https://github.com/venkataratnam19/index.html-docker.git/)

Step2: cd index.html-docker folder.

Step3: Build the Docker Image using the following command: docker build -t <nameofyourimage> .
  
Step4: Run the Docker image using the below command:

docker run -d -p 80:80 <nameofyourcontainer> <nameofyourimage>
  
Step5: check the status using the following command: docker ps  -a

