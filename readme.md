# Rancher

Rancher is a container management platform for Kubernetes, providing the tools to successfully run Kubernetes anywhere. Rancher server installation can manage hundreds of Kubernetes clusters from the same interface. 

It adds significant value on top of Kubernetes, first by centralizing role-based access control (RBAC) for all of the clusters and giving global admins the ability to control cluster access from one location. It then enables detailed monitoring and alerting for clusters and their resources, ships logs to external providers, and integrates directly with Helm via the Application Catalog. Rancher can plug in an external CI/CD system, or it can include a pipeline engine to help automatically deploy and upgrade workloads.

Get started for a proof of concept by running the below command
```cmd
docker run -d --restart=unless-stopped -p 80:80 -p 443:443 rancher/rancher
```
>The above command launches Rancher – very intuitive, clean & clutter free UI. Just going through the tabs in the UI gives you a clear picture of the features it offer

## Features

1.	Open Source (but can be supported by the vendor) & excellent [documentation](https://github.com/rancher/rancher)
2.	Can [manage a k8s cluster as well as import](https://rancher.com/docs/rancher/v2.x/en/cluster-provisioning/) an existing cluster
3.	Supports K8s cluster on bare metal, virtualized environment, on-prem, public & private cloud. Infact, it also supports kubernetes light (k3s) for IoT. https://k3s.io/
4.	Identity and access management  
    a.	All major identity providers supported for [authentication](https://rancher.com/docs/rancher/v2.x/en/admin-settings/authentication/). Also provides its own local user registry  
    b.	[RBAC](https://rancher.com/docs/rancher/v2.x/en/admin-settings/rbac/) with in-built Roles defined at the Global, Cluster & Project level. Supports creating [custom roles](https://rancher.com/docs/rancher/v2.x/en/admin-settings/rbac/default-custom-roles/) too
5.	Centralized [pod security](https://rancher.com/docs/rancher/v2.x/en/admin-settings/pod-security-policies/) & [network policies](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/editing-clusters/)
6.	Offers [service mesh](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/istio/) through Istio
7.	Cluster [monitoring](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/monitoring/) through Prometheus & [logging](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/logging/) is integrated with Syslog along with various others
8.	Offers [certificate management](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/certificate-rotation/)
9.	Provides a single pane of glass for all the clusters – short demo here - https://www.youtube.com/watch?v=LX0zVh-AYm4
