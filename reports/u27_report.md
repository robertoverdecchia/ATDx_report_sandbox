
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](./json/onap_cli.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-ems.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-ems) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-ems) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-driver-ems.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-sfc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-sfc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-sfc) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-driver-sfc.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-multivimproxy.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-multivimproxy) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-multivimproxy) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-multivimproxy.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-resmanagement.json)</p>
# Project report summaries
## Project: _onap/cli_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_cli.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/cli) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_cli) <br> [Complete issue report (JSON)](./json/onap_cli.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                        |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------|
| OpenRemoteCli.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | grpc/grpc-client/src/main/java/org/open/infc/grpc/client/OpenRemoteCli.java |
| OnapCommand.java   |              3 |             0 |           3 |      0 |           0 |           0 |            0 | framework/src/main/java/org/onap/cli/fw/cmd/OnapCommand.java                |

## Project: _onap/vfc-nfvo-driver-ems_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-ems.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-ems) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-ems) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-driver-ems.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                            |
|:-------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------|
| MsgType.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | ems/boco/src/main/java/org/onap/vfc/nfvo/emsdriver/collector/alarm/MsgType.java |

## Project: _onap/vfc-nfvo-driver-sfc_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-sfc.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-sfc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-sfc) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-driver-sfc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                  |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------|
| DriverResource.java     |              8 |             0 |           8 |      0 |           0 |           0 |            0 | sfc-driver/src/main/java/org/onap/sfc/resources/DriverResource.java   |
| SdnServiceConsumer.java |              3 |             0 |           2 |      0 |           1 |           0 |            0 | sfc-driver/src/main/java/org/onap/sfc/service/SdnServiceConsumer.java |

## Project: _onap/vfc-nfvo-multivimproxy_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-multivimproxy.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-multivimproxy) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-multivimproxy) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-multivimproxy.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                               |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------|
| ServiceException.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | service/src/main/java/org/onap/vfc/nfvo/multivimproxy/common/util/restclient/ServiceException.java |

## Project: _onap/vfc-nfvo-resmanagement_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](./json/onap_vfc-nfvo-resmanagement.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                    |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------------------------|
| ServiceException.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/common/util/restclient/ServiceException.java |

