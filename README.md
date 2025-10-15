# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-484-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--15-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 484                      |
| Total Reports: 6,437                 |
| Unique Sources: 1,876                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1724 ███████████████████████████████████ ( 27.0%)
         HTTP Bad User Agent ▏ 1455 █████████████████████████████ ( 22.8%)
HTTP Admin Interface Probing ▏  681 █████████████ ( 10.6%)
        HTTP Sensitive Files ▏  617 ████████████ (  9.6%)
         HTTP Wordpress Scan ▏  457 █████████ (  7.1%)
       CVE-2017-9841 Exploit ▏  324 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  303 ██████ (  4.7%)
     HTTP Backdoors Attempts ▏  274 █████ (  4.3%)
            HTTP CVE Probing ▏  237 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  125 ██ (  2.0%)
      CVE-2022-41082 Exploit ▏   66 █ (  1.0%)
                 Netgear RCE ▏   49 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   24 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1891 ███████████████████████████████████ ( 34.2%)
United Kingdom ▏  992 ██████████████████ ( 18.0%)
       Ireland ▏  748 █████████████ ( 13.5%)
        France ▏  395 ███████ (  7.2%)
     Singapore ▏  302 █████ (  5.5%)
   Netherlands ▏  293 █████ (  5.3%)
         Japan ▏  269 ████ (  4.9%)
     Australia ▏  266 ████ (  4.8%)
       Germany ▏  201 ███ (  3.6%)
      Bulgaria ▏  165 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-08 ▏   33 ███████████████ (  9.9%)
2025-10-09 ▏   42 ███████████████████ ( 12.7%)
2025-10-10 ▏   30 █████████████ (  9.0%)
2025-10-11 ▏   43 ███████████████████ ( 13.0%)
2025-10-12 ▏   38 █████████████████ ( 11.4%)
2025-10-13 ▏   76 ███████████████████████████████████ ( 22.9%)
2025-10-14 ▏   58 ██████████████████████████ ( 17.5%)
2025-10-15 ▏   12 █████ (  3.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!