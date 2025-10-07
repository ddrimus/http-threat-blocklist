# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-479-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--10--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 479                      |
| Total Reports: 6,068                 |
| Unique Sources: 1,774                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 1610 ███████████████████████████████████ ( 26.7%)
         HTTP Bad User Agent ▏ 1378 █████████████████████████████ ( 22.9%)
HTTP Admin Interface Probing ▏  643 █████████████ ( 10.7%)
        HTTP Sensitive Files ▏  565 ████████████ (  9.4%)
         HTTP Wordpress Scan ▏  445 █████████ (  7.4%)
       CVE-2017-9841 Exploit ▏  308 ██████ (  5.1%)
      HTTP Crawl Non Statics ▏  291 ██████ (  4.8%)
     HTTP Backdoors Attempts ▏  262 █████ (  4.3%)
            HTTP CVE Probing ▏  217 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  122 ██ (  2.0%)
      CVE-2022-41082 Exploit ▏   61 █ (  1.0%)
                 Netgear RCE ▏   43 █ (  0.7%)
 HTTP Path Traversal Probing ▏   39 █ (  0.6%)
      CVE-2019-18935 Exploit ▏   23 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   20 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1761 ███████████████████████████████████ ( 33.9%)
United Kingdom ▏  924 ██████████████████ ( 17.8%)
       Ireland ▏  740 ██████████████ ( 14.3%)
        France ▏  376 ███████ (  7.2%)
     Singapore ▏  289 █████ (  5.6%)
     Australia ▏  259 █████ (  5.0%)
         Japan ▏  247 ████ (  4.8%)
   Netherlands ▏  241 ████ (  4.6%)
       Germany ▏  193 ███ (  3.7%)
      Bulgaria ▏  161 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-09-30 ▏   33 █████████████████████████ ( 14.0%)
2025-10-01 ▏   40 ██████████████████████████████ ( 16.9%)
2025-10-02 ▏   35 ██████████████████████████ ( 14.8%)
2025-10-03 ▏   31 ███████████████████████ ( 13.1%)
2025-10-04 ▏   19 ██████████████ (  8.1%)
2025-10-05 ▏   31 ███████████████████████ ( 13.1%)
2025-10-06 ▏   46 ███████████████████████████████████ ( 19.5%)
2025-10-07 ▏    1 █ (  0.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!