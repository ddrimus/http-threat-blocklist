# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-531-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 531                      |
| Total Reports: 3,958                 |
| Unique Sources: 1,191                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  989 ███████████████████████████████████ ( 25.1%)
         HTTP Bad User Agent ▏  876 ███████████████████████████████ ( 22.2%)
HTTP Admin Interface Probing ▏  435 ███████████████ ( 11.0%)
        HTTP Sensitive Files ▏  338 ███████████ (  8.6%)
         HTTP Wordpress Scan ▏  327 ███████████ (  8.3%)
       CVE-2017-9841 Exploit ▏  254 ████████ (  6.4%)
      HTTP Crawl Non Statics ▏  192 ██████ (  4.9%)
     HTTP Backdoors Attempts ▏  189 ██████ (  4.8%)
            HTTP CVE Probing ▏  128 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  108 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   32 █ (  0.8%)
                 Netgear RCE ▏   27 █ (  0.7%)
 HTTP Path Traversal Probing ▏   25 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   10 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1055 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  606 ████████████████████ ( 17.6%)
       Ireland ▏  547 ██████████████████ ( 15.9%)
     Australia ▏  240 ███████ (  7.0%)
        France ▏  235 ███████ (  6.8%)
         Japan ▏  226 ███████ (  6.6%)
     Singapore ▏  192 ██████ (  5.6%)
   Netherlands ▏  122 ████ (  3.5%)
      Bulgaria ▏  114 ███ (  3.3%)
       Germany ▏  102 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-16 ▏   84 ███████████████████████████████████ ( 16.1%)
2025-08-17 ▏   67 ███████████████████████████ ( 12.8%)
2025-08-18 ▏   78 ████████████████████████████████ ( 14.9%)
2025-08-19 ▏   84 ███████████████████████████████████ ( 16.1%)
2025-08-20 ▏   70 █████████████████████████████ ( 13.4%)
2025-08-21 ▏   65 ███████████████████████████ ( 12.5%)
2025-08-22 ▏   65 ███████████████████████████ ( 12.5%)
2025-08-23 ▏    9 ███ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!