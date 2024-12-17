<!-- SPDX-FileCopyrightText: 2024 Zentrum für Digitale Souveränität der Öffentlichen Verwaltung (ZenDiS) GmbH SPDX-License-Identifier: Apache-2.0 -->

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add denkhaus https://denkhaus.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
denkhaus` to see the charts.

To install the nginx-s3-gateway chart:

    helm install my-nginx-s3-gateway denkhaus/nginx-s3-gateway

To uninstall the chart:

    helm delete my-nginx-s3-gateway
