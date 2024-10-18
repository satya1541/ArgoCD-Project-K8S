# Argo CD 

## Argo CD
A declarative, GitOps continuous delivery tool for Kubernetes. It automates the deployment of applications to Kubernetes clusters using Git repositories as the source of truth.

## GitOps
A methodology for continuous deployment that uses Git as the single source of truth for declarative infrastructure and applications. Changes are made in Git, and automated processes ensure that the actual state matches the desired state defined in Git.

## Application
In Argo CD, an application is a Kubernetes resource that represents a deployed service. It consists of a manifest that defines the desired state, including which Kubernetes resources to create and how to configure them.

## Repository
A Git repository that contains the Kubernetes manifests or Helm charts for the applications you want to deploy and manage with Argo CD.

## Sync
The process of aligning the actual state of a Kubernetes application with its desired state defined in the Git repository. Argo CD monitors the application and can automatically synchronize changes.

## Health Status
A status indicator that reflects the current health of an application in Argo CD, such as `Healthy`, `Degraded`, or `Missing`, based on the state of the Kubernetes resources.

## Sync Status
A status indicator that shows whether the application is in sync with the desired state defined in Git, such as `Synced` or `OutOfSync`.

## Application Set
A custom resource in Argo CD that enables managing multiple applications with a single configuration. It allows you to define a template and create applications dynamically based on the defined criteria.

## Helm
A package manager for Kubernetes that allows users to define, install, and upgrade applications using Helm charts. Argo CD supports Helm for application deployments.

## Rollback
The process of reverting an application to a previous version or state. Argo CD allows users to easily rollback applications to earlier revisions in Git.

## Dashboard
The web-based user interface of Argo CD that provides an overview of the applications, their statuses, and the ability to perform actions like syncing and rolling back.

## CLI (Command Line Interface)
A command-line tool for interacting with Argo CD, allowing users to perform operations like creating applications, syncing, and managing the configuration.

## Notifications
Argo CD can send notifications about application events and status changes to different channels, such as Slack or email, to keep teams informed.

## Multi-cluster Support
Argo CD can manage applications deployed across multiple Kubernetes clusters, enabling centralized deployment and monitoring from a single control plane.


