# Emr4all Distribution OpenMRS 3.0 Application

This project holds the build configuration for the emr4all EMR OpenMRS 3.0 application.

## Quick start

### Package the distribution and prepare the run

```
docker compose build
```

OR 

```
docker-compose build 
```

### Run the app

```
docker compose -p emr4all-emr up -d
```

OR 

```
docker-compose -p emr4all-emr up -d 
```

The new OpenMRS UI is accessible at http://localhost/openmrs/spa

OpenMRS Legacy UI is accessible at http://localhost/openmrs
