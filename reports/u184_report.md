
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](./json/onap_portal.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](./json/onap_vid.json)</p>
# Project report summaries
## Project: _onap/portal_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](./json/onap_portal.json)</p>
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

## Project: _onap/vid_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](./json/onap_vid.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                      |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------|
| ServiceRelationships.java        |             11 |             0 |           0 |      0 |          11 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/ServiceRelationships.java             |
| AsyncRequestStatus.java          |             11 |             0 |           0 |      0 |          11 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/mso/rest/AsyncRequestStatus.java                |
| LogicalLinkResponse.java         |              6 |             0 |           0 |      0 |           6 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/LogicalLinkResponse.java              |
| PnfProperties.java               |              6 |             0 |           0 |      0 |           6 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/PnfProperties.java                    |
| MsoRequestDetails.java           |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/changeManagement/MsoRequestDetails.java         |
| Relationship.java                |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/Relationship.java                     |
| ChangeManagementServiceImpl.java |              5 |             0 |           0 |      0 |           0 |           0 |            5 | vid-app-common/src/main/java/org/onap/vid/services/ChangeManagementServiceImpl.java       |
| GetTenantsResponse.java          |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/AaiGetTenatns/GetTenantsResponse.java |
| PnfResult.java                   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/PnfResult.java                        |
| MsoExceptionResponse.java        |              4 |             0 |           1 |      0 |           3 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/model/MsoExceptionResponse.java                 |
