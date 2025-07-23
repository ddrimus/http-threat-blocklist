# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-500-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 500                      |
| Total Reports: 2,141                 |
| Unique Sources: 743                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  526 ███████████████████████████████████ ( 24.7%)
         HTTP Bad User Agent ▏  508 █████████████████████████████████ ( 23.8%)
HTTP Admin Interface Probing ▏  230 ███████████████ ( 10.8%)
        HTTP Sensitive Files ▏  180 ███████████ (  8.4%)
         HTTP Wordpress Scan ▏  158 ██████████ (  7.4%)
       CVE-2017-9841 Exploit ▏  136 █████████ (  6.4%)
     HTTP Backdoors Attempts ▏  108 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  105 ██████ (  4.9%)
   CVE-2018-20062 (Thinkphp) ▏   66 ████ (  3.1%)
            HTTP CVE Probing ▏   61 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   23 █ (  1.1%)
                 Netgear RCE ▏   11 █ (  0.5%)
 HTTP Path Traversal Probing ▏    9 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  590 ███████████████████████████████████ ( 31.0%)
United Kingdom ▏  433 █████████████████████████ ( 22.7%)
       Ireland ▏  393 ███████████████████████ ( 20.6%)
     Australia ▏   98 █████ (  5.1%)
   Netherlands ▏   93 █████ (  4.9%)
         Japan ▏   84 ████ (  4.4%)
     Singapore ▏   78 ████ (  4.1%)
       Germany ▏   53 ███ (  2.8%)
         China ▏   42 ██ (  2.2%)
      Bulgaria ▏   41 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-16 ▏   86 ████████████████████████████ ( 13.7%)
2025-07-17 ▏   88 █████████████████████████████ ( 14.0%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 16.7%)
2025-07-19 ▏   85 ████████████████████████████ ( 13.6%)
2025-07-20 ▏   66 ██████████████████████ ( 10.5%)
2025-07-21 ▏   93 ███████████████████████████████ ( 14.8%)
2025-07-22 ▏   95 ███████████████████████████████ ( 15.2%)
2025-07-23 ▏    9 ███ (  1.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!