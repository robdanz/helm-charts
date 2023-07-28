## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add robdanz https://robdanz.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
robdanz` to see the charts.

To install the cloudflare-tunnel-remote chart:

    helm install my-cloudflare-tunnel-remote robdanz/cloudflare-tunnel-remote

To uninstall the chart:

    helm delete my-cloudflare-tunnel-remote
