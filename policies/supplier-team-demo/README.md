# Conjur Example Policies for Consumer Teams

This folder contains example CyberArk Conjur policies to help consumer teams—teams that build software for end users—implement secure secrets management. These files demonstrate how to configure Conjur to handle secrets needed for various tools and environments in the software development lifecycle.

## Files Overview

| File                          | Description                                                                                             |
|-------------------------------|---------------------------------------------------------------------------------------------------------|
| `_variables.yml`              | Stores global variables required by multiple applications or pipelines.                                 |
| `jenkins-build-pipeline.yml`  | Defines secrets and access for Jenkins during the build process.                                        |
| `jenkins-deploy-pipeline.yml` | Defines secrets and access permissions for Jenkins during the deployment process.                       |
| `openshift-namespace-1.yml`   | Configures secrets and access for an OpenShift namespace (e.g., dev or staging environment).            |
| `openshift-namespace-2.yml`   | Configures secrets and access for a second OpenShift namespace.                                         |
| `rhaap.yml`                   | Demonstrates integration of Conjur secrets management with Red Hat Advanced Cluster Management (RHACM). |
