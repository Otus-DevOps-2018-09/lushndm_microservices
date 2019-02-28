# lushndm_microservices repository

### Homework-25 (kubernetes-5)
 - Configured Prometheus in kubernetes
 - Configured Prometheus and Grafana for metrics collecting

### Homework-24 (kubernetes-4)
 - Configured Helm
 - Configured Gitlab in Kubernetes
 - Started CI/CD pipeline in Kubernetes

### Homework-23 (kubernetes-3)
 - Configured LoadBalancer Service
 - Configured Ingress Service
 - Configured TLS Termination
 - Configured Network Policies
 - Configured PersistentVolumes
 - Configured PersistentVolumeClaims

### Homework-22 (kubernetes-2)
 - Configured local environment for Kubernetes by Minikube.
 - Configured Kubernetes cluster in GKE.
 - Started Reddit app servces in GKE cluster.

### Homework-21 (kubernetes-1)
 - Described App with Kubernetes Deployment manifests.
 - Configured Kubernetes components manualy during Kubernetes_The_Hard_Way tutorial.

### Homework-20 (logging-1)
 - Configured EFK (fluentd, elasticsearch, kibana) stack for collecting, parsing and visualization logs.
 - Configured json parsing filter for structured logs.
 - Configured regexp parsing filter and grok_pattern filters for non-structured logs.
 - Configured Zipkin service for distributed tracing.

### Homework-19 (monitoring-2)
 - Configured cAdvisor for docker containers monitoring.
 - Started Grafana. Configured dashboards in Grafana for docker containers monitoring.
 - Configured dashboards (Histogram, 95th procentile) in Grafana for app services monitoring.
 - Configured dashboards in Grafana for business logic monitoring.
 - Started Alertmanager. Configured alert to Slack channel by webhook from Prometheus.

### Homework-18 (monitoring-1)
 - Tested Prometheus in docker container.
 - Created config prometheus.yml
 - Builded docker-compose images for app services and prometheus.
 - Tested healthchecks.
 - Started node_exporter docker container. Tested docker-host CPU load.
 - Pushed images to Docker Hub. https://hub.docker.com/u/lushndm

### Homework-17 (gitlab-ci-2)
 - Described Dev environment.
 - Described Staging and Production environment.
 - Added conditions and restrictions by Only.
 - Added dynamic environments: new-feature and bugfix.

### Homework-16 (gitlab-ci-1)
 - Prepared installation of Gitlab CI.
 - Tuned up pipeline.
 - Tuned up runner.
 - Prepared repos with reddit-app.
 - Described stages of CI for reddit-app.

### Homework-15 (docker-4)
 - None network driver.
 - Host network driver.
 - Bridge network driver.
 - Installed docker-compose. Added docker-compose.yml.
 - Parametrized docker-compose.yml with .env file.
 - If you do not set this var, the COMPOSE_PROJECT_NAME defaults to the basename of the project directory.

### Homework-14 (docker-3)
 - Divided our application into components: post-py, comment, ui and mongo.
 - Builded the images with our services. Added network aliases to containers.
 - Launched our containers on reddit network.
 - Improved ui image. Rebuilt ui image from ubuntu:16.04.
 - Improved ui image. Rebuilt ui image from alpine linux.
 - Created docker volume. Restarted containers with docker volume.

### Homework-13 (docker-2)
 - Setuped docker-machine and run docker-host gce instance.
 - Builded image Reddit by Dockerfile, start.sh, mongod.conf and db_config.
 - Runned container from Reddit image on gce instance.
 - Setuped Docker Hub. Pushed Reddit image to Docker Hub.
 - Started Reddit docker container from Docker Hub on local machine.

### Homework-12 (docker-1)
 - Installed Docker. Started first container hello-world. Created image from container. Deleted used containers and images.
