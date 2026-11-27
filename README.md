
# Introduction to Infrastructure as Code (IaC)

## 1. Objective

The objective of this practical lab is to understand the fundamentals of Infrastructure as Code (IaC) and learn how to deploy and configure an application using Docker Compose.

## 2. Key Concepts

### Infrastructure as Code (IaC)

Infrastructure as Code (IaC) is an approach that allows infrastructure to be defined, configured, and managed through code rather than manual operations. It helps automate deployments, ensure consistency, and reproduce environments reliably.

### Docker Compose

Docker Compose is a tool used to define and manage multi-container Docker applications through a YAML configuration file, usually named `docker-compose.yml`.

It allows multiple services, networks, volumes, and port mappings to be configured in a single file.

## 3. Practical Lab: Deploying Odoo with Docker Compose

### Tasks

1. Deploy the Odoo application using Docker Compose.
2. Refer to the official Docker Hub documentation for Odoo:  
   https://hub.docker.com/_/odoo
3. Modify the `docker-compose.yml` file to expose port **80** of the Odoo container externally instead of port **8069**.
4. Modify the Docker Compose configuration so that the Odoo and database containers belong to the same dedicated network named `odoo_network`, using the `bridge` network driver.
5. Verify that the Odoo application is accessible.
