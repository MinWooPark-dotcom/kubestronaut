# Kubestronaut

올해 가장 큰 목표였던 Kubestronaut를 한국에서는 79번 째로 달성했습니다!🎉  
그동안의 여정을 돌이켜보며 미래의 Kubestronaut를 위해 각 자격증별 준비 방법과 팁을 공유하고자 합니다.  
2025년 9월 20일 기준으로 Kubestronaut는 전세계에 2220명, 한국에 79명이 있습니다.

## 목차
- [Kubestronaut란](#kubestronaut란)
- [Kubestronaut를 도전한 계기](#kubestronaut를-도전한-계기)
- [Kubestronaut가 되면 좋은 점](#kubestronaut가-되면-좋은-점)
- [Kubestronaut가 되는 방법](#kubestronaut가-되는-방법)
- [Kubernetes 자격증별 특징](#kubernetes-자격증별-특징)
- [Kubernetes 자격증별 준비 전략](#kubernetes-자격증별-준비-전략)
- [References](#References)

## Kubestronaut란

> **The Kubestronaut program recognizes community leaders who have consistently invested in their ongoing education and grown their skill level with Kubernetes and Cloud Native.**

CNCF(Cloud Native Computing Foundation) 재단에서 운영하는 Kubernetes 자격증(CKA, CKAD, CKS, KCNA, KCSA)을 모두 취득한 사람들에게 주어지는 타이틀입니다.  
Kubernetes와 Astronaut를 합친 단어로 생태계를 깊이 탐험하고 항해하는 사람, 쿠버네티스의 우주비행사라는 의미를 갖고 있습니다.

## Kubestronaut를 도전한 계기

언젠가 LinkedIn에서 Kubernetes에 대한 깊이 있는 글들을 접한 적이 있습니다.  
그 글을 쓴 이들의 프로필에는 공통적으로 Kubestronaut라는 타이틀이 있었고, 그때부터 호기심이 생겼습니다.  
Kubestronaut가 되기 위해서는 CNCF에서 운영하는 Kubernetes 자격증(CKA, CKAD, CKS, KCNA, KCSA)을 모두 취득해야 했습니다.  
그 중 CKA, CKAD, CKS는 실습형 시험으로 진행되기 때문에 준비 과정에서 Kubernetes를 깊이 이해하고 다룰 수 있다는 생각을 했습니다.  
Kubestronaut라는 타이틀은 제 커리어에 더욱 자신감을 부여하고 DevOps 엔지니어로서 역량을 증명할 수 있는 방법이라고 생각했습니다.  
또한 제게 이러한 도전의 계기를 만들어준 동료들과 글로벌 커뮤니티와 연결될 수 있는 특별한 기회라는 점에서 더욱 의미가 있었습니다.

## Kubestronaut의 혜택

### Global Networking

Kubestronaut가 된다면 다음과 같은 혜택이 주어집니다.

> - An exclusive Kubestronaut jacket to show off your elite status
> - A Credly badge to showcase your expertise
> - Access to the dedicated/private Kubestronaut Slack channel and mailing list
> - Five coupons for 50%-off certifications each year, for yourself or to share
> - 20%-off three CNCF events (KubeCon or KubeDays) a year

여느 자격증처럼 badge가 주어지는 등 일반적인 혜택도 있지만 제가 생각하는 해당 타이틀의 특별한 점은 네트워킹이라고 생각합니다.  
Kubestronaut들이 네트워킹을 할 수 있는 private slack channel에 초대되어 전세계 사람들과 소통할 수 있습니다.  
저는 아직 KubeCon을 가보진 못했지만 행사 사진들을 보면 많은 사람들이 Kubestronaut jacket을 입고 다니는 사진을 볼 수 있었습니다.  
오프라인에서도 소속감을 느끼며 조금 더 편안한 마음으로 서로 다가갈 수 있을 거 같다는 생각을 합니다.  
마지막으로 CNCF 재단에 이름과 얼굴이 등재되는 것 또한 Kubernetes를 사랑하는 사람들에게는 특별한 경험을 할 수 있습니다.

## Kubestronaut가 되는 방법

Kubestronaut가 되기 위해선 CNCF 재단에서 운영하는 Kubernetes 자격증(CKA, CKAD, CKS, KCNA, KCSA)을 모두 취득해야합니다.  
자격증마다 개편사항이 있기에 언제 작성했느냐에 따라 특징이 다를 수 있습니다.  
2025년 9월 8일 기준으로 각 자격증의 특징을 간략히 소개 드리겠습니다.  
위 시험들은 응시 방식에 따라 2개로 나눌 수 있습니다.

### 실습형 시험 준비 팁 - CKA, CKAD, CKS

실습형으로 진행되는 CKA, CKAD, CKS가 있으며, 객관식으로 진행되는 KCNA, KCSA가 있습니다.  
실습형의 경우 리소스를 다루는 방식인 선언형(Declarative)과 명령형(Imperative) 모두 능숙해야 합니다.  
제한 시간이 있는 시험인만큼 빠른 속도로 풀이를 하는 것이 중요하기에 명령형 방식을 주로 사용하여 문제 풀이를 하게 됩니다.  
kubectl 명령어로 요구사항을 모두 적용한 리소스를 생성하기 어려운 경우 `--dry-run=client -o yaml`로 기본 틀을 잡아주는 yaml 파일을 생성하고 vim과 같은 편집기로 선언형으로 나머지 요구사항을 충족시켜주면 시간 절약에 도움이 됩니다.  
그리고 공식문서에 얼마나 빠르게 레퍼런스를 찾는지가 중요합니다.  
이는 시험을 준비하는 과정에서 각 문제 유형마다 적절한 키워드를 사용하여 필요한 문서를 찾고, 해당 문서에서 문자열 검색을 통해 해결 방법에 힌트가 되는 부분을 찾아가는 연습을 해 보는 것이 도움이 됩니다.

### 객관식 시험 준비 팁 - KCNA, KCSA

객관식의 경우 각 개념의 출제 유형을 파악하는 것이 중요합니다.  
공식 문서와 강의를 통해 가볍게 학습을 한 뒤 문제를 풀어보면서 시험에서 각 개념마다 무엇을 중점을 두고 있는지 분석을 해야합니다.  
한 가지 주의 해야 할 점은 합격만을 목표로 두고 준비를 하면 문제를 푸는 요령만 늘기만 하고 과정에서 얻을 수 있는 지식들은 놓칠 수 있습니다.  
의도적으로 지식 습득에 중점을 두고 합격은 같이 따라오는 보너스로 생각하는게 과정과 결과에서 모두 의미있는 경험이 될 수 있다고 생각합니다.

## Kubernetes 자격증별 특징

각 자격증별 난이도는 상중하로 표기했으며, 이는 5가지 자격증을 상대 평가를 기준으로 하였습니다.

### CKA: Certified Kubernetes Administrator

- **난이도**: 중
- **시험 시간**: 120분
- **문항 수**: 17문항
- **합격 기준**: 66점
- **출제 범위**:
    - Storage 10%
    - Troubleshooting 30%
    - Workloads & Scheduling 15%
    - Cluster Architecture, Installation & Configuration 25%
    - Services & Networking 20%
- **특징**:
    - 클러스터를 설치·구성·운영하는 능력을 평가.
    - 운영자(Administrator)로서의 기본기를 증명하는 자격증.

### CKAD: Certified Kubernetes Application Developer

- **난이도**: 중
- **시험 시간**: 120분
- **문항 수**: 16문항
- **합격 기준**: 66점
- **출제 범위**:
    - Application Design and Build 20%
    - Application Deployment 20%
    - Application Observability and Maintenance 15%
    - Application Environment, Configuration and Security 25%
    - Services and Networking 20%
- **특징**:
    - 개발자 관점에서 애플리케이션을 Kubernetes에 배포·운영하는 능력을 평가.
    - 리소스 작성 능력과 Troubleshooting을 동시에 요구.

### CKS: Certified Kubernetes Security Specialist

- **난이도**: 상
- **시험 시간**: 120분
- **문항 수**: 16문항
- **합격 기준**: 67점
- **출제 범위**:
    - Cluster Setup 15%
    - Cluster Hardening 15%
    - System Hardening 10%
    - Minimize Microservice Vulnerabilities 20%
    - Supply Chain Security 20%
    - Monitoring, Logging and Runtime Security 20%
- **특징**:
    - Kubernetes 보안 전반을 다루는 최고 난이도의 시험.
    - DevSecOps/SRE 영역에 가까운 심화 지식을 요구.
    - CKA, CKAD에 비해 생소한 개념이 많아 준비 난이도가 높음.

### KCNA: Kubenetes and Cloud Native Associate

- **난이도**: 하
- **시험 시간**: 90분
- **문항 수**: 60문항 (객관식)
- **합격 기준**: 75점
- **출제 범위**:
    - Kubernetes Fundamentals
    - Cloud Native Concepts
    - CI/CD, GitOps, Observability 기초
    - Security 기초
- **특징**:
    - 입문자용으로 가장 적합.
    - Kubernetes뿐 아니라 CNCF 생태계 전반의 기본기를 확인할 수 있음.

### KCSA: Kubernetes and Cloud Native Security Associate

- **난이도**: 하
- **시험 시간**: 90분
- **문항 수**: 60문항 (객관식)
- **합격 기준**: 75점
- **출제 범위**:
    - Kubernetes Security Fundamentals
    - Cloud Native Security Concepts
    - Threat Modeling & Compliance Basics
- **특징**:
    - 보안 개념에 초점을 둔 입문형 시험.
    - CKS의 기초 버전으로, 함께 준비하면 시너지 효과가 큼.
    - DevOps에서 보안 영역까지 확장

## Kubernetes 자격증별 상세 준비 전략
- [CKA 준비 전략](./certs/cka.md)
- [CKAD 준비 전략](./certs/ckad.md)
- [CKS 준비 전략](./certs/cks.md)
- [KCNA 준비 전략](./certs/kcna.md)
- [KCSA 준비 전략](./certs/kcsa.md)

## References

- [Kubestronaut Program](https://www.cncf.io/training/kubestronaut/)
- [Certified Kubernetes Administrator (CKA)](https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/?utm_source=google&utm_medium=paid-search&utm_campaign=24q2-evergreen-lf_training&utm_term=tnc-apac-search-lf-cka&utm_content=tnc-apac-search-lf-cka-eg_rsa&gad_source=1&gad_campaignid=21372789068&gbraid=0AAAAAD2R-lqpgralyWAbDziWwdeFN3xSs&gclid=Cj0KCQjw8eTFBhCXARIsAIkiuOxCp3qy48eZYQPF1_ywGNNIqEf2UrvnmFVJM_7AMgrdh5qAtRqS7hQaAr1LEALw_wcB)
- [Certified Kubernetes Application Developer (CKAD)](https://training.linuxfoundation.org/certification/certified-kubernetes-application-developer-ckad/?utm_source=google&utm_medium=paid-search&utm_campaign=24q2-evergreen-lf_training&utm_term=tnc-apac-search-lf-ckad&utm_content=tnc-apac-search-lf-ckad-eg_rsa&gad_source=1&gad_campaignid=21372789068&gbraid=0AAAAAD2R-lqpgralyWAbDziWwdeFN3xSs&gclid=Cj0KCQjw8eTFBhCXARIsAIkiuOwAn-qPyw1knqlDZMb-LzhSL7Y21f-JNs1byFI-OerVT0cMIKt3hnwaAlQuEALw_wcB)
- [Certified Kubernetes Security Specialist (CKS)](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/)
- [Kubernetes and Cloud Native Associate (KCNA)](https://training.linuxfoundation.org/certification/kubernetes-cloud-native-associate/)
- [Kubernetes and Cloud Native Security Associate (KCSA)](https://training.linuxfoundation.org/certification/kubernetes-and-cloud-native-security-associate-kcsa/)