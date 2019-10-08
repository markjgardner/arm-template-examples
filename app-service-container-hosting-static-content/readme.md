## Hosting static content on App Service for Containers

This template will create an azure app service runing nginx in a container. The static content to be served is stored in a blob container and mapped to the running app via volume mounts. Two deployment slots are created and mapped to separate volumes to allow for content review prior to publishing (via slot swap).

### Resources created
1 Linux app service plan
1 App service
  1 Additional Deployment slot
1 Storage account
  2 Blob containers