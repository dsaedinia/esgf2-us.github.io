---
title: Data Access
---
There are a lot of ways a user can access data:

* `Metagrid`: MetaGrid is the next-generation search interface for the Earth System Grid Federation (ESGF). It's a user-friendly web application designed to help researchers find and access climate model data stored within the ESGF. Think of it as a more advanced way to search for and retrieve the data needed for climate research. 
For more information visit [Metagrid]()
* `Intake-ESGF`: A [Kubernetes volume specification](https://kubernetes.io/docs/concepts/storage/volumes/) for the volume containing the data
* `Cookbooks` (optional): A name for the volume - by default, a name is derived from the `mountPath`
* `ESG Pull` (optional): Options for the volume mount, e.g. `mountPropagation` for `hostPath` volumes

