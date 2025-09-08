# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-546-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--08-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 546                      |
| Total Reports: 4,823                 |
| Unique Sources: 1,427                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1247 ███████████████████████████████████ ( 25.9%)
         HTTP Bad User Agent ▏ 1072 ██████████████████████████████ ( 22.3%)
HTTP Admin Interface Probing ▏  515 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  435 ████████████ (  9.0%)
         HTTP Wordpress Scan ▏  383 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  274 ███████ (  5.7%)
      HTTP Crawl Non Statics ▏  245 ██████ (  5.1%)
     HTTP Backdoors Attempts ▏  225 ██████ (  4.7%)
            HTTP CVE Probing ▏  163 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  111 ███ (  2.3%)
      CVE-2022-41082 Exploit ▏   44 █ (  0.9%)
                 Netgear RCE ▏   34 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   17 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1270 ███████████████████████████████████ ( 30.6%)
United Kingdom ▏  723 ███████████████████ ( 17.4%)
       Ireland ▏  639 █████████████████ ( 15.4%)
        France ▏  356 █████████ (  8.6%)
     Australia ▏  250 ██████ (  6.0%)
         Japan ▏  238 ██████ (  5.7%)
     Singapore ▏  234 ██████ (  5.6%)
       Germany ▏  153 ████ (  3.7%)
   Netherlands ▏  149 ████ (  3.6%)
      Bulgaria ▏  140 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-01 ▏   22 ████████████ (  6.5%)
2025-09-02 ▏   40 ███████████████████████ ( 11.8%)
2025-09-03 ▏   59 ██████████████████████████████████ ( 17.5%)
2025-09-04 ▏   52 ██████████████████████████████ ( 15.4%)
2025-09-05 ▏   52 ██████████████████████████████ ( 15.4%)
2025-09-06 ▏   49 ████████████████████████████ ( 14.5%)
2025-09-07 ▏   60 ███████████████████████████████████ ( 17.8%)
2025-09-08 ▏    4 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!