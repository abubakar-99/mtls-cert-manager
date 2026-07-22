# mtls-cert-manager

![Go](https://img.shields.io/badge/Go-1.22-00ADD8?logo=go) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Issues and rotates mTLS certificates with embedded ACME-like CA.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/mtls-cert-manager
cd mtls-cert-manager
go mod tidy
```

## Usage

```bash
go run cmd/main.go
```

## Architecture

```
mtls-cert-manager/
├── src/
│   ├── main.go
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
