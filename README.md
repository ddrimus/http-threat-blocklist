# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-490-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--19-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 490                      |
| Total Reports: 6,664                 |
| Unique Sources: 1,929                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1802 ███████████████████████████████████ ( 27.2%)
         HTTP Bad User Agent ▏ 1495 █████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  710 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  645 ████████████ (  9.7%)
         HTTP Wordpress Scan ▏  470 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  334 ██████ (  5.0%)
      HTTP Crawl Non Statics ▏  306 █████ (  4.6%)
     HTTP Backdoors Attempts ▏  280 █████ (  4.2%)
            HTTP CVE Probing ▏  247 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.9%)
      CVE-2022-41082 Exploit ▏   69 █ (  1.0%)
                 Netgear RCE ▏   54 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   25 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1977 ███████████████████████████████████ ( 34.6%)
United Kingdom ▏ 1038 ██████████████████ ( 18.1%)
       Ireland ▏  760 █████████████ ( 13.3%)
        France ▏  395 ██████ (  6.9%)
   Netherlands ▏  324 █████ (  5.7%)
     Singapore ▏  305 █████ (  5.3%)
         Japan ▏  278 ████ (  4.9%)
     Australia ▏  267 ████ (  4.7%)
       Germany ▏  211 ███ (  3.7%)
         India ▏  165 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-12 ▏   37 █████████████████ (  9.0%)
2025-10-13 ▏   76 ███████████████████████████████████ ( 18.5%)
2025-10-14 ▏   58 ██████████████████████████ ( 14.1%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 18.5%)
2025-10-16 ▏   63 █████████████████████████████ ( 15.4%)
2025-10-17 ▏   48 ██████████████████████ ( 11.7%)
2025-10-18 ▏   47 █████████████████████ ( 11.5%)
2025-10-19 ▏    5 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!