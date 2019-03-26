



#gcp

## 学习资源：

###   archtect
https://inthecloud.withgoogle.com/onboard/global-classic.html

### big data & machine-learning
https://inthecloud.withgoogle.com/onboard/global-machine-learning.html

# gke



## Create a Project 


## config env

```
gcloud init


gcloud config set compute/region us-west1



gcloud config set compute/zone us-west1-c

```


## create a k8s cluster 


```
# Create a cluster
gcloud container clusters create  my-first-cluster

# config the kubectl
gcloud container clusters get-credentials my-first-cluster


# Deploy an App
kubectl run hello-server --image gcr.io/google-samples/hello-app:1.0 --port 8080


# Delete the Cluster
gcloud container clusters delete  my-first-cluster

```
