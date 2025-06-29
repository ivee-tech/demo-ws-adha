# demo-ws-adha
Copilot training repo

## Planets Solar System Application

This repository contains a complete solar system visualization web application built with Three.js, featuring interactive 3D planets with realistic textures and orbital mechanics.

### Features

- **Interactive 3D Solar System**: Built with Three.js for smooth 3D rendering
- **Realistic Planet Textures**: High-quality images for all planets
- **Orbital Controls**: Mouse/touch controls for navigation
- **Planet Rotation**: Each planet rotates at different speeds
- **Containerized Deployment**: Docker support with nginx
- **Kubernetes Ready**: Complete K8s manifests for deployment
- **CI/CD Pipeline**: Azure DevOps pipelines for automated builds

### Quick Start

#### Local Development
```bash
cd planets
python3 -m http.server 8080
# Open http://localhost:8080 in your browser
```

#### Docker Deployment
```bash
cd planets
docker build -t planets-app .
docker run -p 8080:80 planets-app
# Open http://localhost:8080 in your browser
```

### Project Structure

- **`planets/`** - Frontend application with Three.js solar system
- **`docs/`** - Project documentation and architecture diagrams
- **`.github/`** - GitHub Copilot instructions and prompts
- **`planets/.k8s/`** - Kubernetes deployment manifests
- **`planets/.pipelines/`** - Azure DevOps CI/CD pipeline configurations

### Documentation

For detailed information about the architecture, deployment, and development, see the [docs](./docs/) folder:

- [Frontend Implementation](./docs/frontend.md)
- [Backend Plans](./docs/backend.md)
- [Deployment Guide](./docs/deployment.md)
- [Unit Testing](./docs/unit-tests.md)
- [Project Plan](./docs/plan.md)
