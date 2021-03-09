[![CircleCI](https://circleci.com/gh/giantswarm/cass-operator-app.svg?style=shield)](https://circleci.com/gh/giantswarm/cass-operator-app)

# cass-operator chart

Giant Swarm offers the DataStax Kubernetes Operator for Apache Cassandra which can be installed in workload clusters.
Here we define the cass-operator chart with its templates and default configuration.

The DataStax Kubernetes Operator for Apache Cassandra® can be used to manage Cassandra on Kubernetes

## Installing

There are 3 ways to install this app onto a workload cluster.

1. [Using our web interface](https://docs.giantswarm.io/ui-api/web/app-platform/#installing-an-app)
2. [Using our API](https://docs.giantswarm.io/api/#operation/createClusterAppV5)
3. Directly creating the [App custom resource](https://docs.giantswarm.io/ui-api/management-api/crd/apps.application.giantswarm.io/) on the management cluster.

## Configuring

Configuration values are documented in [`helm/cass-operator/README.md`](https://github.com/giantswarm/cass-operator-app/blob/master/helm/cass-operator/README.md).

See our [full reference page on how to configure applications](https://docs.giantswarm.io/app-platform/app-configuration/) for more details.

## Compatibility

This app has been tested to work with the following workload cluster release versions:

* Kubernetes >= 1.19.x

## Credit

* https://github.com/GoogleCloudPlatform/spark-on-k8s-operator/tree/master/charts/spark-operator-chart
