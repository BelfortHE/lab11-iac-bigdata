# Lab 11 - Infraestructura Big Data como Código con Terraform y Floci

Plataforma AWS local (S3 + Glue Data Catalog) aprovisionada con Terraform sobre Floci.

## Uso

1. `docker compose up -d`
2. `cd terraform`
3. `terraform init`
4. `terraform plan`
5. `terraform apply`
6. `terraform destroy`

El archivo `terraform.tfstate` no se versiona.
