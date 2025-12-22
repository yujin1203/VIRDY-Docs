---
description: 'Vicon 세팅'
sidebar_label: 'Vicon 세팅'
sidebar_position: 7
---

# Vicon 세팅

## Vicon Subject 생성

![Vicon1](/img/Page_AvatarSettings/MotionSet/Vicon_1.png) <br/>
Vicon은 액터를 <strong>```Subject```</strong>로 명명합니다. 각 액터의 **```Subject```** 이름을 잘 구분하여 생성합니다.

## VIRDY - Vicon 활성화

![Vicon2](/img/Page_AvatarSettings/MotionSet/Vicon_Settings_2.png) <br/>
모션 트래킹 탭에서 Vicon 디바이스를 선택합니다. <br/>
Vicon에서 설정한 **```Subject```** 이름을 <strong>```서브젝트 이름```</strong>에 정확하게 입력합니다. <span class="highlight">**대소문자, 공백**</span> 등을 구분하므로 정확히 입력해주세요.

### Vicon Prop 사용법
Vicon Prop의 이름을 정확하게 입력하면 자동으로 데이터를 받아옵니다. <br/>
여러개의 프랍을 등록하는 경우는 <span class="highlight_text">**Prop1, Prop2, Prop3...**</span>과 같이 ,를 넣어 분류해주시면 됩니다.

### 프랍, 소유 프랍, 핸드 프랍 트래킹 모드
기본 <span class="highlight_text">**'프랍 서브젝트 이름'**</span>에 할당되는 Prop은 <span class="highlight_text">**Global Prop**</span>을 의미합니다. <br/>
누구나 사용하고 쥘 수 있는 Prop입니다. (ex. 의자, 책상, 뿅망치 등) <br/>

소유 프랍은 각 액터가 전용으로 사용할 Prop을 의미합니다. <br/>
조금 더 정교한 Prop Tracking을 지원하기에 개개인의 맞춤 프랍이 있을 경우 사용해주세요. <br/>

### 디바이스 아이피 주소

<strong>```디바이스 아이피 주소```</strong>는 Shogun 소프트웨어가 실행중인 PC의 IP 주소를 입력합니다. <br/>
VIRDY와 Shogun을 <span class="highlight_text">**같은 PC**</span>에서 사용중일 경우 **```localhost```** 혹은 <strong>```127.0.0.1```</strong>로 입력합니다.

### 포트

Vicon Shogun의 기본 포트값은 <strong>```801```</strong>입니다. 특별한 사유가 없는 한 기본 포트를 사용해주세요.