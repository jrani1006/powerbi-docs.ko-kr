---
title: Power BI 프리미엄이란?
description: Power BI 프리미엄은 조직 또는 팀의 전용 용량으로, 사용자별 라이선스를 구입하지 않고도 더욱 신뢰할 수 있는 성능과 대용량 데이터 볼륨을 제공합니다.
author: mgblythe
ms.author: mblythe
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-admin
ms.topic: conceptual
ms.date: 09/11/2018
LocalizationGroup: Premium
ms.openlocfilehash: 87847575d4fff3d3530847246be5bc8f720b5141
ms.sourcegitcommit: c51461690e8faa121a1325957ca79b7a3975e8b8
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/12/2018
ms.locfileid: "44512136"
---
# <a name="power-bi-premium---what-is-it"></a>Power BI 프리미엄이란?
Power BI Premium은 조직 또는 팀에 대해 Power BI 서비스를 실행하는 전용 리소스를 제공합니다. 더욱 신뢰할 수 있는 성능을 제공하고 더 큰 데이터 볼륨을 사용하도록 설정합니다. 또한 프리미엄을 통해 뷰어를 위한 사용자별 라이선스를 구입할 필요 없이 광범위하게 콘텐츠를 배포할 수 있습니다.

*프리미엄 용량*에 작업 영역을 할당하여 Power BI Premium을 활용할 수 있습니다. 프리미엄 용량은 조직을 위한 전용 리소스입니다. 프리미엄 용량에 할당되지 않은 작업 영역은 *공유 용량*에 있습니다. 공유 용량을 사용하면 다른 고객이 공유하는 계산 리소스에서 워크로드가 실행됩니다. 공유 용량에서 모든 사용자를 위해 환경의 품질을 보장하도록 더 많은 제한이 개별 사용자에게 적용됩니다.

[!INCLUDE [powerbi-premium-illustration](./includes/powerbi-premium-illustration.md)]

<iframe width="560" height="315" src="https://www.youtube.com/embed/lNQDkN0GXzU?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

## <a name="capacity-tiers"></a>용량 계층

Power BI 내에는 두 가지 유형의 용량이 있습니다. 공유 용량 및 Power BI 프리미엄 용량입니다. 차이점을 살펴보면 다음과 같습니다.

|  | 공유 용량 | Power BI 프리미엄 용량 |
| --- | --- | --- |
| **새로 고침 빈도** |8/일 |48/일 |
| **전용 하드웨어로 격리** |![](media/service-premium/not-available.png "사용할 수 없음") |![](media/service-premium/available.png "사용 가능함") |
| **엔터프라이즈 배포 대상** ***모든 사용자*** | | |
| 앱 및 공유 |![](media/service-premium/not-available.png "사용할 수 없음") |![](media/service-premium/available.png "사용 가능함")<sup>1</sup> |
| 포함된 API 및 컨트롤 |![](media/service-premium/not-available.png "사용할 수 없음") |![](media/service-premium/available.png "사용 가능함")<sup>2</sup> |
| **Power BI 보고서 온-프레미스 게시** |![](media/service-premium/not-available.png "사용할 수 없음") |![](media/service-premium/available.png "사용 가능함") |

*<sup>1</sup> 자세한 내용은 [Power BI Pro 및 Power BI Premium을 사용하는 사용자 기능](service-free-vs-pro.md) 기능을 참조하세요.*  
*<sup>2</sup> 향후에 Power BI Premium에 제공될 향상된 기능입니다.*

### <a name="premium-capacity"></a>프리미엄 용량

Power BI 프리미엄 용량의 사용을 시작하려면 작업 영역을 용량에 할당해야 합니다. 프리미엄 용량으로 작업 영역을 지원하면 다음을 얻을 수 있습니다.

* **예약된 새로 고침**: 공유 용량을 사용하면 가져온 모델 데이터 집합에 대해 예약된 새로 고침이 하루 8번으로 제한됩니다. Premium 작업 영역에 있는 데이터 집합의 경우 하루 최대 48번까지 새로 고침을 예약할 수 있습니다. 향상된 예약된 새로 고침은 DirectQuery에 대해 예약된 캐시 새로 고침 설정에 적용되지 않으며 프리미엄 용량 및 공유 용량 간에 동일하게 유지됩니다.
* **전용 하드웨어로 격리**: 공유 용량의 특성으로 인해 안전 조치에도 불구하고 보고서 및 대시보드의 성능은 용량에 있는 다른 워크로드의 리소스 요청의 영향을 받을 수 있습니다. 그러나 프리미엄 용량은 관련되지 않은 워크로드와 분리하여 워크로드에 대해 더 일관되고 신뢰할 수 있는 성능을 제공합니다.

앱이 프리미엄 용량으로 지원되는 경우(즉, 현재 Premium에 할당된 앱 작업 영역에서 게시된 경우) 할당된 라이선스에 관계없이 조직의 모든 사용자가 게시된 앱을 사용할 수 있습니다.

프리미엄 용량에 작업 영역을 할당하는 방법에 대한 자세한 내용은 [Power BI Premium 관리](service-admin-premium-manage.md)를 참조하세요.

### <a name="shared-capacity"></a>공유 용량

기본적으로 작업 영역은 공유 용량에 있습니다. 이는 앱 작업 영역과 함께 개인적인 *내 작업 영역*을 포함합니다. 공유 용량은 다른 고객에 의해 공유되는 계산 리소스에서 워크로드를 실행하는 Power BI에 익숙한 환경입니다.

<a name="premiumskus"/>

### <a name="premium-capacity-nodes"></a>프리미엄 용량 노드

Power BI 프리미엄은 서로 다른 v-코어 용량으로 노드 구성에서 사용할 수 있습니다. 특정 SKU 제안 및 비용에 대한 자세한 내용은 [Power BI 가격 책정](https://powerbi.microsoft.com/pricing/)을 참조하세요. 또한 [비용 계산기](https://powerbi.microsoft.com/calculator/)를 사용할 수 있습니다. 포함된 분석 용량 계획에 관한 정보는 [Power BI 엔터프라이즈 배포 계획 백서](https://aka.ms/pbienterprisedeploy)를 참조하세요.

* P 노드는 포함된 배포 또는 서비스 배포에 사용할 수 있습니다.
* EM 노드는 포함된 배포에만 사용할 수 있습니다. EM 노드에는 Power BI Pro 라이선스가 없는 사용자와 앱 공유와 같은 프리미엄 기능에 대한 액세스 권한이 없습니다.

>[!NOTE]
>이 표의 링크는 Office 365 전역 관리자인 사용자에 대해서만 정상적으로 작동하고, 그 외의 사용자는 404 오류를 수신합니다.

| 용량 노드 | 총 V 코어<br/>*(백 엔드 + 프런트 엔드)* | 백 엔드 V 코어 | 프런트 엔드 V 코어 | DirectQuery/라이브 연결 제한 | 사용량이 가장 많은 시간에 최대 페이지 렌더링 | 가용성 |
| --- | --- | --- | --- | --- | --- | --- |
| [EM1(매월)](https://portal.office.com/SubscriptionDetails?OfferId=4004702D-749C-4F74-BF47-3048F1833780&adminportal=1) |1개 가상 코어 |0.5v-코어, 2.5GB RAM |0.5v-코어 |초당 3.75 |150-300 |사용 가능함 |
| [EM2(매월)](https://portal.office.com/SubscriptionDetails?OfferId=4004702D-749C-4F74-BF47-3048F1833780&adminportal=1) |2v-코어 |1v-코어, 5GB RAM |1개 가상 코어 |초당 7.5 |301-600 |사용 가능함 |
| [EM3(매월)](https://portal.office.com/SubscriptionDetails?OfferId=4004702D-749C-4F74-BF47-3048F1833780&adminportal=1) |4v-코어 |2v-코어, 10GB RAM |2v-코어 | |601-1,200 |사용 가능함 |
| [P1](https://portal.office.com/SubscriptionDetails?OfferId=b3ec5615-cc11-48de-967d-8d79f7cb0af1&adminportal=1) |8v-코어 |4v-코어, 25GB RAM |4v-코어 |초당 30 |1,201-2,400 |사용 가능함([매월](https://portal.office.com/SubscriptionDetails?OfferId=E4C8EDD3-74A1-4D42-A738-C647972FBE81&adminportal=1)도 사용 가능함) |
| [P2](https://portal.office.com/SubscriptionDetails?OfferId=062F2AA7-B4BC-4B0E-980F-2072102D8605&adminportal=1) |16v-코어 |8v-코어, 50GB RAM |8v-코어 |초당 60 |2,401-4,800 |사용 가능함 |
| [P3](https://portal.office.com/SubscriptionDetails?OfferId=40c7d673-375c-42a1-84ca-f993a524fed0&adminportal=1) |32v-코어 |16v-코어, 100GB RAM |16v-코어 |초당 120 |4,801-9600 |사용 가능함 |

* 프런트 엔드 V 코어는 웹 서비스, 대시보드 및 보고서 문서 관리, 액세스 권한 관리, 예약, API, 업로드 및 다운로드, 일반적으로 사용자 환경에 관련된 모든 항목에 책임이 있습니다.
* 백 엔드 V 코어는 어려운 작업: 쿼리 처리, 캐시 관리, R 서버 실행, 데이터 새로 고침, 자연어 처리, 실시간 피드, 보고서 및 이미지의 서버 쪽 렌더링에 책임이 있습니다. 백 엔드 V 코어를 사용하여 메모리의 일정량도 예약됩니다. 큰 데이터 모델 또는 많은 수의 활성 데이터 집합을 처리할 때 충분한 메모리를 갖는 것은 특히 중요해지고 있습니다.

## <a name="power-bi-report-server"></a>Power BI Report Server
Power BI Premium에는 조직의 Power BI Report Server를 온-프레미스에서 실행할 수 있는 기능도 포함됩니다. 자세한 내용은 [Power BI Report Server 시작](report-server/get-started.md)을 참조하세요.

## <a name="next-steps"></a>다음 단계
[Power BI 프리미엄 FAQ](service-premium-faq.md)  
[Power BI 프리미엄 릴리스 정보](service-premium-release-notes.md)  
[Power BI 프리미엄 구매 방법](service-admin-premium-purchase.md)  
[Power BI 프리미엄 관리](service-admin-premium-manage.md)  
[Microsoft Power BI 프리미엄 백서](https://aka.ms/pbipremiumwhitepaper)  
[Power BI 엔터프라이즈 배포 계획 백서](https://aka.ms/pbienterprisedeploy)  
[조직에서 Power BI 관리](service-admin-administering-power-bi-in-your-organization.md)  

궁금한 점이 더 있나요? [Power BI 커뮤니티에 질문합니다.](https://community.powerbi.com/)
