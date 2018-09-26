---

copyright:

  years: 2015, 2018
lastupdated: "2018-04-13"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}

# 구조적 개요
{: #patterns}

프로젝트 성공을 위해 충분한 시간을 들여 필요한 리소스 및 엔터프라이즈 요구사항을 계획하고 디자인하십시오. 시작하는 데 도움을 받으려면 다음 질문을 고려하십시오.{:shortdesc}

* 개발 중인 앱의 수와 유형은 무엇입니까?
* 앱이 어떤 서비스에 액세스해야 합니까?
* 개발 프로세스에서 누가 협업하고 각각 어떤 역할을 수행합니까?
* 프로젝트의 각 단계에 어느 정도의 격리가 필요합니까?
* 엔터프라이즈에서 인프라 리소스를 제공합니까?
* 회사에서 어떻게 의사소통합니까?
* 조직 및 영역 사용을 명확히 식별하기 위해 구현할 수 있는 이름 지정 표준이 있습니까?

필요한 클라우드 환경의 유형을 결정하는 과정의 일부로 계정, 조직, 영역, 리소스 및 팀 구성원의 구조를 계획하십시오.

대부분의 회사의 경우 단일 {{site.data.keyword.Bluemix_notm}} 계정으로 충분합니다. 둘 이상의 비즈니스 영역이 있는 대기업의 경우 각 비즈니스 도메인마다 별도의 {{site.data.keyword.Bluemix_notm}} 계정을 사용할 수 있습니다. 예를 들어, 대형 은행 내에 소매 및 상업 분야에 대한 별도의 계정이 있을 수 있습니다.

다음 표는 일부 핵심 요소를 요약하여 보여줍니다.

|요소   |설명 |
|-----------|---------------|
||하나 이상의 조직을 포함합니다. 둘 이상의 조직을 작성하려면 종량과금제 계정이 있어야 합니다. |
||하나의 계정만 소유할 수 있습니다. |
||하나 이상의 조직 관리자를 추가하여 조직에 대한 읽기 및 쓰기 권한을 포함하는 조직 관리를 위임할 수 있습니다. |
||다른 {{site.data.keyword.Bluemix_notm}} 계정의 영역과 조직의 팀 구성원이 될 수 있습니다. |
|조직 |하나 이상의 영역을 포함합니다. |
||하나 이상의 조직 관리자를 포함합니다. |
||하나 이상의 팀 구성원을 포함합니다. 각 팀 구성원은 하나 이상의 역할을 부여받을 수 있습니다. |
||영역 내 배치된 애플리케이션에서 생성된 사용 요금은 조직 레벨에서 보고됩니다. |
|영역 |하나 이상의 리소스를 포함합니다. |
||하나 이상의 앱을 포함합니다. |
||하나 이상의 영역 관리자를 포함합니다. |
||하나 이상의 팀 구성원을 포함합니다. 각 사용자는 이미 소유 조직의 팀 구성원이어야 합니다. 각 팀 구성원은 하나 이상의 역할을 부여받을 수 있습니다. |
|팀 구성원 |여러 계정에 있는 하나 이상의 조직과 영역에 추가될 수 있습니다. |
||동일한 조직, 영역 또는 둘 다에 있는 둘 이상의 역할에 지정될 수 있습니다. |
{:caption="표 1. 핵심 요소 설명" caption-side="top"}
