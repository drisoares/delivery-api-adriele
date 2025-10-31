# Delivery Tech API

Sistema de delivery desenvolvido com Spring Boot e Java 21.

## 🚀 Tecnologias
- **Java 21 LTS** (versão mais recente)
- Spring Boot 3.2.x
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## ⚡ Recursos Modernos Utilizados
- Records (Java 14+)
- Text Blocks (Java 15+)
- Pattern Matching (Java 17+)
- Virtual Threads (Java 21)

## 🏃‍♂️ Como executar
1. **Pré-requisitos:** JDK 21 instalado
2. Clone o repositório
```bash
git clone https://github.com/drisoares/delivery-api-adriele.git
cd delivery-api-adriele
```
3. Execute: `./mvnw spring-boot:run` (Linux/Mac) ou `.\mvnw.cmd spring-boot:run` (Windows)
4. Acesse: http://localhost:8080/health

## 📋 Endpoints
- GET /health - Status da aplicação (inclui versão Java)
- GET /info - Informações da aplicação
- GET /h2-console - Console do banco H2

## 🔧 Configuração
- Porta: 8080
- Banco: H2 em memória
- Profile: development
- Console H2: http://localhost:8080/h2-console
  - JDBC URL: `jdbc:h2:mem:deliverydb`
  - Username: `sa`
  - Password: (vazio)

## 📁 Estrutura do Projeto
```
src/
├── main/
│   ├── java/com/deliverytech/delivery/
│   │   ├── DeliveryApiApplication.java     # Classe principal
│   │   └── HealthController.java           # Controller de health check
│   └── resources/
│       └── application.properties          # Configurações da aplicação
└── test/
    └── java/com/deliverytech/delivery/
        └── DeliveryApiApplicationTests.java
```

## 🎯 Funcionalidades Implementadas
- ✅ Configuração Spring Boot com JDK 21
- ✅ Health Check endpoints
- ✅ Integração com banco H2
- ✅ DevTools para hot reload
- ✅ Console H2 para desenvolvimento
- ✅ Logs estruturados

## 👨‍💻 Desenvolvedor
Adriele Soares  
Desenvolvido com JDK 21 e Spring Boot 3.2.x

## 📝 Notas de Desenvolvimento
Este projeto foi desenvolvido como parte de um exercício prático de desenvolvimento de APIs REST com Spring Boot, utilizando as mais recentes funcionalidades do Java 21.