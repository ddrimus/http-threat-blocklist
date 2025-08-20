# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-547-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--20-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 547                      |
| Total Reports: 3,755                 |
| Unique Sources: 1,155                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  929 ███████████████████████████████████ ( 24.8%)
         HTTP Bad User Agent ▏  846 ███████████████████████████████ ( 22.6%)
HTTP Admin Interface Probing ▏  409 ███████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  313 ███████████ (  8.4%)
        HTTP Sensitive Files ▏  304 ███████████ (  8.1%)
       CVE-2017-9841 Exploit ▏  249 █████████ (  6.7%)
     HTTP Backdoors Attempts ▏  183 ██████ (  4.9%)
      HTTP Crawl Non Statics ▏  175 ██████ (  4.7%)
            HTTP CVE Probing ▏  122 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  108 ████ (  2.9%)
      CVE-2022-41082 Exploit ▏   32 █ (  0.9%)
                 Netgear RCE ▏   25 █ (  0.7%)
 HTTP Path Traversal Probing ▏   22 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   10 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1001 ███████████████████████████████████ ( 30.8%)
United Kingdom ▏  591 ████████████████████ ( 18.2%)
       Ireland ▏  536 ██████████████████ ( 16.5%)
     Australia ▏  230 ████████ (  7.1%)
         Japan ▏  222 ███████ (  6.8%)
     Singapore ▏  187 ██████ (  5.7%)
        France ▏  170 █████ (  5.2%)
   Netherlands ▏  122 ████ (  3.7%)
       Germany ▏  102 ███ (  3.1%)
      Bulgaria ▏   93 ███ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-13 ▏   46 █████████████████ (  9.0%)
2025-08-14 ▏   53 ████████████████████ ( 10.4%)
2025-08-15 ▏   91 ███████████████████████████████████ ( 17.8%)
2025-08-16 ▏   86 █████████████████████████████████ ( 16.8%)
2025-08-17 ▏   67 █████████████████████████ ( 13.1%)
2025-08-18 ▏   78 ██████████████████████████████ ( 15.3%)
2025-08-19 ▏   84 ████████████████████████████████ ( 16.4%)
2025-08-20 ▏    6 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!