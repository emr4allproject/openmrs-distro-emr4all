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

```bash
The new OpenMRS UI is accessible at http://<DOMAIN>/openmrs/spa

OpenMRS Legacy UI is accessible at http://<DOMAIN>/openmrs
```

You can optionally deploy the openmrs_sync_bundle to your Raspbery PI and set this distro up as your remote distro with the following [instructions](https://github.com/emr4allproject/openmrs_sync_bundle#README.md). 



