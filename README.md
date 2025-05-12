# Somalia EMR OpenMRS 3.0 Application

This project holds the build configuration for the Somalia EMR OpenMRS 3.0 application.

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
docker compose -p somalia-emr up -d
```

OR 

```
docker-compose -p somalia-emr up -d 
```

The new OpenMRS UI is accessible at http://localhost/openmrs/spa

OpenMRS Legacy UI is accessible at http://localhost/openmrs
