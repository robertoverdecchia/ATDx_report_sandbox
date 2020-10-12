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
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_externalapi-nbi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/externalapi-nbi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_externalapi-nbi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_externalapi-nbi.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_music.json)</p>
 | |

# Project report summaries
## Project: _onap/dmaap-datarouter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                    |
|:-------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------------------------|
| StatusLog.java     | 4              | 0             | 0           | 0      | 4           | 0           | 0            | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java                   |
| RLEBitSet.java     | 2              | 2             | 0           | 0      | 0           | 0           | 0            | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/RLEBitSet.java     |
| LOGJSONObject.java | 2              | 2             | 0           | 0      | 0           | 0           | 0            | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/LOGJSONObject.java |
| NodeConfig.java    | 1              | 0             | 0           | 0      | 1           | 0           | 0            | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/NodeConfig.java                  |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |

## Project: _onap/externalapi-nbi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_externalapi-nbi.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/externalapi-nbi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_externalapi-nbi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_externalapi-nbi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                 |
|:-------------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-------------------------------------------------------------------------------------------|
| MongoConfig.java                     | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/onap/nbi/configuration/MongoConfig.java                                  |
| ExecutionTaskProcessorScheduler.java | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/nbi/apis/serviceorder/workflow/ExecutionTaskProcessorScheduler.java |
| EventFactory.java                    | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/nbi/apis/hub/service/EventFactory.java                              |
| E2EServiceUtils.java                 | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/nbi/apis/serviceorder/utils/E2EServiceUtils.java                    |
| MacroServiceUtils.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/nbi/apis/serviceorder/utils/MacroServiceUtils.java                  |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                          |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                          |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                          |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                          |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                          |

## Project: _onap/music_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_music.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                     |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| RestMusicDataAPI.java       |             18 |             0 |           6 |      0 |          12 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicDataAPI.java             |
| RestMusicLocksAPI.java      |             11 |             0 |           8 |      0 |           3 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicLocksAPI.java            |
| MusicUtil.java              |              8 |             0 |           5 |      0 |           2 |           0 |            1 | music-core/src/main/java/org/onap/music/main/MusicUtil.java                    |
| RestMusicQAPI.java          |              7 |             0 |           0 |      0 |           7 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicQAPI.java                |
| CipherUtil.java             |              4 |             0 |           0 |      0 |           4 |           0 |            0 | music-core/src/main/java/org/onap/music/main/CipherUtil.java                   |
| MusicDeadlockException.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | music-core/src/main/java/org/onap/music/exceptions/MusicDeadlockException.java |
| MusicCassaCore.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | music-core/src/main/java/org/onap/music/service/impl/MusicCassaCore.java       |
| JsonInsert.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | music-core/src/main/java/org/onap/music/datastore/jsonobjects/JsonInsert.java  |
| JsonSelect.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | music-core/src/main/java/org/onap/music/datastore/jsonobjects/JsonSelect.java  |
| MusicServiceException.java  |              2 |             0 |           2 |      0 |           0 |           0 |            0 | music-core/src/main/java/org/onap/music/exceptions/MusicServiceException.java  |

