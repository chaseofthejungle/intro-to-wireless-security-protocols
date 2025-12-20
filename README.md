# Intro to Wireless Security Protocols Overview Guide

**Description/Overview:** Four commonly known wireless security protocols include WEP and three versions of WPA: WPA, WPA2, and WPA3. Of these four protocols, WEP and WPA are widely considered obsolete (although WPA introduced security improvements, through the implementation of dynamic encryption keys and TKIP), WPA2 is still in popular use today (especially when WPA3 is not readily plausible), and WPA3 offers the strongest encryption, authentication, and other protections.

#### Table of Contents

1. [Who is the Wi-Fi Alliance?](#alliance)
2. [Wireless Security Protocols Overview](#protocols)
3. [Comparison Table: WEP, WPA, WPA2, WPA3](#comparison)
4. [Cracking Tools](#cracking)
5. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="alliance">Who is the Wi-Fi Alliance?</a>

The *[Wi-Fi Alliance](https://www.wi-fi.org/)* (formerly the Wireless Ethernet Compatibility Alliance, or *WECA*) is an Austin, Texas based non-profit organization that claims the legal trademark rights to the 'Wi-Fi Certified' logo and operates a variety of Wi-Fi related certification programs. When vendors place the Wi-Fi trademark on their devices, it is specifically in reference to this organization and its technology and standards.

<hr />

## 2. <a name="protocols">Wireless Security Protocols Overview</a>

(TODO)

<hr />

## 3. <a name="comparison">Comparison Table: WEP, WPA, WPA2, WPA3</a>

| Characteristic | Wired Equivalent Privacy (WEP) | Wi-Fi Protected Access (WPA) | WPA2 | WPA3 |
| :---: | :---: | :---: | :---: | :---: |
| Quality | Poor (obsolete). Heavily vulnerable. | Poor (obsolete). Heavily vulnerable, though not as much as WEP. | Good, but WPA3 is more secure. | Most secure (strongest encryption and authentication). |
| Encryption Standard | RC4 (with Static Keys) | TKIP (with Dynamic Keys) | AES (with CCMP) | AES (with GCMP) |
| Key Management | Static | Dynamic | Dynamic | Dynamic and Unique keys for Individualized/Custom Encryption) |
| When to Use | Ideally Never | Ideally Never | If WPA3 is Not Supported | If Network Supports It, Use It (Update Devices to Do So, if Possible) |
| Year Introduced | 1997 | 2003 | 2004 | 2018 |
| How Long to Crack | Within Minutes | Highly Variable (depending on password strength) | Highly Variable (depending on password strength) | Implausible to Crack (if passwords are complex) |

<hr />

## 4. <a name="cracking">Cracking Tools</a>

(TODO: Section covering the following tools...

* **Aircrack-ng**
* **Hashcat**
* **Kismet**
* **PixieWPS**
* **Weaver**
* **Wifite**)

<hr />

## 5. <a name="supplemental">Supplemental Resources</a>

* *[RFC 2236: Internet Group Management Protocol, Version 2](https://datatracker.ietf.org/doc/html/rfc2236)*
* *[RFC 2759: Microsoft PPP CHAP Extensions, Version 2](https://datatracker.ietf.org/doc/html/rfc2759)*
* *[RFC 5415: Control And Provisioning of Wireless Access Points (CAPWAP) Protocol Specification](https://datatracker.ietf.org/doc/html/rfc5415)*
