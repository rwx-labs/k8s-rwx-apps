# k8s-rwx-apps [![App Status](https://argo-cd.infra.rwx.im/api/badge?name=k8s-rwx-apps)](https://argo-cd.infra.rwx.im/applications/k8s-rwx-apps)

This repository contains the app-of-apps deployments for apps dedicated to the
rwx.im project.

They are deployed in [**@mkroman**][mkroman]s Kubernetes cluster. More
information can be found in [mkroman/k8s].

[mkroman]: https://github.com/mkroman
[mkroman/k8s]: https://github.com/mkroman/k8s

## Applications

| App         | Path                           | Status      |
|-------------|--------------------------------|-------------|
| element-web | [`element-web/`](element-web/) | [![App Status](https://argo-cd.infra.rwx.im/api/badge?name=element-web)](https://argo-cd.infra.rwx.im/applications/element-web) |
| wayback     | [`wayback/`](wayback/)         | [![App Status](https://argo-cd.infra.rwx.im/api/badge?name=wayback)](https://argo-cd.infra.rwx.im/applications/wayback) |
