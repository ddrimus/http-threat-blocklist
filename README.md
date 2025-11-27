# HTTP Threat Blocklist

This repository provides a **daily-updated blocklist** of IP addresses involved in malicious HTTP attacks targeting servers. Designed to protect both your systems and mine, the blocklist defends against common HTTP-based threats, including **probing**, **exploit attempts**, and **malicious bots**.

[![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-red)](.)
[![IPs Blocked](https://img.shields.io/badge/IPs%20Blocked-527-blue)](.)
[![Last Updated](https://img.shields.io/badge/Updated-2025--11--27-brightgreen)](.)

## 🔍 About This List

This is my **private blocklist**, built from traffic that actually made it through multiple layers of defense — including **Cloudflare**, **CrowdSec**, and IP rate limits. I also block entire regions like **China** and **Russia**, so if something shows up here, it means it **slipped through all of that** and still tried something shady.

*In short: this list catches the ones that got further than they should have.*

## 📈 Current Threat Status

```
+--------------------------------------+
|           THREAT OVERVIEW            |
+--------------------------------------+
| Status: HIGH                         |
| Active IPs: 527                      |
| Total Reports: 8,979                 |
| Unique Sources: 2,467                |
+--------------------------------------+
```

*Threat levels: significant malicious activity detected!*

## 🎯 Attack Patterns

```
🔥 Most Common Attack Types
──────────────────────────

                HTTP Probing ▏ 2568 ███████████████████████████████████ ( 28.8%)
         HTTP Bad User Agent ▏ 1977 ██████████████████████████ ( 22.1%)
        HTTP Sensitive Files ▏  978 █████████████ ( 10.9%)
HTTP Admin Interface Probing ▏  969 █████████████ ( 10.8%)
         HTTP Wordpress Scan ▏  580 ███████ (  6.5%)
       CVE-2017-9841 Exploit ▏  381 █████ (  4.3%)
      HTTP Crawl Non Statics ▏  378 █████ (  4.2%)
     HTTP Backdoors Attempts ▏  366 ████ (  4.1%)
            HTTP CVE Probing ▏  322 ████ (  3.6%)
   CVE-2018-20062 (Thinkphp) ▏  133 █ (  1.5%)
      CVE-2022-41082 Exploit ▏   93 █ (  1.0%)
                 Netgear RCE ▏   75 █ (  0.8%)
 HTTP Path Traversal Probing ▏   40 █ (  0.4%)
       CVE-2021-26086 (Jira) ▏   38 █ (  0.4%)
      CVE-2019-18935 Exploit ▏   34 █ (  0.4%)
```

## 🌍 Geographic Distribution

```
🗺️ Top Source Countries
───────────────────────

 United States ▏ 2666 ███████████████████████████████████ ( 34.6%)
United Kingdom ▏ 1477 ███████████████████ ( 19.2%)
       Ireland ▏  900 ███████████ ( 11.7%)
   Netherlands ▏  596 ███████ (  7.7%)
        France ▏  460 ██████ (  6.0%)
         Japan ▏  440 █████ (  5.7%)
     Singapore ▏  356 ████ (  4.6%)
     Australia ▏  293 ███ (  3.8%)
       Germany ▏  280 ███ (  3.6%)
         India ▏  240 ███ (  3.1%)
```

## 📊 Activity Timeline

```
📅 Recent Activity (7 days)
──────────────────────────

2025-11-20 ▏   46 ███████████████████ ( 11.4%)
2025-11-21 ▏   52 █████████████████████ ( 12.8%)
2025-11-22 ▏   68 ████████████████████████████ ( 16.8%)
2025-11-23 ▏   47 ███████████████████ ( 11.6%)
2025-11-24 ▏   59 ████████████████████████ ( 14.6%)
2025-11-25 ▏   84 ███████████████████████████████████ ( 20.7%)
2025-11-26 ▏   44 ██████████████████ ( 10.9%)
2025-11-27 ▏    5 ██ (  1.2%)
```

## 🔒 Security Notes

- **False Positives**: This blocklist is generated from automated threat detection.
- **Legitimate Traffic**: Review before implementing in production environments.
- **Rate Limiting**: Consider implement rate limiting alongside IP blocking.
- **Monitoring**: Monitor your logs for blocked legitimate traffic.

## 🤝 Contributing

If you have any improvements, additional information, or notice any IPs that shouldn't be on the list, we'd love to hear from you! Feel free to open a pull request with your suggestions or details.

If you believe your IP has been mistakenly blocked and would like to request an unban, please provide all relevant information in an issue. I will review your case and address it promptly. Your contributions, suggestions, and feedback are always welcome and appreciated!