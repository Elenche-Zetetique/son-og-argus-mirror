# Son of Argus

## Overview
**Son of Argus** is a utility designed to manage and synchronize Helm charts for an [ArgoCD](https://argo-cd.readthedocs.io/) instance. It ensures that deployed applications remain up-to-date by automatically updating ArgoCD applications whenever the upstream Helm chart repository is modified.

## Features
- Stores Helm charts for an ArgoCD instance.
- Monitors repositories for changes.
- Automatically updates deployments when new versions of Helm charts are available.

## Prerequisites
Ensure you have the following installed:
- Kubernetes cluster with ArgoCD configured
- Git repository for storing Helm charts

## Usage

1. Deploy ArgoCD instance (s. [Infrastellar](https://github.com/Elenche-Zetetique/infrastellar-mirror))

2. Define your ArgoCD-application file inside the above mentioned repository

3. Define the templates for your application in the current repository.

4. Wait until the added charts appear in ArgoCD instance.

## License
This project is licensed under the [**Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)**](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en) license.

### Summary:
- You are **free to use, modify, and share** this software **for non-commercial purposes**.
- **Commercial use is strictly prohibited**.
- No warranties or liability: The author is **not responsible** for any issues arising from use.

## Authors
Maintained by [**Elenche Zetetique**](https://elenche-zetetique.com/).