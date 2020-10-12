# ATDx Report Summary
Following the overview of the ATDx analysis of your projects.

In short, the ATDx analysis is based on software metrics aggregation, and statistical severity evaluation of the aggregated values across a portfolio of software projects.

ATDx provides an overview of the project Architectural Technical Debt (ATD) in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the Java throwable class “Exception” and its subclasses
* **JVMS**: potential misuse of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, an overview of the ATDx values is presented, followed by the top classes of the project contributing to the ATDx values.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problematics (only a maximum of 10 classes are provided per project). Similarly, empty rows may indicate that only few classes are affected by ATDx violations.
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-iotdb.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-iotdb) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-iotdb) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_incubator-iotdb.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_plc4x.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/plc4x) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_plc4x) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_plc4x.json)</p>
# Project report summaries
## Project: _apache/incubator-iotdb_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-iotdb.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-iotdb) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-iotdb) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_incubator-iotdb.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                   |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------|
| IoTDBRpcDataSet.java           |             21 |             0 |           1 |      0 |          20 |           0 |            0 | service-rpc/src/main/java/org/apache/iotdb/rpc/IoTDBRpcDataSet.java                          |
| RamUsageEstimator.java         |              9 |             0 |           3 |      0 |           6 |           0 |            0 | tsfile/src/main/java/org/apache/iotdb/tsfile/utils/RamUsageEstimator.java                    |
| BinaryExpression.java          |              9 |             5 |           0 |      0 |           4 |           0 |            0 | tsfile/src/main/java/org/apache/iotdb/tsfile/read/expression/impl/BinaryExpression.java      |
| TSFInputFormat.java            |              8 |             0 |           0 |      0 |           8 |           0 |            0 | hadoop/src/main/java/org/apache/iotdb/hadoop/tsfile/TSFInputFormat.java                      |
| DatabaseConnectController.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | grafana/src/main/java/org/apache/iotdb/web/grafana/controller/DatabaseConnectController.java |
| FilterOperator.java            |              4 |             3 |           0 |      0 |           1 |           0 |            0 | spark-tsfile/src/main/java/org/apache/iotdb/spark/tsfile/qp/common/FilterOperator.java       |
| RegularDataEncoder.java        |              4 |             0 |           4 |      0 |           0 |           0 |            0 | tsfile/src/main/java/org/apache/iotdb/tsfile/encoding/encoder/RegularDataEncoder.java        |
| SQLConstant.java               |              4 |             0 |           0 |      0 |           4 |           0 |            0 | spark-tsfile/src/main/java/org/apache/iotdb/spark/tsfile/qp/common/SQLConstant.java          |
| Tablet.java                    |              4 |             0 |           0 |      0 |           4 |           0 |            0 | tsfile/src/main/java/org/apache/iotdb/tsfile/write/record/Tablet.java                        |
| TSRecord.java                  |              3 |             0 |           0 |      0 |           3 |           0 |            0 | tsfile/src/main/java/org/apache/iotdb/tsfile/write/record/TSRecord.java                      |

## Project: _apache/plc4x_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_plc4x.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/plc4x) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_plc4x) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_plc4x.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                                                   |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------------------|
| LittleEndianDecoder.java        |             39 |             0 |           0 |      0 |           0 |           0 |           39 | sandbox/test-java-amsads-driver/src/main/java/org/apache/plc4x/java/amsads/protocol/util/LittleEndianDecoder.java                            |
| JavaLanguageTemplateHelper.java |             38 |             0 |          10 |      0 |           0 |           0 |           28 | build-utils/language-java/src/main/java/org/apache/plc4x/language/java/JavaLanguageTemplateHelper.java                                       |
| TriggerConfiguration.java       |             12 |             0 |          12 |      0 |           0 |           0 |            0 | plc4j/tools/scraper/src/main/java/org/apache/plc4x/java/scraper/triggeredscraper/triggerhandler/TriggerConfiguration.java                    |
| DriverTestsuiteRunner.java      |              8 |             0 |           1 |      0 |           0 |           0 |            7 | plc4j/utils/test-utils/src/main/java/org/apache/plc4x/test/driver/DriverTestsuiteRunner.java                                                 |
| S7Step7ServerAdapter.java       |              7 |             0 |           0 |      0 |           0 |           0 |            7 | sandbox/plc-simulator/src/main/java/org/apache/plc4x/simulator/server/s7/protocol/S7Step7ServerAdapter.java                                  |
| SerialChannel.java              |              6 |             0 |           6 |      0 |           0 |           0 |            0 | plc4j/transports/serial/src/main/java/org/apache/plc4x/java/transport/serial/SerialChannel.java                                              |
| Df1Protocol.java                |              5 |             0 |           0 |      0 |           1 |           0 |            4 | sandbox/test-java-df1-driver/src/main/java/org/apache/plc4x/java/df1/protocol/Df1Protocol.java                                               |
| ExpressionStringListener.java   |              5 |             0 |           5 |      0 |           0 |           0 |            0 | build-utils/protocol-base-mspec/src/main/java/org/apache/plc4x/plugins/codegenerator/language/mspec/expression/ExpressionStringListener.java |
| WaterTankService.java           |              5 |             0 |           5 |      0 |           0 |           0 |            0 | plc4j/examples/hello-webapp/webapp/src/main/java/org/apache/plc4x/examples/watertank/service/WaterTankService.java                           |
| DF1Utils.java                   |              5 |             0 |           4 |      0 |           1 |           0 |            0 | sandbox/test-java-df1-driver/src/main/java/org/apache/plc4x/java/df1/util/DF1Utils.java                                                      |

