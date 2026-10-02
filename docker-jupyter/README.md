# Docker & JupyterLab

This section documents the deployment of JupyterLab inside a Docker container hosted on Ubuntu Server and its remote access from Windows Server.

The objective was to provide a containerized data analysis environment while maintaining controlled access through the internal network.

## Docker Deployment

Ubuntu Server was used as the Docker host.

The JupyterLab environment was deployed using the image:

```text
jupyter/base-notebook
