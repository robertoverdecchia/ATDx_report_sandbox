
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/onap_vnfsdk-functest.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-functest) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-functest) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-functest.json)</p>|<img src="./plots/onap_vnfsdk-refrepo.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-refrepo.json)</p>|<img src="./plots/onap_vnfsdk-validation.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-validation.json)</p>
 | |

# Project report summaries
## Project: _onap/vnfsdk-functest_
|./plots/onap_vnfsdk-functest.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-functest) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-functest) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-functest.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                           |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnf-sdk-function-test/src/main/java/org/onap/vnfsdk/functest/models/TaskRecord.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/vnfsdk-refrepo_
|./plots/onap_vnfsdk-refrepo.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-refrepo.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vnfsdk/marketplace/db/wrapper/BaseHandler.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/VTPResource.java                           |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/vnfsdk-validation_
|./plots/onap_vnfsdk-validation.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](./json/onap_vnfsdk-validation.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| ValidationException.java |              3 |             1 |           2 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/ValidationException.java |

