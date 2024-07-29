# project

To build and run the image file locally
1. Type `docker build -t app-name .` to build the image
2. Type `docker run -p 8080:8080 image-name` to deploy image

To Push the Docker Image to the Container Registry
1. Type `docker login` in the terminal
2. Enter your username and password
3. Type `docker push dockerhub-username/your-repo-name`

To Deploy the Helm Chart to the Kubernetes Cluster
1. Type `helm upgrade --install app-name ./path-to-helm-chart`

To Access the Deployed Application
1. Type `kubectl get svc`
2. Open the link in your browser
