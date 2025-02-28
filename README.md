## k8s-task-image

This repo builds a Debian-based OCI container image which includes latest
`kubectl`, and specific versions of both `helm` and `kapp`.

The image is then used in various GitHub actions scripts to deploy Helm charts
to Kubernetes.
