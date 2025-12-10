# 🌙 LunaFlow
### Next-Generation Service Observability & Management Agent

![Version](https://img.shields.io/github/v/release/lunasoft-llc/lunaflow?style=for-the-badge&color=6366f1)
![Platform](https://img.shields.io/badge/Platform-Windows_x64-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

**LunaFlow** is a powerful, self-contained desktop agent designed to bring enterprise-grade observability, topology visualization, and management to your local and cloud microservices. Built with a stunning, modern interface and powered by the robustness of .NET 9, LunaFlow transforms how developers and operators interact with their infrastructure.

---

## ✨ Key Features

### 🔭 **Deep Observability**
*   **Dynamic Topology Map**: Visualize your entire architecture with a real-time, interactive node graph. See how services connect, detect latency bottlenecks, and spot health issues at a glance.
*   **Live Metrics**: Monitor CPU, Memory, Network I/O, and custom application metrics with beautiful, real-time charts.
*   **Centralized Logs**: Aggregated logging with powerful search and filtering capabilities to debug issues faster.

### 🐳 **Container Intelligence**
*   **Docker Compose Integration**: Automatically detect, map, and monitor your local Docker Compose projects. View container logs, status, and resource usage without leaving the UI.
*   **Service Health Checks**: Automated heartbeat and endpoint monitoring for all your registered services.

### ⚡ **Power & Control**
*   **Custom Dashboards**: Build your perfect command center using a drag-and-drop grid system. Widgets for every metric and data point you care about.
*   **Intelligent Alerting**: Define complex alert rules and thresholds. Get notified before your users do.
*   **API Documentation**: Integrated Swagger/OpenAPI viewer to explore and test your microservices' APIs directly within LunaFlow.

### 🛡️ **Enterprise Ready**
*   **Secure Access**: Built-in User Management and Role-Based Access Control (RBAC).
*   **License Management**: Flexible licensing tiers (Pro, Enterprise) to match your scale.
*   **Self-Contained**: Runs as a single binary. No complex dependencies, no pre-installed .NET Runtime required.

---

## 🚀 Getting Started

### Prerequisites
*   Windows 10/11 (x64)
*   A modern web browser (Edge, Chrome, Firefox)

### Installation
1.  **Download**: Head to the [Releases Page](https://github.com/lunasoft-llc/lunaflow/releases) and download the latest `LunaFlow-Windows-vX.Y.Z.zip`.
2.  **Extract**: Unzip the contents to a folder of your choice (e.g., `C:\Apps\LunaFlow`).
3.  **Run**: Double-click `LunaFlow.Desktop.exe`.
4.  **Launch**: The application will automatically open your default browser to `http://localhost:5000`.

### First Login
On the first run, LunaFlow will generate a secure **Initial Admin Password**.
*   Navigate to the installation folder.
*   Use `admin` as the username and `admin123` as the password to log in.

> **Note**: We strongly recommend changing your password and creating new users immediately after the first login.

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
