
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-multivimproxy.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-multivimproxy) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-multivimproxy) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-multivimproxy.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-resmanagement.json)</p>
# Project report summaries
## Project: _onap/vfc-nfvo-multivimproxy_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-multivimproxy.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-multivimproxy) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-multivimproxy) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-multivimproxy.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                               |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------|
| ServiceException.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | service/src/main/java/org/onap/vfc/nfvo/multivimproxy/common/util/restclient/ServiceException.java |

## Project: _onap/vfc-nfvo-resmanagement_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-resmanagement.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                       |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------|
| ServiceException.java     |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/common/util/restclient/ServiceException.java    |
| SitesRoa.java             |              2 |             0 |           2 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/SitesRoa.java                      |
| LocationBusinessImpl.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/business/impl/LocationBusinessImpl.java |
| NsRoa.java                |              1 |             0 |           1 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/NsRoa.java                         |
| VnfRoa.java               |              1 |             0 |           1 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/VnfRoa.java                        |
| VmServiceImpl.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/group/impl/VmServiceImpl.java           |

