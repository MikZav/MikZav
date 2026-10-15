# Михаил Заворин

**DevOps-инженер / системный администратор** · Барнаул

Строю и сопровождаю инфраструктуру на Linux: контейнеризация сервисов, мониторинг и алертинг, почтовые системы, сети и VPN, автоматизация рутины на Python и Bash. Развиваюсь в направлении DevOps: CI/CD, IaC, оркестрация.

💻 [github.com/MikZav](https://github.com/MikZav)

---

## Опыт работы

### Stutzen — DevOps / системный администратор
*04.2025 — настоящее время*

- Сопровождение парка серверов на **Ubuntu Server 24.04**; все сервисы в **Docker Compose** с закреплёнными сетями и политиками автозапуска
- Развернул и поддерживаю **корпоративный почтовый сервер** (Postfix, Dovecot на базе docker-mailserver, веб-почта Roundcube); HTTPS через nginx-proxy и Let's Encrypt
- Построил **систему мониторинга**: Prometheus, Grafana, Alertmanager, node/blackbox/postfix exporters; оповещения в Bitrix24 через собственный webhook-адаптер (Python, Flask)
- Участвую в разработке и деплое внутреннего веб-приложения **autozakaz** (Python, FastAPI, PostgreSQL, Docker): ведение репозитория на GitHub, работа через feature-ветки и pull request'ы
- Автоматизировал отчётность: Python-скрипты по cron формируют Excel-отчёты из MySQL и рассылают их по почте, плюс почасовой алерт о задержках
- Сети и безопасность: VPN-инфраструктура на **Xray / VLESS Reality** (3x-ui), маршрутизация трафика серверов через туннель с исключениями (policy routing, iptables/connmark)
- Резервное копирование серверов через UrBackup

### V4Y — спортивные трансляции · инфраструктура и разработка
*20XX — настоящее время*

- Проводим онлайн-трансляции городских соревнований (OBS → VK)
- Разработал **веб-титровалку** для эфира: операторская панель, графика участников, афиши и спонсорский модуль, которые подключаются в OBS как browser source
- Хостинг проекта: Docker Compose (Caddy, Python-бэкенд, PHP, PostgreSQL), автоматический HTTPS
- Автоматизация пост-продакшна: нарезка записи эфира по участникам

---

## Стек

**ОС и администрирование:** Linux (Ubuntu Server), systemd, cron, Bash

**Контейнеры:** Docker, Docker Compose

**Веб и прокси:** Nginx, Caddy, Let's Encrypt

**Мониторинг:** Prometheus, Grafana, Alertmanager, exporters

**Почта:** Postfix, Dovecot, Roundcube

**Базы данных:** PostgreSQL, MySQL / MariaDB

**Языки:** Python (FastAPI, Flask), Bash, SQL

**Сети:** iptables, policy routing, VPN (Xray, sing-box)

**Git:** Git, GitHub (PR workflow)

**Сейчас изучаю:** CI/CD (GitHub Actions), Ansible, Kubernetes
