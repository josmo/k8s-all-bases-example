[![Build Status](https://drone.pelo.tech/api/badges/josmo/k8s-all-bases-example/status.svg)](https://drone.pelo.tech/josmo/k8s-all-bases-example)
![Release Status](https://img.shields.io/badge/status-beta-yellow.svg?style=flat)
[![](https://images.microbadger.com/badges/image/josmo/k8s-all-bases-example.svg)](https://microbadger.com/images/josmo/k8s-all-bases-example "Get your own image badge on microbadger.com")

# K8s all bases example

### About

* Simple docker nginx app
* K8s with external-dns and cert-manager working to auto create dns and lts
* Drone for deployments and promotion from master -> staging -> prod
* Quick add of build number and commit sha
