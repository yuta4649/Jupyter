# JupyterHub Helm chart

[![Documentation](https://img.shields.io/badge/Documentation-z2jh.jupyter.org-blue?logo=read-the-docs&logoColor=white)](https://z2jh.jupyter.org)
[![GitHub](https://img.shields.io/badge/Source_code-github-blue?logo=github&logoColor=white)](https://github.com/jupyterhub/zero-to-jupyterhub-k8s)
[![Discourse](https://img.shields.io/badge/Help_forum-discourse-blue?logo=discourse&logoColor=white)](https://discourse.jupyter.org/c/jupyterhub/z2jh-k8s)
[![Gitter](https://img.shields.io/badge/Social_chat-gitter-blue?logo=gitter&logoColor=white)](https://gitter.im/jupyterhub/jupyterhub)
<br>
[![Latest stable release of the Helm chart](https://img.shields.io/badge/dynamic/json.svg?label=Latest%20stable%20release&url=https://hub.jupyter.org/helm-chart/info.json&query=$.jupyterhub.stable&logo=helm&logoColor=white)](https://jupyterhub.github.io/helm-chart#jupyterhub)
[![Latest pre-release of the Helm chart](https://img.shields.io/badge/dynamic/json.svg?label=Latest%20pre-release&url=https://hub.jupyter.org/helm-chart/info.json&query=$.jupyterhub.pre&logo=helm&logoColor=white)](https://jupyterhub.github.io/helm-chart#development-releases-jupyterhub)
[![Latest development release of the Helm chart](https://img.shields.io/badge/dynamic/json.svg?label=Latest%20dev%20release&url=https://hub.jupyter.org/helm-chart/info.json&query=$.jupyterhub.latest&logo=helm&logoColor=white)](https://jupyterhub.github.io/helm-chart#development-releases-jupyterhub)

The JupyterHub Helm chart is accompanied with an installation guide at [z2jh.jupyter.org](https://z2jh.jupyter.org). Together they enable you to deploy [JupyterHub](https://jupyterhub.readthedocs.io) in a Kubernetes cluster that can make Jupyter environments available to several thousands of simultaneous users.

## 構築手順

初期構築手順
```bash
helm upgrade --install jupyter ./
```
更新手順
```bash
helm upgrade jupyter ./
```
削除手順
```bash
helm delete jupyter
```
