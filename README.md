# kubectl-ai-demo
Set of prompts for the YAML manifests using kubectl-ai plugin

To create a set of prompts for the given YAML manifests using kubectl-ai plugin, I'll provide prompts for each file in the list. Please note that these prompts are examples, and you may customize them based on your specific use case.

## Portfolio of Prompts:

| NAME                   | PROMPT                                   | DESCRIPTION                                   | EXAMPLE                                      |
|------------------------|------------------------------------------|-----------------------------------------------|----------------------------------------------|
| app.yaml               | Apply the deployment manifest for the app | Deploy the main application using a deployment | [app.yaml](/yaml /app.yaml)             |
| app-livenessProbe.yaml | Configure liveness probe for the app      | Set up a liveness probe to monitor app health | [app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml)|
| app-readinessProbe.yaml| Add readiness probe for the app           | Define a readiness probe to check app readiness| [app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml)|
| app-volumeMounts.yaml  | Mount volumes for the app                 | Attach volumes to containers for data storage  | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml)  |
| app-cronjob.yaml       | Schedule a cron job for the app           | Create a cron job to run tasks periodically    | [app-cronjob.yaml](/yaml/app-cronjob.yaml)       |
| app-job.yaml           | Run a one-time job for the app            | Execute a job once to perform specific tasks   | [app-job.yaml](/yaml/app-job.yaml)        |
| app-multicontainer.yaml| Define a multi-container pod for the app  | Set up a pod with multiple containers           | [app-multicontainer.yaml](/yaml/app-multicontainer.yaml)|
| app-resources.yaml     | Configure resource limits for the app     | Set CPU and memory limits for better control   | [app-resources.yaml](/yaml/app-resources.yaml)    |
| app-secret-env.yaml    | Use environment variables from secrets    | Inject secrets into environment variables      | [app-secret-env.yaml](/yaml/app-secret-env.yaml)   |
