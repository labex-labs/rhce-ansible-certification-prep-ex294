# RHCE-in-Ansible-Schulung Certification Prep Path

## Sprachen

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/de/learn/rhce-ansible"><img width="128px" src="https://file.labex.io/path/yhXXtMLd7wiu.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Pfad-Starten-whitesmoke?style=for-the-badge)](https://labex.io/de/learn/rhce-ansible)

Prepare for the Red Hat Certified Engineer in Ansible exam (EX294) with a structured, hands-on learning path. This roadmap focuses on Ansible Automation Platform workflows, Git and ansible-navigator, inventories and managed nodes, idempotent playbooks, variables, facts, templates, Vault, roles, content collections, and automating standard RHCSA administration tasks on RHEL, plus performance-based exam tasks and real-world enterprise scenarios. Guided RHCE in Ansible courses, labs, and practice exam practice will be added over time to help you build skills aligned with EX294 objectives.

**Kurse**: 3 · **Labs**: 58

## Kurse

### 1. [RHCE Ansible Vorbereitung (EX294)](https://labex.io/de/courses/rhce-ansible-prep)

Ein einsteigerfreundlicher Vorbereitungskurs für die RHCE-Ansible-Zertifizierung mit 30 geführten Experimenten, die von den Grundlagen eines Ansible-Projekts bis hin zu Inventaren, Playbooks, Rollen, Collections und der angewandten RHEL-Automatisierung reichen.

[Kurs Starten](https://labex.io/de/courses/rhce-ansible-prep) · Labs: 30

#### Grundlagen von Ansible-Projekten

|   Index | Name                                                          | Schwierigkeit   | Übung                                                                                                                            |
|---------|---------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Vorbereiten eines Ansible-Projekts mit Git                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/prepare-an-ansible-project-with-git-664182?course=rhce-ansible-prep)                    |
|       2 | 🧩  Konfiguration von ansible.cfg und Projekt-Standardwerten   | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-ansible-cfg-and-project-defaults-664171?course=rhce-ansible-prep)             |
|       3 | 🧩  ansible-navigator und Execution Environments konfigurieren | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-ansible-navigator-and-execution-environments-664172?course=rhce-ansible-prep) |
|       4 | 🧩  Playbooks mit Navigator ausführen und überprüfen           | Anfänger        | [Labor Starten](https://labex.io/de/labs/run-and-inspect-playbooks-with-navigator-664186?course=rhce-ansible-prep)               |
|       5 | 🧩  Offline Ansible-Dokumentation verwenden                    | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-offline-ansible-documentation-664193?course=rhce-ansible-prep)                      |

#### Inventar, Konnektivität und Zielsteuerung

|   Index | Name                                                       | Schwierigkeit   | Übung                                                                                                                        |
|---------|------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Statische Inventare mit Gruppen und Variablen erstellen | Anfänger        | [Labor Starten](https://labex.io/de/labs/build-static-inventories-with-groups-and-variables-664170?course=rhce-ansible-prep) |
|       2 | 🧩  SSH-Schlüssel und Privilegienerweiterung konfigurieren  | Anfänger        | [Labor Starten](https://labex.io/de/labs/configure-ssh-keys-and-privilege-escalation-664173?course=rhce-ansible-prep)        |
|       3 | 🧩  Managed Nodes mit Ad-hoc-Befehlen testen                | Anfänger        | [Labor Starten](https://labex.io/de/labs/test-managed-nodes-with-ad-hoc-commands-664189?course=rhce-ansible-prep)            |
|       4 | 🧩  Ziel-Hosts mit Mustern und Limits                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/target-hosts-with-patterns-and-limits-664188?course=rhce-ansible-prep)              |
|       5 | 🧩  Basisdateien auf verwalteten Knoten bereitstellen       | Anfänger        | [Labor Starten](https://labex.io/de/labs/deploy-baseline-files-to-managed-nodes-664177?course=rhce-ansible-prep)             |

#### Playbook-Logik und Zuverlässigkeit

|   Index | Name                                                    | Schwierigkeit   | Übung                                                                                                                    |
|---------|---------------------------------------------------------|-----------------|--------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Idempotente Playbooks mit Standardmodulen schreiben  | Anfänger        | [Labor Starten](https://labex.io/de/labs/write-idempotent-playbooks-with-common-modules-664195?course=rhce-ansible-prep) |
|       2 | 🧩  Dienste mit Handlern verwalten                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/manage-services-with-handlers-664181?course=rhce-ansible-prep)                  |
|       3 | 🧩  Verwendung von Schleifen, Fakten und Bedingungen     | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-loops-facts-and-conditionals-664192?course=rhce-ansible-prep)               |
|       4 | 🧩  Ergebnisse registrieren und Aufgabenstatus steuern   | Anfänger        | [Labor Starten](https://labex.io/de/labs/register-results-and-control-task-status-664184?course=rhce-ansible-prep)       |
|       5 | 🧩  Fehlerbehandlung mit Blocks, Rescue und Always       | Anfänger        | [Labor Starten](https://labex.io/de/labs/handle-failures-with-blocks-and-rescue-664178?course=rhce-ansible-prep)         |
|       6 | 🧩  Idempotenz von Playbooks validieren                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/validate-playbook-idempotence-664194?course=rhce-ansible-prep)                  |
|       7 | 🧩  Fehlerbehebung bei YAML, Jinja2 und Modul-Parametern | Anfänger        | [Labor Starten](https://labex.io/de/labs/troubleshoot-yaml-jinja2-and-module-errors-664190?course=rhce-ansible-prep)     |

#### Variablen, Vorlagen, Rollen und Collections

|   Index | Name                                                                  | Schwierigkeit   | Übung                                                                                                                   |
|---------|-----------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Strukturierung von Playbooks mit Imports und Includes              | Anfänger        | [Labor Starten](https://labex.io/de/labs/structure-playbooks-with-imports-and-includes-664187?course=rhce-ansible-prep) |
|       2 | 🧩  Gruppenvariablen, Hostvariablen und Fakten verwalten               | Anfänger        | [Labor Starten](https://labex.io/de/labs/manage-group-host-variables-and-facts-664180?course=rhce-ansible-prep)         |
|       3 | 🧩  Benutzerdefinierte Fakten erstellen und verwenden                  | Anfänger        | [Labor Starten](https://labex.io/de/labs/create-and-use-custom-facts-664175?course=rhce-ansible-prep)                   |
|       4 | 🧩  Konfigurationsdateien mit Templates rendern                        | Anfänger        | [Labor Starten](https://labex.io/de/labs/render-configuration-files-with-templates-664185?course=rhce-ansible-prep)     |
|       5 | 🧩  Secrets schützen und verwenden mit Ansible Vault                   | Anfänger        | [Labor Starten](https://labex.io/de/labs/protect-and-use-secrets-with-ansible-vault-664183?course=rhce-ansible-prep)    |
|       6 | 🧩  Probleme bei der Variablenrangfolge debuggen                       | Anfänger        | [Labor Starten](https://labex.io/de/labs/debug-variable-precedence-issues-664176?course=rhce-ansible-prep)              |
|       7 | 🧩  Erstellen und Anwenden einer wiederverwendbaren Rolle              | Anfänger        | [Labor Starten](https://labex.io/de/labs/create-and-apply-a-reusable-role-664174?course=rhce-ansible-prep)              |
|       8 | 🧩  Rollen und Content-Collections installieren                        | Anfänger        | [Labor Starten](https://labex.io/de/labs/install-roles-and-content-collections-664179?course=rhce-ansible-prep)         |
|       9 | 🧩  Verwendung von Collection-Inhalten in einem vollständigen Workflow | Anfänger        | [Labor Starten](https://labex.io/de/labs/use-collection-content-in-a-complete-workflow-664191?course=rhce-ansible-prep) |

#### Angewandte RHEL-Automatisierungs-Workflows

|   Index | Name                                                                | Schwierigkeit   | Übung                                                                                                                     |
|---------|---------------------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------|
|       1 | 🧩  Automatisierung von Paketen, Diensten und Firewalls              | Anfänger        | [Labor Starten](https://labex.io/de/labs/automate-packages-services-and-firewalls-664166?course=rhce-ansible-prep)        |
|       2 | 🧩  Automatisierung von Benutzern, Dateien und geplanten Aufgaben    | Anfänger        | [Labor Starten](https://labex.io/de/labs/automate-users-files-and-scheduled-tasks-664169?course=rhce-ansible-prep)        |
|       3 | 🧩  Speicher- und Mount-Konfiguration automatisieren                 | Anfänger        | [Labor Starten](https://labex.io/de/labs/automate-storage-and-mount-configuration-664168?course=rhce-ansible-prep)        |
|       4 | 🧩  Sicherheitskonfigurationen auf verwalteten Knoten automatisieren | Anfänger        | [Labor Starten](https://labex.io/de/labs/automate-security-settings-across-managed-nodes-664167?course=rhce-ansible-prep) |

### 2. [RHCE in Ansible Übungsprüfung 01](https://labex.io/de/courses/rhce-ansible-practice-exam-01)

Eine praxisorientierte RHCE-Übungsprüfung für Ansible mit 14 unabhängigen Automatisierungs-Herausforderungen. Die Themen umfassen die Einrichtung von Ansible-Projekten, Inventories, Playbooks, Variablen, Templates, Vault, Rollen, Collections sowie die Automatisierung der RHEL-Administration.

[Kurs Starten](https://labex.io/de/courses/rhce-ansible-practice-exam-01) · Labs: 14

#### Ansible-Umgebung, Navigation und Versionsverwaltung

|   Index | Name                                                             | Schwierigkeit   | Übung                                                                                                                                          |
|---------|------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Initialisierung eines Automatisierungsprojekt-Repositorys     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-initialize-an-automation-project-repository-664410?course=rhce-ansible-practice-exam-01)     |
|       2 | 🎯  Ansible und Navigator-Ausführung konfigurieren                | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-configure-ansible-and-navigator-execution-664406?course=rhce-ansible-practice-exam-01)       |
|       3 | 🎯  Verwendung der Offline-Dokumentation für einen Modul-Workflow | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-use-offline-documentation-for-a-module-workflow-664416?course=rhce-ansible-practice-exam-01) |

#### Inventare und verwaltete Knoten

|   Index | Name                                                                | Schwierigkeit   | Übung                                                                                                                                           |
|---------|---------------------------------------------------------------------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Inventory-Gruppen und Host-Variablen erstellen                   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-build-inventory-groups-and-host-variables-664405?course=rhce-ansible-practice-exam-01)        |
|       2 | 🎯  Zugriff auf verwaltete Knoten und Baseline-Dateien konfigurieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-configure-managed-node-access-and-baseline-files-664407?course=rhce-ansible-practice-exam-01) |

#### Plays, Playbooks, Module und Ablaufsteuerung

|   Index | Name                                                        | Schwierigkeit   | Übung                                                                                                                                         |
|---------|-------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Einen Dienst idempotent bereitstellen                    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-deploy-a-service-idempotently-664409?course=rhce-ansible-practice-exam-01)                  |
|       2 | 🎯  Host-spezifische Logik mit Schleifen und Fakten anwenden | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-apply-host-specific-logic-with-loops-and-facts-664403?course=rhce-ansible-practice-exam-01) |
|       3 | 🎯  Ein fehlerhaftes Playbook wiederherstellen               | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-recover-a-faulty-playbook-664413?course=rhce-ansible-practice-exam-01)                      |

#### Variablen, Fakten, Templates, Vault und Inhalte

|   Index | Name                                                        | Schwierigkeit   | Übung                                                                                                                                        |
|---------|-------------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Hostspezifische Konfigurationsvorlagen rendern           | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-render-host-specific-configuration-templates-664414?course=rhce-ansible-practice-exam-01)  |
|       2 | 🎯  Dienste-Geheimnisse mit Vault schützen und bereitstellen | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-protect-and-deploy-service-secrets-with-vault-664412?course=rhce-ansible-practice-exam-01) |
|       3 | 🎯  Fakten und Variablen-Präzedenz auflösen                  | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-resolve-facts-and-variable-precedence-664415?course=rhce-ansible-practice-exam-01)         |

#### Rollen, Collections und Automatisierung von RHCSA-Aufgaben

|   Index | Name                                                                   | Schwierigkeit   | Übung                                                                                                                                    |
|---------|------------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Erstellen einer Webserver-Rolle                                     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-create-a-web-server-role-664408?course=rhce-ansible-practice-exam-01)                  |
|       2 | 🎯  Installieren und Verwenden von bereitgestellten Collection-Inhalten | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-install-and-use-staged-collection-content-664411?course=rhce-ansible-practice-exam-01) |
|       3 | 🎯  Automatisierung des Administrationsstatus für mehrere Hosts         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-automate-multi-host-administration-state-664404?course=rhce-ansible-practice-exam-01)  |

### 3. [RHCE in Ansible Übungsprüfung 02](https://labex.io/de/courses/rhce-ansible-practice-exam-02)

Eine zweite praxisorientierte RHCE in Ansible-Übungsprüfung mit 14 unabhängigen Automatisierungs-Herausforderungen. Diese decken Ansible-Konfiguration, Inventare, Playbook-Zuverlässigkeit, Templates, Vault, Rollen, Collections sowie die Automatisierung der RHEL-Administration ab.

[Kurs Starten](https://labex.io/de/courses/rhce-ansible-practice-exam-02) · Labs: 14

#### Ansible-Umgebung, Navigation und Versionsverwaltung

|   Index | Name                                                      | Schwierigkeit   | Übung                                                                                                                                        |
|---------|-----------------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Struktur eines Automatisierungs-Repositorys reparieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-repair-an-automation-repository-layout-664426?course=rhce-ansible-practice-exam-02)        |
|       2 | 🎯  Navigator für eine Staged Runtime konfigurieren        | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-configure-navigator-for-a-staged-runtime-664420?course=rhce-ansible-practice-exam-02)      |
|       3 | 🎯  Fehlerbehebung bei der Ansible-Konfigurationspriorität | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-troubleshoot-ansible-configuration-precedence-664429?course=rhce-ansible-practice-exam-02) |

#### Inventare und verwaltete Knoten

|   Index | Name                                                | Schwierigkeit   | Übung                                                                                                                            |
|---------|-----------------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Modellierung von Umgebungen im Inventory         | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-model-environments-in-inventory-664422?course=rhce-ansible-practice-exam-02)   |
|       2 | 🎯  Wiederherstellung der Managed-Node-Konnektivität | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-restore-managed-node-connectivity-664427?course=rhce-ansible-practice-exam-02) |

#### Plays, Playbooks, Module und Ablaufsteuerung

|   Index | Name                                                 | Schwierigkeit   | Übung                                                                                                                                       |
|---------|------------------------------------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Handler für Multi-Service-Updates konfigurieren   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-configure-handlers-for-multi-service-updates-664419?course=rhce-ansible-practice-exam-02) |
|       2 | 🎯  Wiederherstellung nach Paket- und Aufgabenfehlern | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-recover-from-package-and-task-failures-664424?course=rhce-ansible-practice-exam-02)       |
|       3 | 🎯  Bedingte Firewall- und Serviceregeln erstellen    | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-build-conditional-firewall-and-service-rules-664418?course=rhce-ansible-practice-exam-02) |

#### Variablen, Fakten, Templates, Vault und Inhalte

|   Index | Name                                                                             | Schwierigkeit   | Übung                                                                                                                                          |
|---------|----------------------------------------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Anwendungskonfigurationen aus Vorlagen generieren                             | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-generate-application-configs-from-templates-664421?course=rhce-ansible-practice-exam-02)     |
|       2 | 🎯  Vault-geschützte Anmeldedaten rotieren                                        | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-rotate-vault-protected-credentials-664428?course=rhce-ansible-practice-exam-02)              |
|       3 | 🎯  Benutzerdefinierte Fakten veröffentlichen und Variablen-Overrides korrigieren | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-publish-custom-facts-and-fix-variable-overrides-664423?course=rhce-ansible-practice-exam-02) |

#### Rollen, Collections und Automatisierung von RHCSA-Aufgaben

|   Index | Name                                                                        | Schwierigkeit   | Übung                                                                                                                                               |
|---------|-----------------------------------------------------------------------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|       1 | 🎯  Refactoring eines monolithischen Playbooks in Rollen                     | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-refactor-a-monolithic-playbook-into-roles-664425?course=rhce-ansible-practice-exam-02)            |
|       2 | 🎯  Sammlungsinhalte für die Systemkonfiguration verwenden                   | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-use-collection-content-for-system-configuration-664430?course=rhce-ansible-practice-exam-02)      |
|       3 | 🎯  Automatisierung von Repository-, Web-, Benutzer- und Zeitplan-Compliance | Anfänger        | [Challenge Starten](https://labex.io/de/labs/rhel-automate-repository-web-user-and-schedule-compliance-664417?course=rhce-ansible-practice-exam-02) |

## Über LabEx

[LabEx](https://labex.io) ist eine interaktive, praktische Lernplattform für Programmierung und Technologie. Sie kombiniert Labore, KI-Unterstützung und virtuelle Maschinen für eine videofreie, praktische Lernerfahrung. Mit einem strikten 'Learning by Doing'-Ansatz, interaktiven Online-Umgebungen im Browser mit automatisierten Schritt-für-Schritt-Überprüfungen, strukturierter Inhaltsorganisation mit dem Skill-Tree-basierten System, und einer wachsenden Lernressource von 30 Skill Trees und über 6.000 Laboren, [LabEx](https://labex.io) bietet umfassende praktische Bildung. Die Plattform umfasst den Lernassistenten Labby, aufgebaut auf den neuesten KI-Modellen, der eine konversationelle Lernerfahrung bietet.

