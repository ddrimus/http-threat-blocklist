# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-491-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 491                      |
| Total Reports: 6,507                 |
| Unique Sources: 1,896                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1742 ███████████████████████████████████ ( 26.9%)
         HTTP Bad User Agent ▏ 1469 █████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  690 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  624 ████████████ (  9.7%)
         HTTP Wordpress Scan ▏  460 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  328 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  305 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏  277 █████ (  4.3%)
            HTTP CVE Probing ▏  243 ████ (  3.8%)
   CVE-2018-20062 (Thinkphp) ▏  125 ██ (  1.9%)
      CVE-2022-41082 Exploit ▏   67 █ (  1.0%)
                 Netgear RCE ▏   52 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   24 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1913 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1003 ██████████████████ ( 18.0%)
       Ireland ▏  754 █████████████ ( 13.5%)
        France ▏  395 ███████ (  7.1%)
   Netherlands ▏  305 █████ (  5.5%)
     Singapore ▏  302 █████ (  5.4%)
         Japan ▏  274 █████ (  4.9%)
     Australia ▏  266 ████ (  4.8%)
       Germany ▏  203 ███ (  3.6%)
      Bulgaria ▏  165 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-09 ▏   35 ████████████████ (  9.7%)
2025-10-10 ▏   30 █████████████ (  8.3%)
2025-10-11 ▏   43 ███████████████████ ( 11.9%)
2025-10-12 ▏   38 █████████████████ ( 10.5%)
2025-10-13 ▏   76 ███████████████████████████████████ ( 21.0%)
2025-10-14 ▏   58 ██████████████████████████ ( 16.0%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 21.0%)
2025-10-16 ▏    6 ██ (  1.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!