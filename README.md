<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/axoflow/axosyslog-docker/raw/main/docs/axoflow-logo-color.svg">
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/axoflow/axosyslog-docker/raw/main/docs/axoflow-logo-white.svg">
    <img alt="Axoflow" src="https://github.com/axoflow/axosyslog-docker/raw/main/docs/axoflow-logo-color.svg" width="550">
  </picture>
</p>

# AxoSyslog OpenTelemetry Demo Helm Chart - a cloud-native distribution of syslog-ng by Axoflow

This repository contains the OpenTelemetry Demo [chart](https://helm.sh/docs/topics/charts/) for [AxoSyslog](https://github.com/axoflow/axosyslog-docker), which is intended to make it convenient to install AxoSyslog's OpenTelemetry demonstration based on [OpenTelemetry Demo](https://github.com/open-telemetry/opentelemetry-demo).

You can read more about syslog-ng's and AxoSyslog's OpenTelemetry support in Axoflow's [blog post](https://axoflow.com/opentelemetry-support-in-more-detail-in-axosyslog-and-syslog-ng/).

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

## Contact and support

In case you need help or want to contact us, open a [GitHub issue](https://github.com/axoflow/opentelemetry-demo/issues), or come chat with us in the [syslog-ng channel of the Axoflow Discord server](https://discord.gg/4Fzy7D66Qq).

## About Axoflow

The [Axoflow](https://axoflow.com) founder team consists of successful entrepreneurs with a vast knowledge and hands-on experience about observability, log management, and how to apply these technologies in the enterprise security context. We also happen to be the creators of wide-spread open source technologies in this area, like syslog-ng and the [Logging operator for Kubernetes](https://github.com/kube-logging/logging-operator).

To learn more about our products and our open-source projects, visit the [Axoflow blog](https://axoflow.com/blog/), or [subscribe to the Axoflow newsletter](https://axoflow.com/#newsletter-subscription).
