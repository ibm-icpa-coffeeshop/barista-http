# Coffee Shop demo barista-http service

This microservice provides a RESTful implementation of a barista for the Coffee Shop demo using Open Liberty. The barista processes requests for coffee synchronously when it receives an HTTP POST request. For more information on the Coffee Shop scenario, see [Design and deliver an event-driven, cloud-native application at lightning speed](https://developer.ibm.com/tutorials/accelerator-for-event-driven-solutions/).

## Local development

This project has been developed using [Appsody](https://appsody.dev/).  To build and run the service locally, use the command `appsody run`.  This will start the service inside a local Docker container.   For more information, see [Local development](https://appsody.dev/docs/using-appsody/local-development). 

## Building and deploying to a Kubernetes cluster

To deploy the service to a Kubernetes cluster, use the command `appsody deploy`. This will build a Docker image suitable for production, and deploy it by creating the necessary resources on your Kubernetes cluster. For more information, see [Deploying](https://appsody.dev/docs/using-appsody/deploying).  You can also use the [GitOps repo](https://github.com/ibm-icpa-coffeeshop/gitops-dev) to deploy the complete application.