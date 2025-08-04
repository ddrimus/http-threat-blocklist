# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-551-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--04-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 551                      |
| Total Reports: 2,886                 |
| Unique Sources: 952                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  720 ███████████████████████████████████ ( 25.0%)
         HTTP Bad User Agent ▏  653 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  314 ███████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  235 ███████████ (  8.2%)
        HTTP Sensitive Files ▏  229 ███████████ (  8.0%)
       CVE-2017-9841 Exploit ▏  188 █████████ (  6.5%)
     HTTP Backdoors Attempts ▏  148 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  134 ██████ (  4.7%)
   CVE-2018-20062 (Thinkphp) ▏   91 ████ (  3.2%)
            HTTP CVE Probing ▏   86 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   26 █ (  0.9%)
                 Netgear RCE ▏   16 █ (  0.6%)
 HTTP Path Traversal Probing ▏   16 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  784 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  528 ███████████████████████ ( 20.8%)
       Ireland ▏  449 ████████████████████ ( 17.7%)
         Japan ▏  176 ███████ (  6.9%)
     Australia ▏  149 ██████ (  5.9%)
     Singapore ▏  137 ██████ (  5.4%)
   Netherlands ▏  111 ████ (  4.4%)
       Germany ▏   78 ███ (  3.1%)
         China ▏   66 ██ (  2.6%)
        France ▏   57 ██ (  2.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-28 ▏   62 ███████████████████████ ( 15.5%)
2025-07-29 ▏   48 █████████████████ ( 12.0%)
2025-07-30 ▏   12 ████ (  3.0%)
2025-07-31 ▏   80 █████████████████████████████ ( 20.0%)
2025-08-01 ▏   94 ███████████████████████████████████ ( 23.4%)
2025-08-02 ▏   13 ████ (  3.2%)
2025-08-03 ▏   81 ██████████████████████████████ ( 20.2%)
2025-08-04 ▏   11 ████ (  2.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!