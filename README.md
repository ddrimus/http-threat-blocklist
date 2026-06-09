# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-546-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2026--06--09-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 546                      |
| Total Reports: 17,208                |
| Unique Sources: 4,580                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 5118 ███████████████████████████████████ ( 29.9%)
         HTTP Bad User Agent ▏ 3143 █████████████████████ ( 18.4%)
HTTP Admin Interface Probing ▏ 2229 ███████████████ ( 13.0%)
        HTTP Sensitive Files ▏ 1770 ████████████ ( 10.3%)
         HTTP Wordpress Scan ▏ 1467 ██████████ (  8.6%)
      HTTP Crawl Non Statics ▏  958 ██████ (  5.6%)
     HTTP Backdoors Attempts ▏  682 ████ (  4.0%)
            HTTP CVE Probing ▏  632 ████ (  3.7%)
       CVE-2017-9841 Exploit ▏  455 ███ (  2.7%)
      CVE-2022-41082 Exploit ▏  191 █ (  1.1%)
   CVE-2018-20062 (Thinkphp) ▏  146 █ (  0.9%)
                 Netgear RCE ▏  136 █ (  0.8%)
       CVE-2021-26086 (Jira) ▏   73 █ (  0.4%)
 HTTP Path Traversal Probing ▏   61 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   53 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 5589 ███████████████████████████████████ ( 39.8%)
United Kingdom ▏ 1800 ███████████ ( 12.8%)
       Ireland ▏ 1280 ████████ (  9.1%)
   Netherlands ▏ 1056 ██████ (  7.5%)
        France ▏  917 █████ (  6.5%)
     Singapore ▏  781 ████ (  5.6%)
        Canada ▏  747 ████ (  5.3%)
         Japan ▏  722 ████ (  5.1%)
       Germany ▏  632 ███ (  4.5%)
     Australia ▏  511 ███ (  3.6%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2026-06-02 ▏   33 █████████████████████ ( 10.5%)
2026-06-03 ▏   54 ██████████████████████████████████ ( 17.3%)
2026-06-04 ▏   55 ███████████████████████████████████ ( 17.6%)
2026-06-05 ▏   43 ███████████████████████████ ( 13.7%)
2026-06-06 ▏   45 ████████████████████████████ ( 14.4%)
2026-06-07 ▏   41 ██████████████████████████ ( 13.1%)
2026-06-08 ▏   40 █████████████████████████ ( 12.8%)
2026-06-09 ▏    2 █ (  0.6%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!