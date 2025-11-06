# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-532-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--06-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 532                      |
| Total Reports: 7,792                 |
| Unique Sources: 2,188                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2187 ███████████████████████████████████ ( 28.2%)
         HTTP Bad User Agent ▏ 1708 ███████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  855 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  824 █████████████ ( 10.6%)
         HTTP Wordpress Scan ▏  519 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  349 █████ (  4.5%)
      HTTP Crawl Non Statics ▏  341 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  321 █████ (  4.1%)
            HTTP CVE Probing ▏  277 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  128 ██ (  1.7%)
      CVE-2022-41082 Exploit ▏   80 █ (  1.0%)
                 Netgear RCE ▏   64 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   28 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   27 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2305 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1278 ███████████████████ ( 19.0%)
       Ireland ▏  828 ████████████ ( 12.3%)
   Netherlands ▏  469 ███████ (  7.0%)
        France ▏  437 ██████ (  6.5%)
         Japan ▏  354 █████ (  5.3%)
     Singapore ▏  321 ████ (  4.8%)
     Australia ▏  278 ████ (  4.1%)
       Germany ▏  242 ███ (  3.6%)
         India ▏  201 ███ (  3.0%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-30 ▏   44 ███████████████████████ ( 10.9%)
2025-10-31 ▏   60 ████████████████████████████████ ( 14.9%)
2025-11-01 ▏   49 ██████████████████████████ ( 12.1%)
2025-11-02 ▏   60 ████████████████████████████████ ( 14.9%)
2025-11-03 ▏   65 ███████████████████████████████████ ( 16.1%)
2025-11-04 ▏   61 ████████████████████████████████ ( 15.1%)
2025-11-05 ▏   62 █████████████████████████████████ ( 15.3%)
2025-11-06 ▏    3 █ (  0.7%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!