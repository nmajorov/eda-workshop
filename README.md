# Event-Driven Architecture Workshop

## Prepare OpenShift

This demo has been tested in Red Hat OpenShift Container Platform 4.7 version.

As a normal user in your OpenShift cluster, create a ```eda-workshop``` namespace:

```shell script
❯ oc login -u user
❯ oc new-project eda-workshop
```

## Deploy Operators

Follow [the instructions](./01-operators/README.md)

## Deploy Metrics Platform

Follow [the instructions](./02-metrics/README.md)

## Deploy Streaming Platform

Follow [the instructions](./04-kafka/README.md)

## Deploy Service Registry

Follow [the instructions](./05-service-registry/README.md)

## Deploy DataGrid

Follow [the instructions](./07-datagrid/README.md)