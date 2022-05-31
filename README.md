

<!-- toc -->

- [Node.js sample app on OpenShift!](#nodejs-sample-app-on-openshift)
  * [OpenShift Origin v3 setup](#openshift-origin-v3-setup)
    + [Running a virtual machine with Vagrant](#running-a-virtual-machine-with-vagrant)
    + [Running a virtual machine managed by minishift](#running-a-virtual-machine-managed-by-minishift)
    + [Starting a Docker container](#starting-a-docker-container)
    + [Downloading the Binary](#downloading-the-binary)
    + [Running an Ansible playbook](#running-an-ansible-playbook)
  * [Creating a project](#creating-a-project)
  * [Creating new apps](#creating-new-apps)
    + [Create a new app from source code (method 1)](#create-a-new-app-from-source-code-method-1)
    + [Create a new app from a template (method 2)](#create-a-new-app-from-a-template-method-2)
    + [Build the app](#build-the-app)
    + [Deploy the app](#deploy-the-app)
    + [Configure routing](#configure-routing)
    + [Create a new app from an image (method 3)](#create-a-new-app-from-an-image-method-3)
    + [Setting environment variables](#setting-environment-variables)
    + [Success](#success)
    + [Pushing updates](#pushing-updates)
  * [Debugging](#debugging)
  * [Web UI](#web-ui)
  * [Looking for help](#looking-for-help)
  * [Compatibility](#compatibility)
  * [License](#license)

<!-- tocstop -->

## Node.js sample app on OpenShift!
-----------------

This example will serve a welcome page and the current hit count as stored in a database.

