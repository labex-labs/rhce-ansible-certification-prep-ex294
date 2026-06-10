# Formación RHCE in Ansible Certification Prep Path

## Idiomas

🇺🇸 [English](README.md) 🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 

<div align="center">
<a href="https://labex.io/es/learn/rhce-ansible"><img width="128px" src="https://file.labex.io/path/yhXXtMLd7wiu.png"></a>
</div>

[![Start-Learning](https://img.shields.io/badge/Iniciar-Ruta-whitesmoke?style=for-the-badge)](https://labex.io/es/learn/rhce-ansible)

Prepare for the Red Hat Certified Engineer in Ansible exam (EX294) with a structured, hands-on learning path. This roadmap focuses on Ansible Automation Platform workflows, Git and ansible-navigator, inventories and managed nodes, idempotent playbooks, variables, facts, templates, Vault, roles, content collections, and automating standard RHCSA administration tasks on RHEL, plus performance-based exam tasks and real-world enterprise scenarios. Guided RHCE in Ansible courses, labs, and practice exam practice will be added over time to help you build skills aligned with EX294 objectives.

**Cursos**: 3 · **Laboratorios**: 58

## Cursos

### 1. [Preparación para RHCE Ansible (EX294)](https://labex.io/es/courses/rhce-ansible-prep)

Un curso de preparación para RHCE Ansible ideal para principiantes, que incluye 30 experimentos guiados que abarcan desde los fundamentos de proyectos Ansible hasta inventarios, playbooks, roles, colecciones y automatización aplicada en RHEL.

[Iniciar Curso](https://labex.io/es/courses/rhce-ansible-prep) · Laboratorios: 30

#### Fundamentos de proyectos de Ansible

|   Índice | Nombre                                                               | Dificultad   | Práctica                                                                                                                               |
|----------|----------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Preparar un proyecto de Ansible con Git                           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/prepare-an-ansible-project-with-git-664182?course=rhce-ansible-prep)                    |
|        2 | 🧩  Configurar ansible.cfg y los valores predeterminados del proyecto | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-ansible-cfg-and-project-defaults-664171?course=rhce-ansible-prep)             |
|        3 | 🧩  Configurar ansible-navigator y entornos de ejecución              | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-ansible-navigator-and-execution-environments-664172?course=rhce-ansible-prep) |
|        4 | 🧩  Ejecutar e inspeccionar Playbooks con Navigator                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/run-and-inspect-playbooks-with-navigator-664186?course=rhce-ansible-prep)               |
|        5 | 🧩  Uso de la documentación offline de Ansible                        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-offline-ansible-documentation-664193?course=rhce-ansible-prep)                      |

#### Inventario, conectividad y segmentación

|   Índice | Nombre                                                | Dificultad   | Práctica                                                                                                                           |
|----------|-------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Crear inventarios estáticos con grupos y variables | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/build-static-inventories-with-groups-and-variables-664170?course=rhce-ansible-prep) |
|        2 | 🧩  Configurar claves SSH y escalada de privilegios    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/configure-ssh-keys-and-privilege-escalation-664173?course=rhce-ansible-prep)        |
|        3 | 🧩  Probar nodos gestionados con comandos ad hoc       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/test-managed-nodes-with-ad-hoc-commands-664189?course=rhce-ansible-prep)            |
|        4 | 🧩  Segmentación de hosts con patrones y límites       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/target-hosts-with-patterns-and-limits-664188?course=rhce-ansible-prep)              |
|        5 | 🧩  Implementar archivos base en nodos gestionados     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/deploy-baseline-files-to-managed-nodes-664177?course=rhce-ansible-prep)             |

#### Lógica y fiabilidad de los Playbooks

|   Índice | Nombre                                                        | Dificultad   | Práctica                                                                                                                       |
|----------|---------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Escribir Playbooks idempotentes con módulos comunes        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/write-idempotent-playbooks-with-common-modules-664195?course=rhce-ansible-prep) |
|        2 | 🧩  Gestionar servicios con Handlers                           | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/manage-services-with-handlers-664181?course=rhce-ansible-prep)                  |
|        3 | 🧩  Uso de bucles, hechos y condicionales                      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-loops-facts-and-conditionals-664192?course=rhce-ansible-prep)               |
|        4 | 🧩  Registrar resultados y controlar el estado de las tareas   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/register-results-and-control-task-status-664184?course=rhce-ansible-prep)       |
|        5 | 🧩  Manejo de fallos con bloques y rescue                      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/handle-failures-with-blocks-and-rescue-664178?course=rhce-ansible-prep)         |
|        6 | 🧩  Validar la idempotencia de un Playbook                     | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/validate-playbook-idempotence-664194?course=rhce-ansible-prep)                  |
|        7 | 🧩  Solución de problemas de YAML, Jinja2 y errores de módulos | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/troubleshoot-yaml-jinja2-and-module-errors-664190?course=rhce-ansible-prep)     |

#### Variables, plantillas, roles y colecciones

|   Índice | Nombre                                                             | Dificultad   | Práctica                                                                                                                      |
|----------|--------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Estructurar Playbooks con Imports e Includes                    | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/structure-playbooks-with-imports-and-includes-664187?course=rhce-ansible-prep) |
|        2 | 🧩  Gestionar variables de grupo, de host y hechos (facts)          | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/manage-group-host-variables-and-facts-664180?course=rhce-ansible-prep)         |
|        3 | 🧩  Crear y utilizar hechos personalizados                          | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/create-and-use-custom-facts-664175?course=rhce-ansible-prep)                   |
|        4 | 🧩  Renderizar archivos de configuración con plantillas             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/render-configuration-files-with-templates-664185?course=rhce-ansible-prep)     |
|        5 | 🧩  Proteger y utilizar secretos con Ansible Vault                  | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/protect-and-use-secrets-with-ansible-vault-664183?course=rhce-ansible-prep)    |
|        6 | 🧩  Depurar problemas de precedencia de variables                   | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/debug-variable-precedence-issues-664176?course=rhce-ansible-prep)              |
|        7 | 🧩  Crear y aplicar un rol reutilizable                             | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/create-and-apply-a-reusable-role-664174?course=rhce-ansible-prep)              |
|        8 | 🧩  Instalar roles y colecciones de contenido                       | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/install-roles-and-content-collections-664179?course=rhce-ansible-prep)         |
|        9 | 🧩  Uso de contenido de colecciones en un flujo de trabajo completo | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/use-collection-content-in-a-complete-workflow-664191?course=rhce-ansible-prep) |

#### Flujos de trabajo de automatización aplicados en RHEL

|   Índice | Nombre                                                                | Dificultad   | Práctica                                                                                                                        |
|----------|-----------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🧩  Automatizar paquetes, servicios y firewalls                        | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/automate-packages-services-and-firewalls-664166?course=rhce-ansible-prep)        |
|        2 | 🧩  Automatización de usuarios, archivos y tareas programadas          | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/automate-users-files-and-scheduled-tasks-664169?course=rhce-ansible-prep)        |
|        3 | 🧩  Automatizar la configuración de almacenamiento y puntos de montaje | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/automate-storage-and-mount-configuration-664168?course=rhce-ansible-prep)        |
|        4 | 🧩  Automatizar configuraciones de seguridad en nodos gestionados      | Principiante | [Iniciar Laboratorio](https://labex.io/es/labs/automate-security-settings-across-managed-nodes-664167?course=rhce-ansible-prep) |

### 2. [Examen de práctica 01 de RHCE en Ansible](https://labex.io/es/courses/rhce-ansible-practice-exam-01)

Un examen de práctica práctico de RHCE en Ansible con 14 desafíos de automatización independientes que cubren la configuración de proyectos de Ansible, inventarios, playbooks, variables, plantillas, Vault, roles, colecciones y la automatización de la administración de RHEL.

[Iniciar Curso](https://labex.io/es/courses/rhce-ansible-practice-exam-01) · Laboratorios: 14

#### Entorno, navegación y control de versiones de Ansible

|   Índice | Nombre                                                              | Dificultad   | Práctica                                                                                                                                     |
|----------|---------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Inicializar un repositorio de proyecto de automatización         | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-initialize-an-automation-project-repository-664410?course=rhce-ansible-practice-exam-01)     |
|        2 | 🎯  Configurar la ejecución de Ansible y Navigator                   | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-configure-ansible-and-navigator-execution-664406?course=rhce-ansible-practice-exam-01)       |
|        3 | 🎯  Uso de documentación offline para un flujo de trabajo de módulos | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-use-offline-documentation-for-a-module-workflow-664416?course=rhce-ansible-practice-exam-01) |

#### Inventarios y nodos gestionados

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                                      |
|----------|----------------------------------------------------------------|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Construir grupos de inventario y variables de host          | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-build-inventory-groups-and-host-variables-664405?course=rhce-ansible-practice-exam-01)        |
|        2 | 🎯  Configurar el acceso al nodo gestionado y los archivos base | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-configure-managed-node-access-and-baseline-files-664407?course=rhce-ansible-practice-exam-01) |

#### Plays, Playbooks, módulos y control de flujo

|   Índice | Nombre                                                    | Dificultad   | Práctica                                                                                                                                    |
|----------|-----------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Desplegar un servicio de forma idempotente             | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-deploy-a-service-idempotently-664409?course=rhce-ansible-practice-exam-01)                  |
|        2 | 🎯  Aplicar lógica específica del host con bucles y hechos | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-apply-host-specific-logic-with-loops-and-facts-664403?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  Recuperar un Playbook defectuoso                       | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-recover-a-faulty-playbook-664413?course=rhce-ansible-practice-exam-01)                      |

#### Variables, hechos (facts), plantillas, Vault y contenido

|   Índice | Nombre                                                               | Dificultad   | Práctica                                                                                                                                   |
|----------|----------------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Renderizar plantillas de configuración específicas para cada host | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-render-host-specific-configuration-templates-664414?course=rhce-ansible-practice-exam-01)  |
|        2 | 🎯  Proteger y desplegar secretos de servicio con Vault               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-protect-and-deploy-service-secrets-with-vault-664412?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  Resolver hechos y precedencia de variables                        | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-resolve-facts-and-variable-precedence-664415?course=rhce-ansible-practice-exam-01)         |

#### Roles, colecciones y automatización de tareas RHCSA

|   Índice | Nombre                                                        | Dificultad   | Práctica                                                                                                                               |
|----------|---------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Crear un rol de servidor web                               | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-create-a-web-server-role-664408?course=rhce-ansible-practice-exam-01)                  |
|        2 | 🎯  Instalar y utilizar contenido de una colección almacenada  | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-install-and-use-staged-collection-content-664411?course=rhce-ansible-practice-exam-01) |
|        3 | 🎯  Automatizar el estado de administración de múltiples hosts | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-automate-multi-host-administration-state-664404?course=rhce-ansible-practice-exam-01)  |

### 3. [Examen de práctica 02 de RHCE en Ansible](https://labex.io/es/courses/rhce-ansible-practice-exam-02)

Un segundo examen de práctica práctico de RHCE en Ansible que incluye 14 desafíos de automatización independientes, los cuales abarcan configuración de Ansible, inventarios, fiabilidad de playbooks, plantillas, Vault, roles, colecciones y automatización de la administración de RHEL.

[Iniciar Curso](https://labex.io/es/courses/rhce-ansible-practice-exam-02) · Laboratorios: 14

#### Entorno, navegación y control de versiones de Ansible

|   Índice | Nombre                                                         | Dificultad   | Práctica                                                                                                                                   |
|----------|----------------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Reparar la estructura de un repositorio de automatización   | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-repair-an-automation-repository-layout-664426?course=rhce-ansible-practice-exam-02)        |
|        2 | 🎯  Configurar Navigator para un entorno de ejecución preparado | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-configure-navigator-for-a-staged-runtime-664420?course=rhce-ansible-practice-exam-02)      |
|        3 | 🎯  Solucionar la precedencia de configuración de Ansible       | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-troubleshoot-ansible-configuration-precedence-664429?course=rhce-ansible-practice-exam-02) |

#### Inventarios y nodos gestionados

|   Índice | Nombre                                           | Dificultad   | Práctica                                                                                                                       |
|----------|--------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Modelado de entornos en el inventario         | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-model-environments-in-inventory-664422?course=rhce-ansible-practice-exam-02)   |
|        2 | 🎯  Restaurar la conectividad del nodo gestionado | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-restore-managed-node-connectivity-664427?course=rhce-ansible-practice-exam-02) |

#### Plays, Playbooks, módulos y control de flujo

|   Índice | Nombre                                                                | Dificultad   | Práctica                                                                                                                                  |
|----------|-----------------------------------------------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Configurar manejadores para actualizaciones de servicios múltiples | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-configure-handlers-for-multi-service-updates-664419?course=rhce-ansible-practice-exam-02) |
|        2 | 🎯  Recuperación ante fallos de paquetes y tareas                      | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-recover-from-package-and-task-failures-664424?course=rhce-ansible-practice-exam-02)       |
|        3 | 🎯  Crear reglas condicionales de firewall y servicios                 | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-build-conditional-firewall-and-service-rules-664418?course=rhce-ansible-practice-exam-02) |

#### Variables, hechos (facts), plantillas, Vault y contenido

|   Índice | Nombre                                                                | Dificultad   | Práctica                                                                                                                                     |
|----------|-----------------------------------------------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Generar configuraciones de aplicaciones a partir de plantillas     | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-generate-application-configs-from-templates-664421?course=rhce-ansible-practice-exam-02)     |
|        2 | 🎯  Rotar credenciales protegidas por Vault                            | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-rotate-vault-protected-credentials-664428?course=rhce-ansible-practice-exam-02)              |
|        3 | 🎯  Publicar hechos personalizados y corregir anulaciones de variables | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-publish-custom-facts-and-fix-variable-overrides-664423?course=rhce-ansible-practice-exam-02) |

#### Roles, colecciones y automatización de tareas RHCSA

|   Índice | Nombre                                                                       | Dificultad   | Práctica                                                                                                                                          |
|----------|------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|        1 | 🎯  Refactorizar un Playbook monolítico en roles                              | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-refactor-a-monolithic-playbook-into-roles-664425?course=rhce-ansible-practice-exam-02)            |
|        2 | 🎯  Uso de contenido de colecciones para la configuración del sistema         | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-use-collection-content-for-system-configuration-664430?course=rhce-ansible-practice-exam-02)      |
|        3 | 🎯  Automatizar el cumplimiento de repositorios, web, usuarios y programación | Principiante | [Iniciar Desafío](https://labex.io/es/labs/rhel-automate-repository-web-user-and-schedule-compliance-664417?course=rhce-ansible-practice-exam-02) |

## Acerca de LabEx

[LabEx](https://labex.io) es una plataforma de aprendizaje interactiva y práctica dedicada a la programación y la tecnología. Combina laboratorios, asistencia de IA y máquinas virtuales para proporcionar una experiencia de aprendizaje práctica sin videos. Con un enfoque estricto de 'Aprender Haciendo', entornos en línea interactivos dentro del navegador con verificaciones paso a paso automatizadas, organización de contenido estructurada con el sistema basado en Árbol de Habilidades, y un recurso de aprendizaje en crecimiento de 30 Árboles de Habilidades y más de 6,000 Laboratorios, LabEx ofrece educación práctica integral. La plataforma incluye al asistente de aprendizaje Labby, construido sobre los últimos modelos de IA, que proporciona una experiencia de aprendizaje conversacional.

