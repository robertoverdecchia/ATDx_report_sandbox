
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-apigateway.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/msb-apigateway) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-apigateway) <br> [Complete issue report (JSON)](./json/onap_msb-apigateway.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-java-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/msb-java-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-java-sdk) <br> [Complete issue report (JSON)](./json/onap_msb-java-sdk.json)</p>
# Project report summaries
## Project: _onap/msb-apigateway_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-apigateway.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/msb-apigateway) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-apigateway) <br> [Complete issue report (JSON)](./json/onap_msb-apigateway.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name           |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                      |
|:---------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------|
| HttpClientUtil.java  |              7 |             0 |           6 |      0 |           1 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/util/HttpClientUtil.java            |
| IServiceDAO.java     |              5 |             0 |           5 |      0 |           0 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/dao/service/IServiceDAO.java        |
| IRouteDAO.java       |              5 |             0 |           5 |      0 |           0 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/dao/route/IRouteDAO.java            |
| ConsulCache.java     |              4 |             0 |           4 |      0 |           0 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/consulextend/cache/ConsulCache.java |
| FileUtil.java        |              4 |             0 |           3 |      0 |           1 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/util/FileUtil.java                  |
| JacksonJsonUtil.java |              4 |             0 |           3 |      0 |           1 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/util/JacksonJsonUtil.java           |
| ServiceDAOImpl.java  |              3 |             0 |           3 |      0 |           0 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/dao/service/ServiceDAOImpl.java     |
| RouteDAOImpl.java    |              3 |             0 |           3 |      0 |           0 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/dao/route/RouteDAOImpl.java         |
| IuiRouteService.java |              3 |             0 |           2 |      0 |           1 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/service/IuiRouteService.java        |
| JedisUtil.java       |              3 |             0 |           2 |      0 |           1 |           0 |            0 | apiroute/apiroute-service/src/main/java/org/onap/msb/apiroute/wrapper/util/JedisUtil.java                 |

## Project: _onap/msb-java-sdk_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-java-sdk.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/msb-java-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-java-sdk) <br> [Complete issue report (JSON)](./json/onap_msb-java-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------|
| RetrofitServiceUtils.java |              4 |             0 |           3 |      0 |           1 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/RetrofitServiceUtils.java |
