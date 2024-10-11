
# Notable Things (and Problems)
This project was forked from [Azure Pet Store Learning Guide](https://github.com/chtrembl/azure-cloud/tree/main/petstore). 

## 00 Setup your environment
Upstream was set up, so to get any future changes to the following:
```
git fetch upstream
git checkout main
git merge upstream/main
```
## 03 Configure App Service for continuous deployment
Skipped to this step to utlize Azure DevOps Pipelines and GitHub Actions to do the build & deploys rather than do so locally. 

## 04 - Configure Git Hub Action for CI/CD into App Service
Delete the "Upload Maven build artifact" task to avoid errors when running Actions workflow.

## 05 - Create an Azure Kubernetes Cluster and configure NGINX Ingress controller
TODO