# Awesome-Edge-Computing-Software-For-IoT

# Awesome-Edge-Computing-Software-For-IoT 🌐 📡

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Edge Computing Software For IoT Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Edge-Computing-Software-For-IoT?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Edge Computing Software for IoT Ecosystem

**Curated List of Commercial Edge Platforms & Open-Source Edge Runtime Tools**  
*Focused on Edge Orchestration, Containerized Workloads, OTA Updates, Device Management, Edge AI Inference & Self-Hosted Edge Platforms*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **edge computing platforms for IoT**, **open-source edge runtime frameworks**, and **device management solutions**. Whether you are looking for enterprise-grade commercial solutions (such as *AWS IoT Greengrass*, *Azure IoT Edge*, and *BalenaCloud*), or self-hostable open-source alternatives (like *K3s*, *MicroK8s*, and *EdgeX Foundry*), this list covers category leaders, edge orchestration, and privacy-respecting IoT infrastructure.

**Key Market Context:**
- **K3s** is the **lightest certified Kubernetes distribution**, with **30MB binary**, **<512MB RAM** requirements, and **millions of edge deployments**.
- **EdgeX Foundry** is the **leading open-source edge middleware platform**, a **Linux Foundation project** with **300+ contributors** and **interoperability across 20+ protocols**.
- **BalenaCloud** is the **most popular commercial edge fleet management platform**, with **support for 100+ device types** and **over-the-air updates**.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The edge computing for IoT market spans **hyperscaler edge platforms** (AWS IoT Greengrass, Azure IoT Edge) that provide **deep cloud integration with local compute and ML inference**, **fleet management platforms** (BalenaCloud, Zededa) that focus on **containerized edge orchestration and OTA updates**, and **industrial edge platforms** (FogHorn, Scale Computing) that offer **real-time analytics and hyperconverged edge infrastructure**. **AWS IoT Greengrass** is **free** — you pay only for AWS services used . **Azure IoT Edge** is **free** — you pay only for Azure services used . **BalenaCloud** offers **free tier for up to 10 devices** with **paid plans from $99/month** .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS IoT Greengrass](https://aws.amazon.com/greengrass/)** ☁️ | Amazon | ~$2.0 Trillion | **Free software**; pay only for AWS services used  | **Free forever** | **AWS-native edge runtime** — **Runs Lambda functions, containers, and ML models at the edge** . **Local data processing, messaging, and device shadows** . **OTA updates and fleet management** . **Integrates with AWS IoT Core, S3, and SageMaker** . |
| **[Azure IoT Edge](https://azure.microsoft.com/en-us/products/iot-edge/)** 🔷 | Microsoft | ~$3.90 Trillion | **Free software**; pay only for Azure services used  | **Free forever** | **Azure-native edge runtime** — **Runs AI, analytics, and custom logic on IoT devices** . **Module marketplace with pre-built modules** . **IoT Edge Hub for local messaging** . **Deep integration with Azure IoT Hub and Machine Learning** . |
| **[BalenaCloud](https://www.balena.io/)** 🐳 | Balena | Private | **Free: 10 devices**; **Paid from $99/month**  | **Free: 10 devices, full fleet management**  | **Container-based edge fleet management** — **Deploy Docker containers to IoT devices** . **100+ supported device types** including Raspberry Pi, Intel NUC, and NVIDIA Jetson . **OTA updates, VPN access, and remote debugging** . **The most developer-friendly edge platform** . |
| **[Zededa](https://zededa.com/)** ⚡ | Zededa | Private | **Custom enterprise pricing**  | **Free trial available** | **Edge orchestration platform** — **Zero-trust security with hardware root of trust** . **Multi-cloud and multi-edge orchestration** . **The most enterprise-ready edge orchestration platform** . |
| **[FogHorn](https://www.foghorn.io/)** 🌫️ | FogHorn (Johnson Controls) | Private | **Custom enterprise pricing**  | **Demo available** | **Edge AI platform (acquired)** — **Real-time analytics and ML at the edge** . **Acquired by Johnson Controls** for building automation. **The most industrial-focused edge AI platform** . |
| **[Scale Computing](https://scalecomputing.com/)** 🖥️ | Scale Computing | Private | **Custom enterprise pricing**  | **Demo available** | **Hyperconverged edge infrastructure** — **Self-healing, self-managing edge clusters** . **Runs VMs and containers at the edge** . **The most reliable edge infrastructure platform** . |
| **[MicroK8s (Commercial Support)](https://microk8s.io/)** ☸️ | Canonical | Private | **Free software**; **Ubuntu Pro from $25/month**  | **Free: single-node Kubernetes**  | **Lightweight Kubernetes for edge** — **Single snap package** . **Auto-scaling, self-healing, and high availability** . **The simplest Kubernetes for edge and IoT** . |
| **[K3s (Commercial Support)](https://k3s.io/)** 🍓 | SUSE (Rancher) | ~$2.5 Billion | **Free software**; **SUSE Rancher Prime from $15/node/month**  | **Free forever** | **Lightweight Kubernetes for edge** — **30MB binary, <512MB RAM** . **The most widely deployed edge Kubernetes** . **Runs on Raspberry Pi, ARM, and x86** . |
| **[AWS IoT Greengrass (Open Source)](https://github.com/aws/aws-iot-greengrass)** 🟢 | Amazon | ~$2.0 Trillion | **Free software** | **Free forever** | **Open-source edge runtime** — **The open-source components of AWS IoT Greengrass** . **Local Lambda execution and messaging** . |
| **[Azure IoT Edge (Open Source)](https://github.com/Azure/iotedge)** 🔵 | Microsoft | ~$3.90 Trillion | **Free software** | **Free forever** | **Open-source edge runtime** — **The open-source components of Azure IoT Edge** . **Module runtime and IoT Edge Hub** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Node-RED](https://github.com/node-red/node-red)** [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers)  
  **Low-code programming for event-driven applications**, Apache-2.0 licensed. **20K+ GitHub stars** — **the most popular open-source IoT flow programming tool** . **Browser-based flow editor** — **wire together devices, APIs, and services** . **4000+ community-contributed nodes** . **Runs on Raspberry Pi, edge devices, and cloud** . **The definitive open-source IoT integration platform** . 🔴

- **[K3s](https://github.com/k3s-io/k3s)** [![Stars](https://img.shields.io/github/stars/k3s-io/k3s?style=social&color=white)](https://github.com/k3s-io/k3s/stargazers)  
  **Lightweight Kubernetes**, Apache-2.0 licensed. **30K+ GitHub stars** — **the lightest certified Kubernetes distribution** . **Single binary under 100MB** — runs on **Raspberry Pi, edge devices, and IoT** . **<512MB RAM** required for the control plane . **Built for resource-constrained environments** . **The standard for edge Kubernetes** . 🍓

- **[EdgeX Foundry](https://github.com/edgexfoundry/edgex-go)** [![Stars](https://img.shields.io/github/stars/edgexfoundry/edgex-go?style=social&color=white)](https://github.com/edgexfoundry/edgex-go/stargazers)  
  **Open-source edge middleware platform**, Apache-2.0 licensed. **Linux Foundation project** — **the leading open-source edge IoT platform** . **Interoperability across 20+ protocols** including MQTT, Modbus, BACnet, and Zigbee . **Device services, core services, and supporting services** . **The most complete open-source edge middleware** . 🏛️

- **[MicroK8s](https://github.com/canonical/microk8s)** [![Stars](https://img.shields.io/github/stars/canonical/microk8s?style=social&color=white)](https://github.com/canonical/microk8s/stargazers)  
  **Lightweight Kubernetes for developers and edge**, Apache-2.0 licensed. **Single snap package** — **install in seconds** . **Add-ons for Istio, Knative, and Kubeflow** . **The simplest Kubernetes for local development and edge** . 📦

- **[KubeEdge](https://github.com/kubeedge/kubeedge)** [![Stars](https://img.shields.io/github/stars/kubeedge/kubeedge?style=social&color=white)](https://github.com/kubeedge/kubeedge/stargazers)  
  **Kubernetes-native edge computing framework**, Apache-2.0 licensed. **CNCF Graduated project** — **extends Kubernetes to edge hosts** . **Cloud-edge collaboration with edge autonomy** . **The most production-proven edge Kubernetes platform** . ☸️

- **[Balena Engine](https://github.com/balena-os/balena-engine)** [![Stars](https://img.shields.io/github/stars/balena-os/balena-engine?style=social&color=white)](https://github.com/balena-os/balena-engine/stargazers)  
  **Moby-based container engine for IoT**, Apache-2.0 licensed. **Optimized for embedded and IoT** — **delta updates and bandwidth efficiency** . **The container engine behind BalenaCloud** . 🐳

- **[BalenaOS](https://github.com/balena-os/balena-os)** [![Stars](https://img.shields.io/github/stars/balena-os/balena-os?style=social&color=white)](https://github.com/balena-os/balena-os/stargazers)  
  **Host OS for containerized IoT devices**, Apache-2.0 licensed. **Minimal Linux OS for running containers** . **Yocto-based with support for 100+ device types** . **The most widely deployed IoT container OS** . 🐧

- **[Open Horizon](https://github.com/open-horizon/anax)** [![Stars](https://img.shields.io/github/stars/open-horizon/anax?style=social&color=white)](https://github.com/open-horizon/anax/stargazers)  
  **Edge computing orchestration platform**, Apache-2.0 licensed. **Linux Foundation project** — **manages containerized workloads at scale** . **Policy-based deployment and autonomous agents** . **The most scalable open-source edge orchestration platform** . 🌅

- **[Project EVE](https://github.com/lf-edge/eve)** [![Stars](https://img.shields.io/github/stars/lf-edge/eve?style=social&color=white)](https://github.com/lf-edge/eve/stargazers)  
  **Edge virtualization engine**, Apache-2.0 licensed. **LF Edge project** — **runs VMs and containers on edge devices** . **The universal edge OS** — **secure, open, and cloud-native** . **The most secure open-source edge OS** . 🛡️

- **[MicroK8s (Snap)](https://github.com/canonical/microk8s)** [![Stars](https://img.shields.io/github/stars/canonical/microk8s?style=social&color=white)](https://github.com/canonical/microk8s/stargazers)  
  **Lightweight Kubernetes snap**, Apache-2.0 licensed. **The simplest Kubernetes for edge** . **Add-ons for IoT and edge workloads** . 📦

- **[Akri](https://github.com/project-akri/akri)** [![Stars](https://img.shields.io/github/stars/project-akri/akri?style=social&color=white)](https://github.com/project-akri/akri/stargazers)  
  **Kubernetes resource interface for edge devices**, Apache-2.0 licensed. **CNCF Sandbox project** — **exposes edge devices as Kubernetes resources** . **The most innovative open-source edge device integration** . 🔌

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new edge computing platforms or open-source edge runtime software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Edge-Computing-Software-For-IoT&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Edge-Computing-Software-For-IoT&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this edge computing for IoT repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow IoT engineers, edge developers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **AWS IoT Greengrass and Azure IoT Edge are free software** — you pay only for the AWS or Azure services consumed . **BalenaCloud offers free tier for up to 10 devices** with **full fleet management** .
- **K3s is the lightest Kubernetes distribution** — **30MB binary, <512MB RAM** — making it the **standard for edge Kubernetes** . **EdgeX Foundry provides interoperability across 20+ protocols** — the **leading open-source edge middleware** .
- **Open-source edge computing tools are not turnkey** — they require **device provisioning, network configuration, and ongoing maintenance** . **K3s and MicroK8s require container orchestration expertise** . **EdgeX Foundry requires device service configuration** . **Always validate edge workload performance and connectivity with a proof-of-concept** before production deployment . 🌐

---

<p align="center">
  <b>Made with ❤️ for IoT engineers, edge developers, and open-source edge computing advocates.</b>
</p>
