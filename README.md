# EShoppingZone Cloud Config Repository

Official Remote Config Repository:
`https://github.com/Abulhasan06/abuleshoppingnewconfigserver.git`

## Commands to Push / Update to GitHub:

```bash
cd "C:\Users\user\Documents\abulEshopping\abulconfig"
git init
git add .
git commit -m "Update microservices cloud configuration with v4 clean databases"
git branch -M main
git remote add origin https://github.com/Abulhasan06/abuleshoppingnewconfigserver.git
git push -u origin main --force
```

## How to Delete Previous Files from Git Repo (Clean Overwrite):
```bash
cd "C:\Users\user\Documents\abulEshopping\abulconfig"
git rm -rf *
git commit -m "Clean previous config"
git add .
git commit -m "Add latest clean v4 microservices properties"
git push origin main --force
```

### Config Files Included:
- `application.properties`
- `api-gateway.properties`
- `auth-service.properties`
- `profile-service.properties`
- `product-service.properties`
- `cart-service.properties`
- `order-service.properties`
- `payment-service.properties`
- `delivery-service.properties`
- `notification-service.properties`
- `wallet-service.properties`
- `website-controller.properties`
