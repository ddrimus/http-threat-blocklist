# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-545-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 545                      |
| Total Reports: 8,624                 |
| Unique Sources: 2,380                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2451 ███████████████████████████████████ ( 28.6%)
         HTTP Bad User Agent ▏ 1906 ███████████████████████████ ( 22.2%)
        HTTP Sensitive Files ▏  938 █████████████ ( 10.9%)
HTTP Admin Interface Probing ▏  926 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  561 ████████ (  6.5%)
       CVE-2017-9841 Exploit ▏  370 █████ (  4.3%)
      HTTP Crawl Non Statics ▏  364 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  353 █████ (  4.1%)
            HTTP CVE Probing ▏  312 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  130 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   89 █ (  1.0%)
                 Netgear RCE ▏   74 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   33 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   31 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2549 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1420 ███████████████████ ( 19.2%)
       Ireland ▏  882 ████████████ ( 11.9%)
   Netherlands ▏  565 ███████ (  7.6%)
        France ▏  447 ██████ (  6.0%)
         Japan ▏  424 █████ (  5.7%)
     Singapore ▏  342 ████ (  4.6%)
     Australia ▏  284 ███ (  3.8%)
       Germany ▏  263 ███ (  3.5%)
         India ▏  236 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-14 ▏   62 ███████████████████████████████████ ( 18.6%)
2025-11-15 ▏   40 ██████████████████████ ( 12.0%)
2025-11-16 ▏   62 ███████████████████████████████████ ( 18.6%)
2025-11-17 ▏   39 ██████████████████████ ( 11.7%)
2025-11-18 ▏   30 ████████████████ (  9.0%)
2025-11-19 ▏   48 ███████████████████████████ ( 14.4%)
2025-11-20 ▏   48 ███████████████████████████ ( 14.4%)
2025-11-21 ▏    4 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!