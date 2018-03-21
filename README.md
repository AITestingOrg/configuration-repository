# Microservices Configuration Repository

Repository to store all configuration files for Microservices project

Following the standard on naming the configuration files the structure will be as follows:

/{application}/{application}-{profile}.yml

{application} maps to "spring.application.name" on the client side;

{profile} maps to "spring.profiles.active" on the client (comma separated list); and

{label} Git Label when files were committed.

E.g.:
/user-service/user-service-dev.yml [label: v1]