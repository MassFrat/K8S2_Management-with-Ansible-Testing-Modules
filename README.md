# Kubernetes Management with Ansible

## Synopsis:
Use the Kubernetes Python client to perform CRUD operations on K8s objects. 
Pass the object definition from a source file or inline. See examples for reading files and using Jinja templates or vault-encrypted files.
Access to the full range of K8s APIs.
Use the kubernetes.core.k8s_info module to obtain a list of items about an object of type kind
Authenticate using either a config file, certificates, password or token
Supports check mode.

## Requirements:
python >= 3.9

kubernetes >= 24.2.0
PyYAML >= 3.11
jsonpatch

Managing Kubernetes clusters and applications can be complex, especially when dealing with multiple environments, scaling requirements, and configuration management. Ansible provides a powerful solution for Kubernetes infrastructure automation through its kubernetes.core collection, which includes the essential k8s modules that enable declarative management of Kubernetes resources.

This guide explains how Ansible can streamline your Kubernetes operations, reduce manual errors, and provide consistent, repeatable deployments across your infrastructure.

## Why Use Ansible for Kubernetes Management?

## Infrastructure as Code Benefits
Ansible transforms Kubernetes management from imperative commands to declarative infrastructure-as-code practices. Instead of manually running kubectl commands, you define your desired infrastructure state in playbooks that can be version-controlled, reviewed, and automatically executed.

## Consistency Across Environments
With Ansible, you can ensure identical configurations across development, staging, and production environments. The same playbooks work across different clusters, reducing environment-specific errors and configuration drift.

## Integration with Existing Workflows
Ansible seamlessly integrates with your existing CI/CD pipelines, configuration management systems, and operational workflows. You can combine Kubernetes resource management with traditional server configuration, network setup, and application deployment tasks.

# The kubernetes.core.k8s Module Collection
The kubernetes.core collection is Ansible's official collection for Kubernetes management, providing specialized modules that interact directly with the Kubernetes API. These modules understand Kubernetes resource types, handle authentication, and provide sophisticated state management capabilities.

# The combination of Ansible's automation capabilities with Kubernetes' container orchestration provides a powerful platform for modern infrastructure management that scales from simple deployments to complex multi-cluster operations.
