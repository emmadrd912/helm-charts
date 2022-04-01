## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

 ``
helm repo add emmadrd912 https://emmadrd912.github.io/helm-charts
 ``

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
` to see the charts.

To install the chart:

    helm install my-webserver emmadrd912/charts-tp4

To uninstall the chart:

    helm delete my-webserver

## Charts

**charts-tp4**

* 0.1.0 : 
	* denowebserver et mariadb déployés.
	* choix des values.

* 0.2.0 :
	* ajout d'un ingress.
	* mariadb en mode statefulset.
