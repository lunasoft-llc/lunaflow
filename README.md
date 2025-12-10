# 🌙 LunaFlow
### Next-Generation Service Observability & Management Agent

![Version](https://img.shields.io/github/v/release/lunasoft-llc/lunaflow?style=for-the-badge&color=6366f1)
![Platform Windows](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Platform Linux](https://img.shields.io/badge/Platform-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Platform macOS](https://img.shields.io/badge/Platform-macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

**LunaFlow** is a powerful, **cross-platform**, self-contained desktop agent designed to bring enterprise-grade observability, topology visualization, and management to your local and cloud microservices. Built with a stunning, modern interface and powered by the robustness of .NET 9, LunaFlow transforms how developers and operators interact with their infrastructure.

---

## ✨ Key Features

### 🔭 **Deep Observability**
*   **Dynamic Topology Map**: Visualize your entire architecture with a real-time, interactive node graph. See how services connect, detect latency bottlenecks, and spot health issues at a glance.
*   **Live Metrics**: Monitor CPU, Memory, Network I/O, and custom application metrics with beautiful, real-time charts.
*   **Centralized Logs**: Aggregated logging with powerful search and filtering capabilities to debug issues faster.

### 🔌 **Integrations**
*   **Message Brokers**: Native monitoring for **Kafka** and **RabbitMQ**. Track consumer lag, throughput, and broker status.
*   **Bridge API**: Ingest custom metrics and logs from any external source via the robust HTTP Bridge endpoint.
*   **Docker & Docker Compose**: Seamless discovery and monitoring of containerized workloads.

### ⚡ **Power & Control**
*   **Custom Dashboards**: Build your perfect command center using a drag-and-drop grid system. Widgets for every metric and data point you care about.
*   **Intelligent Alerting**: Define complex alert rules and thresholds. Get notified before your users do.
*   **Service Health Checks**: Automated heartbeat and endpoint monitoring for all your registered services.
*   **API Documentation**: Integrated Swagger/OpenAPI viewer to explore and test your microservices' APIs directly within LunaFlow.

### 🛡️ **Enterprise Ready**
*   **Secure Access**: Built-in User Management and Role-Based Access Control (RBAC).
*   **Advanced Security**:
    *   **Rate Limiting**: Protects against brute-force attacks and API abuse.
    *   **API Keys**: Secure programmatic access with granular API tokens.
*   **License Management**: Flexible licensing tiers (Pro, Enterprise) unlocking advanced features like Custom Dashboards and API access.
*   **Self-Contained**: Runs as a single binary on Windows, Linux, and macOS. **No .NET Runtime required.**

---

## 🚀 Getting Started

### Prerequisites
*   **Windows**: Windows 10/11 (x64)
*   **Linux**: Modern distribution (Ubuntu, Debian, CentOS, Fedora) - x64
*   **macOS**: macOS 11+ (Big Sur or newer) - x64 or Apple Silicon (via Rosetta 2)
*   **Browser**: A modern web browser (Edge, Chrome, Firefox, Safari)

### Installation

#### 🪟 Windows
1.  **Download**: Get the latest `LunaFlow-Windows-vX.Y.Z.zip` from the [Releases Page](https://github.com/lunasoft-llc/lunaflow/releases).
2.  **Extract**: Unzip the contents to a folder (e.g., `C:\Apps\LunaFlow`).
3.  **Run**: Double-click `LunaFlow.Desktop.exe`.
4.  **Launch**: The app will open in your browser at `http://localhost:5000`.

#### 🐧 Linux
1.  **Download**: Get `LunaFlow-Linux-vX.Y.Z.zip`.
2.  **Extract**: `unzip LunaFlow-Linux-vX.Y.Z.zip -d lunaflow`
3.  **Permissions**: Make the binary executable:
    ```bash
    chmod +x lunaflow/LunaFlow.Desktop
    ```
4.  **Run**: `./lunaflow/LunaFlow.Desktop`

> **Service Mode**: To run LunaFlow as a background systemd service, see the included `lunaflow.service` file in the release package.

#### 🍎 macOS
1.  **Download**: Get `LunaFlow-MacOS-vX.Y.Z.zip`.
2.  **Extract**: Unzip the file.
3.  **Permissions**:
    ```bash
    chmod +x LunaFlow.Desktop
    ```
4.  **Run**: `./LunaFlow.Desktop`

> **Security Note**: If macOS prevents the app from opening because it is from an unidentified developer, go to **System Settings > Privacy & Security** and click "Open Anyway" or control-click the executable and select "Open".

### First Login
*   **URL**: `http://localhost:5000`
*   **Username**: `admin`
*   **Password**: `admin123`

> **Note**: Please change your password immediately after your first login via the User Management settings.

---

## 🛠️ Technology Stack
LunaFlow is built on the cutting edge of modern web development:
*   **Backend**: .NET 9.0 (ASP.NET Core, SignalR)
*   **Frontend**: React 18, Vite, TypeScript
*   **Styling**: TailwindCSS, Shadcn/UI (Radix Primitives)
*   **Visualization**: React Flow, Recharts
*   **Transport**: WebSockets, REST, Kafka/RabbitMQ Integrations

---

## 📜 Legal
*   [Privacy Policy](https://lunasoft.az/privacy)
*   [Terms of Use](https://lunasoft.az/terms)

Copyright © 2025 **Lunasoft LLC**. All Rights Reserved.
