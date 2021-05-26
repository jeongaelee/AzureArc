# AzureArc

## Policy - Azure Arc enabled servers

본 단계에서는 Azure Arc enabled 서버에서 Policy를 적용하는 방법에 대하여 실습 해 봅니다.

### Step 4. Azure Portal에서 Azure Arc enabled server Policy 적용

#### Step 4-1. Azure Portal 검색 창에서 Policy로 검색

![alt text][id1]

[id1]: /images/Step4-01.JPG "Policy"

#### Step 4-2. Policy의 Definition 메뉴 선택

![alt text][id2]

[id2]: /images/Step4-02.jpg "Policy"

#### Step 4-3. 윈도우 서버의 Certificate 만료 Policy 적용
- Category에서 Guest Configuration 선택
- "Certificate"으로 검색
- "Audit Windows machines that contain certificates expiring within the specified number of days" 항목 선택

![alt text][id3]

[id3]: /images/Step4-03.jpg "Policy"

#### Step 4-4. "Assign" 선택하여 Policy를 할당

![alt text][id4]

[id4]: /images/Step4-04.jpg "Policy"

#### Step 4-5. Policy를 적용할 Scope 선택 (Subscription과 Resource Group)

![alt text][id5]

[id5]: /images/Step4-05.jpg "Policy"

#### Step 4-6. Policy Parameter 설정
* Remediation, Non-compliance Message는 기본값으로 설정 후 생성 완료

![alt text][id6]

[id6]: /images/Step4-06.jpg "Policy"

#### Step 4-7. Certificate 만료에 관한 Compliance 확인
- Compliance 메뉴 선택
- "Audit Windows machines that contain certificates expiring within the specified number of days" 항목 선택

![alt text][id7]

[id7]: /images/Step4-07.jpg "Policy"

#### Step 4-8. Compliance 여부 확인
- Compliant 드롭다운 박스 선택

![alt text][id8]

[id8]: /images/Step4-08.jpg "Policy"

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