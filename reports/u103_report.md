
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](./json/onap_dmaap-datarouter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_externalapi-nbi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/externalapi-nbi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_externalapi-nbi) <br> [Complete issue report (JSON)](./json/onap_externalapi-nbi.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](./json/onap_music.json)</p>
 | |

# Project report summaries
## Project: _onap/dmaap-datarouter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](./json/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                        |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------|
| StatusLog.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java |

## Project: _onap/externalapi-nbi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_externalapi-nbi.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/externalapi-nbi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_externalapi-nbi) <br> [Complete issue report (JSON)](./json/onap_externalapi-nbi.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/onap/nbi/apis/serviceorder/workflow/ExecutionTaskProcessorScheduler.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/nbi/apis/hub/service/EventFactory.java                              |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/nbi/apis/serviceorder/utils/E2EServiceUtils.java                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/nbi/apis/serviceorder/utils/MacroServiceUtils.java                  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/music_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](./json/onap_music.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| RestMusicDataAPI.java       |             18 |             0 |           6 |      0 |          12 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicDataAPI.java             |
| RestMusicLocksAPI.java      |             11 |             0 |           8 |      0 |           3 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicLocksAPI.java            |
| MusicUtil.java              |              8 |             0 |           5 |      0 |           2 |           0 |            1 | music-core/src/main/java/org/onap/music/main/MusicUtil.java                    |
| RestMusicQAPI.java          |              7 |             0 |           0 |      0 |           7 |           0 |            0 | music-rest/src/main/java/org/onap/music/rest/RestMusicQAPI.java                |
| CipherUtil.java             |              4 |             0 |           0 |      0 |           4 |           0 |            0 | music-core/src/main/java/org/onap/music/main/CipherUtil.java                   |
| MusicDeadlockException.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | music-core/src/main/java/org/onap/music/exceptions/MusicDeadlockException.java |
| MusicCassaCore.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | music-core/src/main/java/org/onap/music/service/impl/MusicCassaCore.java       |

