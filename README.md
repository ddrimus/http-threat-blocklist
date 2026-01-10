# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-451-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--01--10-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 451                      |
| Total Reports: 10,581                |
| Unique Sources: 2,915                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3116 ███████████████████████████████████ ( 29.6%)
         HTTP Bad User Agent ▏ 2322 ██████████████████████████ ( 22.0%)
        HTTP Sensitive Files ▏ 1163 █████████████ ( 11.0%)
HTTP Admin Interface Probing ▏ 1163 █████████████ ( 11.0%)
         HTTP Wordpress Scan ▏  682 ███████ (  6.5%)
      HTTP Crawl Non Statics ▏  442 ████ (  4.2%)
     HTTP Backdoors Attempts ▏  417 ████ (  4.0%)
       CVE-2017-9841 Exploit ▏  406 ████ (  3.9%)
            HTTP CVE Probing ▏  363 ████ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  140 █ (  1.3%)
      CVE-2022-41082 Exploit ▏  107 █ (  1.0%)
                 Netgear RCE ▏   86 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   47 █ (  0.4%)
 HTTP Path Traversal Probing ▏   41 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   39 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3278 ███████████████████████████████████ ( 36.1%)
United Kingdom ▏ 1661 █████████████████ ( 18.3%)
       Ireland ▏  990 ██████████ ( 10.9%)
   Netherlands ▏  685 ███████ (  7.5%)
        France ▏  505 █████ (  5.6%)
         Japan ▏  500 █████ (  5.5%)
     Singapore ▏  473 █████ (  5.2%)
       Germany ▏  355 ███ (  3.9%)
     Australia ▏  342 ███ (  3.8%)
         India ▏  288 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-01-03 ▏   37 ████████████████████████ ( 13.0%)
2026-01-04 ▏   52 ███████████████████████████████████ ( 18.3%)
2026-01-05 ▏   30 ████████████████████ ( 10.6%)
2026-01-06 ▏   41 ███████████████████████████ ( 14.4%)
2026-01-07 ▏   29 ███████████████████ ( 10.2%)
2026-01-08 ▏   41 ███████████████████████████ ( 14.4%)
2026-01-09 ▏   52 ███████████████████████████████████ ( 18.3%)
2026-01-10 ▏    2 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!