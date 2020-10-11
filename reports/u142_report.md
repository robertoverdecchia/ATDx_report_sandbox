
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-slingfeature-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-slingfeature-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-slingfeature-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-slingfeature-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-whiteboard.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-whiteboard) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-whiteboard) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-whiteboard.json)</p>
# Project report summaries
## Project: _apache/sling-slingfeature-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-slingfeature-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-slingfeature-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-slingfeature-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-slingfeature-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| ProjectHelper.java      |             16 |             0 |          15 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/ProjectHelper.java            |
| Aggregate.java          |             11 |             0 |           0 |      0 |          11 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/Aggregate.java          |
| UpdateVersionsMojo.java |              9 |             0 |           1 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/UpdateVersionsMojo.java |
| Preprocessor.java       |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/Preprocessor.java             |
| Environment.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/Environment.java              |
| FeatureProjectInfo.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/FeatureProjectInfo.java       |
| ApisJarMojo.java        |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/ApisJarMojo.java        |
| InfoMojo.java           |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/InfoMojo.java           |
| JarDecompressor.java    |              2 |             1 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/JarDecompressor.java    |
| Substitution.java       |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/Substitution.java             |

## Project: _apache/sling-whiteboard_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-whiteboard.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-whiteboard) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-whiteboard) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-whiteboard.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                           |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------|
| AuthenticationHandlerSAML2.java |             14 |             0 |          14 |      0 |           0 |           0 |            0 | saml-handler/src/main/java/org/apache/sling/auth/saml2/AuthenticationHandlerSAML2.java         |
| ModelPersistorImpl.java         |             10 |             0 |          10 |      0 |           0 |           0 |            0 | SlingModelPersist/src/main/java/org/apache/sling/models/persistor/impl/ModelPersistorImpl.java |
| KeyPairCredentials.java         |              8 |             0 |           7 |      0 |           1 |           0 |            0 | saml-handler/src/main/java/org/apache/sling/auth/saml2/sp/KeyPairCredentials.java              |
| VerifySignatureCredentials.java |              7 |             0 |           6 |      0 |           1 |           0 |            0 | saml-handler/src/main/java/org/apache/sling/auth/saml2/sp/VerifySignatureCredentials.java      |
| ModelPersistor.java             |              4 |             0 |           4 |      0 |           0 |           0 |            0 | SlingModelPersist/src/main/java/org/apache/sling/models/persistor/ModelPersistor.java          |
| TokenStore.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | saml-handler/src/main/java/org/apache/sling/auth/saml2/TokenStore.java                         |
| Saml2UserMgtServiceImpl.java    |              2 |             0 |           0 |      0 |           2 |           0 |            0 | saml-handler/src/main/java/org/apache/sling/auth/saml2/impl/Saml2UserMgtServiceImpl.java       |

