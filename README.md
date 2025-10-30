# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-522-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 522                      |
| Total Reports: 7,388                 |
| Unique Sources: 2,091                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2051 ███████████████████████████████████ ( 27.9%)
         HTTP Bad User Agent ▏ 1619 ███████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  805 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  768 █████████████ ( 10.5%)
         HTTP Wordpress Scan ▏  501 ████████ (  6.8%)
       CVE-2017-9841 Exploit ▏  344 █████ (  4.7%)
      HTTP Crawl Non Statics ▏  326 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  310 █████ (  4.2%)
            HTTP CVE Probing ▏  265 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.7%)
      CVE-2022-41082 Exploit ▏   76 █ (  1.0%)
                 Netgear RCE ▏   62 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2183 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1198 ███████████████████ ( 18.8%)
       Ireland ▏  802 ████████████ ( 12.6%)
        France ▏  429 ██████ (  6.7%)
   Netherlands ▏  423 ██████ (  6.7%)
         Japan ▏  320 █████ (  5.0%)
     Singapore ▏  316 █████ (  5.0%)
     Australia ▏  274 ████ (  4.3%)
       Germany ▏  219 ███ (  3.4%)
         India ▏  196 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-23 ▏   78 ███████████████████████████████████ ( 17.1%)
2025-10-24 ▏   76 ██████████████████████████████████ ( 16.7%)
2025-10-25 ▏   66 █████████████████████████████ ( 14.5%)
2025-10-26 ▏   62 ███████████████████████████ ( 13.6%)
2025-10-27 ▏   50 ██████████████████████ ( 11.0%)
2025-10-28 ▏   61 ███████████████████████████ ( 13.4%)
2025-10-29 ▏   52 ███████████████████████ ( 11.4%)
2025-10-30 ▏   10 ████ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!