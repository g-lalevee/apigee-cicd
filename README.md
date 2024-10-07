[![Generic badge](https://img.shields.io/badge/status-work--in--progress-important.svg)](https://shields.io/) 

***

:warning: **This is not an official Google product.**<BR>This implementation is not an official Google product, nor is it part of an official Google product. Support is available on a best-effort basis via GitHub.

***

<BR>

## <img src="https://github.com/g-lalevee/apigee-cicd/blob/main/apigee-logo.jpg?raw=true" alt="logo" width="40"/> Welcome to the apigee-cicd wiki! 

This wiki contains links to sample Apigee CI/CD implementations and tools, for [Apigee Edge/OPDK](https://docs.apigee.com/), [Apigee X/hybrid](https://cloud.google.com/apigee/docs/) + [Application Integration](https://cloud.google.com/apigee/docs/api-platform/integration/what-is-apigee-integration) & [Connectors](https://cloud.google.com/apigee/docs/api-platform/connectors/about-connectors).

<BR>


##  Apigee 

Simple Apigee proxy deployment using main pipeline solutions:

||  Pipeline |  API Proxy & Config. |  App. Integration (1)|  API Hub (2) | 
|---|---|---|---|---|
|<img src="https://cdn.iconscout.com/icon/free/png-256/azure-devops-3628645-3029870.png" width="30"> |  Azure Pipeline | [My GitHub](https://github.com/g-lalevee/Apigee-Simple-Azure-Pipeline) <sup>\*</sup> | [My GitHub](https://github.com/g-lalevee/AppInt-Simple-Azure-Pipeline) | - |
<img src="https://seeklogo.com/images/B/bitbucket-logo-D072214725-seeklogo.com.png" width="30"> | Bitbucket | [My Bitbucket](https://bitbucket.org/g-lalevee/apigee-simple-bitbucket-pipeline) <sup>\*</sup> | - | - |
|<img src="https://avatars.githubusercontent.com/u/5055988" width="30"> | Buildkite |  [My GitHub](https://github.com/g-lalevee/Apigee-Simple-buildkite-Pipeline) | - | - |
|<img src="https://a.slack-edge.com/80588/img/plugins/circleci/service_512.png" width="30"> | CircleCI |  [My GitHub](https://github.com/g-lalevee/Apigee-Simple-CircleCI-Pipeline) | - | - |
|<img src="https://raw.githubusercontent.com/phylus-alpha/phylus/master/images/github.png" width="30"> |  GitHub | [My GitHub](https://github.com/g-lalevee/Apigee-Simple-Github-Pipeline) <sup>\*</sup> |  -  | - |
| <img src="https://about.gitlab.com/images/logo.png" width="30"> |  GitLab | [My GitLab](https://gitlab.com/clalevee/apigee-simple-gitlab_ci-pipeline-v2) <sup>\*</sup> | [My GitLab](https://gitlab.com/clalevee/appint-simple-gitlab_ci-pipeline) |  -  |
|<img src="https://avatars.githubusercontent.com/u/38220399?s=200&v=4" width="30"> |  Google Cloud Build | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-pipeline)   <img src="https://github.com/g-lalevee/apigee-cicd/blob/main/apigee-logo.jpg?raw=true" alt="logo" width="20"/>  |  - | - |
|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Jenkins_logo.svg/1200px-Jenkins_logo.svg.png" width="30"> |  Jenkins | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-pipeline)   <img src="https://github.com/g-lalevee/apigee-cicd/blob/main/apigee-logo.jpg?raw=true" alt="logo" width="20"/>  | - | - |

<sup>\*</sup> Updated with OAS file test using stoplight spectral
  
(1) End to end deployment and testing of an [Apigee Connector](https://cloud.google.com/apigee/docs/api-platform/connectors/about-connectors) (Google BigQuery), an [Application Integration](https://cloud.google.com/apigee/docs/api-platform/integration/what-is-apigee-integration) workflow.

(2) API SDLC ("design-first" approach) illustration relying on [Apigee API hub](https://cloud.google.com/apigee/docs/api-hub/what-is-api-hub) and Apigee X/hybrid 
<BR>

##  Apigee Complementary tools

|  Tool |  Link | Description | 
|---|---|---|
|  CICD Pipeline for SharedFlows | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-sharedflow-pipeline) <img src="https://github.com/g-lalevee/apigee-cicd/blob/main/apigee-logo.jpg?raw=true" alt="logo" width="20"/>  |  CI/CD pipeline for Apigee sharedflow using the Apigee Deploy Maven Plugin |
|  Apigee X Environment Selector | [My GitHub](https://github.com/g-lalevee/apigee-envselector) | Select CI/CD pipeline target environment from an Environment Group |

<BR>




