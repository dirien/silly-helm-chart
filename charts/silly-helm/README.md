# Silly Helm Chart

![Version: 0.1.4](https://img.shields.io/badge/Version-0.1.4-informational?style=for-the-badge)
![Type: application](https://img.shields.io/badge/Type-application-informational?style=for-the-badge)
![AppVersion: 0.1.0](https://img.shields.io/badge/AppVersion-0.1.0-informational?style=for-the-badge)

## Description
This is a very silly Helm chart, which is applying some Kubernetes resources without any real purpose.

## Usage

Please add the silly-helm repository before installing any chart provided by this repository:

```bash
helm repo add silly-helm https://dirien.github.io/silly-helm-chart
helm repo update
```

If you use the OCI capability of Helm 3, you don't need to add the repository, but you can directly install the chart:

```bash
helm install silly-helm oci://ghcr.io/dirien/charts/silly-helm --version 0.1.4
```

### Installing the Chart (non-OCI)

To install the chart with the release name silly-helm run:

```bash
helm install silly-helm silly-helm/silly-helm --version 0.1.4
```

