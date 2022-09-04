# Packer 101

> Packer lets you bake AMIs with your application / configuration thereby reducing a number of dependencies while actually making the deployment. 
> Packer creates deployable artifacts like AMIs and containers and decouples creation of artifacts from their deployment - djk29a

Benefits 

* "You can place multiple builders and share provisioners [to create a] plan that builds in Azure, AWS, Vsphere"

* Cloud Agnostic Image building

* Immutable sytem bulding

* Terraform Deployment


# So Far

I was able to build a Ubuntu based Docker Container using Packer.

Packer configuration is almost identical with Terraform, so its easy enough to pick up alongside it.

Next is provisioning this Docker image.
