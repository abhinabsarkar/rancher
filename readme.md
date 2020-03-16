# Rancher

Rancher is a container management platform for Kubernetes, providing the tools to successfully run Kubernetes anywhere.

## Features

1.	Open Source (but can be supported by the vendor) & excellent [documentation](https://github.com/rancher/rancher)
2.	Easy to get started for a proof of concept by running the below command
```cmd
docker run -d --restart=unless-stopped -p 80:80 -p 443:443 rancher/rancher
```
>The above command launches Rancher – very intuitive, clean & clutter free UI. Just going through the tabs in the UI gives you a clear picture of the features it offer
3.	Can [manage a k8s cluster as well as import](https://rancher.com/docs/rancher/v2.x/en/cluster-provisioning/) an existing cluster
4.	Supports K8s cluster on bare metal, virtualized environment, on-prem, public & private cloud. Infact, it also supports kubernetes light (k3s) for IoT. https://k3s.io/
5.	Identity and access management 
a.	All major identity providers supported for [authentication](https://rancher.com/docs/rancher/v2.x/en/admin-settings/authentication/). Also provides its own local user registry
b.	[RBAC](https://rancher.com/docs/rancher/v2.x/en/admin-settings/rbac/) with in-built Roles defined at the Global, Cluster & Project level. Supports creating [custom roles](https://rancher.com/docs/rancher/v2.x/en/admin-settings/rbac/default-custom-roles/) too
6.	Centralized [pod security](https://rancher.com/docs/rancher/v2.x/en/admin-settings/pod-security-policies/) & [network policies](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/editing-clusters/)
7.	Offers [service mesh](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/istio/) through Istio
8.	Cluster [monitoring](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/monitoring/) through Prometheus & [logging](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/tools/logging/) is integrated with Syslog along with various others
9.	Offers [certificate management](https://rancher.com/docs/rancher/v2.x/en/cluster-admin/certificate-rotation/)
10.	Provides a single pane of glass for all the clusters – short demo here - https://www.youtube.com/watch?v=LX0zVh-AYm4
