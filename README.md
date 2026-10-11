# 🏢 BMS API (Building Management System)

[![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge&logo=openjdk)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=for-the-badge&logo=spring)](https://spring.io/projects/spring-boot)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker)](https://www.docker.com/)

API backend em **Java / Spring Boot** para centralização e controle inteligente de sistemas prediais (energia, climatização, iluminação e acessos).

---

## 📌 Sobre o Projeto

O **BMS API** é o núcleo de processamento do sistema de **Automação Predial Integrada (BMS)**. Ele centraliza comandos de telemetria e controle de dispositivos IoT espalhados pelo edifício, permitindo redução do consumo energético, monitoramento de ocupação e automação de rotinas em prédios comerciais e residenciais.

## 🚀 Funcionalidades

- ⚡ **Gestão Energética:** Monitoramento de consumo de energia por setor e horário.
- ❄️ **Controle de Climatização (HVAC):** Acionamento automatizado de ar-condicionado baseado em temperatura e ocupação.
- 💡 **Iluminação Inteligente:** Programação de circuitos de lâmpadas com dimerização e sensores de presença.
- 🚪 **Controle de Acesso:** Auditoria e autorização de entradas e saídas de ambientes monitorados.

## 🛠️ Tecnologias Utilizadas

- **Java 17 (LTS)**
- **Spring Boot 3** (Spring Web, Spring Security, Spring Data JPA)
- **PostgreSQL / H2 Database**
- **Docker & Dockerfile** para containerização

## ⚙️ Como Executar Localmente

### Com Maven
```bash
git clone https://github.com/IuryAlmeidaDev/bms-api.git
cd bms-api
./mvnw clean spring-boot:run
```

### Com Docker
```bash
docker build -t bms-api .
docker run -p 8080:8080 bms-api
```

---

## 👤 Autor

Desenvolvido por **[Iury Almeida](https://github.com/IuryAlmeidaDev)**.
