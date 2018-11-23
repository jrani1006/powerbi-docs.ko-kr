---
title: Power BI 사용자 지정 시각적 개체에 대한 질문과 대답
description: Power BI 사용자 지정 시각적 개체에 대한 질문과 대답 목록을 찾아보세요.
author: markingmyname
ms.author: maghan
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 10/29/2018
LocalizationGroup: Visualizations
ms.openlocfilehash: 064d32944f52f6e391d4a7ec4df41ecbf09b7e3f
ms.sourcegitcommit: 02f918a4f27625b6f4e47473193ebc8219db40e2
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/07/2018
ms.locfileid: "51223079"
---
# <a name="frequently-asked-questions-about-power-bi-custom-visuals"></a>Power BI 사용자 지정 시각적 개체에 대한 질문과 대답

## <a name="organizational-custom-visuals"></a>조직의 사용자 지정 시각적 개체

**관리자는 조직의 사용자 지정 시각적 개체를 어떻게 관리할 수 있나요?**

관리 포털의 “조직의 사용자 지정 시각적 개체” 탭 아래에서 관리자는 [엔터프라이즈의 모든 조직 사용자 지정 시각적 개체를 보고 관리](https://docs.microsoft.com/power-bi/service-admin-portal#organization-visuals)(추가, 사용하거나 사용하지 않도록 설정 및 삭제)할 수 있습니다.
이러한 시각적 개체를 더 이상 메일 또는 공유 폴더로 공유할 필요가 없습니다. 조직의 리포지토리에 배포되면 조직의 사용자는 쉽게 검색할 수 있고 조직의 사용자 지정 시각적 개체를 Power BI Desktop 또는 서비스에서 바로 보고서로 가져올 수 있습니다. 조직의 사용자 지정 시각적 개체는 “내 조직” 탭 아래 Desktop 및 서비스의 기본 제공 저장소에서 찾을 수 있습니다. 관리자가 새로운 조직의 사용자 지정 시각적 개체 버전을 업로드하면 조직의 모든 사용자가 동일한 업데이트된 버전을 가져옵니다. 이러한 시각적 개체를 사용하는 모든 보고서가 자동으로 업데이트되므로 보고서 작성자는 이러한 시각적 개체의 새 버전을 가져오기 위해 보고서의 시각적 개체를 삭제할 필요가 없습니다. 업데이트 메커니즘은 Marketplace 시각적 개체와 유사합니다.

**관리자가 공개 Marketplace에서 조직 저장소로 사용자 지정 시각적 개체를 업로드하는 경우 공급업체가 공개 Marketplace에서 시각적 개체를 업데이트하면 해당 시각적 개체가 자동으로 업데이트되나요?**

아니요. 공개 Marketplace에서는 자동 업데이트가 없습니다.
필요한 경우 관리자가 조직의 사용자 지정 시각적 개체 버전을 업데이트해야 합니다.

**조직의 저장소를 사용하지 않도록 설정하는 방법이 있나요?**

아니요. Power BI Desktop 및 서비스에는 항상 “내 조직” 탭이 표시됩니다. 관리자는 관리 포털에서 모든 조직의 사용자 지정 시각적 개체를 사용하지 않도록 설정하거나 삭제할 수 있고 조직의 저장소는 비어 있습니다.
  
**관리자가 관리 포털(테넌트 설정)에서 사용자 지정 시각적 개체를 사용하지 않도록 설정하는 경우에도 사용자가 조직의 사용자 지정 시각적 개체에 액세스할 수 있나요?**

예. 관리자가 관리 포털에서 사용자 지정 시각적 개체를 사용하지 않도록 설정해도 조직의 저장소에 영향을 주지 않습니다. 일부 조직은 사용자 지정 시각적 개체를 사용하지 않도록 설정하고 Power BI 관리자가 가져오고 조직의 저장소에 업로드한 엄선한 시각적 개체만 사용하도록 설정합니다. 관리 포털에서 사용자 지정 시각적 개체를 사용하지 않도록 설정해도 Power BI Desktop에는 적용되지 않습니다. Desktop 사용자는 계속해서 공개 Marketplace의 사용자 지정 시각적 개체를 보고서에 추가하고 사용할 수 있습니다. 그러나 이러한 공개 사용자 지정 시각적 개체는 Power BI 서비스에 게시되면 렌더링을 중지하고 적절한 오류를 표시합니다. Power BI 서비스를 사용하는 경우 공개 Marketplace에서 사용자 지정 시각적 개체를 가져올 수 없습니다. 관리 포털의 사용자 지정 시각적 개체 설정이 Power BI 서비스에 적용되므로 조직의 저장소에 있는 시각적 개체만 가져올 수 있습니다.

**조직의 저장소 및 조직의 사용자 지정 시각적 개체가 훌륭한 엔터프라이즈 솔루션을 만드는 이유는 무엇인가요?**

* 모든 사용자가 Power BI 관리자가 제어하는 동일한 시각적 개체 버전을 가져옵니다. 관리자가 관리 포털에서 시각적 개체 버전을 업데이트하면 조직의 모든 사용자가 업데이트된 버전을 자동으로 가져옵니다.

* 더 이상 메일 또는 공유 폴더를 통해 시각적 개체 파일을 공유할 필요가 없습니다! 한 곳에서 로그인한 모든 멤버에게 표시됩니다.

* 보안 및 지원 가능성이 제공됩니다. 새로운 조직의 사용자 지정 시각적 개체 버전이 Marketplace 시각적 개체와 비슷하게 모든 보고서에서 자동으로 업데이트됩니다.

* 조직의 사용자 지정 시각적 개체를 사용하는 조직의 사용자는 조직의 보안 요소인 조직의 사용자 지정 시각적 개체를 보고 사용하려면 로그인해야 합니다.

* 관리자는 조직에서 사용할 수 있는 사용자 지정 시각적 개체를 제어할 수 있습니다.

* 관리자는 관리 포털에서 테스트하기 위해 시각적 개체를 사용하도록/사용하지 않도록 설정할 수 있습니다. 해당 시각적 개체는 조직의 멤버에게만 허용되므로 보안이 강화됩니다.

## <a name="certified-custom-visuals"></a>인증된 사용자 지정 시각적 개체

**인증된 사용자 지정 시각적 개체란 무엇인가요?**

인증된 사용자 지정 시각적 개체는 특정 [지정된](power-bi-custom-visuals-certified.md) 코드 요구 사항 및 Power BI 팀의 테스트를 충족한 [Marketplace](https://appsource.microsoft.com/marketplace/apps?page=1&product=power-bi-visuals)의 시각적 개체입니다.  수행된 테스트는 시각적 개체가 외부 서비스 또는 리소스에 액세스하지 않는지 확인하도록 설계되었습니다. 그러나 Microsoft는 타사 사용자 지정 시각적 개체의 작성자가 아니므로 해당 시각적 개체의 기능을 확인하려는 고객은 직접 작성자에게 문의하는 것이 좋습니다.

## <a name="next-steps"></a>다음 단계

문제 해결에 대한 자세한 내용은 [Power BI 사용자 지정 시각적 개체 문제 해결](power-bi-custom-visuals-troubleshoot.md)을 방문하세요.