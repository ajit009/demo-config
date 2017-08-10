# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured docker services

### Service registry and configuration server:
- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:
- employeeOps (microservice application)
- employeeOps's postgresql database
- employeeOps's elasticsearch search engine
- portalEmp (gateway application)
- portalEmp's postgresql database
- portalEmp's elasticsearch search engine
- taskOps (microservice application)
- taskOps's postgresql database
- taskOps's elasticsearch search engine

### Additional Services:

- [JHipster Console](http://localhost:5601)
Once started, it will be necessary to create the index pattern using the UI and start the `jhipster-import-dashboards` container again with: `docker-compose up jhipster-import-dashboards`
- [Zipkin](http://localhost:9400)
