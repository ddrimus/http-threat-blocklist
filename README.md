# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-564-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--09--05-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 564                      |
| Total Reports: 4,659                 |
| Unique Sources: 1,393                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1193 ███████████████████████████████████ ( 25.7%)
         HTTP Bad User Agent ▏ 1044 ██████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  496 ██████████████ ( 10.7%)
        HTTP Sensitive Files ▏  409 ███████████ (  8.8%)
         HTTP Wordpress Scan ▏  373 ██████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  273 ████████ (  5.9%)
      HTTP Crawl Non Statics ▏  233 ██████ (  5.0%)
     HTTP Backdoors Attempts ▏  221 ██████ (  4.8%)
            HTTP CVE Probing ▏  158 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  111 ███ (  2.4%)
      CVE-2022-41082 Exploit ▏   40 █ (  0.9%)
                 Netgear RCE ▏   34 █ (  0.7%)
 HTTP Path Traversal Probing ▏   29 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   16 █ (  0.3%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1239 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  689 ███████████████████ ( 17.2%)
       Ireland ▏  618 █████████████████ ( 15.4%)
        France ▏  332 █████████ (  8.3%)
     Australia ▏  250 ███████ (  6.2%)
         Japan ▏  238 ██████ (  5.9%)
     Singapore ▏  226 ██████ (  5.6%)
       Germany ▏  146 ████ (  3.6%)
   Netherlands ▏  137 ███ (  3.4%)
      Bulgaria ▏  136 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-29 ▏   56 █████████████████████████████████ ( 16.8%)
2025-08-30 ▏   55 ████████████████████████████████ ( 16.5%)
2025-08-31 ▏   48 ████████████████████████████ ( 14.4%)
2025-09-01 ▏   23 █████████████ (  6.9%)
2025-09-02 ▏   40 ███████████████████████ ( 12.0%)
2025-09-03 ▏   59 ███████████████████████████████████ ( 17.7%)
2025-09-04 ▏   52 ██████████████████████████████ ( 15.6%)
2025-09-05 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!