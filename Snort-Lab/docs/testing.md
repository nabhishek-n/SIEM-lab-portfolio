# Snort Alert Testing Procedure

## Environment

- Snort: Snort++ 3.12.2.0
- OS: Ubuntu 24.04.4 LTS
- Interface: lo
- Detection mode: Live packet monitoring

## 1. Start Snort

Snort was started using:

```bash
sudo snort -c /usr/local/snort/etc/snort/snort.lua -i lo -A alert_fast
