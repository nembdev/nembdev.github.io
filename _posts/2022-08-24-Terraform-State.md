# Key facts about Terraform State

State is a necessary and vital requirement for Terraform to function

State is the database that keeps track of resource to remote object mappings.

While it is not "real-time" it allows cloud infra to scale at large.

* 1:1 resource to remote object mapping 
* Metadata is tracked and stored 
* Attribute values are cached
* Use planning options to avoid rate limits 
* Remote state can be used to lock and avoid collisions
