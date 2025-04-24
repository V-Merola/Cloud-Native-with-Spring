# Cloud Native with Spring - Progetto

Benvenuto nel progetto *Cloud Native with Spring*, ispirato dal libro *Cloud Native Spring in Action* di Thomas Vitale. Questo progetto è una dimostrazione pratica dell'adozione di principi e tecnologie cloud-native, progettato per essere modulare e scalabile. La struttura si basa su un'architettura a microservizi, dove ogni componente è sviluppato come un microservizio indipendente, gestito tramite container Docker e orchestrato tramite Kubernetes.

## 🌍 Panoramica del progetto

Il progetto si propone di costruire un'applicazione in grado di gestire un negozio online in un contesto cloud-native, seguendo i principi e le tecnologie più moderne. Ogni microservizio ha una propria logica e database, con una comunicazione asincrona tra i vari componenti tramite Kafka.

### 📦 Microservizi inclusi nel progetto
Al momento il progetto include i seguenti microservizi:

- **Catalog Service** - Gestisce il catalogo dei prodotti.  
  [Vai alla repo del Catalog Service](https://github.com/V-Merola/catalog-service)

_Nota: Altri microservizi verranno aggiunti in futuro._

### ⚙️ Tecnologie principali
- **Spring Boot** - Per la creazione dei microservizi.
- **Docker** - Per la containerizzazione dei servizi.
- **Kubernetes** - Per l'orchestrazione e il deploy dei container.
- **Kafka** - Per la gestione della comunicazione asincrona tra i microservizi.
- **Spring Cloud** - Per la gestione dei microservizi e delle configurazioni centralizzate.
- **Prometheus & Grafana** - Per il monitoraggio e la raccolta di metriche.
- **Eureka** - Per il Service Discovery.

## 🚀 Come avviare il progetto

1. **Clona il repository:**

   ```bash
   git clone https://github.com/V-Merola/cloud-native-with-spring.git
   cd cloud-native-with-spring
