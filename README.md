# Bahmni Forms OpenMRS Module
This module is responsible for manipulating Bahmni forms and their translations.

## Building command
### Build and Testing
```
mvn package -P deploy-web -D deploy.path="../../openmrs-1.8.x/webapp/src/main/webapp"
```

### Build and Skip Testing
```
mvn package -P deploy-web -D deploy.path="../../openmrs-1.8.x/webapp/src/main/webapp" -Dmaven.test.skip=true
```