# helm-chart-webserver
This Repository contains the code for the helm chart which is used to launch the pod with httpd webserver having PHP
Helm is a package manager for Kubernetes. It behaves similar to other package managers (yum, apt, npm, maven, pip, gems) but it works at the application level allowing you to deploy multiple manifests together.

Helm offers several extra features on top of vanilla Kubernetes deployments, some of which are:

The ability to group multiple Kubernetes manifests together and treat them as a single entity (for deployments, rollbacks, and storage). Groups of Manifests are called Helm Charts.
Built-in templating for Kubernetes manifests, putting an end to custom template systems that you might use for replacing things such as the Docker tag inside a manifest.
The ability to create Charts of Charts which contain the templates as well as default values. This means that you can describe the dependencies of an application in the service level and deploy everything at the same time.
The ability to create catalogs of applications (Helm repositories) that function similar to traditional package repositories (think npm registry, cpan, maven central, ruby gems etc).
