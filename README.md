# test0

# Table of contents

- [렌트카](#---)
  - [서비스 시나리오](#서비스-시나리오)
  - [체크포인트](#체크포인트)
  - [분석/설계](#분석설계)
  - [구현:](#구현-)
    - [DDD 의 적용](#ddd-의-적용)
	  - [GateWay 적용](#GateWay 적용)
	  - [CQRS/saga/correlation](#폴리글랏-퍼시스턴스)
    - [동기식 호출 과 Fallback 처리](#동기식-호출-과-Fallback-처리)
	  - [폴리글랏 퍼시스턴스](#폴리글랏-퍼시스턴스)
	
  - [운영](#운영)
    - [CI/CD 설정](#cicd설정)
    - [Deploy / Pipeline](#Deploy-Pipeline)
    - [ConfigMap](#ConfigMap)		
    - [동기식 호출 / 서킷 브레이킹 / 장애격리](#동기식-호출-서킷-브레이킹-장애격리)
    - [오토스케일 아웃](#오토스케일-아웃)
    - [무정지 재배포](#무정지-재배포)
    - [Liveness Probe](#Liveness-Probe)
  - [신규 개발 조직의 추가](#신규-개발-조직의-추가)




![image](https://user-images.githubusercontent.com/11002207/131057532-81eb1449-70de-40fe-9ba1-9f76aa6a00de.png)

![image](https://user-images.githubusercontent.com/11002207/130976216-5507d61c-696a-4098-b402-95da99d7e3a9.png)
