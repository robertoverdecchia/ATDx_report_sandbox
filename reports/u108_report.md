
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](./json/onap_cli.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-refrepo.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-validation.json)</p>
 | |

# Project report summaries
## Project: _onap/cli_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](./json/onap_cli.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                        |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------|
| OpenRemoteCli.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | grpc/grpc-client/src/main/java/org/open/infc/grpc/client/OpenRemoteCli.java |
| OnapCommand.java   |              3 |             0 |           3 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/cmd/OnapCommand.java                |

## Project: _onap/vnfsdk-refrepo_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-refrepo.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vnfsdk/marketplace/db/wrapper/BaseHandler.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/VTPResource.java                           |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/vnfsdk-validation_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-validation.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| ValidationException.java |              3 |             1 |           2 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/ValidationException.java |

