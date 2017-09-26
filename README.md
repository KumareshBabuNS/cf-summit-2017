# cf-summit-2017
Presentation and demos for 
[Manage Distributed Secrets in Applications on Cloud Foundry With Spring Cloud Vault](https://cfeu17.sched.com/event/Bity) at 
[CloudFoundry Summit Europe 2017](https://www.cloudfoundry.org/event/europe-2017).

## Spring Vault Demo

This demonstrates the usage of the _transit_ secret backend of vault in a typical spring boot based web application with JPA.
In this sample sensible data like social security and credit card numbers are encrypted before storing in the database and
decrypted before returning these to the rest api.


