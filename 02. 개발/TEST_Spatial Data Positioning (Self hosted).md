---
title: TEST_Spatial Data Positioning (Self hosted)
date: 2025-04-29 
tester: 김영록, 김지숙
version: 25.04.30
feature: Spatial Data Positioning (Self hosted)
status: 공유됨
tags:
  - 테스트기록
---

### 🔹 기능 개요

- 기능명: Spatial Data Positioning (Self hosted)  
- 목적: 변경 기능점검 및 개선안 도출  
- 버전: 25.04.329 
- 작성자: 김영록, 김지숙

---

### 🔹 시나리오 요약

> 부산 데이터 이용 Datum 생성하지 않고 Scale/Transform 수행 
> 4/29, 30 논의 내용 

---

### 🔹 테스트 시나리오 결과

| 시나리오 | 기대 동작 | 실제 동작 | 결과 |
|----------|------------|------------|--------|
| 1.  |  |  | ✅ |
| 2.  |  | | 🔴 |
| 3.  |  |  | 🟡 |

---

### 🔹 개선 제안

- [ ] 3D 모델 이동 속도
- [ ] Scale Reference Model /Transform Jump to 동작 일관성 
- [ ] Scale 이 별도로 필요하지 않을 수 있음...

---

### 🔹 논의 / 결정사항

-  Basic/Advance Mode 구분 
	- Basic Mode  Minimap 이미지 확대/축소하는 Pin 을 이용 
	- Basic Mode에서 Scale 조정이 필요없는 Data 경우 Scale 이용 Lock 여부를 선택하도록 함. 
	- Advance Mode 현재 구현된 기능 개선하여 탑재 (?)
- 화면에서 객체 다중선택 
- 기능실행 진입 경로는 1개만 
	- (즉, 화면 Data 선택,>마우스 우클릭>기능실행 하는 동작만 보존, 우측 상단에서 Node Type 선택해서 파일 지정하는 옵션은 제거, 기능 실행 중인 node type 보여주기만 하면 됨. )
