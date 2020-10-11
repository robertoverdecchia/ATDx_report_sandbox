
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-jspc-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-jspc-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-jspc-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-jspc-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-maven-launchpad-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-maven-launchpad-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-maven-launchpad-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-maven-launchpad-plugin.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-app-cms.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-app-cms) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-app-cms) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-app-cms.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-form.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-form) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-form) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-form.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-bundleresource-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-bundleresource-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-bundleresource-impl) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-bundleresource-impl.json)</p>

# Project report summaries
## Project: _apache/sling-jspc-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-jspc-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-jspc-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-jspc-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-jspc-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                 |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------|
| JspCServletContext.java    |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspCServletContext.java    |
| JspcMojo.java              |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspcMojo.java              |
| JspCTldLocationsCache.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspCTldLocationsCache.java |
| JspCIOProvider.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspCIOProvider.java        |
| JspCClassLoaderWriter.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspCClassLoaderWriter.java |

## Project: _apache/sling-kickstart-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| LauncherCallable.java           |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/LauncherCallable.java           |
| ProcessDescriptionProvider.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescriptionProvider.java |
| StartMojo.java                  |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/StartMojo.java                  |
| BuildConstants.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/BuildConstants.java                 |
| PortHelper.java                 |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/PortHelper.java                 |
| ProcessDescription.java         |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescription.java         |
| Main.java                       |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/launcher/Main.java                  |

## Project: _apache/sling-maven-launchpad-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-maven-launchpad-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-maven-launchpad-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-maven-launchpad-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-maven-launchpad-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                         |
|:-----------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------|
| LaunchpadPluginLifecycleParticipant.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/projectsupport/LaunchpadPluginLifecycleParticipant.java |
| RunMojo.java                             |              1 |             1 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/projectsupport/RunMojo.java                             |
| StartMojo.java                           |              1 |             1 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/projectsupport/StartMojo.java                           |
| AttachPartialBundleListMojo.java         |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/projectsupport/AttachPartialBundleListMojo.java         |

## Project: _apache/sling-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                           |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------|
| GenerateAdapterMetadataMojo.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | sling-maven-plugin/src/main/java/org/apache/sling/maven/bundlesupport/GenerateAdapterMetadataMojo.java         |
| WebDavPutDeployMethod.java       |              3 |             0 |           3 |      0 |           0 |           0 |            0 | sling-maven-plugin/src/main/java/org/apache/sling/maven/bundlesupport/deploy/method/WebDavPutDeployMethod.java |
| AbstractBundleInstallMojo.java   |              1 |             0 |           0 |      0 |           1 |           0 |            0 | sling-maven-plugin/src/main/java/org/apache/sling/maven/bundlesupport/AbstractBundleInstallMojo.java           |

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

## Project: _apache/sling-org-apache-sling-app-cms_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-app-cms.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-app-cms) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-app-cms) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-app-cms.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| FormRequestImpl.java     |              3 |             0 |           3 |      0 |           0 |           0 |            0 | reference/src/main/java/org/apache/sling/cms/reference/forms/impl/FormRequestImpl.java |
| BaseInsightProvider.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | core/src/main/java/org/apache/sling/cms/core/insights/impl/BaseInsightProvider.java    |

## Project: _apache/sling-org-apache-sling-auth-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:--------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| AbstractAuthenticationHandler.java    |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/auth/core/spi/AbstractAuthenticationHandler.java  |
| AuthenticationInfo.java               |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/engine/auth/AuthenticationInfo.java               |
| AuthenticationHandler.java            |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/engine/auth/AuthenticationHandler.java            |
| Authenticator.java                    |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/engine/auth/Authenticator.java                    |
| NoAuthenticationHandlerException.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/engine/auth/NoAuthenticationHandlerException.java |

## Project: _apache/sling-org-apache-sling-auth-form_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-form.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-form) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-form) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-form.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                         |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------|
| FormAuthenticationHandler.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/auth/form/impl/FormAuthenticationHandler.java |
| TokenStore.java                |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/auth/form/impl/TokenStore.java                |

## Project: _apache/sling-org-apache-sling-bundleresource-impl_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-bundleresource-impl.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-bundleresource-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-bundleresource-impl) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-bundleresource-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| BundleResourceURLConnection.java |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/bundleresource/impl/BundleResourceURLConnection.java |

