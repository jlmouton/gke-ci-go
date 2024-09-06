# gke-ci-go
A test repo for a demo of Cloud Build deploying a Go app to Google Kubernetes Engine Autopilot

This example expects:
- a GKE Autopilot cluster already created with the default name: autopilot-cluster-1
- my test project name is hardcoded several times in the cloudbuild.yaml and the deployment.yaml, and must be replaced with the name of your project
- after the deployment is complete, you need to expose it with a loadbalancer service -- this is done in one click on the Workloads menu
 
