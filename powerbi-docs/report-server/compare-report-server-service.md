---
title: Power BI Report Server 및 Power BI 서비스 비교
description: 이 문서에서는 Power BI Report Server와 Power BI 서비스의 기능을 비교합니다.
keywords: ''
author: maggiesMSFT
ms.author: maggies
ms.date: 05/07/2018
ms.topic: overview
ms.service: powerbi
ms.component: powerbi-report-server
manager: kfile
ms.custom: mvc
ms.openlocfilehash: f78638097ea33f9954f3db78c117f1935a68530b
ms.sourcegitcommit: 52ac456bf2ac025b22ea634c28482f22e1cc19ac
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/10/2018
ms.locfileid: "48908534"
---
# <a name="comparing-power-bi-report-server-and-the-power-bi-service"></a>Power BI Report Server 및 Power BI 서비스 비교

Power BI Report Server 및 Power BI 서비스에는 많은 유사성과 일부 주요 차이점이 있습니다. 이 표에서 유사성과 차이점을 설명합니다.

| 기능 | Power BI Report Server | Power BI 서비스 | 참고
|---------|---------|---------|---------|
| 배포 | 온-프레미스 또는 호스트 클라우드 | 클라우드 | Power BI Premium을 통해 라이선스가 부여된 경우 Azure VM(호스트 클라우드)에 Power BI Report Server를 배포할 수 있습니다.
| 원본 데이터 | 클라우드 및/또는 온-프레미스 | 클라우드 및/또는 온-프레미스 |  
| 라이선스 | Power BI Premium 또는 SQL Server EE(SA 포함) | Power BI Pro 및/또는 Power BI Premium |  
| 수명 주기 | 최신 수명 주기 정책 | 완전히 관리되는 서비스 |  
| 릴리스 주기 | 4개월마다 한 번 | 1개월에 한 번 | 최신 기능 및 수정은 Power BI 서비스에 대해 먼저 제공됩니다. 대부분의 핵심 기능은 다음 몇 가지 릴리스에서 Power BI Report Server에 대해 제공되고, 일부 기능은 Power BI 서비스에만 적용됩니다.
| Power BI Desktop에서 Power BI 보고서 만들기 | 예 | 예 |  
| 브라우저에서 Power BI 보고서 만들기 | 아니요 | 예 |  
| 게이트웨이 필요 | 아니요 | 온-프레미스 데이터 원본의 경우 예 |  
| 실시간 스트리밍 | 아니요 | 예 | [Power BI에서 실시간 스트리밍](../service-real-time-streaming.md)
| 대시보드 | 아니요 | 예 | [Power BI 서비스의 대시보드](../consumer/end-user-dashboards.md) 
| 앱을 사용하여 보고서 그룹 배포 | 아니요 | 예 | [대시보드 및 보고서로 앱 생성 및 게시](../service-create-distribute-apps.md) 
| 콘텐츠 팩 | 아니요 | 예 | [조직 콘텐츠 팩: 소개](../service-organizational-content-pack-introduction.md) 
| Salesforce와 같은 서비스에 연결 | 아니요 | 예 | Power BI 서비스와 함께 [사용하는 서비스에 연결](../consumer/end-user-connect-to-services.md)
| 질문 및 답변 | 아니요 | 예 | [Power BI 서비스 및 Power BI Desktop의 질문 및 답변](../consumer/end-user-q-and-a.md) 
| 신속한 정보 활용 | 아니요 | 예 | [Power BI를 사용하여 데이터 인사이트를 자동으로 생성](../consumer/end-user-insights.md) 
| Excel에서 분석 | 아니요 | 예 | [Excel에서 분석](../service-analyze-in-excel.md) 
| 페이지가 매겨진 보고서 | 예 | 아니요 | 페이지를 매긴 보고서는 Power BI 서비스에서 사용할 수 없지만, [페이지를 매긴 보고서 항목을 Power BI 대시보드에 고정](https://docs.microsoft.com/sql/reporting-services/pin-reporting-services-items-to-power-bi-dashboards)할 수 있습니다.
| Power BI 모바일 앱 | 예 | 예 | [Power BI 모바일 앱 개요](../consumer/mobile/mobile-apps-for-mobile-devices.md) 
| ARC GIS 지도 | 아니요 | 예 | [Power BI 서비스 및 Power BI Desktop에서 Esri로 ArcGIS 지도 만들기](../power-bi-visualization-arcgis.md)
| Power BI 보고서에 대한 메일 구독 | 아니요 | 예 | Power BI 서비스에서 [보고서 또는 대시보드 구독](../consumer/end-user-subscribe.md) 
| 페이지를 매긴 보고서에 대한 메일 구독 | 예 | 아니요 | [Reporting Services의 메일 전송](https://docs.microsoft.com/sql/reporting-services/subscriptions/e-mail-delivery-in-reporting-services)  
| 데이터 경고 | 아니요 | 예 | Power BI 서비스의 [데이터 경고](../service-set-data-alerts.md)
| 행 수준 보안 | DirectQuery 모드에서 데이터 원본을 통해서만 | DirectQuery(데이터 원본) 및 가져오기 모드에서 사용 가능 | Power BI를 사용하는 [RLS(행 수준 보안)](../service-admin-rls.md) 
| 전체 화면 모드 | 아니요 | 예 | Power BI 서비스의 [전체 화면 모드](../service-fullscreen-mode.md) 
| 고급 Office 365 공동 작업 | 아니요 | 예 | Office 365를 사용하여 [앱 작업 영역에서 공동 작업](../service-collaborate-power-bi-workspace.md) 
| R 시각적 개체 | 아니요 | 예 | Power BI 서비스에서 [R 시각적 개체 만들기](../visuals/service-r-visuals.md)  
| 미리 보기 기능 | 아니요 | 예 | [Power BI 서비스 미리 보기 기능 옵트인](../consumer/end-user-preview-features.md) 
| 사용자 지정 시각적 개체 | 예 | 예 | [Power BI의 사용자 지정 시각적 개체](../power-bi-custom-visuals.md) 
| Power BI Desktop | 보고서 서버에 최적화된 버전으로, 보고서 서버로 다운로드할 수 있음 | Power BI 서비스에 최적화된 버전으로, Windows 스토어에서 사용 가능 | [보고서 서버용 Power BI Desktop](https://powerbi.microsoft.com/report-server/) <br><br> [Power BI 서비스용 Power BI Desktop](http://aka.ms/pbidesktopstore)

## <a name="next-steps"></a>다음 단계
[Power BI Report Server 설치](install-report-server.md)  



