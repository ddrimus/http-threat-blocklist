# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-490-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--22-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 490                      |
| Total Reports: 2,038                 |
| Unique Sources: 721                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  500 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  491 ██████████████████████████████████ ( 24.2%)
HTTP Admin Interface Probing ▏  217 ███████████████ ( 10.7%)
        HTTP Sensitive Files ▏  169 ███████████ (  8.3%)
         HTTP Wordpress Scan ▏  150 ██████████ (  7.4%)
       CVE-2017-9841 Exploit ▏  126 ████████ (  6.2%)
      HTTP Crawl Non Statics ▏  102 ███████ (  5.0%)
     HTTP Backdoors Attempts ▏  101 ███████ (  5.0%)
   CVE-2018-20062 (Thinkphp) ▏   62 ████ (  3.1%)
            HTTP CVE Probing ▏   58 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   22 █ (  1.1%)
                 Netgear RCE ▏   11 █ (  0.5%)
 HTTP Path Traversal Probing ▏    9 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  562 ███████████████████████████████████ ( 31.0%)
United Kingdom ▏  415 █████████████████████████ ( 22.9%)
       Ireland ▏  384 ███████████████████████ ( 21.2%)
   Netherlands ▏   88 █████ (  4.8%)
         Japan ▏   81 █████ (  4.5%)
     Australia ▏   78 ████ (  4.3%)
     Singapore ▏   77 ████ (  4.2%)
       Germany ▏   53 ███ (  2.9%)
         China ▏   42 ██ (  2.3%)
      Bulgaria ▏   35 ██ (  1.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-15 ▏   94 ███████████████████████████████ ( 15.2%)
2025-07-16 ▏   88 █████████████████████████████ ( 14.2%)
2025-07-17 ▏   88 █████████████████████████████ ( 14.2%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 16.9%)
2025-07-19 ▏   85 ████████████████████████████ ( 13.7%)
2025-07-20 ▏   66 ██████████████████████ ( 10.6%)
2025-07-21 ▏   93 ███████████████████████████████ ( 15.0%)
2025-07-22 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!