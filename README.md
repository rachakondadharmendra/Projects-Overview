
#  Projects Overview

| Upcoming Projects                                                    | Ongoing Projects                       | Completed Projects                                                | Blocker Reason                                  | Project Status | GitHub URL                                                                                            |
| -------------------------------------------------------------------- | -------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------- | -------------- | ----------------------------------------------------------------------------------------------------- |
|                                                                      |                                        | ECS Cluster setup with AWS in-house CI/CD pipeline using IaC tool |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Terraform-ECS-Setup)                                 |
|                                                                      |                                        | Monitoring setup with Prometheus, Grafana                         |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Monitoring-Setup)                                    |
|                                                                      |                                        | Error Page Templates                                              |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Error-Code-Templates)                                |
|                                                                      |                                        | Portfolio-v1.0                                                    |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Portfolio-v1.0)                                      |
|                                                                      |                                        | Built a 3-tier application for DevOps projects                    |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/3-Tier-Application)                                  |
|                                                                      |                                        | Documentation of Nginx Configuration Production                   |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Nginx-Prod-Configuration)                            |
|                                                                      |                                        | Jenkins CAC setup                                                 |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Jenkins-CAC)                                         |
|                                                                      |                                        | Uptime Kuma Setup                                                 |                                                 | Completed      | [Website](https://uptime-kuma.rachakondadharmendra.info/status/portfolio)                             |
|                                                                      |                                        | EKS cluster creation using terraform (Different concepts)         |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/EKS-Cluster-Terraform)                               |
|                                                                      |                                        | Jenkins DevSecOps pipeline CI                                     |                                                 | Completed      | [GitHub](https://github.com/rachakondadharmendra/Jenkins-CAC/tree/main/Jenkins-DevSecOps-CI-Pipeline) |
|                                                                      | Working on Medium Blog                 |                                                                   |                                                 | On Hold        |                                                                                                       |
|                                                                      | Kubernetes integration with Istio.     |                                                                   |                                                 | In Progress    |                                                                                                       |
|                                                                      | Kubernetes integration with Karpenter. |                                                                   |                                                 | In Progress    |                                                                                                       |
|                                                                      |                                        | Jenkins DevSecOps pipeline CD                                     | Waiting for K8 New setup completion with addone | On Hold        |                                                                                                       |
| Portfolio Website                                                    |                                        |                                                                   | Need to create Project pages/Dashboard          | On Hold        | [WEBSITE](https://rachakondadharmendra.info/#projects)                                                |
| Complete Kubernetes Cluster Setup, Disaster Recovery Plans and Usage |                                        |                                                                   |                                                 | Planned        |                                                                                                       |



## Live Website: Rachakonda Dharmendra's Portfolio

**URL**: [https://rachakondadharmendra.info/](https://rachakondadharmendra.info/)

**Description**: The website is a 3-tier application consisting of frontend built with React.js, backend with Golang, and MongoDB as the database. 

**Usage**:
- Users/clients can submit data through the contact form on the website, which is then transmitted to the database via a Golang API.
- Admins can access the data submitted by users through the following path: [https://rachakondadharmendra.info/admin](https://rachakondadharmendra.info/admin).
- Superadmins have additional privileges such as deletion, updating, and patching of data. They can access their dashboard via [https://rachakondadharmendra.info/superadmin](https://rachakondadharmendra.info/superadmin).

**API Documentation**:
For API-related details, please visit: [https://rachakondadharmendra.info/api/all](https://rachakondadharmendra.info/api/all)

**Warning**: This website is hosted on a UAT (User Acceptance Testing) environment and is solely intended to showcase the usage of a 3-tier application architecture. It is not intended for production use.

## Server Monitoring: Uptime Kuma

**URL**: [https://uptime-kuma.rachakondadharmendra.info/status/portfolio](https://uptime-kuma.rachakondadharmendra.info/status/portfolio)

**Description**: This temporary server is newly provisioned with SSL(via certbot)
