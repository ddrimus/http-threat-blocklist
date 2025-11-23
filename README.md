# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-537-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--23-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 537                      |
| Total Reports: 8,743                 |
| Unique Sources: 2,415                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2491 ███████████████████████████████████ ( 28.6%)
         HTTP Bad User Agent ▏ 1935 ███████████████████████████ ( 22.3%)
        HTTP Sensitive Files ▏  947 █████████████ ( 10.9%)
HTTP Admin Interface Probing ▏  942 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  565 ███████ (  6.5%)
       CVE-2017-9841 Exploit ▏  375 █████ (  4.3%)
      HTTP Crawl Non Statics ▏  368 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  355 ████ (  4.1%)
            HTTP CVE Probing ▏  318 ████ (  3.7%)
   CVE-2018-20062 (Thinkphp) ▏  131 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   90 █ (  1.0%)
                 Netgear RCE ▏   74 █ (  0.9%)
 HTTP Path Traversal Probing ▏   39 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   34 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   32 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2591 ███████████████████████████████████ ( 34.5%)
United Kingdom ▏ 1433 ███████████████████ ( 19.1%)
       Ireland ▏  891 ████████████ ( 11.9%)
   Netherlands ▏  572 ███████ (  7.6%)
        France ▏  451 ██████ (  6.0%)
         Japan ▏  430 █████ (  5.7%)
     Singapore ▏  345 ████ (  4.6%)
     Australia ▏  289 ███ (  3.8%)
       Germany ▏  274 ███ (  3.6%)
         India ▏  238 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-16 ▏   62 ███████████████████████████████ ( 17.7%)
2025-11-17 ▏   39 ████████████████████ ( 11.1%)
2025-11-18 ▏   30 ███████████████ (  8.6%)
2025-11-19 ▏   48 ████████████████████████ ( 13.7%)
2025-11-20 ▏   48 ████████████████████████ ( 13.7%)
2025-11-21 ▏   52 ██████████████████████████ ( 14.9%)
2025-11-22 ▏   68 ███████████████████████████████████ ( 19.4%)
2025-11-23 ▏    3 █ (  0.9%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!