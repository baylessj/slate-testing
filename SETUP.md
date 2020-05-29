# Setup instructions

Recommended to run this locally, the docker container didn't work well for me.

- Generate Swagger.yaml file from backend with drf-yasg
- Download the yaml file from localhost:8000/swagger.yaml
- Using npm's swagger-to-slate, generate the markdown index file from the downloaded swagger yaml file `swagger-to-slate -i /path/to/swagger.yaml`

