# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-375-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--22-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 375                      |
| Total Reports: 13,053                |
| Unique Sources: 3,445                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3859 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2628 ███████████████████████ ( 20.2%)
HTTP Admin Interface Probing ▏ 1592 ██████████████ ( 12.3%)
        HTTP Sensitive Files ▏ 1282 ███████████ (  9.9%)
         HTTP Wordpress Scan ▏ 1066 █████████ (  8.2%)
      HTTP Crawl Non Statics ▏  595 █████ (  4.6%)
     HTTP Backdoors Attempts ▏  537 ████ (  4.1%)
            HTTP CVE Probing ▏  456 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  439 ███ (  3.4%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  137 █ (  1.1%)
                 Netgear RCE ▏  104 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   57 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 3993 ███████████████████████████████████ ( 36.5%)
United Kingdom ▏ 1755 ███████████████ ( 16.0%)
       Ireland ▏ 1142 ██████████ ( 10.4%)
   Netherlands ▏  807 ███████ (  7.4%)
     Singapore ▏  668 █████ (  6.1%)
         Japan ▏  659 █████ (  6.0%)
        France ▏  659 █████ (  6.0%)
       Germany ▏  475 ████ (  4.3%)
     Australia ▏  412 ███ (  3.8%)
         India ▏  371 ███ (  3.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-15 ▏   84 ███████████████████████████████████ ( 25.9%)
2026-03-16 ▏   27 ███████████ (  8.3%)
2026-03-17 ▏   22 █████████ (  6.8%)
2026-03-18 ▏   52 █████████████████████ ( 16.0%)
2026-03-19 ▏   32 █████████████ (  9.9%)
2026-03-20 ▏   48 ████████████████████ ( 14.8%)
2026-03-21 ▏   51 █████████████████████ ( 15.7%)
2026-03-22 ▏    8 ███ (  2.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!