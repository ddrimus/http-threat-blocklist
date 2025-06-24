# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-LOW-green)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-23-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--06--24-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: LOW                          |
| Active IPs: 23                       |
| Total Reports: 36                    |
| Unique Sources: 23                   |
+--------------------------------------+
```

*Threat levels: boring (and we like it).*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏   13 ███████████████████████████████████ ( 36.1%)
                HTTP Probing ▏   10 ██████████████████████████ ( 27.8%)
         HTTP Wordpress Scan ▏    3 ████████ (  8.3%)
        HTTP Sensitive Files ▏    2 █████ (  5.6%)
      HTTP Crawl Non Statics ▏    2 █████ (  5.6%)
HTTP Admin Interface Probing ▏    2 █████ (  5.6%)
                 Netgear RCE ▏    1 ██ (  2.8%)
            HTTP CVE Probing ▏    1 ██ (  2.8%)
     HTTP Backdoors Attempts ▏    1 ██ (  2.8%)
      CVE-2022-41082 Exploit ▏    1 ██ (  2.8%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏   12 ███████████████████████████████████ ( 33.3%)
       Ireland ▏   11 ████████████████████████████████ ( 30.6%)
United Kingdom ▏    4 ███████████ ( 11.1%)
     Singapore ▏    3 ████████ (  8.3%)
   Netherlands ▏    3 ████████ (  8.3%)
     Argentina ▏    2 █████ (  5.6%)
       Belgium ▏    1 ██ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-06-23 ▏   29 ███████████████████████████████████ ( 80.6%)
2025-06-24 ▏    7 ████████ ( 19.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!