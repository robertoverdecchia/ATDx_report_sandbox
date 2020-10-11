
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/onap_appc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/appc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_appc) <br> [Complete issue report (JSON)](./json/onap_appc.json)</p>|<img src="./plots/onap_optf-fgps.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](./json/onap_optf-fgps.json)</p>
# Project report summaries
## Project: _onap/appc_
|./plots/onap_appc.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/appc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_appc) <br> [Complete issue report (JSON)](./json/onap_appc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                               |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------------------------------|
| DGGeneralDBService.java     |             25 |             0 |          25 |      0 |           0 |           0 |            0 | appc-config/appc-data-services/provider/src/main/java/org/onap/appc/data/services/db/DGGeneralDBService.java                       |
| DesignDBService.java        |             19 |             0 |          19 |      0 |           0 |           0 |            0 | appc-inbound/appc-design-services/provider/src/main/java/org/onap/appc/design/dbervices/DesignDBService.java                       |
| RequestValidator.java       |             11 |             0 |          10 |      0 |           1 |           0 |            0 | appc-inbound/appc-interfaces-service/bundle/src/main/java/org/onap/appc/interfaces/service/executor/RequestValidator.java          |
| ConfigComponentAdaptor.java |              8 |             0 |           6 |      0 |           2 |           0 |            0 | appc-config/appc-config-adaptor/provider/src/main/java/org/onap/appc/ccadaptor/ConfigComponentAdaptor.java                         |
| FlowSequenceGenerator.java  |              7 |             0 |           7 |      0 |           0 |           0 |            0 | appc-config/appc-flow-controller/provider/src/main/java/org/onap/appc/flow/controller/node/FlowSequenceGenerator.java              |
| RequestFailedException.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | appc-adapters/appc-iaas-adapter/appc-iaas-adapter-bundle/src/main/java/org/onap/appc/adapter/iaas/impl/RequestFailedException.java |
| ArtificatTransformer.java   |              6 |             0 |           6 |      0 |           0 |           0 |            0 | appc-config/appc-config-params/provider/src/main/java/org/onap/sdnc/config/params/transformer/ArtificatTransformer.java            |
| ParseAdminArtifcat.java     |              6 |             0 |           6 |      0 |           0 |           0 |            0 | appc-config/appc-encryption-tool/provider/src/main/java/org/onap/appc/encryptiontool/fqdn/ParseAdminArtifcat.java                  |
| RequestFailedException.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | appc-adapters/appc-rest-adapter/appc-rest-adapter-bundle/src/main/java/org/onap/appc/adapter/rest/impl/RequestFailedException.java |
| ArtifactHandlerNode.java    |              5 |             0 |           5 |      0 |           0 |           0 |            0 | appc-inbound/appc-artifact-handler/provider/src/main/java/org/onap/appc/artifact/handler/node/ArtifactHandlerNode.java             |

## Project: _onap/optf-fgps_
|./plots/onap_optf-fgps.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](./json/onap_optf-fgps.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                           |
|:----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------|
| AAFProxy.java   |              6 |             0 |           0 |      0 |           5 |           1 |            0 | valetapi/src/main/java/org/onap/fgps/api/proxy/AAFProxy.java   |
| CipherUtil.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | valetapi/src/main/java/org/onap/fgps/api/utils/CipherUtil.java |

