# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-498-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 498                      |
| Total Reports: 6,785                 |
| Unique Sources: 1,958                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1846 ███████████████████████████████████ ( 27.4%)
         HTTP Bad User Agent ▏ 1509 ████████████████████████████ ( 22.4%)
HTTP Admin Interface Probing ▏  726 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  671 ████████████ ( 10.0%)
         HTTP Wordpress Scan ▏  475 █████████ (  7.0%)
       CVE-2017-9841 Exploit ▏  337 ██████ (  5.0%)
      HTTP Crawl Non Statics ▏  309 █████ (  4.6%)
     HTTP Backdoors Attempts ▏  281 █████ (  4.2%)
            HTTP CVE Probing ▏  251 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.9%)
      CVE-2022-41082 Exploit ▏   71 █ (  1.1%)
                 Netgear RCE ▏   56 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2010 ███████████████████████████████████ ( 34.6%)
United Kingdom ▏ 1065 ██████████████████ ( 18.3%)
       Ireland ▏  763 █████████████ ( 13.1%)
        France ▏  402 ███████ (  6.9%)
   Netherlands ▏  344 █████ (  5.9%)
     Singapore ▏  307 █████ (  5.3%)
         Japan ▏  278 ████ (  4.8%)
     Australia ▏  267 ████ (  4.6%)
       Germany ▏  211 ███ (  3.6%)
         India ▏  169 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-14 ▏   50 ███████████████████████ ( 12.2%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 18.5%)
2025-10-16 ▏   63 █████████████████████████████ ( 15.4%)
2025-10-17 ▏   48 ██████████████████████ ( 11.7%)
2025-10-18 ▏   47 █████████████████████ ( 11.5%)
2025-10-19 ▏   69 ███████████████████████████████ ( 16.8%)
2025-10-20 ▏   54 ████████████████████████ ( 13.2%)
2025-10-21 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!