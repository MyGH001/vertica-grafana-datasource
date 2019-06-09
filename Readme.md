# Oracle Cloud Infrastructure Data Source for Grafana

## Introduction

This plugin makes queries to the Oracle Cloud Infrastructure Monitoring Service and displays them on Grafana.

If you are running Grafana on a machine instance in Oracle Cloud, use the Service Principal with a configured Dynamic Group and policy to allow you to read metrics and compartments.

If you are running Grafana anywhere else, make sure you have `~/.oci` configured properly. You can do this by installing the Oracle Cloud CLI and running the setup 

## Note

If you're using a version of Grafana that's older than 6.0, you will need to download the zip file and install this plugin manually, or chmod the binary that is downloaded to make it executable.

## Installation Documentation

In order to simplify the installation process, we created detailed guides for you to follow:

* Install Grafana and the Oracle Cloud Infrastructure Data Source for Grafana on a Linux host using [this document](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/linux.md).
* Install Grafana and the Oracle Cloud Infrastructure Data Source for Grafana on a MacOS host using [this document](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/macos.md).
* Install Grafana and the Oracle Cloud Infrastructure Data Source for Grafana on a virtual machine in Oracle Cloud Infrastructure using [this document](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/linuxoci.md).
* Install Grafana and the Oracle Cloud Infrastructure Data Source for Grafana on a virtual machine in Oracle Cloud Infrastructure using Terraform using [this document](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/terraform.md).
* Install Grafana and the Oracle Cloud Infrastructure Data Source for Grafana on Kubernetes in Oracle Cloud Infrastructure using [this document](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/kubernetes.md)

Once you have the data source installed, configure your datasource with your tenancy OCID, default region, and where you're running the plugin (Oracle Cloud or elsewhere).

We also have documentation for how to use the newly installed and configured plugin in our [Using Grafana with Oracle Cloud Infrastructure Data Source](https://github.com/oracle/oci-grafana-plugin/blob/master/docs/using.md) walkthrough.

