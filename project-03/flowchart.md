# 프로젝트 흐름도

```mermaid
flowchart LR

A([Google Form])
-->B([Google Sheets])

B-->C{조건 확인}

C-- 예 -->D([Gmail 알림])
C-- 아니오 -->E([시트에 저장])
```
