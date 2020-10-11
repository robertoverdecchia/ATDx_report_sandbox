
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-api.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-auth-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-impl.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-engine.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-engine) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-engine) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-engine.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-event.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-event) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-event) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-event.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-analyser.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-analyser) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-analyser) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-analyser.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-cpconverter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-cpconverter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-cpconverter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-cpconverter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-extension-apiregions.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-extension-apiregions) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-extension-apiregions) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-extension-apiregions.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-io.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-io) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-io) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-io.json)</p>

# Project report summaries
## Project: _apache/sling-org-apache-sling-api_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| ResourceProviderDTO.java |             10 |             0 |           0 |      0 |          10 |           0 |            0 | src/main/java/org/apache/sling/api/resource/runtime/dto/ResourceProviderDTO.java |
| ResourceUtil.java        |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceUtil.java                    |
| SlingConstants.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/SlingConstants.java                           |
| ResourceChange.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/resource/observation/ResourceChange.java      |
| CompositeValueMap.java   |              3 |             2 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/api/wrappers/CompositeValueMap.java               |
| NonExistingResource.java |              3 |             3 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/api/resource/NonExistingResource.java             |

## Project: _apache/sling-org-apache-sling-auth-core_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-auth-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                            |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------|
| AbstractAuthenticationHandler.java |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/auth/core/spi/AbstractAuthenticationHandler.java |

## Project: _apache/sling-org-apache-sling-discovery-impl_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-impl.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                    |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------|
| DiscoveryServiceImpl.java |              4 |             0 |           2 |      0 |           1 |           0 |            1 | src/main/java/org/apache/sling/discovery/impl/DiscoveryServiceImpl.java |
| View.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/discovery/impl/common/View.java          |

## Project: _apache/sling-org-apache-sling-engine_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-engine.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-engine) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-engine) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-engine.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| EngineConstants.java             |              8 |             0 |           0 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/engine/EngineConstants.java                          |
| SlingServletContext.java         |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/engine/impl/helper/SlingServletContext.java          |
| SlingServletResponseAdapter.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/engine/impl/adapter/SlingServletResponseAdapter.java |
| Util.java                        |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/engine/impl/parameters/Util.java                     |

## Project: _apache/sling-org-apache-sling-event_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-event.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-event) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-event) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-event.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                 |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------|
| QueueServices.java             |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/event/impl/jobs/queues/QueueServices.java             |
| JobQueueImpl.java              |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/event/impl/jobs/queues/JobQueueImpl.java              |
| Environment.java               |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/event/impl/support/Environment.java                   |
| QueueConfigurationManager.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/event/impl/jobs/config/QueueConfigurationManager.java |
| ScheduledJobHandler.java       |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/event/impl/jobs/scheduling/ScheduledJobHandler.java   |

## Project: _apache/sling-org-apache-sling-feature-analyser_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-analyser.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-analyser) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-analyser) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-analyser.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                     |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------|
| CheckBundleExportsImports.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/feature/analyser/task/impl/CheckBundleExportsImports.java |

## Project: _apache/sling-org-apache-sling-feature-cpconverter_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-cpconverter.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-cpconverter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-cpconverter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-cpconverter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| BaseVaultPackageScanner.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/cpconverter/vltpkg/BaseVaultPackageScanner.java |

## Project: _apache/sling-org-apache-sling-feature-extension-apiregions_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-extension-apiregions.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-extension-apiregions) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-extension-apiregions) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-extension-apiregions.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                          |
|:-----------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------------------------------------|
| CheckApiRegionsBundleExportsImports.java |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/sling/feature/extension/apiregions/analyser/CheckApiRegionsBundleExportsImports.java |

## Project: _apache/sling-org-apache-sling-feature-io_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-io.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-io) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-io) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-io.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                            |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------|
| ConfiguratorUtil.java |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/io/ConfiguratorUtil.java |

