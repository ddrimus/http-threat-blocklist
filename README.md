# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-551-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--05-brightgreen)](.)

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
| Total Reports: 2,954                 |
| Unique Sources: 965                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  737 ███████████████████████████████████ ( 25.0%)
         HTTP Bad User Agent ▏  668 ███████████████████████████████ ( 22.7%)
HTTP Admin Interface Probing ▏  320 ███████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  243 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  232 ███████████ (  7.9%)
       CVE-2017-9841 Exploit ▏  193 █████████ (  6.6%)
     HTTP Backdoors Attempts ▏  151 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  137 ██████ (  4.7%)
   CVE-2018-20062 (Thinkphp) ▏   95 ████ (  3.2%)
            HTTP CVE Probing ▏   88 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   26 █ (  0.9%)
                 Netgear RCE ▏   17 █ (  0.6%)
 HTTP Path Traversal Probing ▏   17 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  801 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  530 ███████████████████████ ( 20.4%)
       Ireland ▏  456 ███████████████████ ( 17.6%)
         Japan ▏  178 ███████ (  6.9%)
     Australia ▏  157 ██████ (  6.1%)
     Singapore ▏  143 ██████ (  5.5%)
   Netherlands ▏  111 ████ (  4.3%)
       Germany ▏   81 ███ (  3.1%)
         China ▏   69 ███ (  2.7%)
        France ▏   67 ██ (  2.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-29 ▏   35 █████████████ (  8.9%)
2025-07-30 ▏   12 ████ (  3.0%)
2025-07-31 ▏   80 █████████████████████████████ ( 20.3%)
2025-08-01 ▏   94 ███████████████████████████████████ ( 23.9%)
2025-08-02 ▏   13 ████ (  3.3%)
2025-08-03 ▏   81 ██████████████████████████████ ( 20.6%)
2025-08-04 ▏   79 █████████████████████████████ ( 20.1%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!