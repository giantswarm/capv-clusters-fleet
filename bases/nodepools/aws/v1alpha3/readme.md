# Input Variables

Expected variables are in the table below.

| Variable | Expected Value |
| :--: | :--: |
| `cluster_id` | Workload Cluster name, MUST comply with the [Kubernetes Names](https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names) |
| `machine_deployment_id` | Machine deployment name, MUST comply with the [Kubernetes Names](https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names) |
| `organization` | Organization name, the `org-` prefix MUST not be part of it and MUST comply with the [Kubernetes Names](https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names) |
| `release` | Workload Cluster release version, reference the [Giantswarm docs](https://docs.giantswarm.io/general/releases/) for more insight on releases |
