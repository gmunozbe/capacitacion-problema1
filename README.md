docker build -t gmunozbe/orbis-training-docker:0.1.0 .
docker push gmunozbe/orbis-training-docker:0.1.0
docker tag 7db9c916bc4e gmunozbe/orbis-training-docker:0.2.0