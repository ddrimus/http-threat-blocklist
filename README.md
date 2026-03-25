# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-386-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--03--25-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 386                      |
| Total Reports: 13,220                |
| Unique Sources: 3,486                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 3910 ███████████████████████████████████ ( 29.7%)
         HTTP Bad User Agent ▏ 2642 ███████████████████████ ( 20.1%)
HTTP Admin Interface Probing ▏ 1628 ██████████████ ( 12.4%)
        HTTP Sensitive Files ▏ 1290 ███████████ (  9.8%)
         HTTP Wordpress Scan ▏ 1093 █████████ (  8.3%)
      HTTP Crawl Non Statics ▏  611 █████ (  4.6%)
     HTTP Backdoors Attempts ▏  543 ████ (  4.1%)
            HTTP CVE Probing ▏  458 ████ (  3.5%)
       CVE-2017-9841 Exploit ▏  440 ███ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  144 █ (  1.1%)
      CVE-2022-41082 Exploit ▏  139 █ (  1.1%)
                 Netgear RCE ▏  104 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   58 █ (  0.4%)
 HTTP Path Traversal Probing ▏   46 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   45 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 4043 ███████████████████████████████████ ( 36.6%)
United Kingdom ▏ 1757 ███████████████ ( 15.9%)
       Ireland ▏ 1151 █████████ ( 10.4%)
   Netherlands ▏  814 ███████ (  7.4%)
        France ▏  673 █████ (  6.1%)
     Singapore ▏  670 █████ (  6.1%)
         Japan ▏  661 █████ (  6.0%)
       Germany ▏  476 ████ (  4.3%)
     Australia ▏  420 ███ (  3.8%)
        Canada ▏  392 ███ (  3.5%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-03-18 ▏   45 ███████████████████████ ( 12.8%)
2026-03-19 ▏   32 ████████████████ (  9.1%)
2026-03-20 ▏   48 █████████████████████████ ( 13.7%)
2026-03-21 ▏   51 ██████████████████████████ ( 14.5%)
2026-03-22 ▏   67 ███████████████████████████████████ ( 19.1%)
2026-03-23 ▏   47 ████████████████████████ ( 13.4%)
2026-03-24 ▏   59 ██████████████████████████████ ( 16.8%)
2026-03-25 ▏    2 █ (  0.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!