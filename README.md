# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-455-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 455                      |
| Total Reports: 9,884                 |
| Unique Sources: 2,727                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2884 ███████████████████████████████████ ( 29.3%)
         HTTP Bad User Agent ▏ 2173 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏ 1101 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1067 ████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  625 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  414 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  400 ████ (  4.1%)
     HTTP Backdoors Attempts ▏  390 ████ (  4.0%)
            HTTP CVE Probing ▏  348 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  139 █ (  1.4%)
      CVE-2022-41082 Exploit ▏   99 █ (  1.0%)
                 Netgear RCE ▏   80 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   41 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2999 ███████████████████████████████████ ( 35.3%)
United Kingdom ▏ 1602 ██████████████████ ( 18.9%)
       Ireland ▏  960 ███████████ ( 11.3%)
   Netherlands ▏  650 ███████ (  7.7%)
         Japan ▏  472 █████ (  5.6%)
        France ▏  467 █████ (  5.5%)
     Singapore ▏  427 ████ (  5.0%)
     Australia ▏  327 ███ (  3.9%)
       Germany ▏  305 ███ (  3.6%)
      Bulgaria ▏  276 ███ (  3.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-12-16 ▏   39 ███████████████████████████ ( 16.2%)
2025-12-17 ▏   34 ████████████████████████ ( 14.1%)
2025-12-18 ▏   49 ███████████████████████████████████ ( 20.3%)
2025-12-19 ▏   30 █████████████████████ ( 12.4%)
2025-12-20 ▏   29 ████████████████████ ( 12.0%)
2025-12-21 ▏   17 ████████████ (  7.1%)
2025-12-22 ▏   36 █████████████████████████ ( 14.9%)
2025-12-23 ▏    7 █████ (  2.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!