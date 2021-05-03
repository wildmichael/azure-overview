# [Netzwerk]

* **[Application Gateway]**: Applikations-Gateway mit Lastenausgleich,
    Layer-7-Routing, SSL-Offloading und Zertifikats-Verwaltung, Unterstützung
    für private, öffentliche und hybride Web-Applikationen,
    Web-Applikations-Firewall, 99.95% Verfügbarkeits-SLA.
* **[Azure Bastion]**: Verwalteter Dienst für den privaten Zugriff auf
    Cloud-VMs mit RDP und SSH-Protokoll, ohne dass deren IP-Adressen vom öffentlichen Internet zugänglich wären.
* **[Azure DNS]**: Domain-Name-Service von Microsoft. Unterstützt private
    DNS-Zonen für virtuelle Netzwerke. Private und öffentliche Zonen können
    den gleichen DNS-Namen ohne Konflikt verwenden.
* **[Azure Firewall]**: Stateful Firewall für die virtuellen Cloud-Netzwerke.
    Skaliert dynamisch ohne dass die Kapazitäten vorreserviert werden müssen.
    Mit TLS-Inspektion und Angriffserkennungs- und Verhinderungssystem.
* **[Azure Load Balancer]**: Lastenausgleich und automatische Skalierung der
    Ressourcen mit Integritätsprüfungen. Direkte Integration mit Cloud VMs
    und Diensten. Sowohl für privaten als auch Internetverkehr. NAT-Regeln
    für höhere Sicherheit. Unterstützt IPv6.
* **[Azure Firewall Manager]**: Zentrales Verwaltungstool für Netzwerk-Policies
    und Routing-Management für global verteilte, Software-definierte Perimeter.
    Konfiguration und Logging für mehrere Azure Firewall Instanzen und mehrere
    virtuelle Netzwerke. Kann mit Third-Party Security-as-a-Service Anbietern
    integriert werden.
* **[Azure Front Door]**: Ein verwaltetes Content Distribution Network (CDN)
    mit eingebauten Sicherheits-Tools, wie Schutz vor DDoS und
    Bot-Netzwerken. Die Web-Applikation-Firewall (WAF) bietet SSL-Offloading.
    Der Premium Service (Vorschau) bietet zusätzlich eine Platform für die
    statische und dynamische Beschleunigung und Echtzeit-Analysen.
* **[Azure Internet Analyzer]** (Vorschau): Erlaubt das Testen von Änderungen
    an der Netzwerkinfrastruktur bezüglich der Leistung für Kunden.
    Verschiedene Azure Dienste, z.B. das Azure Content Delivery Network und
    Azure Front Door, können ausprobiert und die Veränderungen in der
    Performance gemessen und analysiert werden.
* **[Azure Private Link]**: Dienst, um virtuelle Netzwerke von Kunden mit den
    eigenen Azure Diensten und on-premise und Peer-Netzwerken zu verbinden, ohne dass
    die Daten über das öffentliche Internet fliessen. Bietet Schutz vor
    Datenexfiltration.
* **[Network Watcher]**: Dienst zur Netzwerküberwachung und Paketflussanalyse.
    VPN-Verbindungsprobleme können analysiert und die häufig auftretenden
    können automatisch diagnostiziert werden. Die erstellten
    Datenflussprotokolle und Muster können zur Erfüllung von
    Compliance-Vorgaben und zur Überwachung des Netzwerksicherheitsprofils
    verwendet werden.
* **[Traffic Manager]**: Dienst für DNS-basierten Lastausgleich und
    automatisches Failover. Lokale und Cloud-Dienste können nahtlos
    integriert werden. Es stehen verschiedene Routingmethoden zur Verfügung:
    Priorität, Leistung, geographische Distanz, gewichteter Roundrobin,
    Subnetz und MultiValue. Mittels geschachtelter Profile können die
    Methoden hierarchisch kombiniert werden. Kann für Geofencing verwendet
    werden. Die Integration mit on-premise Ressourcen ist möglich.
* **[Virtual Network]**: Virtuelle Netzwerkkonfiguration für Cloud-Ressourcen
    und Hybridinfrastruktur. Kann mit IPsec-VPN oder
    [ExpressRoute](/hybrid-multicloud.md) kombiniert werden.
    Eigene IP-Adressen und DNS-Server. Datenverkehr zwischen Subnetzen kann
    kontrolliert werden.
* **[Virtual WAN]**: Dienst für einheitliche, globale Konnektivität und
    Sicherheit. Kann für automatisierte Verbindungen zwischen Filialen
    verwendet werden.
* **[VPN Gateway]**: IPSec VPN für Site-to-Site-Verbindungen und der Anbindung
    lokaler Infrastruktur mit der Cloud. SLA mit 99.9% Verfügbarkeit.
* **[Web Application Firewall]**: Schützt Web-Applikationen vor 10 der
    gängigsten Sicherheitsrisiken, wie SQL Injection oder Cross Site
    Scripting. Anpassbare Regeln. Überwachung mittels [Azure
    Monitor](/management-tools.md).
* **[Azure Orbital]** (Vorschau): Dienst zur Planung von Satellitenverbindungen
    und Datentransfer mit der Cloud über eine Satellitenverbindung ohne
    eigene Erdfunkstelleninfrastruktur. Erlaubt aber auch das Planen und
    Bereitstellen eigener Satelliten-/Erdstelleninfrastruktur und diese als
    Dienst anzubieten.
* **[Azure Route Server]** (Vorschau): Erlaubt es eigener Netzwerkinfrastruktur
  Routing-Informationen mit virtuellen Netzwerken in der Cloud auszutauschen.
  So kann die Konfiguration von Netzwerken, VPN und ExpressRoute automatisch
  angepasst werden, ohne dass diese einzeln konfiguriert werden müssen.

[Netzwerk]: https://azure.microsoft.com/de-de/services/#networking
[Application Gateway]: https://azure.microsoft.com/de-de/services/application-gateway/
[Azure Bastion]: https://azure.microsoft.com/de-de/services/azure-bastion/
[Azure DNS]: https://azure.microsoft.com/de-de/services/dns/
[Azure Firewall]: https://azure.microsoft.com/de-de/services/azure-firewall/
[Lastenausgleich]: https://azure.microsoft.com/de-de/products/azure-load-balancing/
[Azure Firewall Manager]: https://azure.microsoft.com/de-de/services/firewall-manager/
[Azure Front Door]: https://azure.microsoft.com/de-de/services/frontdoor/
[Azure Internet Analyzer]: https://azure.microsoft.com/de-de/services/internet-analyzer/
[Azure Private Link]: https://azure.microsoft.com/de-de/services/private-link/
[Network Watcher]: https://azure.microsoft.com/de-de/services/network-watcher/
[Traffic Manager]: https://azure.microsoft.com/de-de/services/traffic-manager/
[Virtual Network]: https://azure.microsoft.com/de-de/services/virtual-network/
[Virtual WAN]: https://azure.microsoft.com/de-de/services/virtual-wan/
[VPN Gateway]: https://azure.microsoft.com/de-de/services/vpn-gateway/
[Web Application Firewall]: https://azure.microsoft.com/de-de/services/web-application-firewall/
[Azure Orbital]: https://azure.microsoft.com/de-de/services/orbital/
[Azure Route Server]: https://azure.microsoft.com/de-de/services/route-server/
[Azure Load Balancer]: https://azure.microsoft.com/de-de/services/load-balancer/
