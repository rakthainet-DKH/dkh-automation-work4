# DKH Automation Work 4 - เอกสารภาษาไทย

## ภาพรวม

DKH Automation Work 4 เป็นระบบอัตโนมัติแบบครบวงจรที่สร้างขึ้นด้วย Java และ Go microservices

## เริ่มต้นใช้งาน

ดู [README.md](../../README.md) หลักสำหรับคู่มือเริ่มต้นด่วน

## โครงสร้างเอกสาร

- [API Documentation](./API.md)
- [Architecture Guide](./ARCHITECTURE.md)
- [Deployment Guide](./DEPLOYMENT.md)

## คุณสมบัติหลัก

### อัตโนมัติ Workflow
- การเรียกใช้ workflow อัตโนมัติ
- การกำหนดค่าแบบด้วยตนเอง
- การรวมเข้า workflow ภายนอก
- การตรวจสอบแบบเรียลไทม์

### การจัดการ
- จัดการโดยบุคคลเดียว
- การควบคุมการเข้าถึงตามบทบาท
- การบันทึกกิจกรรม
- แdashboard

### ความปลอดภัย
- JWT authentication
- RBAC
- การเก็บข้อมูลแบบเข้ารหัส
- การ audit logging

## เทคโนโลยี

- Java (Spring Boot 3.x)
- Go (Gin/Echo)
- Kubernetes & Docker
- PostgreSQL & MongoDB
- GitHub Actions

## การสนับสนุน

สำหรับคำถามและปัญหา โปรดไปที่:
- [GitHub Issues](https://github.com/rakthainet-DKH/dkh-automation-work-4/issues)
- [GitHub Discussions](https://github.com/rakthainet-DKH/dkh-automation-work-4/discussions)
