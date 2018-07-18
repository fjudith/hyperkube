# Hyperkube

hyperkube is an all-in-one binary for the Kubernetes server components.

This image, based on the [official hyperkube image](https://gcr.io/google_containers/hyperkube), aims to fix the block storage compatibility issues of containerized Kubernetes services with solutions like [rook](https://www.rook.io) or [openebs](https://www.openebs.io/).

## List of added packages

* [open-iscsi](http://www.open-iscsi.com/)
* [xfsprogs](http://oss.sgi.com/projects/xfs/)
* [azure-cli](https://github.com/Azure/azure-cli)


## Reference

* https://github.com/openebs/openebs/issues/1020