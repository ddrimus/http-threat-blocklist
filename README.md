# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-486-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--17-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 486                      |
| Total Reports: 6,565                 |
| Unique Sources: 1,907                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1763 ███████████████████████████████████ ( 27.0%)
         HTTP Bad User Agent ▏ 1478 █████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  700 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  632 ████████████ (  9.7%)
         HTTP Wordpress Scan ▏  464 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  332 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  305 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏  278 █████ (  4.3%)
            HTTP CVE Probing ▏  243 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.9%)
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

 United States ▏ 1938 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1015 ██████████████████ ( 18.0%)
       Ireland ▏  754 █████████████ ( 13.4%)
        France ▏  395 ███████ (  7.0%)
   Netherlands ▏  312 █████ (  5.5%)
     Singapore ▏  304 █████ (  5.4%)
         Japan ▏  277 █████ (  4.9%)
     Australia ▏  266 ████ (  4.7%)
       Germany ▏  204 ███ (  3.6%)
      Bulgaria ▏  165 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-10 ▏   19 ████████ (  5.1%)
2025-10-11 ▏   43 ███████████████████ ( 11.5%)
2025-10-12 ▏   38 █████████████████ ( 10.2%)
2025-10-13 ▏   76 ███████████████████████████████████ ( 20.3%)
2025-10-14 ▏   58 ██████████████████████████ ( 15.5%)
2025-10-15 ▏   76 ███████████████████████████████████ ( 20.3%)
2025-10-16 ▏   63 █████████████████████████████ ( 16.8%)
2025-10-17 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!