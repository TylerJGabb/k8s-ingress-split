# This is a POC for splitting an application via k8s ingress
This POC demonstrates splitting traffic at the ingress level to different services based on the path.

# ⚠️⚠️⚠️Need QEMU Driver and socket_vmnet for Apple Silicon Mac M1⚠️⚠️⚠️
https://medium.com/@sushantkumarsinha22/kubernetes-setting-up-ingress-on-apple-silicon-mac-m1-5fb6bddcb838

# Getting Started
1. Install [minikube](https://minikube.sigs.k8s.io/docs/start/)
2. Install [helm](https://helm.sh/docs/intro/install/)
3. Follow the [steps](https://medium.com/@sushantkumarsinha22/kubernetes-setting-up-ingress-on-apple-silicon-mac-m1-5fb6bddcb838) to enable qemu and socket_vmnet for Apple Silicon Mac M1

```sh
curl the-frontend.com
# hello from fe                                                                     
curl the-frontend.com/api
# hello from be
```