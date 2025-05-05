# 📦 Go Microservices Template

A modular and scalable microservices architecture written in Go. This repository serves as a boilerplate for developing Go-based services with clear boundaries, observability, and containerization best practices.

---

## 🗂️ Project Structure

```

├── broker-service/             # Broker service orchestrates requests between other services
├── authentication-service/     # Authentication service for validating credentials
├── front-end/                  # Front End for testing services
├── project/                    # DevOps and setup scripts
│   ├── make-recipes/            # Makefiles for macOS and Windows
│   ├── Makefile                # Place your Makefile here, depending on OS
└── README.md

```

---

## 🚀 Getting Started

### Prerequisites

- Go 1.20+
- Docker
- `make` (optional but recommended)

---

## 🔧 Running Services

### Using Docker Compose

```bash
docker-compose up --build
```

### Running Locally

```bash
cd project
make up_build
make start
```

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
