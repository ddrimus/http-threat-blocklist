# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-463-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 463                      |
| Total Reports: 1,697                 |
| Unique Sources: 634                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  428 ███████████████████████████████████ ( 25.4%)
                HTTP Probing ▏  412 █████████████████████████████████ ( 24.4%)
HTTP Admin Interface Probing ▏  174 ██████████████ ( 10.3%)
        HTTP Sensitive Files ▏  135 ███████████ (  8.0%)
         HTTP Wordpress Scan ▏  120 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  108 ████████ (  6.4%)
      HTTP Crawl Non Statics ▏   81 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏   80 ██████ (  4.7%)
            HTTP CVE Probing ▏   53 ████ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏   49 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   19 █ (  1.1%)
                 Netgear RCE ▏   10 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  462 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  348 ██████████████████████████ ( 23.1%)
       Ireland ▏  341 █████████████████████████ ( 22.6%)
   Netherlands ▏   72 █████ (  4.8%)
     Singapore ▏   58 ████ (  3.9%)
         Japan ▏   58 ████ (  3.9%)
       Germany ▏   45 ███ (  3.0%)
     Australia ▏   45 ███ (  3.0%)
         China ▏   42 ███ (  2.8%)
      Bulgaria ▏   35 ██ (  2.3%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-11 ▏   69 ███████████████████████ ( 12.2%)
2025-07-12 ▏   63 █████████████████████ ( 11.1%)
2025-07-13 ▏   93 ███████████████████████████████ ( 16.4%)
2025-07-14 ▏   53 █████████████████ (  9.3%)
2025-07-15 ▏  104 ███████████████████████████████████ ( 18.3%)
2025-07-16 ▏   88 █████████████████████████████ ( 15.5%)
2025-07-17 ▏   88 █████████████████████████████ ( 15.5%)
2025-07-18 ▏    9 ███ (  1.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!