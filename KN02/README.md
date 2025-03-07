# KN02

## Aufgabe 1 
IaaS (Infrastructure as a Service)

IaaS stellt virtuelle Maschinen, Speicher und Netzwerke bereit. Nutzer verwalten Betriebssystem, Anwendungen und Sicherheit selbst.

PaaS (Platform as a Service)

PaaS bietet eine Entwicklungsplattform mit Laufzeitumgebungen und Datenbanken. Nutzer konzentrieren sich auf die Anwendungsentwicklung, ohne die Infrastruktur zu verwalten.

## Aufgabe 2
Automatisierung vs. Manuelle Konfiguration

Vorteile der Automatisierung

Automatisierung sorgt für mehr Konsistenz und reduziert menschliche Fehler. IT-Systeme können schneller bereitgestellt und einfacher skaliert werden. Wiederholbare Prozesse und Versionskontrolle erleichtern die Nachverfolgbarkeit von Änderungen.

Infrastructure as Code (IaC)

Mit IaC wird IT-Infrastruktur per Code beschrieben und verwaltet. Dadurch sind Deployments automatisierbar, wiederholbar und versionierbar. Änderungen können nachvollzogen und leicht zurückgesetzt werden.

Zwei IaC-Tools

Terraform

Terraform ist ein Open-Source-Tool zur Verwaltung von Infrastruktur mit deklarativem Code. Es unterstützt verschiedene Cloud-Anbieter und ermöglicht eine einfache Bereitstellung von Ressourcen.

Docker

Docker ist eine Plattform zur Containerisierung von Anwendungen. Anwendungen laufen in isolierten Containern, die portabel, skalierbar und effizient verwaltbar sind.

Kubernetes & Container-Orchestrierung

Kubernetes

Kubernetes ist eine Open-Source-Plattform zur Automatisierung der Verwaltung containerisierter Anwendungen. Es erleichtert die Bereitstellung, Skalierung und Wartung von Containern in einem Cluster.

Container-Orchestrierung

Container-Orchestrierung steuert und verwaltet Container über mehrere Hosts hinweg. Sie sorgt für automatische Skalierung, Lastverteilung und Selbstheilung der Anwendungen.

Das Repository wurde aktualisiert.

## Aufgabe 3
| Aspekt | IaaS | PaaS |
| --------- | ---- | ---- |
| Verwaltung der Infrastruktur | Benutzer                       |Cloud-Anbieter                        |
| Betriebssystempflege         | Benutzer                       | Cloud-Anbieter                        |
| Skalierung & Ressourcen      | Manuell durch Benutzer         | Automatisiert durch Cloud-Anbieter    |
| Hauptnutzer                  | Systemadministratoren, DevOps  | Entwickler, Software-Teams            |
| Beispiel                     | AWS EC2, Google Compute Engine | Google App Engine, Azure App Services |
