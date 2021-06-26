# Helm chart repository

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
helm repo add khuedoan https://khuedoan.github.io/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.
You can then run `helm search repo khuedoan` to see the charts.

To install the `cloudflared` chart:

```sh
helm install cloudflared khuedoan/cloudflared
```

To uninstall the chart:

```sh
helm delete cloudflared
```
