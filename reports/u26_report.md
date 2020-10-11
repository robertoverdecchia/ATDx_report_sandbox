
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-caconfig-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-caconfig-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-caconfig-impl) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-caconfig-impl.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlet-helpers.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlet-helpers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlet-helpers) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlet-helpers.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-jcr-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-jcr-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-jcr-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-jcr-mock.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-osgi-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-osgi-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-osgi-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-osgi-mock.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-resourceresolver-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-resourceresolver-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-resourceresolver-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-resourceresolver-mock.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-sling-mock.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-sling-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-sling-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-sling-mock.json)</p>
# Project report summaries
## Project: _apache/sling-org-apache-sling-api_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>
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
| ResourceMetadata.java    |              2 |             1 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceMetadata.java                |
| ResourceProvider.java    |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceProvider.java                |
| RuntimeDTO.java          |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/api/resource/runtime/dto/RuntimeDTO.java          |
| ValueMapDecorator.java   |              2 |             2 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/api/wrappers/ValueMapDecorator.java               |

## Project: _apache/sling-org-apache-sling-caconfig-impl_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-caconfig-impl.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-caconfig-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-caconfig-impl) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-caconfig-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                        |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| ConfigurationResourceWrapper.java |              8 |             8 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/caconfig/impl/ConfigurationResourceWrapper.java     |
| ConfigurationDataImpl.java        |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/caconfig/management/impl/ConfigurationDataImpl.java |
| ConfigurationBuilderImpl.java     |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/caconfig/impl/ConfigurationBuilderImpl.java         |

## Project: _apache/sling-org-apache-sling-servlet-helpers_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlet-helpers.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlet-helpers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlet-helpers) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlet-helpers.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| MockSlingHttpServletRequest.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/servlethelpers/MockSlingHttpServletRequest.java |
| ResponseBodySupport.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/servlethelpers/ResponseBodySupport.java         |
| AdaptableUtil.java               |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/servlethelpers/AdaptableUtil.java               |

## Project: _apache/sling-org-apache-sling-testing-jcr-mock_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-jcr-mock.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-jcr-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-jcr-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-jcr-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                           |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------|
| MockQuery.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/mock/jcr/MockQuery.java |
| MockJcr.java   |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/mock/jcr/MockJcr.java   |

## Project: _apache/sling-org-apache-sling-testing-osgi-mock_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-osgi-mock.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-osgi-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-osgi-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-osgi-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| OsgiServiceUtil.java   |             12 |             0 |          12 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/OsgiServiceUtil.java        |
| OsgiMetadataUtil.java  |              9 |             0 |           9 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/OsgiMetadataUtil.java       |
| MockBundleContext.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/MockBundleContext.java      |
| ContextPlugins.java    |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/context/ContextPlugins.java |
| ContextPlugin.java     |              4 |             0 |           4 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/context/ContextPlugin.java  |
| MockBundle.java        |              2 |             0 |           2 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/MockBundle.java             |
| MockOsgi.java          |              2 |             0 |           2 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/osgi/MockOsgi.java               |

## Project: _apache/sling-org-apache-sling-testing-resourceresolver-mock_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-resourceresolver-mock.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-resourceresolver-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-resourceresolver-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-resourceresolver-mock.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                    |
|:----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------|
| MockHelper.java |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/testing/resourceresolver/MockHelper.java |

## Project: _apache/sling-org-apache-sling-testing-sling-mock_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-sling-mock.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-sling-mock) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-sling-mock) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-sling-mock.json)</p>
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
| MockSlingHttpServletRequest.java    |              2 |             2 |           0 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/servlet/MockSlingHttpServletRequest.java    |
| LoaderContentHandler.java           |              2 |             0 |           2 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/loader/LoaderContentHandler.java            |
| ContentBuilder.java                 |              2 |             0 |           2 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/testing/mock/sling/builder/ContentBuilder.java                 |

