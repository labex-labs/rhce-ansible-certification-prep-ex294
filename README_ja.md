# RHCE in Ansible トレーニング Certification Prep Path

## 言語

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/ja/learn/rhce-ansible"><img width="128px" src="https://file.labex.io/path/yhXXtMLd7wiu.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/パスを開始-whitesmoke?style=for-the-badge)](https://labex.io/ja/learn/rhce-ansible)

RHCSA（EX200）を前提に、Red Hat Certified Engineer in Ansible（EX294）試験に向けた体系的な実践パスです。RHEL 上の Ansible 自動化、パフォーマンスベースのタスク、現実的なエンタープライズシナリオに焦点を当てます。RHCE in Ansible コース、ラボ、模擬試験の演習は順次追加され、EX294 の目標に沿ったスキルを育成します。

**コース**: 3 · **ラボ**: 58

## コース

### 1. [RHCE Ansible 対策コース (EX294)](https://labex.io/ja/courses/rhce-ansible-prep)

[![RHCE Ansible 対策コース (EX294)](https://course-cover.labex.io/rhce-ansible-prep.png?lang=ja)](https://labex.io/ja/courses/rhce-ansible-prep)

Ansible プロジェクトの基礎からインベントリ、Playbook、ロール、コレクション、そして RHEL 実践自動化まで、30 のガイド付き実験を通して学べる初心者向けの RHCE Ansible 対策コースです。

[コースを開始](https://labex.io/ja/courses/rhce-ansible-prep) · ラボ: 30

#### Ansible プロジェクトの基礎

|   インデックス | 名前                                                    | 難易度   | 練習                                                                                                                       |
|----------|-------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Git を使用した Ansible プロジェクトの準備                        | 初級    | [ラボを開始](https://labex.io/ja/labs/prepare-an-ansible-project-with-git-664182?course=rhce-ansible-prep)                    |
|        2 | 🧩  ansible.cfg の設定とプロジェクトのデフォルト定義                     | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ansible-cfg-and-project-defaults-664171?course=rhce-ansible-prep)             |
|        3 | 🧩  ansible-navigator と実行環境（Execution Environments）の設定 | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ansible-navigator-and-execution-environments-664172?course=rhce-ansible-prep) |
|        4 | 🧩  Navigator を使用した Playbook の実行と検証                    | 初級    | [ラボを開始](https://labex.io/ja/labs/run-and-inspect-playbooks-with-navigator-664186?course=rhce-ansible-prep)               |
|        5 | 🧩  オフラインの Ansible ドキュメントを活用する                         | 初級    | [ラボを開始](https://labex.io/ja/labs/use-offline-ansible-documentation-664193?course=rhce-ansible-prep)                      |

#### インベントリ、接続性、およびターゲット設定

|   インデックス | 名前                                 | 難易度   | 練習                                                                                                                   |
|----------|------------------------------------|-------|----------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  グループと変数を使用した静的インベントリの構築         | 初級    | [ラボを開始](https://labex.io/ja/labs/build-static-inventories-with-groups-and-variables-664170?course=rhce-ansible-prep) |
|        2 | 🧩  SSH キーと特権昇格の設定                  | 初級    | [ラボを開始](https://labex.io/ja/labs/configure-ssh-keys-and-privilege-escalation-664173?course=rhce-ansible-prep)        |
|        3 | 🧩  Ansible アドホックコマンドによる管理対象ノードのテスト | 初級    | [ラボを開始](https://labex.io/ja/labs/test-managed-nodes-with-ad-hoc-commands-664189?course=rhce-ansible-prep)            |
|        4 | 🧩  パターンと制限を使用したターゲットホストの指定         | 初級    | [ラボを開始](https://labex.io/ja/labs/target-hosts-with-patterns-and-limits-664188?course=rhce-ansible-prep)              |
|        5 | 🧩  管理対象ノードへのベースラインファイルのデプロイ        | 初級    | [ラボを開始](https://labex.io/ja/labs/deploy-baseline-files-to-managed-nodes-664177?course=rhce-ansible-prep)             |

#### Playbook のロジックと信頼性

|   インデックス | 名前                                     | 難易度   | 練習                                                                                                               |
|----------|----------------------------------------|-------|------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  共通モジュールを使用した冪等性のある Playbook の作成     | 初級    | [ラボを開始](https://labex.io/ja/labs/write-idempotent-playbooks-with-common-modules-664195?course=rhce-ansible-prep) |
|        2 | 🧩  ハンドラーによるサービスの管理                     | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-services-with-handlers-664181?course=rhce-ansible-prep)                  |
|        3 | 🧩  ループ、ファクト、条件分岐の使用                    | 初級    | [ラボを開始](https://labex.io/ja/labs/use-loops-facts-and-conditionals-664192?course=rhce-ansible-prep)               |
|        4 | 🧩  結果の登録とタスクステータスの制御                   | 初級    | [ラボを開始](https://labex.io/ja/labs/register-results-and-control-task-status-664184?course=rhce-ansible-prep)       |
|        5 | 🧩  ブロックと rescue を使用したエラー処理             | 初級    | [ラボを開始](https://labex.io/ja/labs/handle-failures-with-blocks-and-rescue-664178?course=rhce-ansible-prep)         |
|        6 | 🧩  Playbook の冪等性の検証                    | 初級    | [ラボを開始](https://labex.io/ja/labs/validate-playbook-idempotence-664194?course=rhce-ansible-prep)                  |
|        7 | 🧩  YAML、Jinja2、およびモジュールエラーのトラブルシューティング | 初級    | [ラボを開始](https://labex.io/ja/labs/troubleshoot-yaml-jinja2-and-module-errors-664190?course=rhce-ansible-prep)     |

#### 変数、テンプレート、ロール、およびコレクション

|   インデックス | 名前                                 | 難易度   | 練習                                                                                                              |
|----------|------------------------------------|-------|-----------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  インポートとインクルードによる Playbook の構造化   | 初級    | [ラボを開始](https://labex.io/ja/labs/structure-playbooks-with-imports-and-includes-664187?course=rhce-ansible-prep) |
|        2 | 🧩  グループ変数、ホスト変数、およびファクトの管理         | 初級    | [ラボを開始](https://labex.io/ja/labs/manage-group-host-variables-and-facts-664180?course=rhce-ansible-prep)         |
|        3 | 🧩  カスタムファクトの作成と使用                  | 初級    | [ラボを開始](https://labex.io/ja/labs/create-and-use-custom-facts-664175?course=rhce-ansible-prep)                   |
|        4 | 🧩  テンプレートを使用した設定ファイルのレンダリング        | 初級    | [ラボを開始](https://labex.io/ja/labs/render-configuration-files-with-templates-664185?course=rhce-ansible-prep)     |
|        5 | 🧩  Ansible Vault を使用したシークレットの保護と利用 | 初級    | [ラボを開始](https://labex.io/ja/labs/protect-and-use-secrets-with-ansible-vault-664183?course=rhce-ansible-prep)    |
|        6 | 🧩  変数の優先順位に関する問題のデバッグ              | 初級    | [ラボを開始](https://labex.io/ja/labs/debug-variable-precedence-issues-664176?course=rhce-ansible-prep)              |
|        7 | 🧩  再利用可能なロールの作成と適用                 | 初級    | [ラボを開始](https://labex.io/ja/labs/create-and-apply-a-reusable-role-664174?course=rhce-ansible-prep)              |
|        8 | 🧩  ロールとコンテンツコレクションのインストール          | 初級    | [ラボを開始](https://labex.io/ja/labs/install-roles-and-content-collections-664179?course=rhce-ansible-prep)         |
|        9 | 🧩  コレクションコンテンツを使用した完全なワークフロー       | 初級    | [ラボを開始](https://labex.io/ja/labs/use-collection-content-in-a-complete-workflow-664191?course=rhce-ansible-prep) |

#### RHEL 自動化ワークフローの実践

|   インデックス | 名前                              | 難易度   | 練習                                                                                                                |
|----------|---------------------------------|-------|-------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  パッケージ、サービス、ファイアウォールの自動化      | 初級    | [ラボを開始](https://labex.io/ja/labs/automate-packages-services-and-firewalls-664166?course=rhce-ansible-prep)        |
|        2 | 🧩  ユーザー、ファイル、およびスケジュール済みタスクの自動化 | 初級    | [ラボを開始](https://labex.io/ja/labs/automate-users-files-and-scheduled-tasks-664169?course=rhce-ansible-prep)        |
|        3 | 🧩  ストレージとマウント設定の自動化             | 初級    | [ラボを開始](https://labex.io/ja/labs/automate-storage-and-mount-configuration-664168?course=rhce-ansible-prep)        |
|        4 | 🧩  管理対象ノード全体でのセキュリティ設定の自動化      | 初級    | [ラボを開始](https://labex.io/ja/labs/automate-security-settings-across-managed-nodes-664167?course=rhce-ansible-prep) |

### 2. [RHCE in Ansible 模擬試験 01](https://labex.io/ja/courses/rhce-ansible-practice-exam-01)

[![RHCE in Ansible 模擬試験 01](https://course-cover.labex.io/rhce-ansible-practice-exam-01.png?lang=ja)](https://labex.io/ja/courses/rhce-ansible-practice-exam-01)

Ansible プロジェクトのセットアップ、インベントリ、Playbook、変数、テンプレート、Vault、ロール、コレクション、および RHEL 管理の自動化を網羅した、14 個の独立した自動化課題からなる実践的な RHCE in Ansible 模擬試験です。

[コースを開始](https://labex.io/ja/courses/rhce-ansible-practice-exam-01) · ラボ: 14

#### Ansible 環境、ナビゲーション、およびソース管理

|   インデックス | 名前                              | 難易度   | 練習                                                                                                                                    |
|----------|---------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  自動化プロジェクトリポジトリの初期化           | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-initialize-an-automation-project-repository-664410?course=rhce-ansible-practice-exam-01)     |
|        2 | 🎯  Ansible および Navigator の実行設定  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-configure-ansible-and-navigator-execution-664406?course=rhce-ansible-practice-exam-01)       |
|        3 | 🎯  モジュールワークフローのためのオフラインドキュメント活用 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-use-offline-documentation-for-a-module-workflow-664416?course=rhce-ansible-practice-exam-01) |

#### インベントリと管理対象ノード

|   インデックス | 名前                              | 難易度   | 練習                                                                                                                                     |
|----------|---------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  インベントリグループとホスト変数の構築          | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-build-inventory-groups-and-host-variables-664405?course=rhce-ansible-practice-exam-01)        |
|        2 | 🎯  管理対象ノードのアクセス設定とベースラインファイルの配置 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-configure-managed-node-access-and-baseline-files-664407?course=rhce-ansible-practice-exam-01) |

#### プレイ、Playbook、モジュール、およびフロー制御

|   インデックス | 名前                           | 難易度   | 練習                                                                                                                                   |
|----------|------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  サービスの冪等なデプロイ              | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-deploy-a-service-idempotently-664409?course=rhce-ansible-practice-exam-01)                  |
|        2 | 🎯  ループとファクトを使用したホスト固有ロジックの適用 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-apply-host-specific-logic-with-loops-and-facts-664403?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  故障した Playbook の復旧         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-recover-a-faulty-playbook-664413?course=rhce-ansible-practice-exam-01)                      |

#### 変数、ファクト、テンプレート、Vault、およびコンテンツ

|   インデックス | 名前                               | 難易度   | 練習                                                                                                                                  |
|----------|----------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  ホスト固有の設定テンプレートのレンダリング         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-render-host-specific-configuration-templates-664414?course=rhce-ansible-practice-exam-01)  |
|        2 | 🎯  Vault を使用したサービスシークレットの保護とデプロイ | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-protect-and-deploy-service-secrets-with-vault-664412?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  ファクトと変数の優先順位の解決               | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-resolve-facts-and-variable-precedence-664415?course=rhce-ansible-practice-exam-01)         |

#### ロール、コレクション、および RHCSA タスクの自動化

|   インデックス | 名前                                | 難易度   | 練習                                                                                                                              |
|----------|-----------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Web サーバーロールの作成                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-create-a-web-server-role-664408?course=rhce-ansible-practice-exam-01)                  |
|        2 | 🎯  ステージングされたコレクションコンテンツのインストールと使用 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-install-and-use-staged-collection-content-664411?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  マルチホスト管理状態の自動化                 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-automate-multi-host-administration-state-664404?course=rhce-ansible-practice-exam-01)  |

### 3. [RHCE in Ansible 実践試験 02](https://labex.io/ja/courses/rhce-ansible-practice-exam-02)

[![RHCE in Ansible 実践試験 02](https://course-cover.labex.io/rhce-ansible-practice-exam-02.png?lang=ja)](https://labex.io/ja/courses/rhce-ansible-practice-exam-02)

Ansible の設定、インベントリ、Playbook の信頼性、テンプレート、Vault、ロール、コレクション、および RHEL 管理の自動化を網羅した、14 の独立した自動化課題で構成される RHCE in Ansible 実践試験の第 2 弾です。

[コースを開始](https://labex.io/ja/courses/rhce-ansible-practice-exam-02) · ラボ: 14

#### Ansible 環境、ナビゲーション、およびソース管理

|   インデックス | 名前                                   | 難易度   | 練習                                                                                                                                  |
|----------|--------------------------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  自動化リポジトリのレイアウト修復                  | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-repair-an-automation-repository-layout-664426?course=rhce-ansible-practice-exam-02)        |
|        2 | 🎯  ステージングされたランタイム向けに Navigator を構成する | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-configure-navigator-for-a-staged-runtime-664420?course=rhce-ansible-practice-exam-02)      |
|        3 | 🎯  Ansible 設定の優先順位のトラブルシューティング       | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-troubleshoot-ansible-configuration-precedence-664429?course=rhce-ansible-practice-exam-02) |

#### インベントリと管理対象ノード

|   インデックス | 名前                 | 難易度   | 練習                                                                                                                      |
|----------|--------------------|-------|-------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  インベントリにおけるモデル環境 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-model-environments-in-inventory-664422?course=rhce-ansible-practice-exam-02)   |
|        2 | 🎯  管理ノードの接続性の復元    | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-restore-managed-node-connectivity-664427?course=rhce-ansible-practice-exam-02) |

#### プレイ、Playbook、モジュール、およびフロー制御

|   インデックス | 名前                           | 難易度   | 練習                                                                                                                                 |
|----------|------------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  マルチサービス更新のためのハンドラー設定      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-configure-handlers-for-multi-service-updates-664419?course=rhce-ansible-practice-exam-02) |
|        2 | 🎯  パッケージとタスクの失敗からの復旧         | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-recover-from-package-and-task-failures-664424?course=rhce-ansible-practice-exam-02)       |
|        3 | 🎯  条件付きファイアウォールおよびサービスルールの構築 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-build-conditional-firewall-and-service-rules-664418?course=rhce-ansible-practice-exam-02) |

#### 変数、ファクト、テンプレート、Vault、およびコンテンツ

|   インデックス | 名前                          | 難易度   | 練習                                                                                                                                    |
|----------|-----------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  テンプレートからのアプリケーション設定の生成   | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-generate-application-configs-from-templates-664421?course=rhce-ansible-practice-exam-02)     |
|        2 | 🎯  Vault で保護された認証情報のローテーション | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-rotate-vault-protected-credentials-664428?course=rhce-ansible-practice-exam-02)              |
|        3 | 🎯  カスタムファクトの公開と変数オーバーライドの修正 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-publish-custom-facts-and-fix-variable-overrides-664423?course=rhce-ansible-practice-exam-02) |

#### ロール、コレクション、および RHCSA タスクの自動化

|   インデックス | 名前                                      | 難易度   | 練習                                                                                                                                         |
|----------|-----------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  モノリシックな Playbook のロールへのリファクタリング      | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-refactor-a-monolithic-playbook-into-roles-664425?course=rhce-ansible-practice-exam-02)            |
|        2 | 🎯  コレクションコンテンツを使用したシステム設定               | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-use-collection-content-for-system-configuration-664430?course=rhce-ansible-practice-exam-02)      |
|        3 | 🎯  リポジトリ、Web、ユーザー、およびスケジュールのコンプライアンス自動化 | 初級    | [チャレンジを開始](https://labex.io/ja/labs/rhel-automate-repository-web-user-and-schedule-compliance-664417?course=rhce-ansible-practice-exam-02) |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

