# [`unbound`](https://charts.nodecloud.tech/charts/unbound/)

> A Helm chart for unbound DNS resolver.


## Requirements

- [`helm`](https://helm.sh) - Refer to their [docs](https://helm.sh/docs) to get started.

## Usage

To use this chart add the repo as follows:

```sh
helm repo add nodecloud https://charts.nodecloud.tech
```

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.

To install this chart simply run the following command:

```sh
helm install unbound nodecloud/unbound --namespace=unbound --create-namespace
```

To uninstall this chart simply run the following command:

```sh
helm uninstall unbound --namespace=unbound
```

## License

[MIT](../LICENSE.md) – © 2023 NodeCloud