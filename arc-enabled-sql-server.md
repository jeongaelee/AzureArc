# AzureArc

## Azure Arc enabled SQL servers

본 단계에서는 Azure Arc enabled SQL 서버를 디플로이하고 on-demand SQL Assessment를 실행하는 방법에 대하여 실습 해 봅니다.

### SQL SERVER ONBOARDING PRE-WORK
- Smart Hotel SQL Server에서 IE ESC를 Turn off

![alt text][id0]

[id0]: /images/Step5-00.jpg "Azure Arc enabled SQL Server"

- .Net Framework을 4.8으로 업그레이드, 다운로드 & 인스톨 --> https://dotnet.microsoft.com/download/dotnet-framework/net48 
- Powershell을 Administrator 권한으로 실행하여 아래 입력 :

```
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
Register-PSRepository -Default
Install-Module Az
```

#### Step 1. Azure Arc에서 "SQL Server (Preview)" 메뉴 선택

![alt text][id1]

[id1]: /images/Step5-01.jpg "Azure Arc enabled SQL Server"

#### Step 2. Create SQL Server - Azure Arc를 선택하여 새로운 SQL Server 생성

![alt text][id2]

[id2]: /images/Step5-02.jpg "Azure Arc"

#### Step 3. Project Details과 Server Details 입력

![alt text][id3]

[id3]: /images/Step5-03.JPG "Azure Arc"

#### Step 4. Prerequisites 확인

![alt text][id4]

[id4]: /images/Step5-04.jpg "Azure Arc"

#### Step 5. Run Script 항목에서 Script 다운로드

![alt text][id5]

[id5]: /images/Step5-05.jpg "Azure Arc"

#### Step 6. SQL Server에서 PowerShell을 실행하여 다운로드 받은 스크립트 실행

![alt text][id6]

[id6]: /images/Step5-06.jpg "Azure Arc"

#### Step 7. PowerShell 창에서 스크립트 완료 후 Arc enabled SQL Server 생성 확인

![alt text][id7]

[id7]: /images/Step5-07.jpg "Azure Arc"

#### Step 8. Portal의 SQL Servers (preview) 메뉴에서 서버 생성 확인 

![alt text][id8]

[id8]: /images/Step5-08.jpg "Azure Arc"

<!-- TOC -->
## Azure Arc enabled servers

**실습 순서**

- [Step 1. Deploy Azure Arc enabled server (서버 배포)](https://github.com/jeongaelee/AzureArc/blob/main/deploy-arc-enabled-server.md)
- [Step 2. Azure Arc enabled server inventory (서버 목록 확인)](https://github.com/jeongaelee/AzureArc/blob/main/inventory-arc-enabled-server.md)
- [Step 3. Azure Arc enabled server monitoring (서버 모니터링)](https://github.com/jeongaelee/AzureArc/blob/main/monitor-arc-enabled-server.md)
- [Step 4. Azure Arc enabled server policy (서버 Policy)](https://github.com/jeongaelee/AzureArc/blob/main/policy-arc-enabled-server.md)
- [Step 5. Azure Arc enabled server Azure Security Center 연동](https://github.com/jeongaelee/AzureArc/blob/main/security-arc-enabled-server.md)

<br>

## Azure Arc enabled SQL servers

**실습 순서**

- [Step 6. Azure Arc enabled SQL server](https://github.com/jeongaelee/AzureArc/blob/main/arc-enabled-sql-server.md)

<!-- /TOC -->
