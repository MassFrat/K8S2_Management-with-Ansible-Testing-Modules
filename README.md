# Kubernetes Management with Ansible 

## This module is part of the kubernetes.core collection (version 5.3.0).

You might already have this collection installed if you are using the ansible package. It is not included in ansible-core. To check whether it is installed, run ansible-galaxy collection list.

To install it, use: ansible-galaxy collection install kubernetes.core. You need further requirements to be able to use this module, see Requirements for details.

To use it in a playbook, specify: kubernetes.core.k8s.

<br/>

## Synopsis:
Use the Kubernetes Python client to perform CRUD operations on K8s objects. 
Pass the object definition from a source file or inline. See examples for reading files and using Jinja templates or vault-encrypted files.
Access to the full range of K8s APIs.
Use the kubernetes.core.k8s_info module to obtain a list of items about an object of type kind
Authenticate using either a config file, certificates, password or token
Supports check mode.

<br/>

---------------
## Requirements:
python >= 3.9

kubernetes >= 24.2.0

PyYAML >= 3.11

jsonpatch

---------

<br/>
<br/>

Managing Kubernetes clusters and applications can be complex, especially when dealing with multiple environments, scaling requirements, and configuration management. Ansible provides a powerful solution for Kubernetes infrastructure automation through its kubernetes.core collection, which includes the essential k8s modules that enable declarative management of Kubernetes resources.  
  
This guide explains how Ansible can streamline your Kubernetes operations, reduce manual errors, and provide consistent, repeatable deployments across your infrastructure. 
<br/>
<br/> 

# Why Use Ansible for Kubernetes Management?

## Infrastructure as Code Benefits
Ansible transforms Kubernetes management from imperative commands to declarative infrastructure-as-code practices. Instead of manually running kubectl commands, you define your desired infrastructure state in playbooks that can be version-controlled, reviewed, and automatically executed.

## Consistency Across Environments
With Ansible, you can ensure identical configurations across development, staging, and production environments. The same playbooks work across different clusters, reducing environment-specific errors and configuration drift.

## Integration with Existing Workflows
Ansible seamlessly integrates with your existing CI/CD pipelines, configuration management systems, and operational workflows. You can combine Kubernetes resource management with traditional server configuration, network setup, and application deployment tasks.

<br/>
<br/>

# The kubernetes.core.k8s Module Collection
The kubernetes.core collection is Ansible's official collection for Kubernetes management, providing specialized modules that interact directly with the Kubernetes API. These modules understand Kubernetes resource types, handle authentication, and provide sophisticated state management capabilities.

### The combination of Ansible's automation capabilities with Kubernetes' container orchestration provides a powerful platform for modern infrastructure management that scales from simple deployments to complex multi-cluster operations.
