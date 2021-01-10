curl https://docs.projectcalico.org/manifests/canal.yaml -O



Install cannal
https://docs.projectcalico.org/getting-started/kubernetes/flannel/flannel


Kubernetes network policies are implemented by network plugins rather than Kubernetes itself. 
Simply creating a network policy resource without a network plugin to implement it, will have no effect on network traffic.

The Calico plugin implements the full set of Kubernetes network policy features. In addition, Calico supports Calico network policies, providing additional features and capabilities beyond Kubernetes network policies. Kubernetes and Calico network policies work together seamlessly, so you can choose whichever is right for you, and mix and match as desired.

Resources:
https://rancher.com/blog/2019/2019-03-21-comparing-kubernetes-cni-providers-flannel-calico-canal-and-weave/