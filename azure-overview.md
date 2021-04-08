# Übersicht Azure Dienste

## [Analysen]

* **[Azure Analysis Services]**: BI-Analyse ohne Infrastruktur
* **[Azure Daten-Explorer]**: Verwalteter Dienst zur Datenanalyse aus z.B. Anwendungen, IoT, Websites.
* **[Azure Data Lake Storage]**<a name="data-lake"></a>: Hochverfügbarer, geo-replizierter Speicher für unstrukturierte Daten mit rollenbasierter Rechteverwaltung (RBAC). Kann von anderen Diensten als Datenquelle/ziel genutzt werden.
* **[Azure Data Share]**: Datenfreigabe für andere Organisationen.
* **[Azure Databricks]**: Apache Spark _as a Service_ für Datenanalysen und AI .
* **[Azure Stream Analytics]**: Serverlose Echtzeitanalyse von Datenströmen, z.B. aus IoT. Sowohl in der Cloud als auch als Edge-Computing, nahe an der Datenquelle.
* **[Azure Synapse Analytics]**<a name="synapse"></a>: Datawarehouse mit Apache Spark für Datenanalyse. Hiess früher Azure SQL Datawarehouse.
* **[Azure Data Catalog]**: Metadatenkatalog für Daten, um diese besser und schneller zu finden.
* **[Data Factory]**<a name="factory"></a>: Serverlose Daten-Integration. Sehr viele Konnektoren, um Daten aus unterschiedlichen Quellen zu laden, transformieren und dann in [Azure Synapse Analytics](#synapse) zu speichern.
* **[Data Lake Analytics]**: Big-Data Analyseplatform. Kann Daten aus [Azure Synapse Analytics](#synapse), [Azure Data Lake Storage](#data-lake), [Azure Blob Storage](#blob) und SQL Datenbanken in der Azure Cloud beziehen. Analysen können mit R, Python und U-SQL (SQL-Dialekt+C#) gemacht werden.
* **[Event Hubs]**: Event Streaming Platform für Datenerfassung und Verarbeitung in Echtzeit, ähnlich wie Apache Kafka. Kann mit AMQP, Apache Kafka, aber auch direkt HTTP, integriert werden.
* **[HDInsight]**<a name="hdinsight"></a>: Verwaltete Cluster mit Apache Spark, Apache Hadoop, Apache HBase, Apache Kafka und anderen.
* **[Log Analytics]**: Analyse von Log Daten aus [Azure Monitor](#monitor).
* **[Power BI Embedded]**: White-Label Power BI Komponenten für Kundenseitige Reports, Dashboards, etc.
* **[R-Server for HDInsight]**: Verwalteter Server, um mit der Statistiksoftware R Analysen auf [HDInsight](#hdinsight) durchzuführen.
* **[Azure Purview]**: Daten-Governance - Erstellt Übersichten über Datenlandschaft, klassifiziert vertrauliche Daten und ermittelt Datenherkunft. Für lokale, Cloud- und SaaS-Daten.
* **[Microsoft Graph Data Connect]**: Import grosser Mengen Microsoft 365 Daten nach [Data Factory](#factory) zur weiteren Verarbeitung und Speicherung. Z.B. können dann Machine-Learning-Modelle damit trainiert werden.

[Analysen]: https://azure.microsoft.com/services/#analytics
[Azure Analysis Services]: https://azure.microsoft.com/services/analysis-services/
[Azure Daten-Explorer]: https://azure.microsoft.com/services/data-explorer/
[Azure Data Lake Storage]: https://azure.microsoft.comg/services/storage/data-lake-storage/
[Azure Data Share]: https://azure.microsoft.comg/services/data-share/
[Azure Databricks]: https://azure.microsoft.comg/services/databricks/
[Azure Stream Analytics]: https://azure.microsoft.comg/services/stream-analytics/
[Azure Synapse Analytics]: https://azure.microsoft.comg/services/synapse-analytics/
[Azure Data Catalog]: https://azure.microsoft.comg/services/data-catalog/
[Data Factory]: https://azure.microsoft.comg/services/data-factory/
[Data Lake Analytics]: https://azure.microsoft.comg/services/data-lake-analytics/
[Event Hubs]: https://azure.microsoft.comg/services/event-hubs/
[HDInsight]: https://azure.microsoft.comg/services/hdinsight
[Log Analytics]: https://docs.microsoft.comg/azure/azure-monitor/logs/log-analytics-overview
[Power BI Embedded]: https://azure.microsoft.comg/services/power-bi-embedded
[R-Server for HDInsight]: https://azure.microsoft.comg/services/hdinsight/r-server/
[Azure Purview]: https://azure.microsoft.comg/services/purview/
[Microsoft Graph Data Connect]: https://azure.microsoft.comg/services/graph-data-connect/

## Blockchain

* **[Azure Blockchain-Dienst]**: Erstellung von Blockchainnetzwerken. Momentan nur für Konsortiumblockchains (z.B. Lieferketten).
* **[Azure Blockchain Tokens]**: Entwicklung von Blockchain-Anwendungen um Besitz und Handel von physischen Objekten und digitalen Inhalten zu verwalten. 
* **[Azure Blockchain Workbench]**: Protypenentwicklung von Blockchain-Anwendungen basierend auf Ethereum.

[Azure Blockchain-Dienst]: https://azure.microsoft.comg/services/blockchain-service/
[Azure Blockchain Tokens]: https://azure.microsoft.com/en-us/services/blockchain-tokens/
[Azure Blockchain Workbench]: https://azure.microsoft.com/features/blockchain-workbench/

## Compute

* **[API-Apps]**: Bereitstellung und Verwaltung von APIs in der Cloud, welche [App Service](#app-service) nutzen.
* **[App Service]**<a name="app-service"></a>: Erstellen und Hosten von Web-Apps, mobilen Backends und REST-APIs auf verwalteter Infrastruktur.
* **[Azure CycleCloud]**: Verwaltete Cluster für Hochleistungsrechnen (HPC). Z.B. für Ströhmungssimulationen, Biochemie, Festigkeitsrechnungen, Wetter- oder Klimasimulationen, etc.
* **[Azure Functions]**: Serverloser Betrieb von ereignisgesteuerten Funktionen.
* **[Azure Kubernetes Service] (AKS)**<a name="AKS"></a>: Verwaltete Container-Orchestrierungs-Platform. Wird zur Erstellung von hochskalierbaren Microservice-Architekturen verwendet. Es fallen Kosten für die verwendeten VMs an.
* **[Azure Quantum]**: Marketplace für Anwendungen von Quantencomputern (noch in Vorschau).
* **[Azure Spring Cloud]**: Verwaltete VMWare Spring Cloud, wird zur Erstellung von Microservice-Architekturen auf Basis von Spring Boot und .NET Core Steeltoe verwendet.
* **[VMWare-Lösungen in Azure]**: Erlaubt die Migration von VMWare Lösungen aus dem on-premise Rechenzentrum in die Cloud.
* **[Batch]**: Stapelverarbeitung (z.B. Lohnabrechnungen, Simulationen, Berechnen von Portfoliorisiken, Software Tests, etc.) auf skalierbaren Ressourcen. Kann als Lösung an Kunden angeboten werden.
* **[Cloud Services]**: Platform as a Service (PaaS). Die Anwendung, z.B. Web-App, wird auf einer von Microsoft verwalteten VM betrieben (d.h. Microsoft kümmert sich um Konfiguration, Sicherheitsupdates, etc.)
* **[Container Instances] (ACI)**: Container-Orchestrierungs-Platform, als Alternative zu [AKS](#AKS). Für die VMs fallen keine zusätzlichen Kosten an.
* **[Virtuelle Computer]**: Infrastructure as a Service (IaaS). Virtuelle Computer (VMs) mit Linux und Windows Betriebbsystem. Verfügbar mit unterschiedlichen Leistungsmerkmalen (CPU, Speicherplatz, Memory, etc.).
* **[Mobile Apps]**: Bereitstellen von Backends für Mobile Apps. Nach Kunden segmentierte Push-Nachrichten, AD-Anmeldung für Unternehmenskunden. Offline-Synchronisation. Social-Media-Integration. App-Zugriff auf Unternehmensdaten (lokal und Cloud).
* **[Service Fabric]**: Betrieb von hochverfügbaren, verteilten Apps, Microservices und Containern. Wird von einer Vielzahl von Microsoft-Produkten und Azure-Services verwendet (Skype for Business, Intune, Event Hubs, Data Factory, Cosmos DB, ...). [Vergleich AKS vs. Service Fabric]
* **[SQL Server auf VM]**: Betrieb von MS SQL Server auf einer von Microsoft verwalteten VM. Voller Funktionsumfang von on-premise SQL Server, aber höhere Kosten als die SaaS-Version von SQL Server.
* **[Statische Web-Apps]** (Vorschau): Vereinfachte Entwicklung und Betrieb von statischen Web-Frontents, welche dynamische, serverlose Backends nutzen.
* **[Microsoft Azure Virtual Machine Scale Sets]**: Zur Verwaltung und Skalierung grosser Anzahl von virtueller Maschinen.
* **[Azure Dedicated Host]**: Dedizierte physische Server zum Hosten von VMs. Der Server wird nicht mit anderen Kunden geteilt, was zur Erfüllung von Compliance-Vorgaben nötig sein kann.

[API-Apps]: https://azure.microsoft.comg/services/app-service/api/
[App Service]: https://azure.microsoft.comg/services/app-service
[Azure CycleCloud]: https://azure.microsoft.comg/features/azure-cyclecloud/
[Azure Functions]: https://azure.microsoft.comg/services/functions/
[Azure Kubernetes Service]: https://azure.microsoft.comg/services/kubernetes-service/
[Azure Quantum]: https://azure.microsoft.comg/services/quantum/
[Azure Spring Cloud]: https://azure.microsoft.comg/services/spring-cloud/
[VMWare-Lösungen in Azure]: https://azure.microsoft.comg/services/azure-vmware/
[Batch]: https://azure.microsoft.comg/services/batch/
[Cloud Services]: https://azure.microsoft.comg/services/cloud-services/
[Container Instances]: https://azure.microsoft.comg/services/container-instances/
[Virtuelle Computer]: https://azure.microsoft.comg/services/virtual-machines/
[Mobile Apps]: https://azure.microsoft.comg/services/app-service/mobile/
[Service Fabric]: https://azure.microsoft.comg/services/service-fabric/
[Vergleich AKS vs. Service Fabric]: https://docs.microsoft.com/en-us/archive/blogs/azuredev/service-fabric-and-kubernetes-comparison-part-1-distributed-systems-architecture
[SQL Server auf VM]: https://azure.microsoft.comg/services/virtual-machines/sql-server/
[Statische Web-Apps]: https://azure.microsoft.comg/services/app-service/static/
[Microsoft Azure Virtual Machine Scale Sets]: https://azure.microsoft.comg/services/virtual-machine-scale-sets/
[Azure Dedicated Host]: https://azure.microsoft.com/de-de/services/virtual-machines/dedicated-host/