# [Analysen]

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
* **[Log Analytics]**: Analyse von Log Daten aus [Azure Monitor](/management-tools.md#monitor).
* **[Power BI Embedded]**: White-Label Power BI Komponenten für Kundenseitige Reports, Dashboards, etc.
* **[R-Server for HDInsight]**: Verwalteter Server, um mit der Statistiksoftware R Analysen auf [HDInsight](#hdinsight) durchzuführen.
* **[Azure Purview]**: Daten-Governance - Erstellt Übersichten über Datenlandschaft, klassifiziert vertrauliche Daten und ermittelt Datenherkunft. Für lokale, Cloud- und SaaS-Daten.
* **[Microsoft Graph Data Connect]**: Import grosser Mengen Microsoft 365 Daten nach [Data Factory](#factory) zur weiteren Verarbeitung und Speicherung. Z.B. können dann Machine-Learning-Modelle damit trainiert werden.

[Analysen]: https://azure.microsoft.com/de-de/services/#analytics
[Azure Analysis Services]: https://azure.microsoft.com/de-de/services/analysis-services/
[Azure Daten-Explorer]: https://azure.microsoft.com/de-de/services/data-explorer/
[Azure Data Lake Storage]: https://azure.microsoft.com/de-de/services/storage/data-lake-storage/
[Azure Data Share]: https://azure.microsoft.com/de-de/services/data-share/
[Azure Databricks]: https://azure.microsoft.com/de-de/services/databricks/
[Azure Stream Analytics]: https://azure.microsoft.com/de-de/services/stream-analytics/
[Azure Synapse Analytics]: https://azure.microsoft.com/de-de/services/synapse-analytics/
[Azure Data Catalog]: https://azure.microsoft.com/de-de/services/data-catalog/
[Data Factory]: https://azure.microsoft.com/de-de/services/data-factory/
[Data Lake Analytics]: https://azure.microsoft.com/de-de/services/data-lake-analytics/
[Event Hubs]: https://azure.microsoft.com/de-de/services/event-hubs/
[HDInsight]: https://azure.microsoft.com/de-de/services/hdinsight
[Log Analytics]: https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview
[Power BI Embedded]: https://azure.microsoft.com/de-de/services/power-bi-embedded
[R-Server for HDInsight]: https://azure.microsoft.com/de-de/services/hdinsight/r-server/
[Azure Purview]: https://azure.microsoft.com/de-de/services/purview/
[Microsoft Graph Data Connect]: https://azure.microsoft.com/de-de/services/graph-data-connect/