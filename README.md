# SOC Lab met Wazuh & Sysmon

**Status:** Actief — Part 1 t/m 6 afgerond, Part 7 (laatste deel) volgt binnenkort.
**Auteur:** Asmerom — Junior IT System Engineer & Support Technician.

Dit project is gebaseerd op de "Wazuh SOC Analyst Challenge" van [MyDFIR](https://www.youtube.com/@MyDFIR).

## Doel
Een werkend SOC opbouwen met Wazuh als SIEM-oplossing, zodat ik leer hoe je endpoints monitort, logs analyseert en beveiligingsincidenten opspoort.

## Gebruikte tools
- VMware Workstation Pro
- Ubuntu Server 24.04 (Wazuh-server en tweede endpoint)
- Windows 10 Pro (endpoint)
- Wazuh 4.14 (Manager, Indexer, Dashboard)
- Sysmon (Windows) en Sysmon for Linux

## Documentatie per onderdeel
Elk deel heeft zijn eigen map, met een eigen README en een eigen `images/`-map voor screenshots.

| # | Onderdeel | Map | Status |
|---|-----------|-----|--------|
| 1 | Wazuh-server opzetten | [part1-server-setup/](part1-server-setup/README.md) | ✅ Afgerond |
| 2 | Agents koppelen | [part2-agents/](part2-agents/README.md) | ✅ Afgerond |
| 3 | Telemetrie genereren en logs analyseren | [part3-log-analysis/](part3-log-analysis/README.md) | ✅ Afgerond |
| 4 | Dashboard bouwen | [part4-dashboard/](part4-dashboard/README.md) | ✅ Afgerond |
| 5 | File Integrity Monitoring en een eigen detectieregel | [part5-fim-detection-rule/](part5-fim-detection-rule/README.md) | ✅ Afgerond |
| 6 | Automatisch reageren met Active Response | [part6-active-response/](part6-active-response/README.md) | ✅ Afgerond |
| 7 | SOC-investigatie (eindopdracht) | *volgt* | ⏳ Nog te doen |

## Mapstructuur
```
wazuh-soc-lab/
├── README.md                        ← dit bestand (overzicht)
├── part1-server-setup/
│   ├── README.md                    ← documentatie van dit deel
│   └── images/                      ← screenshots van dit deel
├── part2-agents/
│   ├── README.md
│   └── images/
├── part3-log-analysis/
│   ├── README.md
│   └── images/
├── part4-dashboard/
│   ├── README.md
│   └── images/
├── part5-fim-detection-rule/
│   ├── README.md
│   └── images/
└── part6-active-response/
    ├── README.md
    └── images/
```


