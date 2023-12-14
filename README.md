# This is a POC for splitting an application via k8s ingress

## Need QEMU Driver and socket_vmnet for Apple Silicon Mac M1
https://medium.com/@sushantkumarsinha22/kubernetes-setting-up-ingress-on-apple-silicon-mac-m1-5fb6bddcb838

```sh
curl the-frontend.com
# hello from fe                                                                     
curl the-frontend.com/api
# hello from be
```