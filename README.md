# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-450-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 450                      |
| Total Reports: 1,617                 |
| Unique Sources: 612                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

         HTTP Bad User Agent ▏  412 ███████████████████████████████████ ( 25.6%)
                HTTP Probing ▏  393 █████████████████████████████████ ( 24.4%)
HTTP Admin Interface Probing ▏  166 ██████████████ ( 10.3%)
        HTTP Sensitive Files ▏  130 ███████████ (  8.1%)
         HTTP Wordpress Scan ▏  114 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  102 ████████ (  6.3%)
      HTTP Crawl Non Statics ▏   77 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏   75 ██████ (  4.7%)
            HTTP CVE Probing ▏   50 ████ (  3.1%)
   CVE-2018-20062 (Thinkphp) ▏   44 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏   19 █ (  1.2%)
                 Netgear RCE ▏   10 █ (  0.6%)
 HTTP Path Traversal Probing ▏    9 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.3%)
      CVE-2019-18935 Exploit ▏    4 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  448 ███████████████████████████████████ ( 31.2%)
United Kingdom ▏  331 █████████████████████████ ( 23.1%)
       Ireland ▏  322 █████████████████████████ ( 22.4%)
   Netherlands ▏   69 █████ (  4.8%)
         Japan ▏   58 ████ (  4.0%)
     Singapore ▏   56 ████ (  3.9%)
     Australia ▏   41 ███ (  2.9%)
       Germany ▏   40 ███ (  2.8%)
         China ▏   36 ██ (  2.5%)
      Bulgaria ▏   35 ██ (  2.4%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-10 ▏   53 █████████████████ (  9.8%)
2025-07-11 ▏   72 ████████████████████████ ( 13.3%)
2025-07-12 ▏   63 █████████████████████ ( 11.6%)
2025-07-13 ▏   93 ███████████████████████████████ ( 17.1%)
2025-07-14 ▏   53 █████████████████ (  9.8%)
2025-07-15 ▏  104 ███████████████████████████████████ ( 19.2%)
2025-07-16 ▏   88 █████████████████████████████ ( 16.2%)
2025-07-17 ▏   17 █████ (  3.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!