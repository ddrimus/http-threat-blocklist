# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-509-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--03-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 509                      |
| Total Reports: 5,945                 |
| Unique Sources: 1,733                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1577 ███████████████████████████████████ ( 26.7%)
         HTTP Bad User Agent ▏ 1339 █████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  635 ██████████████ ( 10.8%)
        HTTP Sensitive Files ▏  550 ████████████ (  9.3%)
         HTTP Wordpress Scan ▏  441 █████████ (  7.5%)
       CVE-2017-9841 Exploit ▏  304 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  289 ██████ (  4.9%)
     HTTP Backdoors Attempts ▏  261 █████ (  4.4%)
            HTTP CVE Probing ▏  207 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  121 ██ (  2.0%)
      CVE-2022-41082 Exploit ▏   58 █ (  1.0%)
                 Netgear RCE ▏   41 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.7%)
      CVE-2019-18935 Exploit ▏   22 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1695 ███████████████████████████████████ ( 33.4%)
United Kingdom ▏  897 ██████████████████ ( 17.7%)
       Ireland ▏  740 ███████████████ ( 14.6%)
        France ▏  376 ███████ (  7.4%)
     Singapore ▏  284 █████ (  5.6%)
     Australia ▏  258 █████ (  5.1%)
         Japan ▏  244 █████ (  4.8%)
   Netherlands ▏  234 ████ (  4.6%)
       Germany ▏  192 ███ (  3.8%)
      Bulgaria ▏  161 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-26 ▏   44 ███████████████████████████████████ ( 16.1%)
2025-09-27 ▏   40 ███████████████████████████████ ( 14.6%)
2025-09-28 ▏   43 ██████████████████████████████████ ( 15.7%)
2025-09-29 ▏   25 ███████████████████ (  9.1%)
2025-09-30 ▏   42 █████████████████████████████████ ( 15.3%)
2025-10-01 ▏   40 ███████████████████████████████ ( 14.6%)
2025-10-02 ▏   35 ███████████████████████████ ( 12.8%)
2025-10-03 ▏    5 ███ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!