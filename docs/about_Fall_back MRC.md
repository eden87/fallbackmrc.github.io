---
layout: page
title: Fallback MRC
subtitle: 엣지 기반 자율주행 기능의 Fall back MRC에 따른 운영권 SW 안전성 및 대응방안 검증 기술 개발
---
1. 사업 개요

---

- 연구 개발 전체 평가 구성 방안

![2](/assets/img/about_Fall_back MRC/2.jpg)

2. 연구개발과제 추진 배경

---

- 문제 정의 및 필요성
    - 안전한 자율주행(Lv.4)을 위해 돌발 및 긴급 상황에 대한 차량의 유연한 대처 능력을 요구하나 자율주행차만으로는 차량 센서의 공간적 한계성과 즉각적인 상황인지 능력의 한계가 발생
    - 테슬라, Ford, Daimler 등 차량 통신모듈을 활용한 엣지 기반 무선 소프트웨어 기능(OTA, Over the air)의 경우 실시간 새로운 기능에 대하여 업데이트 할 경우 해킹과 같은 위협을 방어할 수 있는 장점이 있으나, 자율주행 시스템의 안전성 및 시스템 무결성을 깨트릴 수 있는 위험 사항이 발생할 수 있으므로 이에 대한 검증 방법 도출이 필요함
    - 안전한 자율주행(Lv.4)의 경우 운전자가 개입하지 않은 상태에서 시스템의 위험 사항을 판단하여 이를 대응 방안을 도출하고 안전한 방안으로 대응이 가능한지 검증이 필요함
    
     ![3.jpg](/assets/img/about_Fall_back MRC/3.jpg)
    
    - 추진 배경
        - 안전한 자율주행을 위하여 돌발 및 긴급상황(운전자와 자율주행 시스템 문제, 운영설계범위 범위 이탈 등)에서 발생할 수 있는 시스템의 성능 저하, 복구 가능성 등에 대한 분석으로 주행 안전성 확보를 목표로 함
        
     ![4.jpg](/assets/img/about_Fall_back MRC/4.jpg)
        

- 기술적 연구 접근 방향
    - 오작동에 대한 시스템 가동 중단이 허용되지 않는 지능화 된 초연결 사회에서 4급 엣지 기반 자율주행 시스템에 대한 핵심 기능을 정의하고 이에 대한 안전성 평가 및 대응 체계 검증 방안을 수립하고자 함
    - 기존 오작동에 대한 차량의 고장과 안전성 평가 방법으로는 4급 엣지 기반 자율주행 시스템 오작동에 대한 평가와 대응능력이 불가능하여 차량-엣지 통합 기술 개발을 통해 Lv.4급 자율주행 시스템의 오류 상황판단과 비상상황 대처기능에 대한 진보된 평가 기술 개발과 대응 방안을 도출하고자 함
    - 4급 차량-엣지 자율주행차량은 오작동에 대해 최소위험상태(MRC: Minimal Risk Condition) 도달까지 비상상황 대처(DDT fallback)가 주체적으로 동작하는지 검증하고자 함
        
     ![5.jpg](/assets/img/about_Fall_back MRC/5.jpg)
        

2. 과제목표

---

- 엣지 기반 자율주행 SW의 이상 징후를 탐지하여 자율주행 차량 SW에 대한 사이버 복원력 평가 모델 프로세서 개발
    - 엣지 기반 자율주행 SW 운영 안전성 및 신뢰성 평가 모델·프로세스 개발
    - 엣지 기반 자율주행 SW 고장 안전 진단 기술 개발
    - 엣지 기반 차량/인프라 데이터 수집 시스템 개발 및 검증용 데이터 생성
    - 엣지 기반 자율주행 실차/시뮬레이션 검증 환경 및 알고리즘 개발
    - 기 실증 환경 업데이트 개발 및 운용
        
     ![6](/assets/img/about_Fall_back MRC/6.jpg)
        
    

3. 과제 년차별 추진 계획

---

![7.jpg](/assets/img/about_Fall_back MRC/7.jpg)

- 1차년도
    - 엣지 기반 자율주행 운행환경 모델링 및 위험요소, 요구사항 분석
    - 엣지 기반 자율주행 운행 환경 모델링 요소 설계
    - 자율주행시스템 주행 위험 요소 분석
    - 실차 기반 Fall-back MRC 대응방안 검증을 위한 기술 동향 분석
    - 기능안전 평가항목(문서항목) 선정위한 글로벌 동향 조사
    - 자율주행 차량(HW/SW)의 기능 분석 및 최소 위험 상태 평가기준 설계
    - 엣지 기반 자율주행 SW 안전성 평가 시나리오 설계 요구사항 분석
    - 엣지 기반 자율주행 SW 주행 안전성 평가 기술 개발
    - 시뮬레이션 기반 자율주행 SW 안전성 검증 환경 개발
    - 차량·엣지 통합 자율주행 사이버 복원력 fallback 시나리오 관련 자료 수집
    - 자율주행 시스템의 위험사항 분석을 위한 레퍼런스 데이터 수집 및 분석
    - 기 개발된 자율차-엣지-클라우드 간 레퍼런스 데이터 수집
    - 시뮬레이터 인지/판단/제어 알고리즘 인터페이스 설계
    - 시뮬레이터 기반의 자율주행 SW 평가를 위한 인터페이스 관련 기능 요구사항 정의
    - 시나리오 기반 테스트를 위한 주행 환경 설정(도로 형상, 실증 지역 등)
    - 차량-엣지 기반 평가를 위한 시뮬레이션 환경 설계
    - 차량-엣지 기반 평가를 위한 시뮬레이션 기반 자율주행 시스템 모델 설계
    
- 2차년도
    - 엣지 기반 자율주행 운행환경 모델링 및 위험요소 도출
    - 엣지 기반 자율주행 SW 안전성 평가 방법론/가이드라인 개발
    - 실차 기반 Fall-back MRC 대응방안 검증 인터페이스 설계
    - 기능 안전 평가항목(문서항목) 가이드라인 도출
    - 타겟차량에 대해 기능안전 모의평가 수행
    - 자율주행 차량(HW/SW)의 기능 분석 및 최소 위험 상태 평가기준 개발
    - 주행 시험장 기반 자율주행 SW 안전성 및 신뢰성 시험 방법 개발
    - 엣지 기반 자율주행 SW 안전성 평가 시나리오 개발
    - 엣지 기반 자율주행 SW 오류 안전 대책 평가 기술 개발
    - 시뮬레이션 기반 자율주행 SW 안전성 검증 환경 개발
    - 차량-엣지 통합 자율주행 사이버 복원력 fallback 시나리오 마이닝 및 문서화
    - 엣지 기반 차량/인프라 데이터 수집 시스템 개발
    - 시뮬레이터 인지/판단/제어 알고리즘 인터페이스 개발
    - 시뮬레이터 기반의 자율주행 SW 평가를 위한 인터페이스 개발
    - 시뮬레이션 평가를 위한 인터페이스 설계
    - 차량-엣지 연동 자율주행 성능평가 시뮬레이터 기술 개발
    - 주행 시험장 및 실도로 환경 인프라 데이터 수집을 위한 API 업데이트
    
- 3차년도
    - 엣지 기반 자율주행 SW ODD 범위에 따른 평가 검증 프로세스/모델 개발
    - 엣지 기반 자율주행 시스템의 데이터 마이닝 기반 Fall back MRC 검증 소프트웨어 개발
    - 실차 기반 Fall-back MRC 대응방안 검증 인터페이스 개발
    - 시나리오 개발에 고려할 기능안전 관점의 고려항목 도출
    - 자율주행차량(HW/SW)의 기능 분석 및 최소 위험 상태 평가 프로세스 개발
    - 엣지 기반 자율주행 SW 시나리오 확장 개발
    - 엣지 기반 자율주행 SW 안전성 평가 시나리오 국내표준안 개발
    - 차량-엣지 통합 자율주행 SW 오류 진단을 통한 통합 검증 프로세스 개발
    - 엣지 기반 자율주행 SW 오류 대책 안전성 평가 시나리오 구현
    - HILS 기반 자율주행 시스템 고장 모의 테스트 기술 개발
    - 차량-엣지 통합 자율주행 사이버 복원력 fallback 시나리오 평가 협업
    - 엣지 기반 차량/인프라 데이터 수집 및 표준 데이터 변환 시스템 개발
    - 시뮬레이터 인지/판단/제어 동기화 및 연동 검증용 SW 프레임워크 개발
    - 사이버 복원력, 기능안전을 포함한 평가 시나리오 시뮬레이션 맵핑
    - 시뮬레이션 Fallback Test 환경 구축 및 구현
    - 차량-엣지 기반 평가를 위한 시뮬레이션 알고리즘 검증
    - 주행시험장 및 실도로 환경 인프라 활용 자율주행 시스템 검증 데이터 수집
    
- 4차년도
    - 엣지 기반 자율주행 SW 데이터 수집을 통한 자동화 평가 검증 프로세스/모델 개발
    - 엣지 기반 자율주행 시스템의 데이터 마이닝 기반 Fall back MRC 검증 소프트웨어 최적화
    - 실차 기반 Fall-back MRC 대응방안 검증 시험
    - 도출된 기능안전 관점의 고려항목과 시나리오의 연계방안 연구
    - 자율주행차량 시스템 통합 안전성 검증 및 신뢰성 평가 프로세스 검증
    - 엣지 기반 자율주행 SW 안전성 평가 시나리오 국내표준안 개발
    - 엣지 기반 자율주행 SW 안전성 평가 시나리오 표준화
    - 차량-엣지 통합 자율주행 SW 시뮬레이션/실차 고장 안전 진단 기술 검증
    - 고장 모의 테스트 환경 기반 자율주행 SW 고장 안전성 검증
    - 차량-엣지 통합 자율주행 사이버 복원력 fallback 시나리오 개선 및 문서화
    - 엣지 기반 차량/인프라 데이터 수집 및 표준 데이터 변환 시스템 최적화
    - 엣지 기반 차량/인프라 시뮬레이션 테스트 및 검증
    - 시뮬레이션 안전성 검증 솔루션 연동 테스트를 통한 평가 기술 검증
    - 시뮬레이션 환경 구현 및 시뮬레이션 테스트
    - 주행시험장 및 실도로 환경 인프라 활용 데이터 수집/전달 시스템 최적화

4. 최종 목표

---

- 엣지 기반 자율주행 SW의 이상 징후를 탐지하여 자율주행 차량 SW에 대한 사이버 복원력 평가 모델 프로세서 개발
    - 엣지 기반 차량(고장, 안전성 상태 포함), 환경(날씨, 조명 등) 및 기타 위험 요소 분석에 따른 자율주행 SW의 평가 기준 설계/개발
    - 엣지 자율주행차량 SW 안전성을 진단 및 예측하고, 가동 중단이 허용되지 않는 자율주행 시스템의 사이버 복원력 확보 기준 개발
    - 엣지 기반 차량 자율주행 시스템을 폐쇄된 시험장 내에서 모의 테스트를 진행하여 핵심 기능 작동 및 복원력 평가 기술 개발
    
    ![8](/assets/img/about_Fall_back MRC/8.jpg)
    

5. 최종 결과물 구성도

---

- 본 과제의 D 분과 과제와 결과물 연계 구성도

![9](/assets/img/about_Fall_back MRC/9.jpg)

안전한 자율주행을 위하여 돌발 및 긴급상황(운전자와 자율주행 시스템 문제, 운영설계범위 범위 이탈 등)에서 발생할 수 있는 시스템의 성능 저하, 복구 가능성 등에 대한 분석으로 주행 안전성 확보를 목표로 함
