---
title: "Power BI Desktop을 시작할 때 발생하는 문제 해결"
description: "Power BI Desktop을 시작할 때 발생하는 문제 해결"
services: powerbi
documentationcenter: 
author: davidiseminger
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
ms.date: 10/05/2017
ms.author: davidi
ms.openlocfilehash: cbc9c474056370ecde5c818d31a3a344b9b8fb8a
ms.sourcegitcommit: b3ee37e1587f1269ee7dd9daf1685a06dea3b50c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/23/2017
---
# <a name="resolve-issues-when-power-bi-desktop-will-not-launch"></a>Power BI Desktop이 시작되지 않는 문제 해결
**Power BI Desktop**에서 이전 버전의 **Power BI 온-프레미스 데이터 게이트웨이**를 설치하고 실행하는 사용자는 Power BI 온-프레미스 게이트웨이가 로컬 컴퓨터의 명명된 파이프에 배치되는 관리 정책 제한으로 인해 Power BI Desktop을 시작할 수 없게 됩니다. 

## <a name="resolve-issues-with-the-on-premises-data-gateway-and-power-bi-desktop"></a>온-프레미스 데이터 게이트웨이 및 Power BI Desktop 문제 해결
온-프레미스 데이터 게이트웨이와 관련된 문제를 해결하고 Power BI Desktop을 시작하도록 설정하는 세 가지 방법이 있습니다.

### <a name="resolution-1-install-the-latest-version-of-power-bi-on-premises-data-gateway"></a>해결 방법 1: 최신 버전의 Power BI 온-프레미스 데이터 게이트웨이 설치
최신 버전의 Power BI 온-프레미스 데이터 게이트웨이는 로컬 컴퓨터에 명명된 파이프 제한을 설정하지 않으며 Power BI Desktop이 제대로 시작될 수 있도록 합니다. Power BI 온-프레미스 데이터 게이트웨이를 계속 사용해야 하는 경우 이 방법이 권장됩니다. [이 위치](https://go.microsoft.com/fwlink/?LinkId=698863)에서 최신 버전의 Power BI 온-프레미스 데이터 게이트웨이를 다운로드할 수 있습니다. 이 링크는 설치 실행 파일에 대한 직접 다운로드 링크입니다.

### <a name="resolution-2-uninstall-or-stop-the-power-bi-on-premises-data-gateway-windows-service"></a>해결 방법 2: Power BI 온-프레미스 데이터 게이트웨이 Windows 서비스 제거 또는 중지
Power BI 온-프레미스 데이터 게이트웨이가 더 이상 필요하지 않은 경우 제거하거나 Power BI 온-프레미스 데이터 게이트웨이 Windows 서비스를 중지하여 정책 제한을 제거하고 Power BI Desktop이 시작되도록 할 수 있습니다.

### <a name="resolution-3-run-power-bi-desktop-with-administrator-privilege"></a>해결 방법 3: 관리자 권한으로 Power BI Desktop 실행
또는 관리자 권한으로 Power BI Desktop을 시작할 수도 있습니다. 이 경우에도 Power BI Desktop이 성공적으로 시작될 수 있습니다. 이 문서의 앞부분에 설명된 대로 최신 버전의 Power BI 온-프레미스 데이터 게이트웨이를 설치하는 것이 좋습니다.

## <a name="help-with-other-issues-when-launching-power-bi-desktop"></a>Power BI Desktop을 시작할 경우 기타 문제에 대한 도움말
**Power BI Desktop**에서 발생하는 문제를 최대한 처리하려고 노력하고 있습니다. 당사는 많은 고객에 영향을 줄 수 있는 문제를 정기적으로 살펴보고 문서에 포함시키고 있습니다.

**Power BI Desktop** 시작 관련 문제가 온-프레미스 데이터 게이트웨이와 관련되지 않는 경우 또는 이전 솔루션이 작동하지 않는 경우 [Power BI 지원팀](https://support.powerbi.com) (https://support.powerbi.com) 에 인시던트를 제출하여 문제를 식별하고 해결할 수 있습니다.

나중에 **Power BI Desktop**에서 다른 문제가 (없거나 극히 적기를 바랍니다만) 발생할 경우 추적을 설정하고 로그 파일을 수집하여 문제를 분리하고 식별하는 것이 좋습니다. 추적을 설정하려면 **파일 > 옵션 및 설정 > 옵션**을 선택한 후 **진단**을 선택하고 *진단 옵션* 아래에서 **추적 사용** 확인란을 선택합니다. 이 옵션을 설정하려면 **Power BI Desktop**을 실행 중이어야 합니다. 그러면 **Power BI Desktop** 시작과 관련된 이후 문제에서 유용합니다.
