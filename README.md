The Attached yaml files are the kubernetes web service deployment with mongodb .
 
Simpler explanation of each file type in Kubernetes:


Secret:

1)Secrets hold sensitive information like passwords, API keys, or certificates.

2)They keep this info safe and make it available to applications securely.


Deployment:

1)Deployments are like instructions for Kubernetes on how to run your app.

2)They define what your app needs, like how many copies to run and which version to use.


ConfigMap:

1)ConfigMaps store non-secret configuration data.

2)They hold things like database connection strings or settings that your app needs to run.

Service:

1)Services help your app talk to the outside world or other parts of your app.
2)They provide a stable way for other apps or users to find and access your app.
