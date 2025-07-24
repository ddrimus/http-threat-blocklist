# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-505-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--07--24-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 505                      |
| Total Reports: 2,217                 |
| Unique Sources: 759                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  544 ███████████████████████████████████ ( 24.6%)
         HTTP Bad User Agent ▏  523 █████████████████████████████████ ( 23.7%)
HTTP Admin Interface Probing ▏  240 ███████████████ ( 10.9%)
        HTTP Sensitive Files ▏  186 ███████████ (  8.4%)
         HTTP Wordpress Scan ▏  165 ██████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  140 █████████ (  6.3%)
     HTTP Backdoors Attempts ▏  114 ███████ (  5.2%)
      HTTP Crawl Non Statics ▏  109 ███████ (  4.9%)
   CVE-2018-20062 (Thinkphp) ▏   67 ████ (  3.0%)
            HTTP CVE Probing ▏   64 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   23 █ (  1.0%)
                 Netgear RCE ▏   12 █ (  0.5%)
 HTTP Path Traversal Probing ▏   10 █ (  0.5%)
       CVE-2021-26086 (Jira) ▏    5 █ (  0.2%)
      CVE-2019-18935 Exploit ▏    5 █ (  0.2%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  602 ███████████████████████████████████ ( 30.5%)
United Kingdom ▏  456 ██████████████████████████ ( 23.1%)
       Ireland ▏  405 ███████████████████████ ( 20.5%)
     Australia ▏  103 █████ (  5.2%)
   Netherlands ▏   94 █████ (  4.8%)
         Japan ▏   92 █████ (  4.7%)
     Singapore ▏   78 ████ (  4.0%)
       Germany ▏   53 ███ (  2.7%)
         China ▏   48 ██ (  2.4%)
      Bulgaria ▏   41 ██ (  2.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-17 ▏   71 ███████████████████████ ( 11.8%)
2025-07-18 ▏  105 ███████████████████████████████████ ( 17.5%)
2025-07-19 ▏   85 ████████████████████████████ ( 14.2%)
2025-07-20 ▏   66 ██████████████████████ ( 11.0%)
2025-07-21 ▏   93 ███████████████████████████████ ( 15.5%)
2025-07-22 ▏   95 ███████████████████████████████ ( 15.8%)
2025-07-23 ▏   84 ████████████████████████████ ( 14.0%)
2025-07-24 ▏    1 █ (  0.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!