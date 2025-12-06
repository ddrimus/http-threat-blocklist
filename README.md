# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-539-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--12--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 539                      |
| Total Reports: 9,331                 |
| Unique Sources: 2,576                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2698 ███████████████████████████████████ ( 29.1%)
         HTTP Bad User Agent ▏ 2045 ██████████████████████████ ( 22.0%)
        HTTP Sensitive Files ▏ 1041 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏ 1010 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  590 ███████ (  6.4%)
      HTTP Crawl Non Statics ▏  391 █████ (  4.2%)
       CVE-2017-9841 Exploit ▏  386 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  373 ████ (  4.0%)
            HTTP CVE Probing ▏  331 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  135 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   94 █ (  1.0%)
                 Netgear RCE ▏   76 █ (  0.8%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   39 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   35 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2803 ███████████████████████████████████ ( 35.0%)
United Kingdom ▏ 1514 ██████████████████ ( 18.9%)
       Ireland ▏  916 ███████████ ( 11.4%)
   Netherlands ▏  617 ███████ (  7.7%)
        France ▏  465 █████ (  5.8%)
         Japan ▏  457 █████ (  5.7%)
     Singapore ▏  393 ████ (  4.9%)
     Australia ▏  297 ███ (  3.7%)
       Germany ▏  287 ███ (  3.6%)
      Bulgaria ▏  254 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-29 ▏   42 ███████████████████████████████ ( 16.3%)
2025-11-30 ▏   34 █████████████████████████ ( 13.2%)
2025-12-01 ▏   47 ███████████████████████████████████ ( 18.2%)
2025-12-02 ▏   39 █████████████████████████████ ( 15.1%)
2025-12-03 ▏   41 ██████████████████████████████ ( 15.9%)
2025-12-04 ▏   24 █████████████████ (  9.3%)
2025-12-05 ▏   27 ████████████████████ ( 10.5%)
2025-12-06 ▏    4 ██ (  1.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!