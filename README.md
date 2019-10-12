# python-docker-starter

# Build Docker Image
docker build -t my-first-python-app:v1 .

# Run Docker Container using above image
docker run -it -p 5003:5003 my-first-python-app:v1

# Build and push to Azure registry
az acr build --registry workshopmoolshankar --image my-py-app:v1 .
