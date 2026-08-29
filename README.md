# EShoppingZone Cloud Config Repository (abulconfig)

This folder contains the centralized configuration properties for all microservices in the EShoppingZone project.

## How to push these files to your GitHub Repository

Run the following commands in PowerShell from inside this `abulconfig` directory:

```bash
cd "C:\Users\user\Documents\abulEshopping\abulconfig"
git init
git add .
git commit -m "Centralized Cloud Config properties for EShoppingZone microservices"
git branch -M main
git remote add origin https://github.com/Abulhasan06/abuleshoppingnewconfigserver.git
git push -u origin main --force
```

## Files included:
- `application.properties` (Global shared configuration, Eureka URL, Actuator endpoints)
- `api-gateway.properties` (Routing definitions for all services)
- `auth-service.properties` (Port 8081, eshopping_auth_v3, JWT token settings)
- `profile-service.properties` (Port 8082, eshopping_profile_v3)
- `product-service.properties` (Port 8083, eshopping_product_v3)
- `cart-service.properties` (Port 8084, eshopping_cart_v3)
- `order-service.properties` (Port 8085, eshopping_order_v3)
- `payment-service.properties` (Port 8086, eshopping_payment_v3, 90/10 split settings)
- `delivery-service.properties` (Port 8087, eshopping_delivery_v3)
- `notification-service.properties` (Port 8088, eshopping_notification_v3, SMTP Mail)
- `wallet-service.properties` (Port 8089, eshopping_wallet_v3)
- `website-controller.properties` (Port 8090, UI, Gateway service URLs)
