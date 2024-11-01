# CyberArk Conjur Example Policies Repository

This repository contains example CyberArk Conjur policies and integrations designed to help teams securely manage secrets and access permissions across various tools and platforms. The examples focus on real-world use cases, providing adaptable templates for integrating Conjur with different DevOps tools and environments.

## Repository Structure

The repository is organized by use case, with folders that contain example policies for specific scenarios. Each folder includes documentation and policy files for implementing Conjur within that context.

### Folders Overview

| Folder                  | Description                                                                                                               |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------|
| `policies/`             | Contains general example policies for Conjur, demonstrating best practices for organizing and managing secrets and access permissions across various teams. |
| `ansible/`              | Example configurations for integrating Conjur with Ansible, allowing for secure secrets management within playbooks and roles. Includes setup and usage instructions. |
| `github/`               | Provides example policies and integrations for using Conjur with GitHub Actions, enabling secure access to secrets in CI/CD workflows. |
| `jenkins/`              | Contains example policies for integrating Conjur with Jenkins, covering both build and deployment pipelines with secure access to secrets. |
| `kubernetes-openshift/` | Example configurations for integrating Conjur with Kubernetes and OpenShift, enabling secrets management within containers and pods across namespaces. |
