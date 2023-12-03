## yaml-repo list 

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| ----------- | ----------- | ----------- | ----------- |
| app | kubectl apply -f app.yaml | Main configuration file for the application, including various Kubernetes resources | [app.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app.yaml) |
| app-livenessProbe | kubectl apply -f app-livenessProbe.yaml | Defines a liveness probe to check if the application container is running correctly | [app-livenessProbe.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-livenessProbe.yaml) |
| app-readinessProbe | kubectl apply -f app-readinessProbe.yaml | Specifies a readiness probe to check if the application is ready to accept traffic | [app-readinessProbe.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-readinessProbe.yaml) |
| app-volumeMounts | kubectl apply -f app-volumeMounts.yaml | Configures volume mounts for attaching volumes to containers in a pod | [app-volumeMounts.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-volumeMounts.yaml) |
| app-cronjob | kubectl apply -f app-cronjob.yaml | Sets up a CronJob to schedule and run tasks periodically | [app-cronjob.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-cronjob.yaml) |
| app-job | kubectl apply -f app-job.yaml | Defines a Kubernetes Job for running pods to completion, often used for batch processing | [app-job.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-job.yaml) |
| app-multicontainer | kubectl apply -f app-multicontainer.yaml | Describes a pod with multiple tightly coupled containers sharing resources | [app-multicontainer.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-multicontainer.yaml) |
| app-resources | kubectl apply -f app-resources.yaml | Contains resource specifications such as CPU and memory configurations for the application | [app-resources.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-resources.yaml) |
| app-secret-env | kubectl apply -f app-secret-env.yaml | Involves defining environment variables using Kubernetes Secrets, typically for storing sensitive information | [app-secret-env.yaml](https://github.com/Dennyyyyyyy/yaml-repo/blob/main/app-secret-env.yaml) |