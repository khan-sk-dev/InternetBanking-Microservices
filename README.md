<div align="center">
  <h1>🏦 InternetBanking-Microservices</h1>
  <p>Enterprise-Grade Banking Solution Built with Spring Boot Microservices</p>

  [![CI Status](https://github.com/khan-sk-dev/InternetBanking-Microservices/actions/workflows/gradle.yml/badge.svg)](https://github.com/khan-sk-dev/InternetBanking-Microservices/actions/workflows/gradle.yml)
  [![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.4-brightgreen.svg)](https://spring.io/projects/spring-boot)
  [![Java](https://img.shields.io/badge/Java-21-orange.svg)](https://adoptium.net/)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
</div>

## 🌟 Features & Highlights

<div align="center">
  <table>
    <tr>
      <td align="center">🔐<br><b>Secure Authentication</b></td>
      <td align="center">💸<br><b>Fund Transfers</b></td>
      <td align="center">💳<br><b>Bill Payments</b></td>
      <td align="center">📊<br><b>Transaction History</b></td>
    </tr>
    <tr>
      <td align="center">🔄<br><b>Real-time Updates</b></td>
      <td align="center">📱<br><b>Mobile Ready</b></td>
      <td align="center">🛡️<br><b>Fraud Detection</b></td>
      <td align="center">📈<br><b>Analytics</b></td>
    </tr>
  </table>
</div>

## 🏗️ Architecture Overview

<div align="center">
  <img src="https://javatodev.com/content/images/wordpress/2021/05/Microservices-Article-Banking-Core-Concept-1024x870.png" alt="Architecture Diagram" width="800"/>
</div>

## 🛠️ Tech Stack & Tools

<div align="center">

### Core Technologies
<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/gradle/gradle-plain.svg" alt="gradle" width="40"/>
</p>

### Data & Messaging
<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitmq" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40"/>
</p>

### DevOps & Monitoring
<p>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/prometheusio/prometheusio-icon.svg" alt="prometheus" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40"/>
</p>

### CI/CD & Version Control
<p>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="github" width="40"/>
  <img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40"/>
</p>
</div>

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/khan-sk-dev/InternetBanking-Microservices.git

# Navigate to project
cd InternetBanking-Microservices

# Start services
docker-compose up -d
```

## 🔌 Services & Ports

| Service | Port | Health Check |
|---------|------|-------------|
| Config Server | `8090` | [🔗](http://localhost:8090/health) |
| Service Registry | `8081` | [🔗](http://localhost:8081) |
| API Gateway | `8082` | [🔗](http://localhost:8082/health) |
| User Service | `8083` | [🔗](http://localhost:8083/health) |
| Fund Transfer | `8084` | [🔗](http://localhost:8084/health) |
| Core Banking | `8092` | [🔗](http://localhost:8092/health) |

## 🧪 Testing

### Default Test Credentials
```json
{
  "email": "ib_admin@javatodev.com",
  "password": "5V7huE3G86uB"
}
```

### API Documentation
[![Postman](https://img.shields.io/badge/Postman-Collection-orange?logo=postman)](https://www.postman.com/javatodev-api/workspace/javatodev-api-collections)

## 📈 Performance Monitoring

Access monitoring dashboards:
- Prometheus: `http://localhost:9090`
- Grafana: `http://localhost:3000`
- Zipkin: `http://localhost:9411`

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 👥 Contributors

<a href="https://github.com/khan-sk-dev/InternetBanking-Microservices/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=khan-sk-dev/InternetBanking-Microservices" />
</a>

---

<div align="center">
  <p>⭐ Star us on GitHub — it motivates us a lot!</p>
  <p>Made with ❤️ by developers for developers</p>
</div>