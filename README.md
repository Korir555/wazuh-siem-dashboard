# Wazuh SIEM Dashboard

Enterprise-grade Security Information & Event Management (SIEM) system with real-time threat detection, log aggregation, compliance reporting, and automated incident response.

## Features

- Centralized Log Aggregation: 100+ endpoint and network device log sources
- Real-Time Alert Correlation: Automated threat detection with <30min MTTR
- MITRE ATT&CK Mapping: Framework-aligned threat categorization
- Multi-Framework Compliance: GDPR, HIPAA, PCI-DSS, ISO27001 validation
- Automated Response: Webhook/playbook execution for containment
- Executive Dashboards: Risk, compliance, and incident metrics

## Quick Start

```bash
git clone https://github.com/Korir555/wazuh-siem-dashboard.git
cd wazuh-siem-dashboard
docker-compose up -d
```

Access: https://localhost:443 (admin / wazuh)

## Architecture

Wazuh Manager -> Elasticsearch -> Kibana (Visualization)
  |
  Agents (Linux, Windows, Network Devices)

## Technologies

Wazuh 4.5+ | Elasticsearch 8.0+ | Kibana 8.0+ | Python 3.9+ | Docker

## Hiring Relevance

- Safaricom SOC operations, threat detection
- Enterprise SIEM expertise
- Alert tuning and SOC optimization
- Compliance automation and reporting

## Documentation

Full setup, rule configuration, and playbook examples: Case Study

## License

MIT License
