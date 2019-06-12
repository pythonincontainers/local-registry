# local-registry
Examples for "Running Local Registries" Lesson

Use:

$ docker-compose up -d

to bring up three Containers:

- Local Docker Registry available at port 5551
- docker-registry-ui configured to manage Local Docker Registry, available at http://localhost:8880
- Proxy Docker Registry available at port 5552
