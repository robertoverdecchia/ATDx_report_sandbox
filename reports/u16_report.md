
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-api.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-contentloader.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-contentloader) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-contentloader) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-contentloader.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-jackrabbit-accessmanager) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-jackrabbit-usermanager.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-jackrabbit-usermanager) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-jackrabbit-usermanager) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-jackrabbit-usermanager.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-launchpad-integration-tests.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-launchpad-integration-tests) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-launchpad-integration-tests) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-launchpad-integration-tests.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-core.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-javascript.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-javascript) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-javascript) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-javascript.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlets-resolver.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-clients.json)</p>

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

## Project: _apache/sling-org-apache-sling-jcr-contentloader_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-contentloader.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-contentloader) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-contentloader) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-contentloader.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| XmlReader.java |             14 |             0 |           3 |      0 |          10 |           1 |            0 | src/main/java/org/apache/sling/jcr/contentloader/internal/readers/XmlReader.java |
| PathEntry.java |              3 |             3 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/jcr/contentloader/internal/PathEntry.java         |

## Project: _apache/sling-org-apache-sling-jcr-jackrabbit-accessmanager_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-jackrabbit-accessmanager) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-jackrabbit-accessmanager.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                            |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------|
| AbstractAccessPostServlet.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/jcr/jackrabbit/accessmanager/post/AbstractAccessPostServlet.java |

## Project: _apache/sling-org-apache-sling-jcr-jackrabbit-usermanager_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-jackrabbit-usermanager.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-jackrabbit-usermanager) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-jackrabbit-usermanager) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-jackrabbit-usermanager.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                           |
|:------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------|
| AbstractPostServlet.java            |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/jackrabbit/usermanager/impl/post/AbstractPostServlet.java       |
| AuthorizablePrivilegesInfoImpl.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/jackrabbit/usermanager/impl/AuthorizablePrivilegesInfoImpl.java |

## Project: _apache/sling-org-apache-sling-launchpad-integration-tests_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-launchpad-integration-tests.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-launchpad-integration-tests) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-launchpad-integration-tests) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-launchpad-integration-tests.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                              |
|:------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------------------|
| ResourceResolverGeneralTest.java    |             35 |             0 |          33 |      0 |           0 |           0 |            2 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/resourceresolver/ResourceResolverGeneralTest.java |
| ModifyAceTest.java                  |             23 |             0 |          23 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/accessManager/ModifyAceTest.java                  |
| PostServletImportTest.java          |             20 |             0 |          20 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/servlets/post/PostServletImportTest.java          |
| AuthenticationResponseCodeTest.java |             10 |             0 |          10 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/auth/AuthenticationResponseCodeTest.java          |
| CreateUserTest.java                 |             10 |             0 |           6 |      0 |           0 |           0 |            4 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/userManager/CreateUserTest.java                   |
| UpdateGroupTest.java                |             10 |             0 |          10 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/userManager/UpdateGroupTest.java                  |
| UserPrivilegesInfoTest.java         |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/userManager/UserPrivilegesInfoTest.java           |
| GetAclTest.java                     |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/accessManager/GetAclTest.java                     |
| AccessPrivilegesInfoTest.java       |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/accessManager/AccessPrivilegesInfoTest.java       |
| JspScriptingTest.java               |              6 |             0 |           6 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/launchpad/webapp/integrationtest/JspScriptingTest.java                             |

## Project: _apache/sling-org-apache-sling-scripting-core_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                    |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/scripting/core/impl/bundled/Script.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/bundled/PrecompiledScript.java            |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/InternalScriptHelper.java                 |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/BindingsValuesProvidersByContextImpl.java |             0 |           0 |         0 |           0 |           0 |            0 |     0 |

## Project: _apache/sling-org-apache-sling-scripting-javascript_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-javascript.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-javascript) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-javascript) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-javascript.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| EspReader.java          |              9 |             9 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/javascript/io/EspReader.java               |
| SlingGlobal.java        |              3 |             0 |           0 |      0 |           0 |           0 |            3 | src/main/java/org/apache/sling/scripting/javascript/helper/SlingGlobal.java         |
| ScriptableResource.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/scripting/javascript/wrapper/ScriptableResource.java |

## Project: _apache/sling-org-apache-sling-servlets-resolver_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlets-resolver.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                     |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/servlets/resolver/internal/helper/LocationIterator.java                        |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/internal/resolution/ResolutionCache.java                     |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/bundle/tracker/internal/BundledRenderUnitCapabilityImpl.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/internal/helper/ResourceCollector.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-testing-clients_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-clients.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| AbstractSlingClient.java |             10 |             0 |           8 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/AbstractSlingClient.java    |
| OsgiConsoleClient.java   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/osgi/OsgiConsoleClient.java |
| SlingHttpResponse.java   |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingHttpResponse.java      |
| SlingClient.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingClient.java            |
