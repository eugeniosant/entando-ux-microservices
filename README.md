# entando-ux-microservices

```entando-ux-microservices``` is an project that contains a "poc" of the architecture of microservice for the next version of entando (5.0). 

The **Entando UX-Microservices** project includes the following modules:

* **admin-console-webapp**, sample of an Entando microservice based on engine and admin-console core components 
(see [entando-core](https://github.com/entando/entando-core)), useful to provides services of a single plugin/functionality (in this case the services of the plugin "Web Dynamic Form").

* **ems-auth-provider**, sample of an Entando microservice useful to provides services of an "Authentication Provider", used by any other entando instance (Microservice or not).

* **portalexample**, sample of an Entando portal application based on ```engine```, ```admin-console```, ```portal-ui core``` components. In "entando-ux-microservices" it consume the services provided by "admin-console-webapp" and "ems-auth-provider".
