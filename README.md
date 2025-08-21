# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-542-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--21-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 542                      |
| Total Reports: 3,819                 |
| Unique Sources: 1,165                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  949 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  855 ███████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  417 ███████████████ ( 11.0%)
        HTTP Sensitive Files ▏  317 ███████████ (  8.3%)
         HTTP Wordpress Scan ▏  316 ███████████ (  8.3%)
       CVE-2017-9841 Exploit ▏  249 █████████ (  6.5%)
     HTTP Backdoors Attempts ▏  184 ██████ (  4.8%)
      HTTP Crawl Non Statics ▏  181 ██████ (  4.8%)
            HTTP CVE Probing ▏  125 ████ (  3.3%)
   CVE-2018-20062 (Thinkphp) ▏  108 ███ (  2.8%)
      CVE-2022-41082 Exploit ▏   32 █ (  0.8%)
                 Netgear RCE ▏   26 █ (  0.7%)
 HTTP Path Traversal Probing ▏   22 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   14 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   10 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 1016 ███████████████████████████████████ ( 30.7%)
United Kingdom ▏  597 ████████████████████ ( 18.0%)
       Ireland ▏  540 ██████████████████ ( 16.3%)
     Australia ▏  230 ███████ (  6.9%)
         Japan ▏  222 ███████ (  6.7%)
        France ▏  189 ██████ (  5.7%)
     Singapore ▏  188 ██████ (  5.7%)
   Netherlands ▏  122 ████ (  3.7%)
      Bulgaria ▏  105 ███ (  3.2%)
       Germany ▏  102 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-08-14 ▏   48 ██████████████████ (  9.2%)
2025-08-15 ▏   91 ███████████████████████████████████ ( 17.4%)
2025-08-16 ▏   86 █████████████████████████████████ ( 16.4%)
2025-08-17 ▏   67 █████████████████████████ ( 12.8%)
2025-08-18 ▏   78 ██████████████████████████████ ( 14.9%)
2025-08-19 ▏   84 ████████████████████████████████ ( 16.0%)
2025-08-20 ▏   70 ██████████████████████████ ( 13.4%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!