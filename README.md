# Workload Clusters Fleet

Repository for orchestrating configuration of the workload clusters in a GitOps manner.

Flux CRs are in the `default` namespace reconciled by controllers in the `flux-system`
namespace to match how customers use our managed Flux.

This implementation is based on the template and documentation available in our
[gitops-template](https://github.com/giantswarm/gitops-template).

## Docs

You can find [docs on how to add clusters](https://github.com/giantswarm/gitops-template#using-this-repository) to this repo on [the gitops-template repo](https://github.com/giantswarm/gitops-template).
