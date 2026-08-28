# ⚙️ Dropzone Centralized Configuration Repository

Centralized external configuration repository for the **Dropzone Distributed Ticketing System**, powered by **Spring Cloud Config Server**.

---

## 📂 Configuration Structure

This repository provides environment-specific (`dev`, `staging`, `production`) configuration profiles for all microservices in the Dropzone ecosystem:

```
├── application.yml                 # Shared global configuration
├── application-dev.yml             # Shared dev profile defaults
├── application-staging.yml         # Shared staging profile defaults
├── application-production.yml      # Shared production profile defaults
├── api-gateway-*.yml               # Spring Cloud API Gateway configurations
├── order-service-*.yml             # Order microservice profiles
├── inventory-service-*.yml         # Inventory & locking profiles
├── payment-service-*.yml           # Payment gateway settings
├── event-service-*.yml             # Event catalog profiles
├── notification-service-*.yml      # Notification & Kafka channels
├── audit-service-*.yml             # Audit logging settings
├── search-service-*.yml            # Elasticsearch / Search service settings
└── user-service-*.yml              # IAM & User profile settings
```

---

## 🔗 Related Repositories

- [Dropzone Core Platform](https://github.com/SongUylong/dropzone)

---

## 👤 Author

**Song Uylong** ([@SongUylong](https://github.com/SongUylong))
