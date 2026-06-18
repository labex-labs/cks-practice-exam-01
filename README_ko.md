# CKS 실전 모의고사 01

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![CKS 실전 모의고사 01](https://course-cover.labex.io/cks-practice-exam-01.png?lang=ko)](https://labex.io/ko/courses/cks-practice-exam-01)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/cks-practice-exam-01)

클러스터 설정, 클러스터 강화, 시스템 강화, 마이크로서비스 취약점 감소, 공급망 보안 및 런타임 보안을 아우르는 20 개의 독립적인 Kubernetes 보안 챌린지로 구성된 실습형 CKS 모의고사입니다.

![kubernetes](https://img.shields.io/badge/kubernetes-whitesmoke?style=for-the-badge&logo=kubernetes)
![cks](https://img.shields.io/badge/cks-whitesmoke?style=for-the-badge&logo=cks)


## 연습

|   인덱스 | 이름                                        | 난이도   | 연습                                                                                                                                            |
|-------|-------------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------------------------|
|    01 | 🎯  NetworkPolicy 를 사용하여 네임스페이스 트래픽 제한     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=cks-practice-exam-01'>도전 시작</a> |
|    02 | 🎯  TLS Ingress 를 통한 관리자 콘솔 게시             | 중급    | <a target='_blank' href='https://labex.io/ko/labs/publish-an-admin-console-with-tls-ingress-663189?course=cks-practice-exam-01'>도전 시작</a>     |
|    03 | 🎯  배포 전 Kubernetes 바이너리 검증                | 중급    | <a target='_blank' href='https://labex.io/ko/labs/verify-kubernetes-binaries-before-deployment-663194?course=cks-practice-exam-01'>도전 시작</a>  |
|    04 | 🎯  과도한 권한이 부여된 ClusterRoleBinding 축소      | 중급    | <a target='_blank' href='https://labex.io/ko/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=cks-practice-exam-01'>도전 시작</a>   |
|    05 | 🎯  기본 ServiceAccount 토큰 마운트 비활성화          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/disable-default-serviceaccount-token-mounts-663178?course=cks-practice-exam-01'>도전 시작</a>   |
|    06 | 🎯  Incident Reader API 액세스 제한             | 중급    | <a target='_blank' href='https://labex.io/ko/labs/limit-incident-reader-api-access-663186?course=cks-practice-exam-01'>도전 시작</a>              |
|    07 | 🎯  워크로드에 AppArmor 프로필 적용하기                | 고급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-an-apparmor-profile-on-a-workload-663179?course=cks-practice-exam-01'>도전 시작</a>     |
|    08 | 🎯  로컬 Seccomp 프로필 설치                      | 고급    | <a target='_blank' href='https://labex.io/ko/labs/install-a-local-seccomp-profile-663183?course=cks-practice-exam-01'>도전 시작</a>               |
|    09 | 🎯  제한된 파드 보안 (Restricted Pod Security) 적용 | 중급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-restricted-pod-security-663181?course=cks-practice-exam-01'>도전 시작</a>               |
|    10 | 🎯  Projected Files 를 사용한 Secret 보호        | 중급    | <a target='_blank' href='https://labex.io/ko/labs/protect-secrets-with-projected-files-663188?course=cks-practice-exam-01'>도전 시작</a>          |
|    11 | 🎯  런타임 보안 컨텍스트 강화                         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/harden-a-runtime-security-context-663182?course=cks-practice-exam-01'>도전 시작</a>             |
|    12 | 🎯  위험한 사이드카 경계 격리                         | 고급    | <a target='_blank' href='https://labex.io/ko/labs/isolate-a-risky-sidecar-boundary-663185?course=cks-practice-exam-01'>도전 시작</a>              |
|    13 | 🎯  최소화된 승인 이미지 빌드                         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/build-a-minimal-approved-image-663176?course=cks-practice-exam-01'>도전 시작</a>                |
|    14 | 🎯  SBOM 및 체크섬 증거 검증                       | 중급    | <a target='_blank' href='https://labex.io/ko/labs/verify-sbom-and-checksum-evidence-663195?course=cks-practice-exam-01'>도전 시작</a>             |
|    15 | 🎯  KubeLinter 를 사용한 워크로드 매니페스트 스캔         | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scan-workload-manifests-with-kubelinter-663193?course=cks-practice-exam-01'>도전 시작</a>       |
|    16 | 🎯  승인된 이미지 다이제스트로 워크로드 고정                 | 고급    | <a target='_blank' href='https://labex.io/ko/labs/pin-workloads-to-approved-image-digests-663187?course=cks-practice-exam-01'>도전 시작</a>       |
|    17 | 🎯  비밀 정보 (Secret) 접근에 대한 감사 이벤트 검토        | 중급    | <a target='_blank' href='https://labex.io/ko/labs/review-audit-events-for-secret-access-663192?course=cks-practice-exam-01'>도전 시작</a>         |
|    18 | 🎯  의심스러운 런타임 프로세스 탐지                      | 고급    | <a target='_blank' href='https://labex.io/ko/labs/detect-a-suspicious-runtime-process-663177?course=cks-practice-exam-01'>도전 시작</a>           |
|    19 | 🎯  불변 런타임 컨테이너 강제 적용                      | 중급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-immutable-runtime-containers-663180?course=cks-practice-exam-01'>도전 시작</a>          |
|    20 | 🎯  비인가 API 활동 조사                          | 고급    | <a target='_blank' href='https://labex.io/ko/labs/investigate-unauthorized-api-activity-663184?course=cks-practice-exam-01'>도전 시작</a>         |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

## 더 보기

- 🔗 [CKS 교육 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [CKS 교육 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [CKS 교육 무료 튜토리얼](https://github.com/labex-labs/cks-free-tutorials)

