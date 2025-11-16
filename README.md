# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-559-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--16-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 559                      |
| Total Reports: 8,393                 |
| Unique Sources: 2,325                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2377 ███████████████████████████████████ ( 28.5%)
         HTTP Bad User Agent ▏ 1852 ███████████████████████████ ( 22.2%)
HTTP Admin Interface Probing ▏  900 █████████████ ( 10.8%)
        HTTP Sensitive Files ▏  899 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  556 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  366 █████ (  4.4%)
      HTTP Crawl Non Statics ▏  360 █████ (  4.3%)
     HTTP Backdoors Attempts ▏  351 █████ (  4.2%)
            HTTP CVE Probing ▏  303 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  128 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   86 █ (  1.0%)
                 Netgear RCE ▏   70 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   31 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   28 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2475 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1378 ███████████████████ ( 19.1%)
       Ireland ▏  875 ████████████ ( 12.1%)
   Netherlands ▏  533 ███████ (  7.4%)
        France ▏  447 ██████ (  6.2%)
         Japan ▏  419 █████ (  5.8%)
     Singapore ▏  329 ████ (  4.6%)
     Australia ▏  284 ████ (  3.9%)
       Germany ▏  255 ███ (  3.5%)
         India ▏  221 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-09 ▏   57 ███████████████████████████ ( 14.5%)
2025-11-10 ▏   63 ██████████████████████████████ ( 16.0%)
2025-11-11 ▏   57 ███████████████████████████ ( 14.5%)
2025-11-12 ▏   73 ███████████████████████████████████ ( 18.5%)
2025-11-13 ▏   40 ███████████████████ ( 10.2%)
2025-11-14 ▏   64 ██████████████████████████████ ( 16.2%)
2025-11-15 ▏   40 ███████████████████ ( 10.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!