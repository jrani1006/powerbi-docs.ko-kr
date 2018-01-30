---
title: "타사 서비스: Power BI Desktop에 대한 Facebook 커넥터"
description: "타사 서비스: Power BI Desktop에 대한 Facebook 커넥터"
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
ms.date: 12/06/2017
ms.author: davidi
ms.openlocfilehash: 4e8600aac79683a53b7c2075b3d81e91b3354901
ms.sourcegitcommit: d91436de68a0e833ecff18d976de9d9431bc4121
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/06/2017
---
# <a name="facebook-connector-for-power-bi-desktop"></a>Power BI Desktop용 Facebook 커넥터
**Power BI Desktop**의 Facebook 커넥터는 Facebook Graph API를 사용합니다. 이와 같이 기능 및 가용성은 시간에 따라 달라질 수 있습니다.

[Power BI Desktop에 대한 Facebook 커넥터에 대한 자습서](desktop-tutorial-facebook-analytics.md)를 참조할 수 있습니다.

2015년 4월 30일<sup></sup>에 Facebook의 Graph API v1.0이 만료되었습니다. Power BI는 Facebook 커넥터에 대해 내부적으로 Graph API를 사용하여 데이터에 연결하고 분석할 수 있도록 합니다.

2015년 4월 30일<sup></sup> 이전에 작성된 쿼리는 더 이상 작동하지 않거나 더 적은 양의 데이터를 반환합니다. 2015년 4월 30일<sup></sup> 이후부터 Power BI는 Facebook API에 대한 모든 호출에 v2.2를 활용합니다. 2015년 4월 30일 이전에 쿼리가 작성되었으며 이후에 사용하지 않은 경우 요청되는 새로운 권한 집합을 승인하기 위해 다시 인증해야 할 수 있습니다.

변경 내용에 따라 업데이트 릴리스를 시도하기는 하지만 API로 인해 생성하는 쿼리 결과에 영향을 주는 방식이 변경될 수 있습니다. 특정 쿼리가 더 이상 지원되지 않는 경우도 있습니다. 이 종속성으로 인해 이 커넥터를 사용할 때 쿼리 결과를 보장할 수 없습니다.

Facebook API의 변경 사항에 대한 자세한 내용은 [여기](https://developers.facebook.com/docs/apps/changelog#v2_0)를 참조하세요.
