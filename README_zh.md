# RHCE in Ansible 培训 Certification Prep Path

## 支持语言

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/zh/learn/rhce-ansible"><img width="128px" src="https://file.labex.io/path/yhXXtMLd7wiu.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/开始路径-whitesmoke?style=for-the-badge)](https://labex.io/zh/learn/rhce-ansible)

在 RHCSA（EX200）基础上，通过结构化的动手学习路径备考 Red Hat Certified Engineer in Ansible（EX294）考试。本路线图侧重 RHEL 上的 Ansible 自动化、性能型考试任务与真实企业场景，涵盖 ansible-navigator、inventory、playbook、role、collection、模板、Vault 及 RHCSA 管理任务自动化。后续将逐步加入 RHCE in Ansible 课程、实验环境与模拟考试练习，帮助你建立与 EX294 目标一致的能力。

**课程**: 3 · **实验**: 58

## 课程

### 1. [RHCE Ansible 备考指南 (EX294)](https://labex.io/zh/courses/rhce-ansible-prep)

这是一门面向初学者的 RHCE Ansible 备考课程，包含 30 个引导式实验，内容涵盖从 Ansible 项目基础到清单、Playbook、角色、集合以及 RHEL 自动化应用等各个方面。

[开始课程](https://labex.io/zh/courses/rhce-ansible-prep) · 实验: 30

#### Ansible 项目基础

|   序号 | 名称                             | 难度   | 练习                                                                                                                      |
|------|--------------------------------|------|-------------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用 Git 准备 Ansible 项目        | 初级   | [开始实验](https://labex.io/zh/labs/prepare-an-ansible-project-with-git-664182?course=rhce-ansible-prep)                    |
|    2 | 🧩  配置 ansible.cfg 与项目默认设置      | 初级   | [开始实验](https://labex.io/zh/labs/configure-ansible-cfg-and-project-defaults-664171?course=rhce-ansible-prep)             |
|    3 | 🧩  配置 ansible-navigator 和执行环境  | 初级   | [开始实验](https://labex.io/zh/labs/configure-ansible-navigator-and-execution-environments-664172?course=rhce-ansible-prep) |
|    4 | 🧩  使用 Navigator 运行并检查 Playbook | 初级   | [开始实验](https://labex.io/zh/labs/run-and-inspect-playbooks-with-navigator-664186?course=rhce-ansible-prep)               |
|    5 | 🧩  使用离线 Ansible 文档             | 初级   | [开始实验](https://labex.io/zh/labs/use-offline-ansible-documentation-664193?course=rhce-ansible-prep)                      |

#### 清单、连接与目标定位

|   序号 | 名称                | 难度   | 练习                                                                                                                  |
|------|-------------------|------|---------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用组和变量构建静态清单   | 初级   | [开始实验](https://labex.io/zh/labs/build-static-inventories-with-groups-and-variables-664170?course=rhce-ansible-prep) |
|    2 | 🧩  配置 SSH 密钥与权限提升 | 初级   | [开始实验](https://labex.io/zh/labs/configure-ssh-keys-and-privilege-escalation-664173?course=rhce-ansible-prep)        |
|    3 | 🧩  使用临时命令测试受管节点   | 初级   | [开始实验](https://labex.io/zh/labs/test-managed-nodes-with-ad-hoc-commands-664189?course=rhce-ansible-prep)            |
|    4 | 🧩  使用模式和限制定位主机    | 初级   | [开始实验](https://labex.io/zh/labs/target-hosts-with-patterns-and-limits-664188?course=rhce-ansible-prep)              |
|    5 | 🧩  将基准文件部署到受管节点   | 初级   | [开始实验](https://labex.io/zh/labs/deploy-baseline-files-to-managed-nodes-664177?course=rhce-ansible-prep)             |

#### Playbook 逻辑与可靠性

|   序号 | 名称                        | 难度   | 练习                                                                                                              |
|------|---------------------------|------|-----------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用常用模块编写幂等 Playbook    | 初级   | [开始实验](https://labex.io/zh/labs/write-idempotent-playbooks-with-common-modules-664195?course=rhce-ansible-prep) |
|    2 | 🧩  使用 Handlers 管理服务       | 初级   | [开始实验](https://labex.io/zh/labs/manage-services-with-handlers-664181?course=rhce-ansible-prep)                  |
|    3 | 🧩  使用循环、事实和条件判断           | 初级   | [开始实验](https://labex.io/zh/labs/use-loops-facts-and-conditionals-664192?course=rhce-ansible-prep)               |
|    4 | 🧩  注册结果与控制任务状态            | 初级   | [开始实验](https://labex.io/zh/labs/register-results-and-control-task-status-664184?course=rhce-ansible-prep)       |
|    5 | 🧩  使用 block 和 rescue 处理故障 | 初级   | [开始实验](https://labex.io/zh/labs/handle-failures-with-blocks-and-rescue-664178?course=rhce-ansible-prep)         |
|    6 | 🧩  验证 Playbook 的幂等性       | 初级   | [开始实验](https://labex.io/zh/labs/validate-playbook-idempotence-664194?course=rhce-ansible-prep)                  |
|    7 | 🧩  排查 YAML、Jinja2 和模块错误   | 初级   | [开始实验](https://labex.io/zh/labs/troubleshoot-yaml-jinja2-and-module-errors-664190?course=rhce-ansible-prep)     |

#### 变量、模板、角色与集合

|   序号 | 名称                                        | 难度   | 练习                                                                                                             |
|------|-------------------------------------------|------|----------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  使用导入（Import）和包含（Include）构建 Playbook 结构 | 初级   | [开始实验](https://labex.io/zh/labs/structure-playbooks-with-imports-and-includes-664187?course=rhce-ansible-prep) |
|    2 | 🧩  管理组变量、主机变量与事实                          | 初级   | [开始实验](https://labex.io/zh/labs/manage-group-host-variables-and-facts-664180?course=rhce-ansible-prep)         |
|    3 | 🧩  创建并使用自定义事实                             | 初级   | [开始实验](https://labex.io/zh/labs/create-and-use-custom-facts-664175?course=rhce-ansible-prep)                   |
|    4 | 🧩  使用模板渲染配置文件                             | 初级   | [开始实验](https://labex.io/zh/labs/render-configuration-files-with-templates-664185?course=rhce-ansible-prep)     |
|    5 | 🧩  使用 Ansible Vault 保护并使用机密信息             | 初级   | [开始实验](https://labex.io/zh/labs/protect-and-use-secrets-with-ansible-vault-664183?course=rhce-ansible-prep)    |
|    6 | 🧩  调试变量优先级问题                              | 初级   | [开始实验](https://labex.io/zh/labs/debug-variable-precedence-issues-664176?course=rhce-ansible-prep)              |
|    7 | 🧩  创建并应用可重用角色                             | 初级   | [开始实验](https://labex.io/zh/labs/create-and-apply-a-reusable-role-664174?course=rhce-ansible-prep)              |
|    8 | 🧩  安装角色与内容集合                              | 初级   | [开始实验](https://labex.io/zh/labs/install-roles-and-content-collections-664179?course=rhce-ansible-prep)         |
|    9 | 🧩  在完整工作流中使用集合内容                          | 初级   | [开始实验](https://labex.io/zh/labs/use-collection-content-in-a-complete-workflow-664191?course=rhce-ansible-prep) |

#### RHEL 自动化工作流应用

|   序号 | 名称                 | 难度   | 练习                                                                                                               |
|------|--------------------|------|------------------------------------------------------------------------------------------------------------------|
|    1 | 🧩  自动化配置软件包、服务与防火墙 | 初级   | [开始实验](https://labex.io/zh/labs/automate-packages-services-and-firewalls-664166?course=rhce-ansible-prep)        |
|    2 | 🧩  自动化管理用户、文件和定时任务 | 初级   | [开始实验](https://labex.io/zh/labs/automate-users-files-and-scheduled-tasks-664169?course=rhce-ansible-prep)        |
|    3 | 🧩  自动化存储与挂载配置      | 初级   | [开始实验](https://labex.io/zh/labs/automate-storage-and-mount-configuration-664168?course=rhce-ansible-prep)        |
|    4 | 🧩  跨受管节点自动化安全设置    | 初级   | [开始实验](https://labex.io/zh/labs/automate-security-settings-across-managed-nodes-664167?course=rhce-ansible-prep) |

### 2. [RHCE Ansible 实战模拟考试 01](https://labex.io/zh/courses/rhce-ansible-practice-exam-01)

这是一场包含 14 个独立自动化挑战的 RHCE Ansible 实战模拟考试，涵盖了 Ansible 项目设置、清单、Playbook、变量、模板、Vault、角色、集合以及 RHEL 系统管理自动化等核心内容。

[开始课程](https://labex.io/zh/courses/rhce-ansible-practice-exam-01) · 实验: 14

#### Ansible 环境、导航与版本控制

|   序号 | 名称                             | 难度   | 练习                                                                                                                                |
|------|--------------------------------|------|-----------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  初始化自动化项目仓库                  | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-initialize-an-automation-project-repository-664410?course=rhce-ansible-practice-exam-01)     |
|    2 | 🎯  配置 Ansible 和 Navigator 执行环境 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-configure-ansible-and-navigator-execution-664406?course=rhce-ansible-practice-exam-01)       |
|    3 | 🎯  使用离线文档完成模块工作流               | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-use-offline-documentation-for-a-module-workflow-664416?course=rhce-ansible-practice-exam-01) |

#### 清单与受管节点

|   序号 | 名称                 | 难度   | 练习                                                                                                                                 |
|------|--------------------|------|------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  构建清单组与主机变量      | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-build-inventory-groups-and-host-variables-664405?course=rhce-ansible-practice-exam-01)        |
|    2 | 🎯  配置受管节点访问权限与基准文件 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-configure-managed-node-access-and-baseline-files-664407?course=rhce-ansible-practice-exam-01) |

#### Play、Playbook、模块与流程控制

|   序号 | 名称                 | 难度   | 练习                                                                                                                               |
|------|--------------------|------|----------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  以幂等方式部署服务       | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-deploy-a-service-idempotently-664409?course=rhce-ansible-practice-exam-01)                  |
|    2 | 🎯  使用循环和事实应用主机特定逻辑 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-apply-host-specific-logic-with-loops-and-facts-664403?course=rhce-ansible-practice-exam-01) |
|    3 | 🎯  修复故障 Playbook   | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-recover-a-faulty-playbook-664413?course=rhce-ansible-practice-exam-01)                      |

#### 变量、事实、模板、Vault 与内容

|   序号 | 名称                    | 难度   | 练习                                                                                                                              |
|------|-----------------------|------|---------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  渲染主机特定的配置模板        | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-render-host-specific-configuration-templates-664414?course=rhce-ansible-practice-exam-01)  |
|    2 | 🎯  使用 Vault 保护并部署服务机密 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-protect-and-deploy-service-secrets-with-vault-664412?course=rhce-ansible-practice-exam-01) |
|    3 | 🎯  解决事实与变量优先级问题       | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-resolve-facts-and-variable-precedence-664415?course=rhce-ansible-practice-exam-01)         |

#### 角色、集合与 RHCSA 任务自动化

|   序号 | 名称              | 难度   | 练习                                                                                                                          |
|------|-----------------|------|-----------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  创建 Web 服务器角色 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-create-a-web-server-role-664408?course=rhce-ansible-practice-exam-01)                  |
|    2 | 🎯  安装并使用暂存的集合内容 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-install-and-use-staged-collection-content-664411?course=rhce-ansible-practice-exam-01) |
|    3 | 🎯  自动化多主机管理状态   | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-automate-multi-host-administration-state-664404?course=rhce-ansible-practice-exam-01)  |

### 3. [RHCE Ansible 实战模拟考试 02](https://labex.io/zh/courses/rhce-ansible-practice-exam-02)

这是第二套 RHCE Ansible 实战模拟考试，包含 14 个独立的自动化挑战，涵盖了 Ansible 配置、清单管理、Playbook 可靠性、模板、Vault 加密、角色（Roles）、集合（Collections）以及 RHEL 系统管理自动化等核心内容。

[开始课程](https://labex.io/zh/courses/rhce-ansible-practice-exam-02) · 实验: 14

#### Ansible 环境、导航与版本控制

|   序号 | 名称                    | 难度   | 练习                                                                                                                              |
|------|-----------------------|------|---------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  修复自动化仓库布局          | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-repair-an-automation-repository-layout-664426?course=rhce-ansible-practice-exam-02)        |
|    2 | 🎯  为分段运行时配置 Navigator | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-configure-navigator-for-a-staged-runtime-664420?course=rhce-ansible-practice-exam-02)      |
|    3 | 🎯  排查 Ansible 配置优先级问题 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-troubleshoot-ansible-configuration-precedence-664429?course=rhce-ansible-practice-exam-02) |

#### 清单与受管节点

|   序号 | 名称          | 难度   | 练习                                                                                                                  |
|------|-------------|------|---------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  库存中的模型环境 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-model-environments-in-inventory-664422?course=rhce-ansible-practice-exam-02)   |
|    2 | 🎯  恢复受管节点连接 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-restore-managed-node-connectivity-664427?course=rhce-ansible-practice-exam-02) |

#### Play、Playbook、模块与流程控制

|   序号 | 名称              | 难度   | 练习                                                                                                                             |
|------|-----------------|------|--------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  配置多服务更新的处理器  | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-configure-handlers-for-multi-service-updates-664419?course=rhce-ansible-practice-exam-02) |
|    2 | 🎯  从软件包和任务失败中恢复 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-recover-from-package-and-task-failures-664424?course=rhce-ansible-practice-exam-02)       |
|    3 | 🎯  构建条件防火墙与服务规则 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-build-conditional-firewall-and-service-rules-664418?course=rhce-ansible-practice-exam-02) |

#### 变量、事实、模板、Vault 与内容

|   序号 | 名称                        | 难度   | 练习                                                                                                                                |
|------|---------------------------|------|-----------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  使用模板生成应用程序配置           | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-generate-application-configs-from-templates-664421?course=rhce-ansible-practice-exam-02)     |
|    2 | 🎯  轮换 Ansible Vault 保护的凭据 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-rotate-vault-protected-credentials-664428?course=rhce-ansible-practice-exam-02)              |
|    3 | 🎯  发布自定义事实并修复变量覆盖         | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-publish-custom-facts-and-fix-variable-overrides-664423?course=rhce-ansible-practice-exam-02) |

#### 角色、集合与 RHCSA 任务自动化

|   序号 | 名称                      | 难度   | 练习                                                                                                                                     |
|------|-------------------------|------|----------------------------------------------------------------------------------------------------------------------------------------|
|    1 | 🎯  将单体 Playbook 重构为角色   | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-refactor-a-monolithic-playbook-into-roles-664425?course=rhce-ansible-practice-exam-02)            |
|    2 | 🎯  使用集合内容进行系统配置         | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-use-collection-content-for-system-configuration-664430?course=rhce-ansible-practice-exam-02)      |
|    3 | 🎯  自动化仓库、Web、用户及计划任务合规性 | 初级   | [开始挑战](https://labex.io/zh/labs/rhel-automate-repository-web-user-and-schedule-compliance-664417?course=rhce-ansible-practice-exam-02) |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

