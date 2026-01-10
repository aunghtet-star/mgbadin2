# Project Context: mgbadin2

## 🏗 Identifiers
- **App Name:** mgbadin2
- **Subdomain:** 2.mgbadin.top
- **Instance:** Secondary (Clone of mgbadin)

## 🌐 Networking Configuration
- **Backend API Port:** 3002
- **Nginx Config Name:** 2.mgbadin.top
- **API Base URL:** https://2.mgbadin.top/api
- **Environment:** Production (DigitalOcean Droplet)

## 🚀 DevOps & Management
- **PM2 Backend Name:** mgbadin2-backend
- **PM2 Frontend Name:** mgbadin2-frontend
- **Project Root:** /root/nextjsproject/mgbadin2

## 🛠 Critical Rules for Gemini
1. **Port Restriction:** Only use Port 3002 for this project. Port 3001 is reserved for the primary app.
2. **Nginx Path:** The configuration lives in `/etc/nginx/sites-available/2.mgbadin.top`.
3. **PM2 Commands:** When I say "restart," use `pm2 restart mgbadin2-backend`.
4. **Environment Variables:** Ensure `.env` files reflect the 3002 port and the `2.mgbadin.top` origin.