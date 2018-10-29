# Jira on Openshift

This repo provides the necessary files to run Jira on Openshift.

Setting up is straight forward, add the project to Openshift through the CLI so you can point your build image to this
github repo.  Openshift will automatically build the build container from the files in this repo.

https://docs.openshift.com/enterprise/3.0/dev_guide/new_app.html

You can override the <code>JIRA_CLUSTER_CONFIG</code> environment variable with anything to make Jira run in non-cluster mode.

This is important if you do not have a Jira cluster license.


