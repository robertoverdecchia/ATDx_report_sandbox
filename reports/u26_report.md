
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-api.json)</p>|<img src="./plots/apache_sling-org-apache-sling-caconfig-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-caconfig-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-caconfig-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-caconfig-impl.json)</p>|<img src="./plots/apache_sling-org-apache-sling-servlet-helpers.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlet-helpers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlet-helpers) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlet-helpers.json)</p>
 | |
|<img src="./plots/apache_sling-org-apache-sling-testing-jcr-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-jcr-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-jcr-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-jcr-mock.json)</p>|<img src="./plots/apache_sling-org-apache-sling-testing-osgi-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-osgi-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-osgi-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-osgi-mock.json)</p>|<img src="./plots/apache_sling-org-apache-sling-testing-resourceresolver-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-resourceresolver-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-resourceresolver-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-resourceresolver-mock.json)</p>
 | |
|<img src="./plots/apache_sling-org-apache-sling-testing-sling-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-sling-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-sling-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-sling-mock.json)</p>
# Project report summaries
## Project: _apache/sling-org-apache-sling-api_
|./plots/apache_sling-org-apache-sling-api.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-api.json)</p>
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

## Project: _apache/sling-org-apache-sling-caconfig-impl_
|./plots/apache_sling-org-apache-sling-caconfig-impl.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-caconfig-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-caconfig-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-caconfig-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                        |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| ConfigurationResourceWrapper.java |              8 |             8 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/caconfig/impl/ConfigurationResourceWrapper.java |

## Project: _apache/sling-org-apache-sling-servlet-helpers_
|./plots/apache_sling-org-apache-sling-servlet-helpers.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlet-helpers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlet-helpers) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlet-helpers.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                       |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/servlethelpers/MockSlingHttpServletResponse.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlethelpers/MockRequestPathInfo.java          |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-testing-jcr-mock_
|./plots/apache_sling-org-apache-sling-testing-jcr-mock.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-jcr-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-jcr-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-jcr-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                           |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------|
| MockQuery.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/mock/jcr/MockQuery.java |

## Project: _apache/sling-org-apache-sling-testing-osgi-mock_
|./plots/apache_sling-org-apache-sling-testing-osgi-mock.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-osgi-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-osgi-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-osgi-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| OsgiServiceUtil.java   |             12 |             0 |          12 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/OsgiServiceUtil.java        |
| OsgiMetadataUtil.java  |              9 |             0 |           9 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/OsgiMetadataUtil.java       |
| MockBundleContext.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/MockBundleContext.java      |
| ContextPlugins.java    |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/context/ContextPlugins.java |
| ContextPlugin.java     |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/context/ContextPlugin.java  |

## Project: _apache/sling-org-apache-sling-testing-resourceresolver-mock_
|./plots/apache_sling-org-apache-sling-testing-resourceresolver-mock.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-resourceresolver-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-resourceresolver-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-resourceresolver-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/testing/resourceresolver/ResourceTypeUtil.java            |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/testing/resourceresolver/MockResourceResolver.java        |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/testing/resourceresolver/MockValueMap.java                |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/testing/resourceresolver/MockResourceResolverFactory.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-testing-sling-mock_
|./plots/apache_sling-org-apache-sling-testing-sling-mock.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-sling-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-sling-mock) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-sling-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                               |
|:------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------|
| MockJcrSlingRepository.java         |              8 |             0 |           8 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/MockJcrSlingRepository.java                 |
| ImmutableValueMap.java              |              6 |             0 |           0 |      0 |           6 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/builder/ImmutableValueMap.java              |
| ContentLoader.java                  |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/loader/ContentLoader.java                   |
| SlingContextImpl.java               |              4 |             2 |           1 |      0 |           1 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/context/SlingContextImpl.java               |
| MockSling.java                      |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/MockSling.java                              |
| MockMimeTypeService.java            |              3 |             0 |           3 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/services/MockMimeTypeService.java           |
| ContextResourceResolverFactory.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/context/ContextResourceResolverFactory.java |

