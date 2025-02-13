---
title: 사이트 신뢰성 엔지니어링(Site Reliability Engineering)
status: Completed
category: 개념
tags: ["방법론", "", ""]
---

## 개념

사이트 신뢰성 엔지니어링(SRE)은 시스템 운영과 소프트웨어 공학이 결합된 전문 분야이다.
후자에서도 특히 인프라 및 운영 문제가 해당된다.
즉, 사이트 신뢰성 엔지니어는 제품의 기능을 개발하기 보다는, 애플리케이션을 실행하기 위한 시스템을 개발한다.
[데브옵스(DevOps)](/ko/devops/)와도 유사한 점이 있지만, 데브옵스가 코드 개발부터 제품 배포까지의 과정에 집중하는 반면,
SRE는 해당 제품이 배포 환경에서 제대로 동작하는지 확인한다는 점에서 차이가 있다.

## 다루는 문제

애플리케이션을 [안정적](/reliability/)으로 실행하려면, 성능 모니터링, 알람,
디버깅, 문제 해결(troubleshooting) 등 다양한 역량을 필요로 한다. 
이러한 역량을 갖추지 못한 시스템 운영자는 이미 발생한 문제에 대한 대응만 할 수 있으며,
이는 문제를 사전 예방하여 시스템 중단 시간을 단순 시간문제로 만드는 능동적인 방법과 대조된다.

## 문제 해결 방식

SRE 접근 방식은, 기반 시스템을 지속적으로 개선함으로써
소프트웨어 개발 과정에서의 비용, 시간 및 노력을 최소화한다.
이 시스템은 인프라스트럭처와 애플리케이션 구성 요소를 지속적으로 측정하고 모니터링한다. 
문제가 발생하면, 시스템은 사이트 신뢰성 엔지니어들에게 언제, 어디서, 어떻게 해결할지를 알려준다.
이러한 접근 방식은 운영 작업을 자동화하여 높은 [확장성](/ko/scalability)과 신뢰성을 가진 소프트웨어 시스템을 만드는 데 도움이 된다.
