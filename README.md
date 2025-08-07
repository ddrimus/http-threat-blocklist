# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-571-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--08--07-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 571                      |
| Total Reports: 3,129                 |
| Unique Sources: 1,005                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏  777 ███████████████████████████████████ ( 24.9%)
         HTTP Bad User Agent ▏  701 ███████████████████████████████ ( 22.5%)
HTTP Admin Interface Probing ▏  335 ███████████████ ( 10.7%)
         HTTP Wordpress Scan ▏  260 ███████████ (  8.3%)
        HTTP Sensitive Files ▏  242 ██████████ (  7.8%)
       CVE-2017-9841 Exploit ▏  216 █████████ (  6.9%)
     HTTP Backdoors Attempts ▏  162 ███████ (  5.2%)
      HTTP Crawl Non Statics ▏  142 ██████ (  4.6%)
   CVE-2018-20062 (Thinkphp) ▏  102 ████ (  3.3%)
            HTTP CVE Probing ▏   95 ████ (  3.0%)
      CVE-2022-41082 Exploit ▏   27 █ (  0.9%)
                 Netgear RCE ▏   20 █ (  0.6%)
 HTTP Path Traversal Probing ▏   19 █ (  0.6%)
       CVE-2021-26086 (Jira) ▏   11 █ (  0.4%)
      CVE-2019-18935 Exploit ▏    8 █ (  0.3%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏  843 ███████████████████████████████████ ( 30.9%)
United Kingdom ▏  543 ██████████████████████ ( 19.9%)
       Ireland ▏  476 ███████████████████ ( 17.4%)
         Japan ▏  190 ███████ (  7.0%)
     Australia ▏  180 ███████ (  6.6%)
     Singapore ▏  150 ██████ (  5.5%)
   Netherlands ▏  113 ████ (  4.1%)
       Germany ▏   82 ███ (  3.0%)
        France ▏   77 ███ (  2.8%)
         China ▏   77 ███ (  2.8%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-07-31 ▏   80 █████████████████████████████ ( 15.3%)
2025-08-01 ▏   94 ███████████████████████████████████ ( 18.0%)
2025-08-02 ▏   13 ████ (  2.5%)
2025-08-03 ▏   81 ██████████████████████████████ ( 15.5%)
2025-08-04 ▏   79 █████████████████████████████ ( 15.1%)
2025-08-05 ▏   77 ████████████████████████████ ( 14.8%)
2025-08-06 ▏   88 ████████████████████████████████ ( 16.9%)
2025-08-07 ▏   10 ███ (  1.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!