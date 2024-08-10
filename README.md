#  Implementing GitOps with Jenkins on Openshift


In this lab, you implement a GitOps workflow to automate the Samples cluster operator configuration and remove some of the standard templates from your cluster.

## Openshift Cluster Samples Operator
The Cluster Samples Operator manages the sample image streams and templates that OpenShift provides in the openshift namespace. It operates during the installation and 
pgrades of OpenShift and also monitors the openshift namespace to prevent accidental deletion of the sample resources.

## Outcomes
You should be able to:

• Deploy a Jenkins instance with cluster administration rights.

• Complete and deploy a Jenkins pipeline that applies settings for the Cluster Samples Operator.

• Use YAML resource files to exclude standard templates for Ruby on Rails applications from your cluster and configure the Cluster Samples Operator so these templates are not recreated.

• Generate a Jenkins API token.

