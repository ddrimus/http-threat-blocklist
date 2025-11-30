# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-533-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--30-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 533                      |
| Total Reports: 9,116                 |
| Unique Sources: 2,506                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2615 ███████████████████████████████████ ( 28.8%)
         HTTP Bad User Agent ▏ 1999 ██████████████████████████ ( 22.0%)
        HTTP Sensitive Files ▏ 1016 █████████████ ( 11.2%)
HTTP Admin Interface Probing ▏  984 █████████████ ( 10.9%)
         HTTP Wordpress Scan ▏  582 ███████ (  6.4%)
       CVE-2017-9841 Exploit ▏  384 █████ (  4.2%)
      HTTP Crawl Non Statics ▏  380 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  368 ████ (  4.1%)
            HTTP CVE Probing ▏  327 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  133 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   93 █ (  1.0%)
                 Netgear RCE ▏   76 █ (  0.8%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   38 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   34 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2700 ███████████████████████████████████ ( 34.6%)
United Kingdom ▏ 1491 ███████████████████ ( 19.1%)
       Ireland ▏  900 ███████████ ( 11.5%)
   Netherlands ▏  612 ███████ (  7.8%)
        France ▏  462 █████ (  5.9%)
         Japan ▏  450 █████ (  5.8%)
     Singapore ▏  370 ████ (  4.7%)
     Australia ▏  293 ███ (  3.8%)
       Germany ▏  281 ███ (  3.6%)
      Bulgaria ▏  247 ███ (  3.2%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-23 ▏   44 ██████████████████ ( 11.8%)
2025-11-24 ▏   59 ████████████████████████ ( 15.8%)
2025-11-25 ▏   84 ███████████████████████████████████ ( 22.5%)
2025-11-26 ▏   44 ██████████████████ ( 11.8%)
2025-11-27 ▏   46 ███████████████████ ( 12.3%)
2025-11-28 ▏   53 ██████████████████████ ( 14.2%)
2025-11-29 ▏   42 █████████████████ ( 11.3%)
2025-11-30 ▏    1 █ (  0.3%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!