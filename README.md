# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-557-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 557                      |
| Total Reports: 7,999                 |
| Unique Sources: 2,243                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2259 ███████████████████████████████████ ( 28.4%)
         HTTP Bad User Agent ▏ 1756 ███████████████████████████ ( 22.1%)
HTTP Admin Interface Probing ▏  873 █████████████ ( 11.0%)
        HTTP Sensitive Files ▏  856 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  531 ████████ (  6.7%)
       CVE-2017-9841 Exploit ▏  352 █████ (  4.4%)
      HTTP Crawl Non Statics ▏  346 █████ (  4.4%)
     HTTP Backdoors Attempts ▏  328 █████ (  4.1%)
            HTTP CVE Probing ▏  282 ████ (  3.5%)
   CVE-2018-20062 (Thinkphp) ▏  128 █ (  1.6%)
      CVE-2022-41082 Exploit ▏   81 █ (  1.0%)
                 Netgear RCE ▏   66 █ (  0.8%)
 HTTP Path Traversal Probing ▏   39 █ (  0.5%)
      CVE-2019-18935 Exploit ▏   29 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   28 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2376 ███████████████████████████████████ ( 34.4%)
United Kingdom ▏ 1316 ███████████████████ ( 19.1%)
       Ireland ▏  835 ████████████ ( 12.1%)
   Netherlands ▏  492 ███████ (  7.1%)
        France ▏  438 ██████ (  6.3%)
         Japan ▏  379 █████ (  5.5%)
     Singapore ▏  325 ████ (  4.7%)
     Australia ▏  278 ████ (  4.0%)
       Germany ▏  247 ███ (  3.6%)
         India ▏  213 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-02 ▏   55 █████████████████████ ( 12.1%)
2025-11-03 ▏   65 █████████████████████████ ( 14.3%)
2025-11-04 ▏   61 ███████████████████████ ( 13.5%)
2025-11-05 ▏   62 ████████████████████████ ( 13.7%)
2025-11-06 ▏   45 █████████████████ (  9.9%)
2025-11-07 ▏   68 ██████████████████████████ ( 15.0%)
2025-11-08 ▏   89 ███████████████████████████████████ ( 19.6%)
2025-11-09 ▏    8 ███ (  1.8%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!