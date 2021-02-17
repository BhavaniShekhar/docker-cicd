# docker-cicd

This project is build to test the simple Jenkins pipeline, Where the pipeline will execute the following stages:
 stage 1 is aimed to git checkout 
 stage 2 to run the maven command to cleanup
 stage 3 Build docker image
 stage 4 Docker push to Hub
 Stage 5 Remove old container
 Stage 6 Deploy to dev docker container
