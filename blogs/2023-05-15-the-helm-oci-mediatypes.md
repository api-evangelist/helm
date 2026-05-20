---
title: "The Helm OCI MediaTypes"
url: "https://helm.sh/blog/helm-oci-mediatypes"
date: "2023-05-15T00:00:00.000Z"
author: "Andrew Block"
feed_url: "https://helm.sh/blog/atom.xml"
---
Helm introduced full support for storing charts within OCI registries as a distribution method beginning in version 3.8, and while this feature has been available for some time now, there is more underneath the hood than one may realize to make this capability all possible. A number of concepts, working in unison, make it possible to store content aside from traditional container images within OCI registries. This article will explore one of these important concepts, Media Types, their purpose, and how Helm’s own set of Media Types make it possible to extend the storage of charts beyond…
