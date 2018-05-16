# Microservices Configuration Repository

This repository stores all the configuration files of the Microservices project. The Configuration Service retrieves the files from this repository.

Following the standard on naming the configuration files the structure will be as follows:

```
/{application}/{application}-{profile}.yml
```

{application} maps to `spring.application.name` on the client side;

{profile} maps to `spring.profiles.active` on the client side; and

##### Example for Userservice

```
/userservice/userservice-dev.yml [label: v1]
```