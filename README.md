# todo-app-based-ArgoCD-Helm
This project implements a complete GitOps-based deployment workflow for a Todo Application using ArgoCD, Helm, and Kubernetes. The goal of the project is to automate application delivery, enable version-controlled deployments, and ensure continuous reconciliation between Git and the Kubernetes cluster.

##Description##
This project follows a pure GitOps model.
we created a Helm chart for the Todo App, pushed it to a Git repo, and used ArgoCD to continuously sync it into the cluster. Any change committed to Git such as version update or configuration change gets automatically deployed by ArgoCD.
It also detects drift, ensures the cluster always matches Git, and supports automated rollback

⭐Highlights⭐

✔ GitOps Workflow using ArgoCD
✔ Helm Charts for templated Kubernetes manifests
✔ Automated Continuous Delivery
✔ Auto-sync, drift detection, and self-healing
✔ Environment-specific values (dev and prod)
✔ Container image built via CI pipeline
✔ Rollbacks & Version control via Git
✔ Scalable and reproducible deployment model

