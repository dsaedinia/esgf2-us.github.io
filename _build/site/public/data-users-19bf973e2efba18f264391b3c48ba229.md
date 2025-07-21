---
title: Data Access
---
There are a lot of ways a user can access data:

* `mountPath`: The path to mount the volume inside the container
    * `volumeSpec`: A [Kubernetes volume specification](https://kubernetes.io/docs/concepts/storage/volumes/) for
      the volume containing the data
    * `name` (optional): A name for the volume - by default, a name is derived from the `mountPath`
    * `mountOptions` (optional): Options for the volume mount, e.g. `mountPropagation` for `hostPath` volumes

