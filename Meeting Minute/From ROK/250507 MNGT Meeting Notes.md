## **1\. High-Level Overview**

스페이비(Spavy) 런치 전략의 핵심 기준을 "쉐어(Share)"로 재정립.  
 즉, **파일 공유 중심의 네트워크 효과 극대화**를 목표로 제품 기능, 배포 방식, UI/UX 흐름, 사용자 셋업, 서버 업데이트 정책, 클라우드 옵션 등을 **전면 재정비**하는 전략이 논의됨.  
 이 기준 아래, 각 기능별 재설계 방향과 기술적 실행 항목을 정리하고, 주말까지 전체 일정(런칭, 마케팅, 테스트 포함)을 확정하기로 함.

---

## **2\. Tree 구조 요약**

mathematica  
복사편집  
`Spavy Share-Centric Launch Strategy`  
`├── A. 런치 기준 재설정: "Share" 중심`  
`│   └── 네트워크 효과를 위한 간소화 및 전략 재정비`  
`├── B. 사용자 흐름 정리`  
`│   ├── 회원가입 → 셀프 호스트 서버 설치 → 웹 싱크`  
`│   └── 파일 싱크 → 브라우저에서 파일 확인 → URL 생성 및 공유`  
`├── C. 사용자 초대 방식 개선`  
`│   └── 기존 유저 생성 → URL 공유로 대체할 수 있는 대안 탐색`  
`├── D. 기능 롤아웃 전략`  
`│   ├── 서버 재설치 방식 vs OTA 방식(라이선스 매니저 활용)`  
`│   └── 특정 프로젝트 단위로 기능 활성화 가능한 구조 고려`  
`├── E. 셀프호스트 한계 대응`  
`│   └── AWS / Azure 호스팅 테스트 및 사용자 지원 가이드 마련`  
`├── F. 기능별 구조 재정비`  
`│   ├── 1. 액션 트리`  
`│   │   ├── 조회 외 모든 노드를 액션트리 하위로 통합`  
`│   │   └── 시스템/커스텀 트리는 제외`  
`│   ├── 2. 트리 프리셋`  
`│   │   ├── 특정 필터/소트 적용한 트리를 저장`  
`│   │   └── 씬/리스트에서 활용 가능한 사용자화 구조`  
`│   ├── 3. 파일 리스트 개선`  
`│   │   ├── 파일 중심 플랫폼, 풍부한 메타데이터 필요`  
`│   │   ├── 메타데이터 4가지 출처`  
`│   │   │   ├── 생성 솔루션`  
`│   │   │   ├── 시스템 오브 레코드`  
`│   │   │   ├── OS 레벨 프로퍼티`  
`│   │   │   └── 폴더 경로 기반 사용자 메타데이터`  
`│   │   └── ELT 구조로 확장 고려`  
`│   ├── 4. 패키지 리스트`  
`│   │   ├── 파일 묶음 + 썸네일로 리스트화`  
`│   │   └── 씬과 리스트를 하나의 URL로 공유 가능`  
`│   ├── 5. 그리드`  
`│   │   ├── 파일과 그리드 디커플링`  
`│   │   ├── 시스템 노드에서 그리드 로드`  
`│   │   └── 스페이셜 트리와 연동 가능`  
`│   └── 6. 스페이셜 트리`  
`│       ├── 브라우저에서 신규 공간 정보 add`  
`│       └── 액션트리 하위에 배치, 하나의 묶음으로 활용`  
`├── G. 일정 재조정`  
`│   ├── 이번 주말까지 전체 이슈 정리`  
`│   └── 테스트, 웹사이트, 마케팅 일정 포함한 런칭 스케줄 수립`

---

## **3\. 요소별 요약 테이블**

| 항목 | 주요 내용 |
| ----- | ----- |
| **전략 기준** | Share 중심, 네트워크 효과 극대화 |
| **주요 사용자 흐름** | 회원가입 → 셀프 호스트 설치 → 웹 싱크 → 파일 공유 URL 생성 |
| **접근 개선** | 유저 생성 없이 URL 공유 가능성 탐색 |
| **기능 배포 방식** | OTA 방식 및 라이선스 매니저 통한 기능 활성화 검토 |
| **서버 운용 방식** | 로컬 자원 한계 → AWS/Azure 호스팅 테스트 병행 |
| **기능 구조** | 액션트리, 트리 프리셋, 파일리스트, 패키지 리스트, 그리드, 스페이셜트리 |
| **파일 메타데이터 출처** | 생성 솔루션 / 시스템 오브 레코드 / OS / 폴더 경로 |
| **런칭 일정** | 이번 주말까지 전체 마일스톤 재정비 |

---

## **4\. 추출 정보**

### **핵심 키워드**

* Share

* 네트워크 효과

* 액션 트리

* 셀프 호스트

* 클라우드 호스팅 (AWS, Azure)

* OTA (Over-The-Air)

* 파일 리스트, 메타데이터

* 트리 프리셋

* 패키지 리스트

* 스페이셜 트리

* 그리드 디커플링

### **핵심 문구**

* “쉐어를 중심으로 모든 전략을 재수립”

* “기능은 점진적으로 롤아웃”

* “파일을 시작점으로 하는 협업 플랫폼”

* “URL 공유 기반의 확산 구조로 전환”

### **Action Items**

1. 사용자 URL 공유 접근 개선안 정리

2. OTA 기능 오픈 방식 기술검토

3. AWS / Azure 테스트 사례 설계 및 문서화

4. 액션 트리, 트리 프리셋 등 기능 구현 우선순위 확정

5. 전체 일정 및 마케팅 플랜 이번 주말까지 재정비

### **우려 사항**

* 서버 재설치 없이 기능 업데이트 가능한 구조 마련 가능성

* 셀프 호스트 서버의 자원 한계

* 초기 기능 간소화와 확산 전략 간의 균형

### **질문 리스트**

* 기존 사용자 인증 구조 없이 URL 공유가 가능한 구조는 어떻게 구현할 수 있는가?

* 라이선스 매니저를 통해 기능을 OTA로 오픈하는 기술적 제약은?

* 로컬 셀프 호스트 서버에서 리소스 제약 없이 클라우드와 연결하려면 어떤 구조가 적합한가?

