<div align="center">
  <img src="frontend/public/IRIS_CRAWL_Logo_SD.png" alt="IrisCrawl Studio Logo" width="250" />
  <h1>IrisCrawl Studio</h1>
  <p><em>Find Your Photos: Powered by AI.</em></p>

  <!-- GitHub Release Badges -->
  <a href="https://github.com/kolapraneeth22/iriscrawl-studio/releases/latest">
    <img src="https://img.shields.io/github/v/release/kolapraneeth22/iriscrawl-studio?style=for-the-badge&color=00EFFF&labelColor=131313&logo=github" alt="Latest Release" />
  </a>
  <a href="https://github.com/kolapraneeth22/iriscrawl-studio/releases">
    <img src="https://img.shields.io/github/downloads/kolapraneeth22/iriscrawl-studio/total?style=for-the-badge&color=00EFFF&labelColor=131313&logo=icloud" alt="Total Downloads" />
  </a>
  <br />
  <a href="https://github.com/kolapraneeth22/iriscrawl-studio/stargazers">
    <img src="https://img.shields.io/github/stars/kolapraneeth22/iriscrawl-studio?style=social" alt="GitHub stars" />
  </a>
</div>

<br />

Welcome to **IrisCrawl Studio**—a powerful **privacy-first image crawler** and **desktop asset manager** designed to fundamentally change how you interact with your digital memories. Built entirely for your local machine, IrisCrawl acts as an **offline semantic image search** engine, allowing you to find deeply buried photos using nothing but natural language.

Whether you're looking to consolidate decades of scattered photography, implement **facial recognition cataloging** for your family portraits, or simply need a robust **AI photo search** utility, IrisCrawl ensures your data never leaves your hard drive. 

---

## 🏷️ Recommended GitHub Topics
To help the community discover this repository, we recommend applying the following topics in the GitHub sidebar:
`tauri`, `desktop-app`, `ai-photo-search`, `semantic-search`, `clip-embeddings`, `chromadb`, `python-backend`, `cross-platform`, `local-ai`, `privacy-first`, `face-recognition`

---

## 🧠 Architectural Overview

IrisCrawl Studio achieves its bleeding-edge performance by decoupling the heavy AI compute layer from the agile UI rendering layer. 

1. **Native Rust Tauri Window Lifecycle Manager**: Acts as our ultra-lightweight and highly secure shell, orchestrating the desktop UI context with zero web-bloat overhead.
2. **High-Performance Python Sidecar**: A completely frozen, standalone executable bundled directly into the application. It acts as our localized AI nervous system.
3. **Localized FastAPI Routers**: Facilitates asynchronous, lightning-fast IPC (Inter-Process Communication) between the React frontend and the backend neural nets.
4. **Offline ChromaDB Vector Storage**: A highly optimized **local vector database for images**, embedding your semantic search footprint instantly on-disk.
5. **Local CLIP Inference Engines**: Leverages powerful localized **CLIP embeddings** to bridge the gap between human language and visual pixel data—entirely offline.

---

## ⚡ Core Engine Features

| Feature | Description |
| --- | --- |
| 🗣️ **Natural Language Semantic Prompts** | Stop searching by file names. Search for *"dog running on a beach at sunset"* or *"red car in the snow"* and watch the localized CLIP engine retrieve exact matches instantly. |
| 🗂️ **Facial Recognition Clustering** | Automatically groups localized face recognition boundaries into cohesive "People" profiles across your entire localized catalog. |
| ✨ **Automated Smart Culling** | Automatically detects and clusters near-duplicate burst photography or blurry shots, allowing you to instantly clear gigabytes of wasted space. |
| 🛡️ **Zero-Network Privacy Protocols** | 100% offline private processing. Your images are crawled locally, indexed locally, and searched locally. No cloud telemetry, no data scraping. |

---

## 🚀 Step-by-Step User Runway

Ready to experience completely offline semantic visual searching? 

### 1. Download the Installer
Head over to the [GitHub Releases](https://github.com/kolapraneeth22/iriscrawl-studio/releases/latest) page to grab the latest compiled installer payload.
- Choose `IrisCrawl Studio_x64-setup.exe` (NSIS Executable - Recommended)
- Or choose `IrisCrawl Studio_x64_en-US.msi` (MSI Database Installer)

### 2. Run the Setup
Run the downloaded executable file to install IrisCrawl Studio seamlessly onto your machine. 

### 3. Launch the Studio
When you boot IrisCrawl Studio for the first time, the loading screen will gracefully initialize the PyTorch backend, mount your local ChromaDB vector space, and instantly bind to your localhost port. Within 45 seconds, the Studio UI will transition in, completely decoupled from the internet and ready to index your selected directories.

---

## ⚙️ Minimum System Allocations

Because IrisCrawl Studio runs **heavy localized AI inference pipelines** entirely on your native CPU, please ensure your hardware meets our baseline requirements for a smooth experience.

| Requirement | Minimum Allocation | Recommended Allocation |
| --- | --- | --- |
| **Operating System** | Windows 10 x64 Architecture | Windows 11 x64 Architecture |
| **Processor (CPU)** | Intel Core i5 / AMD Ryzen 5 | Intel Core i7 / AMD Ryzen 7+ |
| **Memory (RAM)** | 8 GB System RAM | 16 GB System RAM |
| **Storage (Disk)** | 500 MB for Application & Model Weights | Fast NVMe SSD for instant ChromaDB retrieval |
| **Indexing Speed** | ~3-5 images per second (CPU inference) | ~10-15+ images per second |

---

<div align="center">
  <p>Built with ❤️ for privacy and precision.</p>
</div>
