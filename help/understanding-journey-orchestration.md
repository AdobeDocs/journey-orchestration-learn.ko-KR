---
title: Journey Orchestration 이해
description: Journey Orchestration의 개념, 사용 사례 유형 및 Journey Orchestration 작동 방식의 주요 요소를 파악할 수 있습니다.
feature: Overview
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: cba80e227001486dd97becc826b0a45ab5fc3c53
workflow-type: tm+mt
source-wordcount: '323'
ht-degree: 100%

---

# [!UICONTROL Journey Orchestration] 이해 

[!UICONTROL Journey Orchestration]을 통해 이벤트 또는 데이터 소스에 저장된 상황별 데이터를 활용하여 실시간 오케스트레이션 사용 사례를 구축할 수 있습니다.

## [!UICONTROL Journey Orchestration] 소개

[!UICONTROL Journey Orchestration]은(는) Adobe Experience Platform과 통합된 애플리케이션 서비스입니다. 지능적이고 개방적인 에코시스템을 제공하여 마케팅에서 운영, 서비스에 이르기까지 비즈니스에 필요한 모든 채널에서 확장 가능한 이벤트 기반의 참여를 통해 모든 관련 라이브 데이터를 활성화할 수 있습니다. [!UICONTROL Journey Orchestration]은 Adobe Experience Platform 및 모든 외부 게재 시스템의 모든 데이터를 사용하여 매력적인 경험을 만들고 게재할 수 있습니다.

아래 비디오에서는 다음을 소개합니다.

* [!UICONTROL Journey Orchestration]의 개념 
* 사용 가능한 사용 사례의 유형
* [!UICONTROL Journey Orchestration] 작동 방식의 주요 요소

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12&learn=on)

## 여정 구성 방법

여정 빌드를 준비하기 위한 주요 단계는 다음과 같습니다.

1. [스트리밍 이벤트 구성](/help/configuring-journey-orchestration/configure-streaming-events.md) - [!UICONTROL Journey Orchestration]은(는) 이벤트를 수신 대기하도록 설계되었으므로 이 구성은 필수입니다.
1. [데이터 소스 구성](/help/configuring-journey-orchestration/configure-data-sources.md) - 여정이 이벤트 페이로드에서 전송되는 로컬 데이터만 활용하는 경우 이 구성은 필요하지 않습니다.
1. [사용자 지정 작업 구성](/help/configuring-journey-orchestration/configure-actions.md): JSON 형식의 페이로드가 있는 [!DNL REST API]을(를) 통해 호출할 수 있는 타사 공급자의 서비스를 사용하려는 경우 필요합니다.

>[!NOTE]
>
>이러한 구성 단계에는 기술 지식이 필요합니다. [XDM(경험 데이터 모델)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=ko) 및 [XDM 경험 이벤트 스키마를 구성하는 방법](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=ko)을 잘 알아야 합니다.

## 여정을 만들고 게시하고 분석하는 방법

1. [여정 만들기](/help/building-a-journey/creating-a-journey.md)
1. [여정의 유효성 검사 및 게시](/help/validate-and-publish-a-journey.md)
1. [보고 도구를 통한 여정 분석](/help/analyze-a-journey-via-reporting-tools.md)

## 추가 리소스

* [Journey Orchestration 도움말 센터](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=ko)
* [Adobe Experience Platform 튜토리얼](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=ko)
* [Journey Orchestration에 대한 도움말 찾는 방법](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - 시작](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=ko)
* [Adobe Experience Platform 위치 서비스](https://experienceleague.adobe.com/docs/places/using/home.html?lang=ko)
