# Snippetbox

A web application built following the "Let's Go" book by Alex Edwards.

## About

This project is a code snippet sharing application that demonstrates modern Go web development practices.

## Getting Started

### Prerequisites

- Go 1.19 or later

### Installation

1. Clone the repository

2. Generate a self signed TLS Certificate for HTTPS connection

```bash
cd tls
go run generate_cert.go --rsa-bits=2048 --host=localhost
```

3. Run the Development server
```bash
go run ./cmd/web
```

## Project Structure

- `cmd/web/` - Application-specific code for the executable
- `internal/` - Ancillary non-application-specific code
- `ui/` - User-Interface assets

Built with Go following the patterns and practices from Alex Edwards' "Let's Go" book.