# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-485-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--18-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 485                      |
| Total Reports: 6,614                 |
| Unique Sources: 1,918                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1778 ███████████████████████████████████ ( 27.1%)
         HTTP Bad User Agent ▏ 1488 █████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  707 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  640 ████████████ (  9.7%)
         HTTP Wordpress Scan ▏  465 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  334 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  305 ██████ (  4.6%)
     HTTP Backdoors Attempts ▏  278 █████ (  4.2%)
            HTTP CVE Probing ▏  245 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.9%)
      CVE-2022-41082 Exploit ▏   69 █ (  1.0%)
                 Netgear RCE ▏   53 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   25 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1954 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1028 ██████████████████ ( 18.1%)
       Ireland ▏  754 █████████████ ( 13.3%)
        France ▏  395 ███████ (  7.0%)
   Netherlands ▏  321 █████ (  5.7%)
     Singapore ▏  305 █████ (  5.4%)
         Japan ▏  277 ████ (  4.9%)
     Australia ▏  267 ████ (  4.7%)
       Germany ▏  207 ███ (  3.6%)
      Bulgaria ▏  165 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-11 ▏   41 ██████████████████ ( 10.2%)
2025-10-12 ▏   38 █████████████████ (  9.5%)
2025-10-13 ▏   76 ███████████████████████████████████ ( 18.9%)
2025-10-14 ▏   58 ██████████████████████████ ( 14.4%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 18.9%)
2025-10-16 ▏   63 █████████████████████████████ ( 15.7%)
2025-10-17 ▏   48 ██████████████████████ ( 11.9%)
2025-10-18 ▏    2 █ (  0.5%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!