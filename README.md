# DKH Automation Work 4 🚀

**Advanced Multi-Workflow Automation Platform**

## 🎯 Project Overview

DKH Automation Work 4 เป็นระบบอัตโนมัติแบบครบวงจรที่ออกแบบมาเพื่อจัดการ workflows ที่ซับซ้อนในระบบต่างๆ รวมคุณสมบัติของ Java และ Go microservices พร้อม Kubernetes orchestration เพื่อให้ได้โซลูชัน production-ready

### 🌍 Supported Languages
- **English** (Default)
- **ไทย (Thai)** - Full Support ✅
- ขยายได้สำหรับภาษาอื่น ๆ

## 🏗️ Technology Stack

| องค์ประกอบ | เทคโนโลยี |
|-----------|----------|
| **Backend** | Java (Spring Boot 3.x) + Go (Gin/Echo) |
| **Orchestration** | Kubernetes + Docker |
| **Database** | PostgreSQL 13+ + MongoDB 5.0+ |
| **CI/CD** | GitHub Actions |
| **API** | RESTful + gRPC |
| **Message Queue** | RabbitMQ (Optional) |
| **Monitoring** | Prometheus + Grafana |

## 📁 โครงสร้างโปรเจค

```
dkh-automation-work-4/
├── java-services/                  # Java Spring Boot Services
│   ├── workflow-engine/            # Orchestration หลัก
│   ├── config-manager/             # จัดการ Configuration
│   ├── api-gateway/                # API Gateway
│   └── pom.xml
├── go-services/                    # Go Microservices
│   ├── verification-service/       # ตรวจสอบจากหลายแหล่ง
│   ├── integration-service/        # สำหรับ External Workflows
│   ├── scheduler/                  # Task Scheduling
│   └── go.mod
├── kubernetes/                     # K8s Configurations
│   ├── deployments/
│   ├── services/
│   └── configmaps/
├── docker/                         # Docker Setup
│   ├── Dockerfile.java
│   ├── Dockerfile.go
│   └── docker-compose.yml
├── database/                       # Database Setup
│   ├── postgresql/
│   ├── mongodb/
│   └── migrations/
├── docs/                          # Documentation
│   ├── en/                        # English
│   └── th/                        # ภาษาไทย
└── .github/workflows/             # GitHub Actions
```

## 🚀 Quick Start

### Prerequisites
```bash
- Docker & Docker Compose 20.10+
- Kubernetes 1.20+ (optional)
- Java 17+
- Go 1.20+
- PostgreSQL 13+
- MongoDB 5.0+
```

### Installation

```bash
# Clone repository
git clone https://github.com/rakthainet-DKH/dkh-automation-work-4.git
cd dkh-automation-work-4

# Checkout DKH branch
git checkout DKH

# Start services
docker-compose up -d

# Check services
docker-compose logs -f
```

## ✨ Key Features

### 🔄 Workflow Automation
- ✅ Automated workflow execution
- ✅ Manual configuration support
- ✅ External workflow integration & pulling
- ✅ Real-time execution monitoring
- ✅ Error handling & retry logic

### 👤 Management
- ✅ Single-person management interface
- ✅ User permission control (RBAC)
- ✅ Activity logging & audit trails
- ✅ Dashboard & reporting

### 🔍 Verification
- ✅ Multi-source verification system
- ✅ Data validation & integrity checks
- ✅ Health monitoring

### 🔐 Security
- ✅ JWT Authentication
- ✅ Role-based access control (RBAC)
- ✅ Encrypted data storage
- ✅ Audit logging
- ✅ Rate limiting

## 📚 Documentation

| ภาษา | ลิงค์ |
|------|-------|
| **English** | [README](./docs/en/README.md) \| [API](./docs/en/API.md) \| [Architecture](./docs/en/ARCHITECTURE.md) |
| **ไทย** | [README](./docs/th/README.md) \| [API](./docs/th/API.md) \| [Architecture](./docs/th/ARCHITECTURE.md) |

## 📊 Architecture

```
┌──────────────────────────────────────────────┐
│      API Gateway (Java Spring)               │
├──────────────────────────────────────────────┤
│ Workflow Engine │ Config Manager │ Auth      │
├──────────────────────────────────────────────┤
│ Scheduler │ Verification │ Integration       │
│ (Go Microservices)                          │
├──────────────────────────────────────────────┤
│ PostgreSQL │ MongoDB │ Redis Cache           │
└──────────────────────────────────────────────┘
```

## 🔄 CI/CD Pipeline

GitHub Actions automated workflows:
- ✅ Build & Test
- ✅ Docker image builds
- ✅ Security scanning
- ✅ Deployment to Kubernetes

## 💡 Development

### Branch Strategy
- `main` - Production-ready code
- `DKH` - Development branch
- `feature/*` - Feature branches

### Contributing
1. Create feature branch from `DKH`
2. Make your changes
3. Submit pull request
4. Pass all CI checks

## 📝 License

**Proprietary - DKH Automation System**

## 👤 Author

**rakthainet-DKH**
- GitHub: [@rakthainet-DKH](https://github.com/rakthainet-DKH)
- Repository: [dkh-automation-work-4](https://github.com/rakthainet-DKH/dkh-automation-work-4)

## 🤝 Support

- 📋 Issues: [GitHub Issues](https://github.com/rakthainet-DKH/dkh-automation-work-4/issues)
- 📚 Documentation: [Docs](./docs/)

---

**Status**: 🔄 In Development  
**Version**: 0.1.0-alpha  
**Last Updated**: 2026-06-17  
**Branch**: DKH  

⭐ **Star the repository if you find it helpful!**