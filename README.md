# **go-learning**

## **Setting up the environment**

To find image being used:

> https://hub.docker.com/_/golang/

Build image with:

> docker-compose build --force-rm

The flag ```--force-rm``` always remove intermediate containers.

---

When using ```tty``` flag in docker-compose file select service (defined in the docker-compose file) with:

> docker-compose run --rm <service_name> bash

The ```--rm``` flag deletes the container after exiting it.

## **Building and running**

### **Basics**

To build and run the code use:

> go run <file_name.go>

To only build use:

> go build <file_name.go>

To execute (Mac/Linux):

> ./<file_name.go>

### **Modules**

To create an module use:

> go mod init <module_name>
