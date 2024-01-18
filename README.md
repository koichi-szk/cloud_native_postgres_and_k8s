# cloud_native_postgres_and_k8s

# Cloud Native PostgreSQL and Kubernetes

This repository is Koichi Suzuki's material to use Cloud Native PostgreSQL (CNPG) over Kubernetes cluster.   This includes:

I picked up Ubuntu 22.04 for initial environment.
Magerial for other Linux distro will be covered laer.

* How to configure servers, --> 01 Server Configuration
* Consideration and background of Kubernetes environment installation and configuration, --> 02 Kubernetes environemt background
* Installation and configuration of cluser runtime interface, -> 03 Installing CRI (cluster-runtime-interface)
 * CRI-O, at present
* Installation of Kubernetes tools, --> 04 Installing Kubernetes tools
* Building Kubernetes cluster, --> 05 Building Kubernetes cluster
* Inatallation of Kubernetes CNI plugin, --> 06 Installing Kubenetes CNI plugin
* Installation of Cloud Native PostgreSQL --> 07 Installation of Cloud Native PostgreSQL
* Installation of Cloud Native PostgreSQL plugin, --> 08 Installation of CNPG plugin
* Preparation of permanent volumn for each PostgreSQL pod, --> 09 Permanent volumn preparation
 * Preparation of storageClass,
 * Creating permanentVolumes,
* Simple CNPG manifesto, --> 10 Simple CNPG manifesto
* Starting CNPG,--> 11 Starting CNPG
* Checking CNPG resources, --> Checking CNPG resources
