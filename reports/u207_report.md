
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/apache-dolphinscheduler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-dolphinscheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache-dolphinscheduler) <br> [Complete issue report (JSON)](./json/apache-dolphinscheduler.json)</p>|<img src="./plots/apache_isis.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/isis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_isis) <br> [Complete issue report (JSON)](./json/apache_isis.json)</p>
# Project report summaries
## Project: _apache/incubator-dolphinscheduler_
|./plots/apache-dolphinscheduler.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-dolphinscheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache-dolphinscheduler) <br> [Complete issue report (JSON)](./json/apache-dolphinscheduler.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                            |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------------|
| UpgradeDao.java               |             18 |             0 |          18 |      0 |           0 |           0 |            0 | dolphinscheduler-dao/src/main/java/org/apache/dolphinscheduler/dao/upgrade/UpgradeDao.java                      |
| ResourcesService.java         |             12 |             0 |          11 |      0 |           1 |           0 |            0 | dolphinscheduler-api/src/main/java/org/apache/dolphinscheduler/api/service/ResourcesService.java                |
| SchedulerService.java         |             11 |             0 |           6 |      0 |           2 |           0 |            3 | dolphinscheduler-api/src/main/java/org/apache/dolphinscheduler/api/service/SchedulerService.java                |
| SSHTask.java                  |             10 |             0 |          10 |      0 |           0 |           0 |            0 | dolphinscheduler-server/src/main/java/org/apache/dolphinscheduler/server/worker/task/ssh/SSHTask.java           |
| UsersService.java             |              7 |             0 |           5 |      0 |           2 |           0 |            0 | dolphinscheduler-api/src/main/java/org/apache/dolphinscheduler/api/service/UsersService.java                    |
| SqlTask.java                  |              7 |             0 |           7 |      0 |           0 |           0 |            0 | dolphinscheduler-server/src/main/java/org/apache/dolphinscheduler/server/worker/task/sql/SqlTask.java           |
| DataxTask.java                |              7 |             0 |           7 |      0 |           0 |           0 |            0 | dolphinscheduler-server/src/main/java/org/apache/dolphinscheduler/server/worker/task/datax/DataxTask.java       |
| ProcessImplForWin32.java      |              7 |             1 |           6 |      0 |           0 |           0 |            0 | dolphinscheduler-common/src/main/java/org/apache/dolphinscheduler/common/utils/process/ProcessImplForWin32.java |
| ExecutorService.java          |              6 |             0 |           4 |      0 |           2 |           0 |            0 | dolphinscheduler-api/src/main/java/org/apache/dolphinscheduler/api/service/ExecutorService.java                 |
| ProcessDefinitionService.java |              6 |             0 |           5 |      0 |           1 |           0 |            0 | dolphinscheduler-api/src/main/java/org/apache/dolphinscheduler/api/service/ProcessDefinitionService.java        |

## Project: _apache/isis_
|./plots/apache_isis.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/isis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_isis) <br> [Complete issue report (JSON)](./json/apache_isis.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                                      |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------------------------------------------|
| CommonDtoUtils.java                |             29 |             0 |           1 |      0 |           1 |           0 |           27 | api/applib/src/main/java/org/apache/isis/applib/util/schema/CommonDtoUtils.java                                                           |
| IsisConfiguration.java             |             26 |             0 |           0 |      0 |          26 |           0 |            0 | core/config/src/main/java/org/apache/isis/core/config/IsisConfiguration.java                                                              |
| PojoTester.java                    |             21 |            21 |           0 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/bean/PojoTester.java                          |
| _Json.java                         |             17 |             0 |          16 |      0 |           1 |           0 |            0 | core/commons/src/main/java/org/apache/isis/core/commons/internal/resources/_Json.java                                                     |
| ExcelService.java                  |             16 |             0 |          16 |      0 |           0 |           0 |            0 | subdomains/excel/applib/src/main/java/org/apache/isis/subdomains/excel/applib/dom/ExcelService.java                                       |
| ValueTypeContractTestAbstract.java |             12 |             0 |          12 |      0 |           0 |           0 |            0 | core/internaltestsupport/src/main/java/org/apache/isis/core/internaltestsupport/value/ValueTypeContractTestAbstract.java                  |
| ValueTypeContractTestAbstract.java |             12 |             0 |          12 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/core/value/ValueTypeContractTestAbstract.java |
| JsonMapper.java                    |              9 |             0 |           9 |      0 |           0 |           0 |            0 | viewers/restfulobjects/applib/src/main/java/org/apache/isis/viewer/restfulobjects/applib/util/JsonMapper.java                             |
| Parent.java                        |              8 |             0 |           8 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/core/bidir/Parent.java                        |
| DomainEventHelper.java             |              7 |             0 |           6 |      0 |           1 |           0 |            0 | core/metamodel/src/main/java/org/apache/isis/core/metamodel/facets/DomainEventHelper.java                                                 |

