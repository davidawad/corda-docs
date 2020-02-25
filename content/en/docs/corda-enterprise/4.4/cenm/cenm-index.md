---
title: "What is Corda Enterprise Network Manager?"
date: 2020-01-08T09:59:25Z
---


# What is Corda Enterprise Network Manager?
The Corda Enterprise Network Manager is a commercial offering from R3 that facilitates the operation of a bespoke
            Corda network that gives the operator full control over all aspects of deployment, operation, and the consensus rules.
            This is provided as an alternative to taking advantage of utilising the service-level-managed production components
            that are otherwise be available from [Corda Network](https://corda.network), governed by the independent
            Corda Network Foundation.

The *Corda Enterprise Network Manager* encompasses three main services:


* [Identity Manager Service]({{< relref "identity-manager" >}}) - Enables nodes to join the network, as well as handles revocation of a nodes certificate


* [Network Map Service]({{< relref "network-map" >}}) - Provides a global view of the network


* [Signing Services]({{< relref "signing-service" >}}) - Provides a way to sign approved requests to join the network (CSRs) or revoke a certificate
                    (CRRs) as well as changes to the network map


For a quick start guide on running the ENM services see [Enterprise Network Manager Quick-Start Guide]({{< relref "quick-start" >}}).


