# AWS-Cloud-Infrastructure-with-DevSecOps
API en Flask con PostgreSQL desplegada en AWS de forma totalmente automatizada. La infraestructura se define con Terraform, el pipeline de GitHub Actions construye, analiza (Trivy) y despliega la imagen Docker, y la monitorización se hace con CloudWatch. La fase final despliega la app en Kubernetes con ArgoCD (GitOps).
