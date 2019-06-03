# managed-cluster-config repository

This repo contains static configuration specific to a "managed" OpenShift Dedicated (OSD) cluster.

## Prometheus

A set of rules and alerts that SRE requires to ensure a cluster is functioning.  There are two categories of rules and alerts found here:

1. SRE specific, will never be part of OCP
2. Temporary addition until made part of OCP

## SRE Authorization

Instead of SRE having `cluster-admin` a new ClusterRole is created with some permissions removed.  The ClusterRole can be regenerated in the `generate/sre-authorization` directory.

## Console Branding

Docs TBA.

## OAuth Templates

Docs TBA.

## Resource Quotas

Refer to [deploy/resource/quotas/README.md](deploy/resource/quotas/README.md).

## Image Pruning

Docs TBA.
