# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-496-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 496                      |
| Total Reports: 5,422                 |
| Unique Sources: 1,572                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1422 ███████████████████████████████████ ( 26.4%)
         HTTP Bad User Agent ▏ 1189 █████████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  578 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  490 ████████████ (  9.1%)
         HTTP Wordpress Scan ▏  425 ██████████ (  7.9%)
       CVE-2017-9841 Exploit ▏  292 ███████ (  5.4%)
      HTTP Crawl Non Statics ▏  276 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  251 ██████ (  4.7%)
            HTTP CVE Probing ▏  184 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  116 ██ (  2.2%)
      CVE-2022-41082 Exploit ▏   51 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
                 Netgear RCE ▏   37 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   15 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1519 ███████████████████████████████████ ( 32.6%)
United Kingdom ▏  807 ██████████████████ ( 17.3%)
       Ireland ▏  711 ████████████████ ( 15.3%)
        France ▏  367 ████████ (  7.9%)
     Singapore ▏  269 ██████ (  5.8%)
     Australia ▏  251 █████ (  5.4%)
         Japan ▏  239 █████ (  5.1%)
   Netherlands ▏  174 ████ (  3.7%)
       Germany ▏  172 ███ (  3.7%)
      Bulgaria ▏  150 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-14 ▏   34 ████████████████ (  8.9%)
2025-09-15 ▏   37 █████████████████ (  9.7%)
2025-09-16 ▏   73 ███████████████████████████████████ ( 19.2%)
2025-09-17 ▏   51 ████████████████████████ ( 13.4%)
2025-09-18 ▏   73 ███████████████████████████████████ ( 19.2%)
2025-09-19 ▏   54 █████████████████████████ ( 14.2%)
2025-09-20 ▏   50 ███████████████████████ ( 13.1%)
2025-09-21 ▏    9 ████ (  2.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!