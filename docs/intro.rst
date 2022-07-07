Introduction
============

Nowadays, more and more services are dynamically deployed in Cloud environments. Usually,
the services hosted on virtual machines in Cloud are accessible only via IP addresses or
pre-configured hostnames given by the target Cloud providers, making it difficult to provide
them with meaningful domain names. Dynamic DNS services exist to alleviate this problem, but
none of them is scoped to the Academic realm.

The eduDNS service is designed to provide a universal, vendor-independent Dynamic DNS support
for all GÉANT users. Service owners will log in the eduDNS portal via eduGAIN, register
meaningful, memorable hostnames (e.g. service-portal.vm.edudns.eu), assign the hostname to
their servers then provide access to their services via the hostnames.

eduDNS helps to simplify the deployment of services that are dynamically deployed in Cloud
infrastructures. It removes the obstacles of changing IP addresses of services in Cloud at every
deployment and enables obtaining SSL certificates for the hostnames. Service providers can
migrate services from local servers to Cloud or from a Cloud site to another without noticing
users from the change.
