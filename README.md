# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-514-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--31-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 514                      |
| Total Reports: 7,432                 |
| Unique Sources: 2,100                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2063 ███████████████████████████████████ ( 27.9%)
         HTTP Bad User Agent ▏ 1626 ███████████████████████████ ( 22.0%)
HTTP Admin Interface Probing ▏  813 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  775 █████████████ ( 10.5%)
         HTTP Wordpress Scan ▏  503 ████████ (  6.8%)
       CVE-2017-9841 Exploit ▏  345 █████ (  4.7%)
      HTTP Crawl Non Statics ▏  329 █████ (  4.5%)
     HTTP Backdoors Attempts ▏  312 █████ (  4.2%)
            HTTP CVE Probing ▏  266 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  126 ██ (  1.7%)
      CVE-2022-41082 Exploit ▏   77 █ (  1.0%)
                 Netgear RCE ▏   62 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   26 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   25 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2196 ███████████████████████████████████ ( 34.3%)
United Kingdom ▏ 1203 ███████████████████ ( 18.8%)
       Ireland ▏  807 ████████████ ( 12.6%)
        France ▏  433 ██████ (  6.8%)
   Netherlands ▏  428 ██████ (  6.7%)
         Japan ▏  320 █████ (  5.0%)
     Singapore ▏  317 █████ (  5.0%)
     Australia ▏  278 ████ (  4.3%)
       Germany ▏  219 ███ (  3.4%)
         India ▏  197 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-10-24 ▏   70 ███████████████████████████████████ ( 16.9%)
2025-10-25 ▏   66 █████████████████████████████████ ( 15.9%)
2025-10-26 ▏   62 ███████████████████████████████ ( 14.9%)
2025-10-27 ▏   50 █████████████████████████ ( 12.0%)
2025-10-28 ▏   61 ██████████████████████████████ ( 14.7%)
2025-10-29 ▏   52 ██████████████████████████ ( 12.5%)
2025-10-30 ▏   54 ███████████████████████████ ( 13.0%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!