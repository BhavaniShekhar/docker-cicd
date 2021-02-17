# docker-cicd

This project is build to test the simple Jenkins pipeline, Where the pipeline will execute the following stages:
 1. stage 1 is aimed to git checkout 
 2. stage 2 to run the maven command to cleanup
 3. stage 3 Build docker image
 4. stage 4 Docker push to Hub
 5. Stage 5 Remove old container
 6. Stage 6 Deploy to dev docker container
