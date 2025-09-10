# 🚀 AWS DevOps CI/CD Demo

This project showcases a full-stack DevOps pipeline using AWS, Terraform, GitHub Actions, EC2, CloudWatch, and SSM Parameter Store. It deploys a Node.js app automatically when code is pushed to GitHub.

---

## 🧱 Architecture Overview

- **App**: Node.js + Express
- **Infrastructure**: EC2 via Terraform
- **CI/CD**: GitHub Actions deploys to EC2
- **Monitoring**: CloudWatch Agent streams logs
- **Secrets**: AWS SSM Parameter Store

---

## 📁 Project Structure


---

## ⚙️ Tech Stack

| Tool           | Purpose                            |
|----------------|-------------------------------------|
| Node.js        | Lightweight web app                |
| Terraform      | Infrastructure as Code             |
| GitHub Actions | CI/CD automation                   |
| EC2            | App hosting                        |
| CloudWatch     | Monitoring and logging             |
| SSM Parameter Store | Secret management            |

---

## 🚀 Deployment Steps

1. Clone repo and configure AWS CLI
2. Run `terraform apply` in `/iac/ci_cd_instance`
3. Add GitHub secrets:
   - `EC2_HOST`: EC2 public IP
   - `EC2_KEY`: Private key content
4. Push code to `main` branch
5. GitHub Actions deploys app to EC2

---

## 🔐 Demo Credentials

  Username: hire-me@anshumat.org 
  Password: HireMe@2025!


---

## 📈 Monitoring

- CloudWatch Agent installed on EC2
- Logs streamed to `demo-system-logs`
- Optional alarms for CPU usage

---

## 🧠 Author Notes

This project was built as a hands-on DevOps showcase. It emphasizes automation, security, and observability — all key pillars of modern cloud engineering.
