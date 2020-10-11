
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aaf-authz.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_music.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_optf-fgps.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_optf-fgps.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_portal.json)</p>
# Project report summaries
## Project: _onap/aaf-authz_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aaf-authz.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| LocateDAO.java     |             13 |             0 |           2 |      0 |          11 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/LocateDAO.java     |
| OAuthTokenDAO.java |             12 |             0 |           0 |      0 |          12 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/OAuthTokenDAO.java |
| ArtiDAO.java       |             11 |             0 |           0 |      0 |          11 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/ArtiDAO.java       |
| Agent.java         |              9 |             0 |           9 |      0 |           0 |           0 |            0 | cadi/aaf/src/main/java/org/onap/aaf/cadi/configure/Agent.java              |
| InXML.java         |              9 |             0 |           1 |      0 |           8 |           0 |            0 | misc/rosetta/src/main/java/org/onap/aaf/misc/rosetta/InXML.java            |
| Cred.java          |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-batch/src/main/java/org/onap/aaf/auth/batch/helpers/Cred.java    |
| FutureDAO.java     |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/FutureDAO.java     |
| HistoryDAO.java    |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/HistoryDAO.java    |
| CredDAO.java       |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/CredDAO.java       |
| AAF_CM.java        |              7 |             0 |           1 |      0 |           6 |           0 |            0 | auth/auth-certman/src/main/java/org/onap/aaf/auth/cm/AAF_CM.java           |

## Project: _onap/music_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_music.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/music) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_music) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_music.json)</p>
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
| JsonInsert.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | music-core/src/main/java/org/onap/music/datastore/jsonobjects/JsonInsert.java  |
| JsonSelect.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | music-core/src/main/java/org/onap/music/datastore/jsonobjects/JsonSelect.java  |
| MusicServiceException.java  |              2 |             0 |           2 |      0 |           0 |           0 |            0 | music-core/src/main/java/org/onap/music/exceptions/MusicServiceException.java  |

## Project: _onap/optf-fgps_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_optf-fgps.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_optf-fgps.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| AAFProxy.java                 |              6 |             0 |           0 |      0 |           5 |           1 |            0 | valetapi/src/main/java/org/onap/fgps/api/proxy/AAFProxy.java                       |
| CipherUtil.java               |              5 |             0 |           5 |      0 |           0 |           0 |            0 | valetapi/src/main/java/org/onap/fgps/api/utils/CipherUtil.java                     |
| AuthorizationInterceptor.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | valetapi/src/main/java/org/onap/fgps/api/interceptor/AuthorizationInterceptor.java |

## Project: _onap/portal_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_portal.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                         |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------|
| ExternalAccessRolesService.java    |             37 |             0 |          37 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/ExternalAccessRolesService.java       |
| RolesController.java               |             28 |             0 |          28 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/RolesController.java               |
| UserRolesCommonServiceImpl.java    |             25 |             0 |          23 |      0 |           2 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/UserRolesCommonServiceImpl.java       |
| OnboardingApp.java                 |             20 |             0 |           0 |      0 |          20 |           0 |            0 | ecomp-portal-BE-os/src/main/java/org/onap/portalapp/portal/transport/OnboardingApp.java                      |
| SharedContextRestController.java   |             12 |             0 |          12 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/SharedContextRestController.java   |
| RolesApprovalSystemController.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/RolesApprovalSystemController.java |
| BasicAuthAccountService.java       |              7 |             0 |           7 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/BasicAuthAccountService.java          |
| EPAppCommonServiceImpl.java        |              7 |             2 |           4 |      0 |           1 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/EPAppCommonServiceImpl.java           |
| CommonSessionCookieUtil.java       |              6 |             0 |           2 |      0 |           4 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/util/CommonSessionCookieUtil.java                    |
| SchedulerController.java           |              6 |             0 |           5 |      0 |           0 |           1 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/SchedulerController.java           |

