Helm chart repo for unintented Helm charts, and helper charts to apply configuration.

Setup:
------

* configure repo for Github pages, public endpoint is https://mcsps.github.io/helm-charts/

Usage:
------

* put the chart packages into the repo
* (re-)create the repo index page

```
helm repo index --url https://mcsps.github.io/helm-charts/ .
```

Content:
--------

* [openstack-service-loadbalancer](charts/openstack-service-loadbalancer) -
  [(src)](https://github.com/mcsps/helm-charts/tree/master/charts/openstack-service-loadbalancer)
* [cinder-csi-snapshot-crds](charts/cinder-csi-snapshot-crds) - 
  [(src)](https://github.com/mcsps/helm-charts/tree/master/charts/cinder-csi-snapshot-crds)
* [cert-manager-crd](charts/cert-manager-crd) - 
  [(src)](https://github.com/mcsps/helm-charts/tree/master/charts/cert-manager-crd)
* [cert-manager-issuer](charts/cert-manager-issuer) - 
  [(src)](https://github.com/mcsps/helm-charts/tree/master/charts/cert-manager-issuer)
* [designate-certmanager-webhook/](charts/designate-certmanager-webhook) -
  [(src)](https://github.com/mcsps/helm-charts/tree/master/charts/designate-certmanager-webhook)


Credits:
--------

inspired by [@mattiaperi](https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417)

Frank Kloeker <f.kloeker@telekom.de>

Life is for sharing. If you have an issue with the code or want to improve it,
feel free to open an issue or an pull request.

