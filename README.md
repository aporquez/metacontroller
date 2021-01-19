# metacontroller
Metacontroller is an add-on for Kubernetes that makes it easy to write and deploy custom controllers in the form of simple scripts. Update the [metacontroller](yaml-k8s/yaml-base/metacontroller) yaml/s using the [github/metacontroller](https://github.com/metacontroller/metacontroller/tree/master/manifests/production)


## Notes
- IMPORTANT: You can only install one copy of this in a given Kubernetes cluster, due to the fact that it has CRDs included in it. You'll get an error if you attempt to install a second copy.
- There is no official helm chart yet [metacontroller/42](https://github.com/metacontroller/metacontroller/issues/42) but we can create a temporary helm chart using the [willnewby/metacontroller](https://github.com/willnewby/charts/tree/adding-metacontroller/stable/metacontroller) as reference.

## TODO
- Create a helm chart version

## References
- https://github.com/metacontroller/metacontroller