# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-563-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--26-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 563                      |
| Total Reports: 4,142                 |
| Unique Sources: 1,234                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1038 ███████████████████████████████████ ( 25.1%)
         HTTP Bad User Agent ▏  927 ███████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  452 ███████████████ ( 10.9%)
        HTTP Sensitive Files ▏  361 ████████████ (  8.7%)
         HTTP Wordpress Scan ▏  339 ███████████ (  8.2%)
       CVE-2017-9841 Exploit ▏  261 ████████ (  6.3%)
      HTTP Crawl Non Statics ▏  200 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏  199 ██████ (  4.8%)
            HTTP CVE Probing ▏  131 ████ (  3.2%)
   CVE-2018-20062 (Thinkphp) ▏  109 ███ (  2.6%)
      CVE-2022-41082 Exploit ▏   33 █ (  0.8%)
                 Netgear RCE ▏   27 █ (  0.7%)
 HTTP Path Traversal Probing ▏   26 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.3%)
      CVE-2019-18935 Exploit ▏   11 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1101 ███████████████████████████████████ ( 30.6%)
United Kingdom ▏  625 ███████████████████ ( 17.4%)
       Ireland ▏  562 █████████████████ ( 15.6%)
        France ▏  266 ████████ (  7.4%)
     Australia ▏  245 ███████ (  6.8%)
         Japan ▏  233 ███████ (  6.5%)
     Singapore ▏  204 ██████ (  5.7%)
      Bulgaria ▏  126 ████ (  3.5%)
   Netherlands ▏  125 ███ (  3.5%)
       Germany ▏  111 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-19 ▏   67 ████████████████████████████████ ( 14.6%)
2025-08-20 ▏   70 ██████████████████████████████████ ( 15.2%)
2025-08-21 ▏   65 ███████████████████████████████ ( 14.1%)
2025-08-22 ▏   65 ███████████████████████████████ ( 14.1%)
2025-08-23 ▏   64 ███████████████████████████████ ( 13.9%)
2025-08-24 ▏   50 ████████████████████████ ( 10.9%)
2025-08-25 ▏   72 ███████████████████████████████████ ( 15.7%)
2025-08-26 ▏    7 ███ (  1.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!