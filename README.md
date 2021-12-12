# Simple Container Based App 

## Build containerized app using the App Studio Build Infrastructure 

This repo contains a a simple container based app that can be built on a bootstrapped App Studio build environment.
The application itself can run and shows a simple web page with these same instructions using a simple node.js server to serve up HTML pages. 

Try it out by cloning `https://github.com/redhat-appstudio/infra-deployments.git`  and setting up your cluster to run the build pipeline.
 
| Step    |    |
| ----------- | ----------- |
| 1.  Bootstrap your cluster    |  hack/bootstrap.sh    |
| 2.  Create project for your pipelines execution. This can be run as any non-admin user (or admin)    |  oc new-project demo     |  
| 3.  Run a build on this repo. |  hack/build/build.sh  https://github.com/jduimovich/single-nodejs-app       |
| 4.  View your build on the OpenShift Console under the pipelines page or view the logs via CLI. |  `tkn.exe pipelinerun logs`   


 hack
Change 2021-12-12-104538 
Change 2021-12-12-104604 
Change 2021-12-12-104647 
Change 2021-12-12-105044 
Change 2021-12-12-105101 
Change 2021-12-12-110102 
Change 2021-12-12-111103 
Change 2021-12-12-112103 
Change 2021-12-12-113104 
Change 2021-12-12-114105 
