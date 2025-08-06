# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-566-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 566                      |
| Total Reports: 3,041                 |
| Unique Sources: 986                  |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  754 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  683 ███████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  329 ███████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  252 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  237 ███████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  204 █████████ (  6.7%)
     HTTP Backdoors Attempts ▏  155 ███████ (  5.1%)
      HTTP Crawl Non Statics ▏  139 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏   98 ████ (  3.2%)
            HTTP CVE Probing ▏   95 ████ (  3.1%)
      CVE-2022-41082 Exploit ▏   27 █ (  0.9%)
                 Netgear RCE ▏   20 █ (  0.7%)
 HTTP Path Traversal Probing ▏   18 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  817 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  536 ██████████████████████ ( 20.1%)
       Ireland ▏  461 ███████████████████ ( 17.3%)
         Japan ▏  186 ███████ (  7.0%)
     Australia ▏  169 ███████ (  6.3%)
     Singapore ▏  150 ██████ (  5.6%)
   Netherlands ▏  113 ████ (  4.2%)
       Germany ▏   81 ███ (  3.0%)
         China ▏   77 ███ (  2.9%)
        France ▏   73 ███ (  2.7%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-30 ▏   12 ████ (  2.7%)
2025-07-31 ▏   80 █████████████████████████████ ( 17.9%)
2025-08-01 ▏   94 ███████████████████████████████████ ( 21.1%)
2025-08-02 ▏   13 ████ (  2.9%)
2025-08-03 ▏   81 ██████████████████████████████ ( 18.2%)
2025-08-04 ▏   79 █████████████████████████████ ( 17.7%)
2025-08-05 ▏   77 ████████████████████████████ ( 17.3%)
2025-08-06 ▏   10 ███ (  2.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!