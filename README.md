# 🚀 DevFest GitOps Demo 🚀

[![docker](https://img.shields.io/badge/docker-3776AB?style=for-the-badge&logo=docker&logoColor=white)](https://img.shields.io/badge/docker-3776AB?style=for-the-badge&logo=docker&logoColor=white)
[![kubernetes](https://img.shields.io/badge/kubernetes-3776AB?style=for-the-badge&logo=kubernetes&logoColor=white)](https://img.shields.io/badge/kubernetes-3776AB?style=for-the-badge&logo=kubernetes&logoColor=white)
[![MIT licensed](https://img.shields.io/badge/license-mit-blue?style=for-the-badge&logo=appveyor)](./LICENSE)
[![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

This repo contains the `GitOps` code of my demo at `DevFest Dakar 2020` on `Continuous Deployment and GitOps in Kubernetes with ArgoCD`.

## Content

You'll find the following directories in this project :

- `infra`: contains manifest files in order to setup a local kubernetes cluster.
I often use [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/) to create local kubernetes cluster for experimenting and learning new stuff. Run the following command in order to create one :

```bash
kind create --config infra/cluster-setup.yaml --name devfest-dakar-2022
```

- The other folders `dev`, `staging` and `prod` host respectively the k8s manifest files for the [spring-boot demo app](https://gitlab.com/devfest-dakar-2022/demo-app).

## Contributing

Feel free to make a PR or report an issue 😃

Oh, one more thing, please do not forget to put a description when you make your PR 🙂

## Author

- [M.B.C.M](https://itdev.sn)
[![My Twitter Link](https://img.shields.io/twitter/follow/the_it_dev?style=social)](https://twitter.com/the_it_dev)

