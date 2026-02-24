<img width="1332" height="691" alt="image" src="https://github.com/user-attachments/assets/f432c773-9aa0-4cd2-a319-641953e3243f" />

# NGINX Proxy Manager
**NGINX Proxy Manager** is an open-source web application that provides a graphical interface for managing reverse proxy configurations powered by NGINX. It enables users to easily handle proxy hosts, SSL certificates, and access controls without editing configuration files directly. The project is popular among self-hosting and home lab communities for simplifying web service management.

## Key facts
- Initial release: 2018
- Developer: Community project by jc21 (Jamie Curnow)
- Written in: Node.js and Vue.js
- License: MIT License
- Deployment: Commonly via Docker

## Features and functionality
NGINX Proxy Manager provides a dashboard to create and manage reverse proxy rules that direct incoming web traffic to internal services. It supports custom domains, path-based routing, and automated certificate management through Let's Encrypt. Users can configure advanced NGINX features such as caching, access lists, and custom headers through simple forms rather than manual editing.

## Use cases
The software is often used to expose self-hosted applications—like media servers, wikis, or dashboards—securely over the internet. It enables centralized SSL management and reverse proxying for multiple hosts, making it a common front end for Dockerized environments or homelab servers. Its browser-based UI lowers the technical barrier for running NGINX configurations.

## Architecture and deployment
NGINX Proxy Manager runs as a containerized stack, typically consisting of an NGINX service, a Node.js backend, and a database (MariaDB or SQLite). The NGINX layer performs the actual proxying, while the web interface stores and generates configuration data dynamically. The modular setup allows it to integrate with other Docker networks for service discovery.

## Community and development
The project maintains an active user base on GitHub and in Docker Hub, with frequent updates and community plugins. Contributions focus on enhancing certificate automation, HTTP/2 support, and improved authentication methods. Its simplicity and active support have made it a popular gateway solution for small-scale deployments and developers seeking an easier NGINX management experience.

