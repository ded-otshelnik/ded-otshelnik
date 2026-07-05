# Hi there! 👋 I'm Andrey Budnikov

---

## Основные компетенции

### DevOps / SRE

[![DevOps / SRE](https://skillicons.dev/icons?i=linux,docker,k8s,prometheus,grafana,gitlab&size=30)](https://skillicons.dev)

#### Навыки и инструменты

- **Системное администрирование**: Linux (Ubuntu, AlmaLinux, Centos), shell-скрипты (Bash);
- **Контейнеризация**: Docker (оптимизация образов, безопасность, Docker Compose, локальный registry), containerd;
- **Kubernetes**: развертывание кластеров на виртуальных машинах (kubeadm, Kubespray), настройка сетей (Calico, Flannel), Helm, Network Policies, NFS, Ingress (NGINX Ingress Controller, MetalLB);
- **Мониторинг**: сбор метрик (стек Prometheus\VictoriaMetrics), визуализация (Grafana);
- **Логирование**: сбор логов (Vector.dev, Grafana Alloy, Fluentbit), хранение (Grafana Loki, Elasticsearch, VictoriaLogs);
- **Трассировка**: инструменты (OpenTelemetry SDK клиенты + OpenTelemetry Collector), хранение (Grafana Tempo);
- **CI/CD**: Github Actions, GitLab CI/CD (настройка пайплайнов, деплой приложений), подключение Gitlab-раннеров к Kubernetes;
- **Хранение секретов**: HashiCorp Vault, Cert-manager, External Secrets Operator; развертывание Vault PKI и настройка TLS-сертификатов и Certificate Authority;
- **ArgoCD**: развертывание приложений из Git-репозиториев, управление проектами, sync-wave, App-of-apps;
- **Управление конфигурацией**: Ansible, Kubespray;
- **Брокеры сообщений**: Apache Kafka, ZeroMQ;

#### Проекты

- Реализован кластер Kubernetes для [онлайн-обработки данных эксперимента NICA/MPD](https://indico.jinr.ru/event/5789/contributions/36384/attachments/26036/46477/MMCP'2026.pdf). Кластер включает в себя подсистемы мониторинга (стек VictoriaMetrics/Prometheus), логирования (Vector.dev + VictoriaLogs), трассировки (OpenTelemetry Collector + Grafana Tempo), хранения секретов (HashiCorp Vault + ESO/Cert-manager), маршрутизации трафика (NGINX Ingress Controller). Деплой приложений осуществляется через ArgoCD на базе Helm-чартов, управление конфигурацией - Ansible + Kubespray.

### Разработка

[![Development](https://skillicons.dev/icons?i=python,cs,cpp,java,django,fastapi,spring,postgres&size=30)](https://skillicons.dev)

#### Навыки и инструменты

- **Языки программирования**: Python (Django, FastAPI, гибридные Python/C++ пакеты), C# (Windows Forms, ASP.NET Core), C/C++ (STL), Java (Spring Boot);
- **ORM-фреймворки**: Django ORM, SQLAlchemy, Hibernate;
- **Архитектура**: микросервисы, контейнеризация
- **Тестирование**: JUnit, PyTest, Tox, линтеры (black, flake8), Postman, pre-commit hooks;
- **Базы данных**: PostgreSQL, MongoDB;
- **Программные пакеты**: сборка и публикация пакетов (Scikit-build, setuptools, PyPI);

#### Проекты

- Реализован [pet-проект онлайн-магазина](https://github.com/ded-otshelnik/python_shop) на стеке Django. Проект запускается через Docker Compose, включая PostgreSQL, Nginx, а также микросервис на Django Rest Framework. Настроен простой HTTPS через self-signed сертификаты. Добавлена авторизация на базе OAuth (Google, Yandex). Стек: Django, Django Rest Framework, Django Allauth.

### Machine Learning / Data Science

[![Machine Learning / Data Science](https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow&size=30)](https://skillicons.dev)

#### Навыки и инструменты

- **ML-фреймворки**: PyTorch, TensorFlow + Keras, Scikit-Learn;
- **Data Science**: обработка и анализ данных (Pandas, NumPy), визуализация данных (Matplotlib, Seaborn, Plotly);
- **Численные методы**: высокопроизводительные вычисления (Numba, JAX), параллельные вычисления (OpenMP, MPI, CUDA);

#### Проекты

- Разработан [программный пакет](https://github.com/ded-otshelnik/nnmd) на Python для создания машинно-обучаемых потенциалов для молекулярно-динамических экспериментов на суперкомпьютерах. Реализовал нейронную сеть высокой размерности, ее обучение/применение в молекулярно-динамическом эксперименте. Стек: PyTorch, Pybind11, CUDA;
- Сконструирована глубокая нейронная сеть и база данных по масс-спектрометрии для обнаружения объектов на снимках растений для фармацевтов. Сеть реализована на основе YOLOv11 модели для обнаружения различных признаков растений, которые исследуются во время разработки новых лекарств. Стек: PyTorch, Ultralytics, SQLAlchemy, psycopg;

---

### Контакты

- Linkedin: <https://www.linkedin.com/in/andrey-budnikov/>
- Email: <budnikov.andrey777@gmail.com>
