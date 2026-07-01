# RHCE in Ansible 교육 Certification Prep Path

**언어:** [English](README.md) · [简体中文](README_zh.md) · [日本語](README_ja.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ko/learn/rhce-ansible">
    <img width="128" src="https://file.labex.io/path/yhXXtMLd7wiu.png" alt="RHCE in Ansible 교육">
  </a>
</p>

Prepare for the Red Hat Certified Engineer in Ansible exam (EX294) with a structured, hands-on learning path. This roadmap focuses on Ansible Automation Platform workflows, Git and ansible-navigator, inventories and managed nodes, idempotent playbooks, variables, facts, templates, Vault, roles, content collections, and automating standard RHCSA administration tasks on RHEL, plus performance-based exam tasks and real-world enterprise scenarios. Guided RHCE in Ansible courses, labs, and practice exam practice will be added over time to help you build skills aligned with EX294 objectives.

[LabEx에서 학습 경로 시작](https://labex.io/ko/learn/rhce-ansible)

**코스**: 3 · **실습**: 58

## 코스

### 1. [RHCE in Ansible 실전 모의고사 01](https://labex.io/ko/courses/rhce-ansible-practice-exam-01)

[![RHCE in Ansible 실전 모의고사 01](https://course-cover.labex.io/rhce-ansible-practice-exam-01.png?lang=ko)](https://labex.io/ko/courses/rhce-ansible-practice-exam-01)

Ansible 프로젝트 설정, 인벤토리, 플레이북, 변수, 템플릿, Vault, 역할 (Roles), 컬렉션 및 RHEL 관리 자동화를 다루는 14 개의 독립적인 자동화 과제로 구성된 실습형 RHCE in Ansible 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/rhce-ansible-practice-exam-01) · 실습: 14

#### Ansible Environment, Navigation, and Source Control

|   인덱스 | 이름                        | 난이도   | 연습                                                                                                                                 |
|-------|---------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------|
|     1 | 자동화 프로젝트 저장소 초기화          | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-initialize-an-automation-project-repository-664410?course=rhce-ansible-practice-exam-01)     |
|     2 | Ansible 및 Navigator 실행 구성 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-configure-ansible-and-navigator-execution-664406?course=rhce-ansible-practice-exam-01)       |
|     3 | 모듈 워크플로우를 위한 오프라인 문서 활용   | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-use-offline-documentation-for-a-module-workflow-664416?course=rhce-ansible-practice-exam-01) |

#### Inventories and Managed Nodes

|   인덱스 | 이름                    | 난이도   | 연습                                                                                                                                  |
|-------|-----------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------|
|     1 | 인벤토리 그룹 및 호스트 변수 빌드   | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-build-inventory-groups-and-host-variables-664405?course=rhce-ansible-practice-exam-01)        |
|     2 | 관리형 노드 액세스 및 기준 파일 구성 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-configure-managed-node-access-and-baseline-files-664407?course=rhce-ansible-practice-exam-01) |

#### Plays, Playbooks, Modules, and Flow Control

|   인덱스 | 이름                        | 난이도   | 연습                                                                                                                                |
|-------|---------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------------|
|     1 | 서비스의 멱등성 (Idempotency) 배포 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-deploy-a-service-idempotently-664409?course=rhce-ansible-practice-exam-01)                  |
|     2 | 루프와 팩트를 활용한 호스트별 로직 적용    | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-apply-host-specific-logic-with-loops-and-facts-664403?course=rhce-ansible-practice-exam-01) |
|     3 | 결함이 있는 플레이북 복구            | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-recover-a-faulty-playbook-664413?course=rhce-ansible-practice-exam-01)                      |

#### Variables, Facts, Templates, Vault, and Content

|   인덱스 | 이름                             | 난이도   | 연습                                                                                                                               |
|-------|--------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------|
|     1 | 호스트별 구성 템플릿 렌더링                | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-render-host-specific-configuration-templates-664414?course=rhce-ansible-practice-exam-01)  |
|     2 | Vault 를 사용하여 서비스 보안 정보 보호 및 배포 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-protect-and-deploy-service-secrets-with-vault-664412?course=rhce-ansible-practice-exam-01) |
|     3 | 팩트 및 변수 우선순위 해결                | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-resolve-facts-and-variable-precedence-664415?course=rhce-ansible-practice-exam-01)         |

#### Roles, Collections, and RHCSA Task Automation

|   인덱스 | 이름                    | 난이도   | 연습                                                                                                                           |
|-------|-----------------------|-------|------------------------------------------------------------------------------------------------------------------------------|
|     1 | 웹 서버 역할 (Role) 생성     | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-create-a-web-server-role-664408?course=rhce-ansible-practice-exam-01)                  |
|     2 | 스테이징된 컬렉션 콘텐츠 설치 및 사용 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-install-and-use-staged-collection-content-664411?course=rhce-ansible-practice-exam-01) |
|     3 | 다중 호스트 관리 상태 자동화      | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-automate-multi-host-administration-state-664404?course=rhce-ansible-practice-exam-01)  |

### 2. [RHCE in Ansible 실전 모의고사 02](https://labex.io/ko/courses/rhce-ansible-practice-exam-02)

[![RHCE in Ansible 실전 모의고사 02](https://course-cover.labex.io/rhce-ansible-practice-exam-02.png?lang=ko)](https://labex.io/ko/courses/rhce-ansible-practice-exam-02)

Ansible 설정, 인벤토리, 플레이북 신뢰성, 템플릿, Vault, 역할 (Roles), 컬렉션 및 RHEL 관리 자동화를 다루는 14 개의 독립적인 자동화 챌린지로 구성된 두 번째 RHCE in Ansible 실전 모의고사입니다.

[코스 시작](https://labex.io/ko/courses/rhce-ansible-practice-exam-02) · 실습: 14

#### Ansible Environment, Navigation, and Source Control

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                                               |
|-------|----------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------|
|     1 | 자동화 저장소 레이아웃 복구            | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-repair-an-automation-repository-layout-664426?course=rhce-ansible-practice-exam-02)        |
|     2 | 스테이징된 런타임을 위한 Navigator 구성 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-configure-navigator-for-a-staged-runtime-664420?course=rhce-ansible-practice-exam-02)      |
|     3 | Ansible 구성 우선순위 문제 해결      | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-troubleshoot-ansible-configuration-precedence-664429?course=rhce-ansible-practice-exam-02) |

#### Inventories and Managed Nodes

|   인덱스 | 이름           | 난이도   | 연습                                                                                                                   |
|-------|--------------|-------|----------------------------------------------------------------------------------------------------------------------|
|     1 | 인벤토리 내 모델 환경 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-model-environments-in-inventory-664422?course=rhce-ansible-practice-exam-02)   |
|     2 | 관리형 노드 연결 복구 | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-restore-managed-node-connectivity-664427?course=rhce-ansible-practice-exam-02) |

#### Plays, Playbooks, Modules, and Flow Control

|   인덱스 | 이름                     | 난이도   | 연습                                                                                                                              |
|-------|------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------|
|     1 | 다중 서비스 업데이트를 위한 핸들러 구성 | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-configure-handlers-for-multi-service-updates-664419?course=rhce-ansible-practice-exam-02) |
|     2 | 패키지 및 작업 실패로부터의 복구     | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-recover-from-package-and-task-failures-664424?course=rhce-ansible-practice-exam-02)       |
|     3 | 조건부 방화벽 및 서비스 규칙 구축    | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-build-conditional-firewall-and-service-rules-664418?course=rhce-ansible-practice-exam-02) |

#### Variables, Facts, Templates, Vault, and Content

|   인덱스 | 이름                         | 난이도   | 연습                                                                                                                                 |
|-------|----------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------|
|     1 | 템플릿을 이용한 애플리케이션 설정 생성      | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-generate-application-configs-from-templates-664421?course=rhce-ansible-practice-exam-02)     |
|     2 | Vault 로 보호된 자격 증명 교체       | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-rotate-vault-protected-credentials-664428?course=rhce-ansible-practice-exam-02)              |
|     3 | 사용자 정의 팩트 게시 및 변수 오버라이드 수정 | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-publish-custom-facts-and-fix-variable-overrides-664423?course=rhce-ansible-practice-exam-02) |

#### Roles, Collections, and RHCSA Task Automation

|   인덱스 | 이름                           | 난이도   | 연습                                                                                                                                      |
|-------|------------------------------|-------|-----------------------------------------------------------------------------------------------------------------------------------------|
|     1 | 모놀리식 플레이북의 역할 (Role) 기반 리팩토링 | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-refactor-a-monolithic-playbook-into-roles-664425?course=rhce-ansible-practice-exam-02)            |
|     2 | 컬렉션 콘텐츠를 활용한 시스템 구성          | 중급    | [도전 시작](https://labex.io/ko/labs/rhel-use-collection-content-for-system-configuration-664430?course=rhce-ansible-practice-exam-02)      |
|     3 | 저장소, 웹, 사용자 및 스케줄 규정 준수 자동화  | 고급    | [도전 시작](https://labex.io/ko/labs/rhel-automate-repository-web-user-and-schedule-compliance-664417?course=rhce-ansible-practice-exam-02) |

### 3. [RHCE Ansible 준비 과정 (EX294)](https://labex.io/ko/courses/rhce-ansible-prep)

[![RHCE Ansible 준비 과정 (EX294)](https://course-cover.labex.io/rhce-ansible-prep.png?lang=ko)](https://labex.io/ko/courses/rhce-ansible-prep)

Ansible 프로젝트 기초부터 인벤토리, 플레이북, 역할 (Role), 컬렉션, 그리고 실무 RHEL 자동화까지 30 개의 가이드형 실험으로 구성된 초보자 맞춤형 RHCE Ansible 준비 과정입니다.

[코스 시작](https://labex.io/ko/courses/rhce-ansible-prep) · 실습: 30

#### Ansible Project Foundations

|   인덱스 | 이름                              | 난이도   | 연습                                                                                                                       |
|-------|---------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|     1 | Git 을 활용한 Ansible 프로젝트 준비       | 초급    | [실습 시작](https://labex.io/ko/labs/prepare-an-ansible-project-with-git-664182?course=rhce-ansible-prep)                    |
|     2 | ansible.cfg 구성 및 프로젝트 기본값 설정    | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ansible-cfg-and-project-defaults-664171?course=rhce-ansible-prep)             |
|     3 | ansible-navigator 및 실행 환경 구성    | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ansible-navigator-and-execution-environments-664172?course=rhce-ansible-prep) |
|     4 | Navigator 를 사용하여 플레이북 실행 및 검사하기 | 초급    | [실습 시작](https://labex.io/ko/labs/run-and-inspect-playbooks-with-navigator-664186?course=rhce-ansible-prep)               |
|     5 | 오프라인 Ansible 문서 활용하기            | 초급    | [실습 시작](https://labex.io/ko/labs/use-offline-ansible-documentation-664193?course=rhce-ansible-prep)                      |

#### Inventory, Connectivity, and Targeting

|   인덱스 | 이름                                              | 난이도   | 연습                                                                                                                   |
|-------|-------------------------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|     1 | 그룹 및 변수를 사용한 정적 인벤토리 구축                         | 초급    | [실습 시작](https://labex.io/ko/labs/build-static-inventories-with-groups-and-variables-664170?course=rhce-ansible-prep) |
|     2 | SSH 키 및 권한 상승 구성                                | 초급    | [실습 시작](https://labex.io/ko/labs/configure-ssh-keys-and-privilege-escalation-664173?course=rhce-ansible-prep)        |
|     3 | Ansible 임시 명령 (Ad Hoc Commands) 을 사용한 관리 노드 테스트 | 초급    | [실습 시작](https://labex.io/ko/labs/test-managed-nodes-with-ad-hoc-commands-664189?course=rhce-ansible-prep)            |
|     4 | 패턴과 제한을 사용한 대상 호스트 지정                           | 초급    | [실습 시작](https://labex.io/ko/labs/target-hosts-with-patterns-and-limits-664188?course=rhce-ansible-prep)              |
|     5 | 관리형 노드에 기준 파일 배포하기                              | 초급    | [실습 시작](https://labex.io/ko/labs/deploy-baseline-files-to-managed-nodes-664177?course=rhce-ansible-prep)             |

#### Playbook Logic and Reliability

|   인덱스 | 이름                                   | 난이도   | 연습                                                                                                               |
|-------|--------------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|     1 | 공통 모듈을 사용한 멱등성 (Idempotent) 플레이북 작성  | 초급    | [실습 시작](https://labex.io/ko/labs/write-idempotent-playbooks-with-common-modules-664195?course=rhce-ansible-prep) |
|     2 | 핸들러를 이용한 서비스 관리                      | 초급    | [실습 시작](https://labex.io/ko/labs/manage-services-with-handlers-664181?course=rhce-ansible-prep)                  |
|     3 | 루프, 팩트 및 조건문 사용                      | 초급    | [실습 시작](https://labex.io/ko/labs/use-loops-facts-and-conditionals-664192?course=rhce-ansible-prep)               |
|     4 | 결과 등록 및 작업 상태 제어                     | 초급    | [실습 시작](https://labex.io/ko/labs/register-results-and-control-task-status-664184?course=rhce-ansible-prep)       |
|     5 | 블록 (Block) 과 복구 (Rescue) 를 이용한 오류 처리 | 초급    | [실습 시작](https://labex.io/ko/labs/handle-failures-with-blocks-and-rescue-664178?course=rhce-ansible-prep)         |
|     6 | Playbook 멱등성 검증                      | 초급    | [실습 시작](https://labex.io/ko/labs/validate-playbook-idempotence-664194?course=rhce-ansible-prep)                  |
|     7 | YAML, Jinja2 및 모듈 오류 문제 해결           | 초급    | [실습 시작](https://labex.io/ko/labs/troubleshoot-yaml-jinja2-and-module-errors-664190?course=rhce-ansible-prep)     |

#### Variables, Templates, Roles, and Collections

|   인덱스 | 이름                                           | 난이도   | 연습                                                                                                              |
|-------|----------------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------|
|     1 | 임포트 (Import) 와 인클루드 (Include) 를 활용한 플레이북 구조화 | 초급    | [실습 시작](https://labex.io/ko/labs/structure-playbooks-with-imports-and-includes-664187?course=rhce-ansible-prep) |
|     2 | 그룹 변수, 호스트 변수 및 팩트 관리                        | 초급    | [실습 시작](https://labex.io/ko/labs/manage-group-host-variables-and-facts-664180?course=rhce-ansible-prep)         |
|     3 | 사용자 지정 팩트 (Custom Facts) 생성 및 사용             | 초급    | [실습 시작](https://labex.io/ko/labs/create-and-use-custom-facts-664175?course=rhce-ansible-prep)                   |
|     4 | 템플릿을 사용한 구성 파일 렌더링                           | 초급    | [실습 시작](https://labex.io/ko/labs/render-configuration-files-with-templates-664185?course=rhce-ansible-prep)     |
|     5 | Ansible Vault 를 사용하여 비밀 정보 보호 및 사용하기         | 초급    | [실습 시작](https://labex.io/ko/labs/protect-and-use-secrets-with-ansible-vault-664183?course=rhce-ansible-prep)    |
|     6 | 변수 우선순위 문제 디버깅                               | 초급    | [실습 시작](https://labex.io/ko/labs/debug-variable-precedence-issues-664176?course=rhce-ansible-prep)              |
|     7 | 재사용 가능한 역할 (Role) 생성 및 적용                    | 초급    | [실습 시작](https://labex.io/ko/labs/create-and-apply-a-reusable-role-664174?course=rhce-ansible-prep)              |
|     8 | 역할 및 콘텐츠 컬렉션 설치                              | 초급    | [실습 시작](https://labex.io/ko/labs/install-roles-and-content-collections-664179?course=rhce-ansible-prep)         |
|     9 | 컬렉션 콘텐츠를 활용한 전체 워크플로우 구성                     | 초급    | [실습 시작](https://labex.io/ko/labs/use-collection-content-in-a-complete-workflow-664191?course=rhce-ansible-prep) |

#### Applied RHEL Automation Workflows

|   인덱스 | 이름                   | 난이도   | 연습                                                                                                                |
|-------|----------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|     1 | 패키지, 서비스 및 방화벽 자동화   | 초급    | [실습 시작](https://labex.io/ko/labs/automate-packages-services-and-firewalls-664166?course=rhce-ansible-prep)        |
|     2 | 사용자, 파일 및 예약된 작업 자동화 | 초급    | [실습 시작](https://labex.io/ko/labs/automate-users-files-and-scheduled-tasks-664169?course=rhce-ansible-prep)        |
|     3 | 스토리지 및 마운트 구성 자동화    | 초급    | [실습 시작](https://labex.io/ko/labs/automate-storage-and-mount-configuration-664168?course=rhce-ansible-prep)        |
|     4 | 관리형 노드 전반의 보안 설정 자동화 | 초급    | [실습 시작](https://labex.io/ko/labs/automate-security-settings-across-managed-nodes-664167?course=rhce-ansible-prep) |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

