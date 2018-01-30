---
title: "Power BI Embedded에 대한 질문과 대답"
description: "Power BI Embedded에 대한 질문과 대답 목록을 찾아보세요."
services: powerbi
documentationcenter: 
author: guyinacube
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: no
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 01/15/2018
ms.author: asaxton
ms.openlocfilehash: aa4401a6c913d38e471f83b88fec351308d25870
ms.sourcegitcommit: 259d7689bcb1683d4d63a245a9b02becea072139
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/17/2018
---
# <a name="frequently-asked-questions-about-power-bi-embedded"></a>Power BI Embedded에 대한 질문과 대답

* 다른 질문이 있는 경우 [Power BI 커뮤니티에 질문합니다](http://community.powerbi.com/).
* 여전히 문제가 있나요? [Power BI 지원 페이지](https://powerbi.microsoft.com/support/)를 방문하세요.

## <a name="general"></a>일반

### <a name="what-is-power-bi-embedded"></a>Power BI Embedded는 무엇입니까?

Microsoft Power BI Embedded를 사용하면 응용 프로그램 개발자는 자체 데이터 시각화 및 컨트롤을 처음부터 새로 만들 필요 없이 완전한 대화형 보고서, 대시보드 및 타일을 포함할 수 있습니다.

### <a name="who-is-the-target-audience-for-power-bi-embedded"></a>Power BI Embedded의 대상 그룹은 누구입니까?

자체 응용 프로그램을 만드는 개발자 및 소프트웨어 회사를 말하며 ISV(독립 소프트웨어 공급업체)라고도 합니다.

### <a name="how-is-power-bi-embedded-different-from-power-bi-the-service"></a>Power BI Embedded는 Power BI 서비스와 어떤 차이가 있습니까?

Power BI Embedded는 분석 솔루션을 처음부터 새로 만들지 않고 응용 프로그램을 빌드한 후 고객의 의사 결정을 도와주는 시각적 개체를 해당 응용 프로그램에 포함하려는 ISV 또는 개발자를 위한 것입니다. 비즈니스 사용자는 포함된 분석 서비스를 사용하여 비즈니스 데이터에 액세스하고 응용 프로그램 내에서 이 데이터를 사용하여 고급 정보를 생성하는 쿼리를 수행할 수 있습니다.

반면, Power BI는 조직의 가장 중요한 비즈니스 데이터의 단일 보기를 제공하는 SaaS(software-as-a-service) 분석 솔루션입니다.

### <a name="what-is-the-difference-between-power-bi-premium-and-power-bi-embedded"></a>Power BI Premium과 Power BI Embedded의 차이점은 무엇인가요?

Power BI Premium은 조직, 파트너, 고객 및 공급업체에 대한 단일 보기를 제공하는 완전한 BI 솔루션을 원하는 기업 고객을 위한 용량입니다. Power BI Premium은 조직의 의사 결정을 도와줍니다. Power BI Premium은 SaaS 제품이며 사용자가 Power BI 포털, 모바일 앱 및 내부에서 개발한 응용 프로그램을 통해 콘텐츠를 사용하는 기능을 기본적으로 제공합니다.

Power BI Embedded는 응용 프로그램을 빌드하고 시각적 개체를 포함하려는 ISV 또는 개발자를 위한 용량입니다. Power BI Embedded는 고객의 의사 결정에 도움을 줍니다. 왜냐하면 Power BI Embedded는 응용 프로그램 개발자를 위한 용량이며 해당 응용 프로그램 고객은 조직 내부 또는 외부의 아무 사용자를 포함하여 Power BI Embedded 용량에 저장된 콘텐츠를 사용할 수 있기 때문입니다. Power BI Embedded 용량은 한 번 클릭으로 웹 게시 또는 한 번 클릭으로 SharePoint 게시를 통해 공유할 수 없으며, SSRS 보고서를 지원하지 않습니다.

### <a name="what-is-the-microsoft-recommendation-for-when-a-customer-should-buy-power-bi-premium-vs-power-bi-embedded"></a>고객이 Power BI Premium 또는 Power BI Embedded 중에 하나를 구매해야 하는 경우 Microsoft에서는 무엇을 추천합니까?

Microsoft는 기업 고객에게는 엔터프라이즈급 셀프 서비스 클라우드 BI 솔루션인 Power BI Premium을, ISV에게는 클라우드 기반의 포함된 분석 구성 요소인 Power BI Embedded를 추천합니다. 그러나 고객이 구매할 수 있는 제품에는 제한이 없습니다.

ISV(일반적으로 대규모)가 P SKU를 사용하여 조직 내에서 사전 패키지 Power BI 서비스의 추가 이점을 누리는 동시에 응용 프로그램에 포함하려는 경우가 있을 수 있습니다. 물론 LOB(기간 업무) 응용 프로그램을 빌드하고 분석 도구를 포함하는 데에만 관심이 있고 사전 패키지 Power BI 서비스에는 관심이 없는 기업은 A SKU를 사용해도 됩니다.

### <a name="how-many-embed-tokens-can-i-create"></a>얼마나 많은 포함 토큰을 만들 수 있습니까?

PRO 라이선스가 있는 포함 토큰은 개발 및 개발 테스트용이므로 Power BI 마스터 계정에서 생성할 수 있는 포함 토큰의 수는 제한적입니다. 프로덕션 환경에 포함하려면 [용량을 구입해야](https://docs.microsoft.com/power-bi/developer/embedded-faq#technical) 합니다. 용량을 구입할 때 생성할 수 있는 포함 토큰 수에는 제한이 없습니다.

### <a name="when-will-power-bi-embedded-be-available-in-azure"></a>언제부터 Azure에서 Power BI Embedded를 사용할 수 있나요?

현재 Power BI Embedded를 사용할 수 있습니다.

## <a name="technical"></a>기술

### <a name="what-is-the-difference-between-the-a-skus-in-azure-and-em-skus-in-office-365"></a>Azure의 A SKU와 Office 365의 EM SKU는 어떤 차이가 있나요?

PowerBI.com은 Software as a Service에 소셜 공동 작업, 전자 메일 구독 등의 여러 기능을 포함하는 엔터프라이즈 솔루션입니다.

Power BI Embedded는 Platform as a Service에서 포함된 분석 솔루션을 만드는 개발자를 위한 API 집합입니다. Embedded 분석 시나리오의 경우 PowerBI.com을 사용하여 ISV 및 개발자의 포함된 분석 솔루션 콘텐츠 및 테넌트 수준 설정 관리를 도와주어야 합니다.

다음은 기능상 차이점의 일부 목록입니다.

|특정  |Power BI Embedded<br>(A SKU) |Power BI Premium 용량<br>(EM SKU)  |
|---------|---------|---------|
|Power BI 앱 작업 영역의 포함된 아티팩트     |Azure 용량 |Office 365 용량 |
|보고서를 사용하려면 Power BI 라이선스 필요 |아니요  |예 |
|Embedded 응용 프로그램에서 Power BI 보고서 사용 |예  |예 |
|SharePoint에서 Power BI 보고서 사용 |아니요 |예 |
|Teams에서 Power BI 보고서 사용 |아니요 |예 |

### <a name="power-bi-now-offers-three-skus-for-embedding-a-skus-em-skus-and-p-skus-which-one-should-i-purchase-for-my-scenario"></a>이제 Power BI는 A SKU, EM SKU, P SKU의 세 가지 SKU를 포함할 수 있습니다. 제 시나리오에는 어떤 용량을 구매해야 하나요?

|  |A SKU(Power BI Embedded)  |EM SKU(Power BI Premium)  |P SKU(Power BI Premium)  |
|---------|---------|---------|---------|
|구입     |Azure Portal |Office |Office |
|사용 사례 |* 자체 응용 프로그램에 콘텐츠 포함 |* 자체 응용 프로그램에 콘텐츠 포함<br>* PowerBI.com 외부의 Power BI FREE 사용자와 콘텐츠를 공유하고 다른 SaaS 응용 프로그램(SharePoint, Teams)에 포함 |* 자체 응용 프로그램에 콘텐츠 포함<br>* PowerBI.com 외부의 Power BI FREE 사용자와 콘텐츠를 공유하고 다른 SaaS 응용 프로그램(SharePoint, Teams)에 포함<br>* PowerBI.com을 통해 Power BI FREE 사용자와 콘텐츠 공유  |
|청구 |시간별 |매월 |매월 |
|약정  |약정 없음 |매년  |매월/매년 |
|차별화 |탁월한 탄력성 - Azure Portal에서 또는 API를 통해 리소스를 강화/규모 축소, 일시 중지/다시 시작 가능  |SharePoint Online 및 Microsoft Teams에 콘텐츠를 포함하는 데 사용 가능 |응용 프로그램에 포함 및 Power BI 서비스 사용을 동일한 용량에 결합 |

### <a name="what-are-the-prerequisites-to-create-a-pbie-capacity-in-azure"></a>Azure에서 PBIE 용량을 만드는 필수 구성 요소는 무엇입니까?

- 조직 디렉토리에 로그인해야 합니다(MSA 계정은 지원되지 않음).
- Power BI 테넌트가 있어야 합니다. 즉, 디렉토리에 있는 한 명 이상의 사용자가 Power BI에 가입해야 합니다. 
- 조직 디렉토리에 Azure 구독이 있어야 합니다.

### <a name="how-can-i-monitor-capacity-consumption"></a>용량 소비를 모니터링하려면 어떻게 하나요?

조만간 Azure를 통해 모니터링을 사용할 수 있습니다. Azure 리소스인 Power BI Embedded는 상태 및 사용 현황을 보여주는 모니터링 KPI를 포함할 예정입니다.

### <a name="will-my-capacity-scale-automatically-to-adjust-to-the-consumption-of-my-app"></a>앱의 소비량에 따라 용량이 자동으로 조정되나요?

아직은 자동 조정 기능이 없지만, 언제든지 조정할 수 있도록 모든 API가 제공됩니다.

### <a name="what-is-the-authentication-model-for-power-bi-embedded"></a>Power BI Embedded의 인증 모델은 무엇인가요?

Power BI Embedded는 앞으로도 계속해서 마스터 사용자 인증(지정된 Power BI Pro 라이선스 사용자)에 Azure AD를 사용하여 Power BI 내에서 응용 프로그램을 인증할 것입니다.

응용 프로그램 사용자의 인증 및 권한 부여는 ISV를 통해 구현되고, ISV는 자체 응용 프로그램에 맞는 자체 인증을 구현할 수 있습니다.

이미 Azure AD 테넌트가 있는 경우 기존 디렉터리를 사용해도 되고, 포함된 응용 프로그램 콘텐츠 보안을 위해 Azure AD 테넌트를 새로 만들어도 됩니다.

### <a name="how-is-power-bi-embedded-different-from-other-azure-services"></a>Power BI Embedded는 다른 Azure 서비스와 어떤 차이가 있나요?

ISV/개발자는 Azure에서 Power BI Embedded를 구매하려면 Power BI 계정이 필요합니다. Power BI Embedded 배포 지역은 Power BI 계정에 따라 결정됩니다. Azure에서 Power BI Embedded 리소스를 관리하여 다음 작업을 수행할 수 있습니다.

* 강화/규모 축소
* 용량 관리자 추가
* 서비스 일시 중지/다시 시작

PowerBI.com을 사용하여 Power BI Embedded 용량에 작업 영역을 할당/할당 취소.

### <a name="what-deploy-regions-are-supported"></a>지원되는 배포 영역은 어디인가요?

오스트레일리아 남동부, 브라질 남부, 캐나다 중부, 미국 동부 2, 인도 서부, 일본 동부, 미국 중북부, 북유럽, 미국 중남부, 동남 아시아, 영국 남부, 유럽 서부, 미국 서부 및 미국 서부 2입니다.

## <a name="licensing"></a>라이선싱

### <a name="how-do-i-purchase-power-bi-embedded"></a>Power BI Embedded를 구매하려면 어떻게 하나요?

Power BI Embedded는 Azure를 통해 제공됩니다.

### <a name="how-power-bi-embedded-be-metered"></a>Power BI Embedded는 요금제가 어떻게 되나요?

Power BI Embedded는 시간당 요금으로 계산됩니다.

### <a name="how-does-the-usage-of-power-bi-embedded-show-up-on-my-bill"></a>청구서에 Power BI Embedded 사용량이 어떻게 표시되나요?

Power BI Embedded는 배포된 노드 유형을 기반으로 예측 가능한 시간당 요금이 청구됩니다. 리소스가 활성화되어 있는 한 사용하지 않는 경우에도 비용이 청구됩니다. 비용 청구를 중지하려면 리소스를 일시 중지해야 합니다. Azure 또는 ARM API를 통해 일시 중지할 수 있습니다.

### <a name="what-happens-if-i-already-purchased-power-bi-premium-and-now-i-want-some-of-the-benefits-of-power-bi-embedded-in-azure"></a>이미 Power BI Premium을 구입했는데 Azure에서 Power BI Embedded의 일부 이점을 사용하고 싶으면 어떻게 하나요?

고객은 계약 기간이 종료될 때까지는 기존에 구매한 Power BI Premium 요금을 계속 지불해야 하며, 기간이 종료되면 해당 시점의 상황을 보고 Power BI Premium을 전환하면 됩니다.

### <a name="do-i-still-have-to-buy-power-bi-premium-to-get-access-to-power-bi-embedded"></a>Power BI Embedded에 액세스하려면 Power BI Premium을 구매해야 하나요?

아니요, Power BI Embedded는 고객에게 솔루션을 배포해야 하는 Azure 기반 용량을 포함하고 있습니다.

### <a name="who-needs-a-power-bi-pro-license-for-power-bi-embedded-and-why"></a>Power BI Embedded에 Power BI Pro 라이선스가 필요한 사람은 누구이고 그 이유는 무엇인가요?

Power BI 작업 영역에 보고서를 추가해야 하는 분석가, REST API를 사용해야 하는 개발자, Power BI 테넌트 및 용량을 관리해야 하는 테넌트 관리자는 Power BI Pro 라이선스가 필요합니다.

Power BI Embedded는 Power BI 포털을 사용하여 포함된 콘텐츠를 관리하고 유효성을 검증할 수 있으므로, 올바른 리포지토리의 보고서에 액세스할 수 있도록 PowerBI.com 내에서 앱을 인증하려면 Power BI Pro 라이선스가 필요 합니다.

### <a name="can-i-get-started-for-free"></a>무료로 시작할 수 있나요?

예, Power BI Embedded에 [Azure 크레딧](https://azure.microsoft.com/free/)을 사용할 수 있습니다.

### <a name="can-i-get-a-trial-experience-for-power-bi-embedded-in-azure"></a>Azure에서 Power BI Embedded 평가판을 받을 수 있나요?

Power BI Embedded는 Azure의 일부이기 때문에 [Azure에 등록할 때 받은 $200 크레딧](https://azure.microsoft.com/free/)으로 서비스를 사용할 수 있습니다.

### <a name="whats-the-purchase-commitment-for-power-bi-embedded"></a>Power BI Embedded의 구매 약정은 어떻게 되나요? 

고객은 시간 단위로 사용량을 변경할 수 있습니다. Power BI Embedded 서비스는 월별 또는 연간 약정이 없습니다.

### <a name="where-is-power-bi-embedded-available-us-government-germany-china-what-is-the-timing"></a>Power BI Embedded는 어디서 제공하나요? 미국 정부? 독일? 중국? 언제부터 제공되나요?

Power BI Embedded는 일반 공급 시 Azure 상용 클라우드를 통해 제공될 예정입니다.  향후 소버린 클라우드 가용성이 추가될 예정입니다.

### <a name="is-power-bi-embedded-available-for-non-profits-and-educational"></a>교육 기관 및 비영리 단체도 Power BI Embedded를 사용할 수 있나요?

교육 기관 및 비영리 단체는 Azure를 구매할 수 있습니다. Azure에는 이러한 고객을 위한 특별 가격이 없습니다.

궁금한 점이 더 있나요? [Power BI 커뮤니티를 이용하세요.](http://community.powerbi.com/)