docker build -t wl-docker/mlops-training-docker .
docker run -it -p 5001:5001 wl-docker/mlops-training-docker  

kubectl apply -f deploy.yaml