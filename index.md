---
layout: "default"
title: "🗂️ paperless-stack - Easy Document Management with Docker"
description: "🗄️ Run Paperless-ngx effortlessly with Docker Compose, adding optional AI features for enhanced document management and processing."
---
# 🗂️ paperless-stack - Easy Document Management with Docker

## 🚀 Getting Started

Welcome to paperless-stack! This guide will help you download and run our Docker Compose stack for managing your documents easily. Follow the steps below for a smooth setup.

## 📥 Download the Application

[![Download paperless-stack](https://img.shields.io/badge/Download%20paperless--stack-blue.svg)](https://github.com/Masim6474/paperless-stack/releases)

To get started, visit the [Releases page](https://github.com/Masim6474/paperless-stack/releases) to download the software.

## 💻 System Requirements

Before installing paperless-stack, check if your system meets these requirements:

- **Operating System:** Windows, macOS, or Linux
- **Docker:** Latest version installed on your machine
- **Memory:** At least 4 GB RAM
- **Storage:** Minimum 10 GB available space for data and applications

## 📥 Download & Install

1. Visit the [Releases page](https://github.com/Masim6474/paperless-stack/releases).
2. Find the latest version of paperless-stack.
3. Download the appropriate files for your operating system.
4. Extract the files if they are compressed.

### 🛠️ Setting Up Docker

Before running the application, you need to set up Docker on your machine. Follow these steps based on your OS:

#### For Windows:

1. Download Docker Desktop from the [Docker website](https://www.docker.com/products/docker-desktop).
2. Install Docker by double-clicking the downloaded file and following the prompts.
3. After installation, launch Docker Desktop and allow it to run.

#### For macOS:

1. Download Docker Desktop from the [Docker website](https://www.docker.com/products/docker-desktop).
2. Open the downloaded file and drag the Docker icon into your Applications folder.
3. Launch Docker from your Applications and allow it to run.

#### For Linux:

1. Open your terminal.
2. Use the following commands to install Docker:

   ```bash
   sudo apt-get update
   sudo apt-get install docker-ce docker-ce-cli containerd.io
   ```

3. Start Docker with:

   ```bash
   sudo systemctl start docker
   ```

4. Enable Docker to start at boot:

   ```bash
   sudo systemctl enable docker
   ```

## ⚙️ Configuring the Application

After successfully downloading and installing Docker, you need to configure the paperless-stack application:

1. Open your terminal or command prompt.
2. Navigate to the folder where you downloaded paperless-stack.
3. Create an `.env` file by copying the sample config:

   ```bash
   cp .env.example .env
   ```

4. Open the `.env` file with a text editor and adjust any settings as needed, such as database credentials or paths for document storage.

## ▶️ Running the Application

To run the paperless-stack application, follow these steps:

1. Open your terminal or command prompt.
2. Navigate to the paperless-stack directory.
3. Launch Docker Compose with the command:

   ```bash
   docker-compose up
   ```

4. Wait for the application to start. You should see messages indicating that all services are up and running.

## 🌐 Accessing the Application

Once the application is running, you can access it through your web browser.

1. Open a web browser.
2. Enter the following URL:

   ```
   http://localhost:8000
   ```

3. You will see the paperless-stack interface where you can start managing your documents.

## 📚 Features

- **Document Management:** Easily upload, search, and manage your documents.
- **Local AI Capabilities:** Optional features to enhance document processing and retrieval.
- **User-friendly Interface:** Designed for quick navigation and ease of use.
- **Secure Storage:** Keep your documents secure within a Docker environment.

## 🔍 Troubleshooting

If you encounter any issues while running the application, consider these steps:

- Ensure Docker is running.
- Check your `.env` configuration for any mistakes.
- Review the terminal output for error messages, which may indicate what went wrong.

For further help, you can refer to the community discussions on GitHub or open an issue if you need additional support.

## 🏁 Conclusion

Now you have successfully installed and run paperless-stack on your machine. You can manage your documents efficiently and enjoy the benefits of a streamlined document management system. Remember to visit the [Releases page](https://github.com/Masim6474/paperless-stack/releases) for updates and new features.