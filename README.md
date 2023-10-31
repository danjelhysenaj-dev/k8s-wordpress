# k8s-wordpress

HELM
====

In order to setup Wordpress way easier rather creating manifests one by one there comes into the game a Package Manager called HELM.
Helm figures out all the Persistence Volumes,Services,Deployments etc for you.

To setup on your environment follow these steps below:

---
    helm install wordpress
    helm upgrade wordpress
    #To rollback version
    helm rollback wordpress 
    helm unistall wordpress
---
