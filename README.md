# K8s
Go to cloud.google.com and make your new account.

#Install gcloud CLI - 
https://cloud.google.com/sdk/docs/quickstart-macos

#Authenticate in Google Cloud, Set Region and Zone
$gcloud auth login
$gcloud config set compute/region us-west1
$gcloud config set compute/zone us-west1-c

#Install Client Tools
brew install cfssl

### OS X

```
curl -o cfssl https://storage.googleapis.com/kubernetes-the-hard-way/cfssl/darwin/cfssl
curl -o cfssljson https://storage.googleapis.com/kubernetes-the-hard-way/cfssl/darwin/cfssljson
```

```
chmod +x cfssl cfssljson
```
