# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-504-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--22-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 504                      |
| Total Reports: 6,862                 |
| Unique Sources: 1,982                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1871 ███████████████████████████████████ ( 27.4%)
         HTTP Bad User Agent ▏ 1524 ████████████████████████████ ( 22.3%)
HTTP Admin Interface Probing ▏  733 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  690 ████████████ ( 10.1%)
         HTTP Wordpress Scan ▏  476 ████████ (  7.0%)
       CVE-2017-9841 Exploit ▏  338 ██████ (  5.0%)
      HTTP Crawl Non Statics ▏  310 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  283 █████ (  4.1%)
            HTTP CVE Probing ▏  254 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.8%)
      CVE-2022-41082 Exploit ▏   72 █ (  1.1%)
                 Netgear RCE ▏   58 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2030 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1082 ██████████████████ ( 18.4%)
       Ireland ▏  763 █████████████ ( 13.0%)
        France ▏  409 ███████ (  7.0%)
   Netherlands ▏  358 ██████ (  6.1%)
     Singapore ▏  307 █████ (  5.2%)
         Japan ▏  281 ████ (  4.8%)
     Australia ▏  269 ████ (  4.6%)
       Germany ▏  211 ███ (  3.6%)
         India ▏  172 ██ (  2.9%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-15 ▏   64 █████████████████████████████ ( 15.1%)
2025-10-16 ▏   63 █████████████████████████████ ( 14.8%)
2025-10-17 ▏   48 ██████████████████████ ( 11.3%)
2025-10-18 ▏   47 █████████████████████ ( 11.1%)
2025-10-19 ▏   69 ███████████████████████████████ ( 16.2%)
2025-10-20 ▏   54 ████████████████████████ ( 12.7%)
2025-10-21 ▏   76 ███████████████████████████████████ ( 17.9%)
2025-10-22 ▏    4 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!