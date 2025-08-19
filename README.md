# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-539-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--19-brightgreen)](.)

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
| Total Reports: 3,682                 |
| Unique Sources: 1,139                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  908 ███████████████████████████████████ ( 24.8%)
         HTTP Bad User Agent ▏  832 ████████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  399 ███████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  306 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  295 ███████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  244 █████████ (  6.7%)
     HTTP Backdoors Attempts ▏  182 ███████ (  5.0%)
      HTTP Crawl Non Statics ▏  172 ██████ (  4.7%)
            HTTP CVE Probing ▏  121 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  107 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   31 █ (  0.8%)
                 Netgear RCE ▏   25 █ (  0.7%)
 HTTP Path Traversal Probing ▏   22 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   10 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  986 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  585 ████████████████████ ( 18.3%)
       Ireland ▏  531 ██████████████████ ( 16.6%)
         Japan ▏  219 ███████ (  6.9%)
     Australia ▏  216 ███████ (  6.8%)
     Singapore ▏  183 ██████ (  5.7%)
        France ▏  160 █████ (  5.0%)
   Netherlands ▏  122 ████ (  3.8%)
       Germany ▏  101 ███ (  3.2%)
         China ▏   92 ███ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-13 ▏   46 █████████████████ ( 10.5%)
2025-08-14 ▏   53 ████████████████████ ( 12.1%)
2025-08-15 ▏   91 ███████████████████████████████████ ( 20.8%)
2025-08-16 ▏   86 █████████████████████████████████ ( 19.6%)
2025-08-17 ▏   67 █████████████████████████ ( 15.3%)
2025-08-18 ▏   78 ██████████████████████████████ ( 17.8%)
2025-08-19 ▏   17 ██████ (  3.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!