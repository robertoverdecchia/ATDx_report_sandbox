
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_cli.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-refrepo.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-validation.json)</p>
 | |

# Project report summaries
## Project: _onap/cli_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_cli.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                       |
|:-------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------|
| OpenRemoteCli.java                   |              4 |             0 |           4 |      0 |           0 |           0 |            0 | grpc/grpc-client/src/main/java/org/open/infc/grpc/client/OpenRemoteCli.java                |
| OnapCommand.java                     |              3 |             0 |           3 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/cmd/OnapCommand.java                               |
| OnapCommandArtifactStore.java        |              2 |             0 |           2 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/store/OnapCommandArtifactStore.java                |
| OnapCommandDiscoveryUtils.java       |              2 |             0 |           1 |      0 |           1 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/utils/OnapCommandDiscoveryUtils.java               |
| OpenInterfaceGrpcClient.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | grpc/grpc-client/src/main/java/org/open/infc/grpc/client/OpenInterfaceGrpcClient.java      |
| OnapCommandSchemaSnmpLoader.java     |              2 |             0 |           1 |      0 |           1 |           0 |            0 | profiles/snmp/src/main/java/org/onap/cli/fw/snmp/schema/OnapCommandSchemaSnmpLoader.java   |
| OnapCommandSchemaCmdLoader.java      |              1 |             0 |           1 |      0 |           0 |           0 |            0 | profiles/command/src/main/java/org/onap/cli/fw/cmd/schema/OnapCommandSchemaCmdLoader.java  |
| ProcessRunner.java                   |              1 |             0 |           1 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/utils/ProcessRunner.java                           |
| OnapCommandExceutionShowCommand.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/cmd/execution/OnapCommandExceutionShowCommand.java |
| MockResponse.java                    |              1 |             0 |           1 |      0 |           0 |           0 |            0 | validate/sample-mock-generator/src/main/java/org/onap/cli/http/mock/MockResponse.java      |

## Project: _onap/vnfsdk-refrepo_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-refrepo.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                   |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------|
| VTPExecutionResource.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/execution/VTPExecutionResource.java        |
| BaseHandler.java          |              1 |             0 |           1 |      0 |           0 |           0 |            0 | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vnfsdk/marketplace/db/wrapper/BaseHandler.java |
| VTPResource.java          |              1 |             0 |           1 |      0 |           0 |           0 |            0 | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/VTPResource.java                           |

## Project: _onap/vnfsdk-validation_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-validation.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| ValidationException.java   |              3 |             1 |           2 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/ValidationException.java   |
| ValidatorSchemaLoader.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/ValidatorSchemaLoader.java |
| VTPValidateCSARBase.java   |              1 |             0 |           1 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/cvc/csar/cc/VTPValidateCSARBase.java       |
| CsarUtil.java              |              1 |             0 |           0 |      0 |           1 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/CsarUtil.java              |
| ManifestFileSplitter.java  |              1 |             0 |           0 |      0 |           0 |           0 |            1 | csarvalidation/src/main/java/org/onap/cvc/csar/parser/ManifestFileSplitter.java  |
| CsarValidator.java         |              1 |             0 |           0 |      0 |           1 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/CsarValidator.java         |

