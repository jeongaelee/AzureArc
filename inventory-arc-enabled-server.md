# AzureArc

## Inventory management - Azure Arc enabled servers

본 단계에서는 Azure Arc enabled 서버를 모니터링 하는 시나리오들에 대하여 실습 해 봅니다.

### Step 2. Azure Portal에서 Azure Arc enabled server 확인

#### Step 2-1. Portal의 검색창에 Resource Graph Explorer 검색 후 메뉴로 이동

![alt text][id1]

[id1]: /images/Step2-01.jpg "Azure Arc 검색"

#### Step 2-2. Resource Graph Explorer 메뉴에서 Query 입력

```
Resources
| where type == 'microsoft.hybridcompute/machines'
| where isnotempty(tags['Datacenter'])
| project name, location, resourceGroup, tags
```

![alt text][id2]

[id2]: /images/Step2-02.jpg "Azure Arc 메뉴"

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