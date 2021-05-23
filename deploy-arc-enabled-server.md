# AzureArc

## Deploy Azure Arc enabled servers

본 단계에서는 Azure Arc enabled 서버를 배포하는 것을 실습 해 봅니다.

### Step 1. Azure Portal에서 Azure에 하이브리드 머신 연결

#### Step 1-1. Portal의 검색창에서 Azure Arc를 검색하여 선택

![alt text][id1]

[id1]: /images/Step1-01.JPG "Azure Arc 검색"

#### Step 1-2. Azure Arc 화면으로 이동

![alt text][id2]

[id2]: /images/Step1-02.JPG "Azure Arc 메뉴"

#### Step 1-3. Server 메뉴 선택

![alt text][id3]

[id3]: /images/Step1-03.jpg "Server 메뉴 선택"

#### Step 1-4. Server 추가

![alt text][id4]

[id4]: /images/Step1-04.JPG "+Add (추가) 선택"

#### Step 1-5. 한대의 Server 추가 (Add a single server )

![alt text][id5]

[id5]: /images/Step1-05.JPG "Generate script 선택"

#### Step 1-6. Azure Arc 설치를 위한 Server의 사전 조건 (Prerequisite) 확인
1) HTTPS 접속이 가능해야 함
2) Azure Arc Agent를 설치하기 위한 outbound 연결이 가능해야 함
3) Local administrator 권한이 있어야 함

![alt text][id6]

[id6]: /images/Step1-06.JPG "사전조건 확인"

#### Step 1-7. Resource Detail 입력

![alt text][id7]

[id7]: /images/Step1-07.JPG "Resrouce Detail 입력"

#### Step 1-8. Tags 입력

![alt text][id8]

[id8]: /images/Step1-08.JPG "Tags 입력"

#### Step 1-9. 스크립트 다운로드

![alt text][id9]

[id9]: /images/Step1-09.JPG "Script 다운로드"

#### Step 1-10. Linux 혹은 Windows 서버에 다운드로 받은 스크립트 설치

![alt text][id10]

[id10]: /images/Step1-10.JPG "스크립트 설치"

#### Step 1-11. Azure Arc 서버 목록 확인

![alt text][id11]

[id11]: /images/Step1-11.JPG "스크립트 설치"


**실습 순서**

<!-- TOC -->

- [Step 1. Deploy Azure Arc enabled server (서버 배포)](#deploy-azure-arc-enabled-server)
- [Step 2. Azure Arc enabled server inventory (서버 목록 확인)](https://github.com/jeongaelee/AzureArc/tree/main/inventory-arc-enabled-servers.md)
- [Step 3. Azure Arc enabled server monitoring (서버 모니터링)](https://github.com/jeongaelee/AzureArc/tree/main/monitor-arc-enabled-servers.md)

<!-- /TOC -->
