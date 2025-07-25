# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-508-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 508                      |
| Total Reports: 2,281                 |
| Unique Sources: 779                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  559 ███████████████████████████████████ ( 24.6%)
         HTTP Bad User Agent ▏  538 █████████████████████████████████ ( 23.7%)
HTTP Admin Interface Probing ▏  245 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  192 ████████████ (  8.5%)
         HTTP Wordpress Scan ▏  170 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  146 █████████ (  6.4%)
     HTTP Backdoors Attempts ▏  116 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  110 ██████ (  4.8%)
   CVE-2018-20062 (Thinkphp) ▏   70 ████ (  3.1%)
            HTTP CVE Probing ▏   68 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   24 █ (  1.1%)
                 Netgear RCE ▏   13 █ (  0.6%)
 HTTP Path Traversal Probing ▏   10 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  616 ███████████████████████████████████ ( 30.4%)
United Kingdom ▏  469 ██████████████████████████ ( 23.2%)
       Ireland ▏  410 ███████████████████████ ( 20.2%)
     Australia ▏  108 ██████ (  5.3%)
         Japan ▏   98 █████ (  4.8%)
   Netherlands ▏   94 █████ (  4.6%)
     Singapore ▏   80 ████ (  4.0%)
         China ▏   55 ███ (  2.7%)
       Germany ▏   54 ███ (  2.7%)
      Bulgaria ▏   41 ██ (  2.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-18 ▏   96 ███████████████████████████████████ ( 16.4%)
2025-07-19 ▏   85 ██████████████████████████████ ( 14.6%)
2025-07-20 ▏   66 ████████████████████████ ( 11.3%)
2025-07-21 ▏   93 █████████████████████████████████ ( 15.9%)
2025-07-22 ▏   95 ██████████████████████████████████ ( 16.3%)
2025-07-23 ▏   84 ██████████████████████████████ ( 14.4%)
2025-07-24 ▏   60 █████████████████████ ( 10.3%)
2025-07-25 ▏    5 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!