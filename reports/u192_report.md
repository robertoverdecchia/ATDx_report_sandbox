
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-ratis.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-ratis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-ratis) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_incubator-ratis.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/knox-gateway.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/knox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=knox-gateway) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/knox-gateway.json)</p>
# Project report summaries
## Project: _apache/incubator-ratis_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-ratis.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-ratis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-ratis) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_incubator-ratis.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                    |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------|
| NativeIO.java         |             40 |             3 |           1 |      0 |          36 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/io/nativeio/NativeIO.java                   |
| VerificationTool.java |              6 |             0 |           6 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/tool/VerificationTool.java   |
| RaftProperties.java   |              6 |             0 |           6 |      0 |           0 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/conf/RaftProperties.java                    |
| MetaStateMachine.java |              5 |             5 |           0 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/server/MetaStateMachine.java |
| NativeCrc32.java      |              5 |             0 |           2 |      0 |           3 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/util/NativeCrc32.java                       |
| ServerProtoUtils.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | ratis-server/src/main/java/org/apache/ratis/server/impl/ServerProtoUtils.java           |
| LogServiceClient.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/api/LogServiceClient.java    |
| LogStateMachine.java  |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/server/LogStateMachine.java  |
| LogAppender.java      |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-server/src/main/java/org/apache/ratis/server/impl/LogAppender.java                |
| NetUtils.java         |              2 |             0 |           1 |      0 |           1 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/util/NetUtils.java                          |

## Project: _apache/knox_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/knox-gateway.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/knox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=knox-gateway) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/knox-gateway.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                             |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------|
| DefaultDispatch.java   |             11 |            10 |           0 |      0 |           1 |           0 |            0 | gateway-adapter/src/main/java/org/apache/hadoop/gateway/dispatch/DefaultDispatch.java            |
| GatewayTestDriver.java |             11 |             0 |           2 |      0 |           9 |           0 |            0 | gateway-test-release-utils/src/main/java/org/apache/knox/gateway/GatewayTestDriver.java          |
| KnoxCLI.java           |             10 |             0 |           8 |      0 |           2 |           0 |            0 | gateway-server/src/main/java/org/apache/knox/gateway/util/KnoxCLI.java                           |
| KnoxLdapRealm.java     |              8 |             4 |           3 |      0 |           1 |           0 |            0 | gateway-adapter/src/main/java/org/apache/hadoop/gateway/shirorealm/KnoxLdapRealm.java            |
| AclParser.java         |              6 |             0 |           1 |      0 |           5 |           0 |            0 | gateway-provider-security-authz-acls/src/main/java/org/apache/knox/gateway/filter/AclParser.java |
| NiFiResponseUtil.java  |              6 |             0 |           5 |      0 |           1 |           0 |            0 | gateway-service-nifi/src/main/java/org/apache/knox/gateway/dispatch/NiFiResponseUtil.java        |
| KnoxSession.java       |              5 |             0 |           5 |      0 |           0 |           0 |            0 | gateway-shell/src/main/java/org/apache/knox/gateway/shell/KnoxSession.java                       |
| KnoxSh.java            |              4 |             0 |           3 |      0 |           1 |           0 |            0 | gateway-shell/src/main/java/org/apache/knox/gateway/shell/KnoxSh.java                            |
| KnoxPamRealm.java      |              4 |             2 |           1 |      0 |           1 |           0 |            0 | gateway-adapter/src/main/java/org/apache/hadoop/gateway/shirorealm/KnoxPamRealm.java             |
| RegEntry.java          |              4 |             0 |           0 |      0 |           4 |           0 |            0 | gateway-server/src/main/java/org/apache/knox/gateway/services/registry/impl/RegEntry.java        |

