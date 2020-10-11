
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](./json/onap_aai-schema-service.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdnc-northbound.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdnc-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdnc-northbound) <br> [Complete issue report (JSON)](./json/onap_sdnc-northbound.json)</p>
# Project report summaries
## Project: _onap/aai-schema-service_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](./json/onap_aai-schema-service.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| XSDElement.java       |             24 |             0 |          24 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/XSDElement.java       |
| NodesYAMLfromOXM.java |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/NodesYAMLfromOXM.java |
| YAMLfromOXM.java      |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/YAMLfromOXM.java      |
| HTMLfromOXM.java      |              4 |             3 |           1 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/HTMLfromOXM.java      |

## Project: _onap/sdnc-northbound_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdnc-northbound.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdnc-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdnc-northbound) <br> [Complete issue report (JSON)](./json/onap_sdnc-northbound.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnfapi/provider/src/main/java/org/onap/sdnc/vnfapi/VnfApiProvider.java |             0 |           0 |         0 |           0 |           1 |            0 |     1 |

