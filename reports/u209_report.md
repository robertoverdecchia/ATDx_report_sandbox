
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-apigateway.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/msb-apigateway) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-apigateway) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_msb-apigateway.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-java-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/msb-java-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-java-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_msb-java-sdk.json)</p>
# Project report summaries
## Project: _onap/msb-apigateway_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-apigateway.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/msb-apigateway) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-apigateway) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_msb-apigateway.json)</p>
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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_msb-java-sdk.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/msb-java-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_msb-java-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_msb-java-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                 |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------|
| RetrofitServiceUtils.java          |              4 |             0 |           3 |      0 |           1 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/RetrofitServiceUtils.java                  |
| RetrofitServiceHandlerFactory.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/handler/RetrofitServiceHandlerFactory.java |
| LBBuilder.java                     |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/handler/impl/LBBuilder.java                |
| ConverterFactoryBuilder.java       |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/handler/impl/ConverterFactoryBuilder.java  |
| ProxyRetrofitCall.java             |              2 |             2 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/ProxyRetrofitCall.java                     |
| RouteException.java                |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/discovery/common/RouteException.java                  |
| RetrofitServiceHandler.java        |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/msb/sdk/httpclient/handler/RetrofitServiceHandler.java        |

