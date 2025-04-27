# NGINX Proxy Manager

# Dependencias:
Necessario o banco de dados ja estar sendo executo.

## 1. Subir o Container do NGINX Proxy Manager

+++bash
docker compose -f /nginx/nginx.yml up -d
+++

## 2. Acesso à página do NGINX

- URL: `http://<IP_DO_HOST>:81`
- Login: `admin@example.com`
- Senha: `changeme`
