# Helm chart for AxoSyslog OpenTelemetry Demo.

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/opentelemetry)](https://artifacthub.io/packages/search?org=axoflow&repo=opentelemetry)
![Kubernetes Version](https://img.shields.io/badge/k8s%20version-%3E=1.19-3f68d7.svg?style=flat-square)


## How to use

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add axosyslog-opentelemetry-demo https://axoflow.github.io/opentelemetry-helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
axosyslog-opentelemetry-demo` to see the charts.

To install the opentelemetry-demo chart:

    helm install my-axosyslog-opentelemetry-demo axosyslog-opentelemetry-demo/opentelemetry-demo

To uninstall the chart:

    helm delete my-axosyslog-opentelemetry-demo



## Usage

[Helm](https://helm.sh) must be installed to use these charts.
Please refer to the [official documentation](https://helm.sh/docs/intro/install/) to get started.

```bash
helm repo add axosyslog-opentelemetry-demo https://axoflow.github.io/opentelemetry-helm-charts
```

You can then see the charts by running:

```bash
helm search repo axosyslog-opentelemetry-demo
```

You can install charts using the following command:

```bash
helm install --generate-name axosyslog-opentelemetry-demo/opentelemetry-demo
# OR
helm install --name my-axosyslog-opentelemetry-demo axosyslog-opentelemetry-demo/opentelemetry-demo
```

> **Tip**: List all installed releases using `helm list`.

To uninstall a chart release:

```bash
helm delete my-axosyslog-opentelemetry-demo
```
