# Hallo, ich bin Mike 👋

Ich absolviere eine Umschulung zum **IT-Systemelektroniker** und beschäftige mich auch außerhalb des Unterrichts intensiv mit Netzwerktechnik, Linux und IT-Infrastruktur.

Mein berufliches Ziel liegt in der IT-Administration, Netzwerktechnik und im Systembetrieb. Dafür verbinde ich die Inhalte meiner Umschulung mit eigenen praktischen Projekten: Ich plane Netzwerke, konfiguriere Firewalls und Switches, betreibe virtuelle Maschinen und Container und arbeite an nachvollziehbaren Backup- und Wiederherstellungsverfahren.

Auch die praktische IT-Sicherheit gehört zu meinen Interessen. In meinem eigenen Testnetz beschäftige ich mich mit Kali Linux, der Aufzeichnung von WLAN-4-Way-Handshakes und anschließenden Offline-Passwortprüfungen mit Hashcat.

Dieses GitHub-Profil dokumentiert meinen Lernweg – mit funktionierenden Lösungen, offenen Baustellen und den Erkenntnissen aus der Fehlersuche.

## 🎯 Was mich antreibt

Ich möchte nicht nur wissen, welche Einstellung funktioniert, sondern auch verstehen, warum sie funktioniert und welche Auswirkungen Änderungen auf das Gesamtsystem haben.

Besonders interessieren mich:

- Netzwerksegmentierung mit VLANs, Routing und kontrollierten Zugriffen zwischen Netzbereichen
- Firewall-Administration und sichere Fernwartung
- Linux-Serverbetrieb, Virtualisierung und Container
- Monitoring, Automatisierung und zuverlässige Backups
- Praktische IT-Sicherheit und die Überprüfung der eigenen Infrastruktur
- WLAN-Sicherheit und die Bedeutung widerstandsfähiger Passwörter
- Das Zusammenspiel von Hardware, Verkabelung und Konfiguration

## 🏠 Mein Homelab

Mein Homelab ist meine praktische Lern- und Testumgebung. Hier baue ich eine Infrastruktur auf, die ich schrittweise erweitere, überprüfe und dokumentiere.

| Bereich | Aufbau und Themen |
|---|---|
| Firewall und Routing | OPNsense auf einem Intel NUC, Firewall-Regeln und Inter-VLAN-Routing |
| Switching | TP-Link Omada SG2008P, VLAN-Zuordnung sowie Trunk- und Access-Ports |
| Netzwerkstruktur | Getrennte Bereiche für Administration, Labor, Clients, IoT und Gäste |
| Netzwerkdienste | DNS und DHCP mit Dnsmasq |
| Virtualisierung | Proxmox VE auf einem weiteren Intel NUC |
| Server und Container | Ubuntu Server als virtuelle Maschine für Docker-Dienste |
| Fernzugriff | Tailscale für den Zugriff auf die eigene Infrastruktur |
| Sicherheitslabor | Kali Linux, Aufzeichnung von WLAN-4-Way-Handshakes und Offline-Passwortprüfungen mit Hashcat |
| Betrieb und Weiterentwicklung | Monitoring, Backup-Automatisierung und Restore-Tests |

Nicht jeder Teil ist endgültig fertig: Das Homelab entwickelt sich mit meinem Wissen und meinen Anforderungen weiter.

## 🧪 Meine Projekte

| Projekt | Inhalt | Status |
|---|---|---|
| [Segmentiertes Heimnetz](https://github.com/ProOstSport/homelab-network-vlan) | Netzwerkplanung, VLANs, OPNsense, Managed Switch, DHCP/DNS und Zugriffsregeln | laufend |
| [Proxmox-Virtualisierung](https://github.com/ProOstSport/homelab-proxmox) | Proxmox VE auf einem Intel NUC und Ubuntu-VM als Grundlage für Docker-Dienste | abgeschlossen |
| [NUC als Homeserver](https://github.com/ProOstSport/homelab-nuc-server) | Linux-Serverbetrieb, Docker, Monitoring, automatisierte Backups und Restore-Tests | laufend |
| [Passwortverwaltung](https://github.com/ProOstSport/homelab-keepassxc-syncthing) | Erprobung einer Passwortverwaltung mit KeePassXC, Containerbetrieb, Syncthing und Offlinezugriff | Testbetrieb |

Die jeweiligen Repositories beschreiben den dokumentierten Projektstand, bekannte Einschränkungen und nächste Schritte.

## 🔐 Praktische Erfahrungen mit IT-Sicherheit

In meinem eigenen, kontrollierten Testnetz habe ich Erfahrungen mit Kali Linux und der Untersuchung von WLAN-Sicherheit gesammelt.

Dazu gehören:

- Arbeiten mit Kali Linux als Umgebung für Sicherheitsanalysen
- Aufzeichnen von WLAN-4-Way-Handshakes im eigenen Testnetz
- Weiterverarbeiten der aufgezeichneten Daten für Offline-Passwortprüfungen mit Hashcat
- Auswerten und Einordnen der Testergebnisse
- Auseinandersetzung mit Passwortqualität und möglichen Schutzmaßnahmen

Dabei geht es mir darum, Schwachstellen zu verstehen und daraus Verbesserungen für die eigene Infrastruktur abzuleiten.

Sicherheitstests führe ich ausschließlich an eigenen Systemen oder mit ausdrücklicher Erlaubnis durch. Zugangsdaten, sensible Aufzeichnungen und fremde Daten gehören nicht in öffentliche Repositories.

## 🛠️ Technologien und praktische Schwerpunkte

### Netzwerk und Sicherheit

OPNsense · TP-Link Omada · VLAN / IEEE 802.1Q · IPv4 und Subnetting · Routing · Firewall-Regeln · DNS / DHCP · Dnsmasq · Tailscale

### Sicherheitsanalyse im Testnetz

Kali Linux · WLAN-Sicherheitsanalyse · Aufzeichnung von 4-Way-Handshakes · Hashcat · Offline-Passwortprüfungen

### Server und Virtualisierung

Linux / Ubuntu Server · Proxmox VE · virtuelle Maschinen · Docker / Docker Compose · SSH · systemd

### Monitoring, Automatisierung und Werkzeuge

Prometheus · Grafana · Uptime Kuma · Bash · Syncthing · KeePassXC · Git / GitHub · Markdown

Die Technologien gehören zu meinen Projekten und Lernfeldern. Mein Kenntnisstand wächst mit der praktischen Umsetzung – ich erhebe keinen Anspruch, bereits jedes Werkzeug vollständig zu beherrschen.

## 📚 Woran ich weiterarbeite

- Firewall-Regeln und Netzwerkzugriffe gezielt planen, testen und dokumentieren
- Mein Verständnis von IPv6, Routing und Netzwerksicherheit vertiefen
- Sicherheitsanalysen im eigenen Labor strukturiert durchführen und Ergebnisse nachvollziehbar dokumentieren
- Erkenntnisse aus WLAN- und Passworttests in konkrete Schutzmaßnahmen übertragen
- Wiederkehrende Verwaltungsaufgaben mit Skripten automatisieren
- Monitoring und Backup-Verfahren weiterentwickeln
- Fehler systematischer eingrenzen und Lösungen reproduzierbar festhalten
- Grundlagen in Java, SQL und der Arbeit mit Node-RED ausbauen

## 📐 So arbeite ich

- Schrittweise statt blind: Änderungen möglichst einzeln durchführen und ihre Auswirkungen prüfen.
- Erst verstehen, dann übernehmen: Befehle und Konfigurationen nachvollziehen, statt sie nur zu kopieren.
- Fehler dokumentieren: Symptome, Ursachen, Lösungswege und Erkenntnisse festhalten.
- Wiederherstellung mitdenken: Vor größeren Eingriffen sichern und die Nutzbarkeit der Backups überprüfen.
- Offen mit dem Projektstand umgehen: Geplante, getestete und abgeschlossene Funktionen klar unterscheiden.
- Sicherheitsanalysen klar begrenzen: Nur eigene oder ausdrücklich freigegebene Systeme innerhalb eines festgelegten Testumfangs untersuchen.
- Sensible Daten schützen: Keine Passwörter, privaten Schlüssel oder sonstigen Zugangsdaten veröffentlichen; Konfigurationen und Screenshots vor dem Hochladen prüfen.
- Nachvollziehbar dokumentieren: Ziele, Aufbau, Entscheidungen, Tests und offene Punkte gehören zum Projekt.

## 🚀 Mein Ziel mit GitHub

Ich nutze GitHub als technische Dokumentation und als Portfolio meiner praktischen Entwicklung.

Meine Projekte sollen zeigen, wie ich an Aufgaben herangehe: von der Planung über die Umsetzung und Fehlersuche bis zur Überprüfung und Dokumentation.

Dabei geht es mir nicht um eine perfekte Musterumgebung, sondern um nachvollziehbare Arbeit und ein immer besseres Verständnis der Technik.

## 📫 Kontakt und Austausch

Fragen, Verbesserungsvorschläge und konstruktives Feedback sind willkommen.

Am einfachsten erreichst du mich über die Issues im jeweiligen Repository. Bitte beziehe dich dabei auf das konkrete Projekt und veröffentliche keine sensiblen Daten.
