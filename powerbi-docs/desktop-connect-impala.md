---
title: "Power BI Desktop에서 Impala 데이터베이스에 연결"
description: "Power BI Desktop에서 Impala 데이터베이스에 쉽게 연결하고 사용"
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
ms.openlocfilehash: 80460bbcf8fb61bc8149304b3be359cd744c1b75
ms.sourcegitcommit: d91436de68a0e833ecff18d976de9d9431bc4121
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/06/2017
---
# <a name="connect-to-an-impala-database-in-power-bi-desktop"></a>Power BI Desktop에서 Impala 데이터베이스에 연결
Power BI Desktop에서 **Impala** 데이터베이스에 연결하고 Power BI Desktop의 다른 데이터 원본처럼 기본 데이터를 사용할 수 있습니다.

## <a name="connect-to-an-impala-database"></a>Impala 데이터베이스에 연결
**Impala** 데이터베이스에 연결하려면 Power BI Desktop의 **홈** 리본 메뉴에서 **데이터 가져오기**를 선택합니다. 왼쪽에 있는 범주에서 **데이터베이스**를 선택하면 **Impala**가 표시됩니다.

![](media/desktop-connect-impala/connect_impala_2.png)

**Impala** 창이 나타나면 상자에 Impala 서버 이름을 입력하거나 붙여 넣고 **확인**을 선택합니다. Power BI로 데이터를 직접 **가져오거나** **DirectQuery**를 사용할 수 있습니다. [DirectQuery 사용](desktop-use-directquery.md)에 대해 자세히 알아볼 수 있습니다.

![](media/desktop-connect-impala/connect_impala_3a.png)

메시지가 표시되면 사용자 이름 및 암호를 입력하거나 익명으로 연결합니다. 둘 다 지원됩니다.

![](media/desktop-connect-impala/connect_impala_4.png)

> [!NOTE]
> 특정 **Impala** 서버에 사용자 이름 및 암호를 입력하면 Power BI Desktop에서 후속 연결을 시도할 때에도 동일한 자격 증명을 사용합니다. **파일 > 옵션 및 설정 > 데이터 원본 설정**으로 이동하여 해당 자격 증명을 수정할 수 있습니다.
> 
> 

성공적으로 연결되면 **탐색기** 창이 나타나고 서버에 사용 가능한 데이터를 표시합니다. 여기서 하나 이상의 요소를 선택하여 **Power BI Desktop**에 가져오고 사용할 수 있습니다.

![](media/desktop-connect-impala/connect_impala_5.png)

## <a name="considerations-and-limitations"></a>고려 사항 및 제한 사항
**Impala** 커넥터에서 유의해야 하는 몇 가지 제한 및 고려 사항이 있습니다.

* 향후 계획에는 **Power BI Gateway**를 사용하는 새로 고침 지원이 포함됩니다.

## <a name="next-steps"></a>다음 단계
Power BI Desktop을 사용하여 연결할 수 있는 모든 종류의 데이터가 있습니다. 데이터 원본에 대한 자세한 내용은 다음 리소스를 확인하세요.

* [Power BI Desktop 시작](desktop-getting-started.md)
* [Power BI Desktop의 데이터 원본](desktop-data-sources.md)
* [Power BI Desktop에서 데이터 셰이핑 및 결합](desktop-shape-and-combine-data.md)
* [Power BI Desktop에서 Excel 통합 문서에 연결](desktop-connect-excel.md)   
* [Power BI Desktop에 데이터 직접 연결](desktop-enter-data-directly-into-desktop.md)   
