# SUSE Cloud Native

A simple web application using cloud native technologies:
- A super-simple blog application using the Flask framework. Dynamic data stored in SQLite DB. Metrics, healthcheck endpoints and logs for monitoring
- Github actions to automate simple tasks on each commit like containerization as a docker image and posting it to DockerHub (https://hub.docker.com/repository/docker/carloshvp/techtrends)
- Setting up a local Kubernetes (K3S) cluster inside a Vagrant Box (SUSE Linux) configured using declarative manifests
- ArgoCD for GitOps using this repo and Helm for parametrization of several environments (e.g. staging, prod)