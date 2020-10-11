
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_incubator-tamaya-extensions.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya-extensions) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya-extensions) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya-extensions.json)</p>|<img src="./plots/apache_incubator-tamaya-sandbox.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya-sandbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya-sandbox) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya-sandbox.json)</p>|<img src="./plots/apache_incubator-tamaya.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya.json)</p>
 | |

# Project report summaries
## Project: _apache/incubator-tamaya-extensions_
|./plots/apache_incubator-tamaya-extensions.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya-extensions) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya-extensions) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya-extensions.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                  |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------|
| ConfigCommands.java      |              7 |             0 |           7 |      0 |           0 |           0 |            0 | modules/osgi/common/src/main/java/org/apache/tamaya/osgi/commands/ConfigCommands.java                 |
| DefaultDynamicValue.java |              5 |             4 |           0 |      0 |           1 |           0 |            0 | modules/injection/standalone/src/main/java/org/apache/tamaya/inject/internal/DefaultDynamicValue.java |
| ConfigResources.java     |              3 |             0 |           2 |      0 |           1 |           0 |            0 | modules/resources/src/main/java/org/apache/tamaya/resource/ConfigResources.java                       |
| Resolver.java            |              3 |             0 |           0 |      0 |           3 |           0 |            0 | modules/resolver/src/main/java/org/apache/tamaya/resolver/Resolver.java                               |
| ConfiguredFieldImpl.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | modules/injection/standalone/src/main/java/org/apache/tamaya/inject/internal/ConfiguredFieldImpl.java |
| BackupCommands.java      |              3 |             0 |           3 |      0 |           0 |           0 |            0 | modules/osgi/common/src/main/java/org/apache/tamaya/osgi/commands/BackupCommands.java                 |

## Project: _apache/incubator-tamaya-sandbox_
|./plots/apache_incubator-tamaya-sandbox.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya-sandbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya-sandbox) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya-sandbox.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:----------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| hjson/src/main/java/org/apache/tamaya/hjson/HJSONPropertySource.java        |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| configjsr/src/main/java/org/apache/tamaya/jsr382/JavaConfigSource.java      |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| remote/src/main/java/org/apache/tamaya/remote/BaseRemotePropertySource.java |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

## Project: _apache/incubator-tamaya_
|./plots/apache_incubator-tamaya.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-tamaya) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-tamaya) <br> [Complete issue report (JSON)](./json/apache_incubator-tamaya.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                      |
|:-----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------|
| TypeLiteral.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | code/api/src/main/java/org/apache/tamaya/TypeLiteral.java |

