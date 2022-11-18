# hax0r

## Description
Tools for pentesting

## Tools

### WiPi Hunter
It is designed to detect illegal wireless network activities performed by special software and hardware

Example: WiFi Pineapple

WiPi-Hunter Modules

PiSavar: Detects activities of PineAP module and starts deauthentication attack (for fake access points – WiFi Pineapple Activities Detection)
PiFinger: Searches for wifi-pineapple traces and calculate wireless network security score
PiDense : Monitor illegal wireless network activities. (Fake Access Points)
PiKarma : Detects wireless network attacks performed by KARMA module (fake AP). Starts deauthentication attack (for fake access points)
https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/network_defense/wipihunter.md

### Leviathan Framework
Leviathan is a mass audit toolkit which has wide range service discovery, brute force, SQL injection detection and running custom exploit capabilities. It consists open source tools such masscan, ncrack, dsss and gives you the flexibility of using them with a combination.

The main goal of this project is auditing as many system as possible in country-wide or in a wide IP range.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/exploitation/leviathan-framework.md

### WHID Injector
Since the first public appearance of HID Attacks, many awesome researches, tools and devices have been released.
However, Offensive Security folks were always seeking a cheap and dedicated hardware that could be controlled remotely (i.e. over WiFi or BT). This is how WHID Injector was born. WHID stands for WiFi-HID injector, it is an USB-Rubberducky / Bad-USB on steroids, designed to fulfill RedTeamers needs during their engagements. Based on an Atmega 32u4 (i.e. Keyboard, mouse and serial emulation) and a ESP-12 (i.e. Wifi AP/Client), It can be easily controlled over the WiFi network and potentially bypass air-gapped environments.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/hardware_iot/whid.md

### LuLu
LuLu is the free open-source macOS firewall that aims to block unauthorized (outgoing) network traffic, unless explicitly approved by the user

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/network_defense/lulu.md

### The OWASP Zed Attack Proxy (ZAP)
The OWASP Zed Attack Proxy (ZAP) is one of the world’s most popular free security tools and is actively maintained by hundreds of international volunteers. It can help you automatically find security vulnerabilities in your web applications while you are developing and testing your applications. Its also a great tool for experienced pentesters to use for manual security testing.

Some of the built in features include: Intercepting proxy server, Traditional and AJAX Web crawlers, Automated scanner, Passive scanner, Forced browsing, Fuzzer, WebSocket support, Scripting languages, and Plug-n-Hack support. It has a plugin-based architecture and an online ‘marketplace’ which allows new or updated features to be added. The GUI control panel is easy to use, and the API functions make it ideal for automation testing and continuous assessments in a SDLC.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/webapp_security/zap.md

### Lynis
Lynis is a security auditing tool for sytems running Linux, macOS, BSD, and other flavors of Unix. The tool performs an in-depth security scan and runs on the system itself. The primary goal is to test security defenses and provide tips for further system hardening. It will also scan for general system information, vulnerable software packages, and possible configuration issues. As Lynis is written in POSIX shell script, it is light on resources and low on dependencies. This makes the tool great for putting it in build pipelines, running it as part of a forensics task or as penetration testing tool during an assignment.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/hardening/lynis.md

### Faraday
Faraday®, a comprehensive platform for vulnerability management that simplifies your work automating scans and reports. A real-time collaborative environment that increases transparency, speed and efficiency for your audits and for your teams. This provides greater visibility and helps you to make smarter security investments and leverage your existing resources.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/vulnerability_assessment/faraday.md

### Halcyon IDE
Halcyon is the first IDE specifically focused on Nmap Script (NSE) Development. This research idea was originated while writing custom Nmap Scripts for Enterprise Penetration Testing Scenarios. The existing challenge in developing Nmap Scripts (NSE) was the lack of a development environment that gives easiness in building custom scripts for real world scanning, at the same time fast enough to develop such custom scripts. Halcyon is free to use, java based application that comes with code intelligence, code builder, auto-completion, debugging and error correction options and also a bunch of other features like other development IDE(s) has. This research was started to give better development interface/environment to researchers and thus enhance the number of NSE writers in the information security community.

Halcyon IDE can understand Nmap library as well as traditional LUA syntax. Possible repetitive codes such as web crawling, bruteforcing etc., is pre-built in the IDE and this makes easy for script writers to save their time while developing majority of test scenarios.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/frameworks/halcyon_ide.md

### Mobile Security Framework – MobSF
Mobile Security Framework (MobSF) is an intelligent, all-in-one open source mobile application (Android/iOS/Windows) automated pen-testing framework capable of performing static and dynamic analysis. It can be used for effective and fast security analysis of Android, iOS and Windows mobile Applications and supports both binaries (APK, IPA & APPX ) and zipped source code. MobSF can also perform Web API Security testing with it’s API Fuzzer that can do Information Gathering, analyze Security Headers, identify Mobile API specific vulnerabilities like XXE, SSRF, Path Traversal, IDOR, and other logical issues related to Session and API Rate Limiting.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/mobile_hacking/mobsf.md

### WarBerryPi
WarBerryPi was built to be used as a hardware implant during red teaming scenarios where we want to obtain as much information as possible in a short period of time with being as stealth as possible. Just find a network port and plug it in. The scripts have been designed in a way that the approach is targeted to avoid noise in the network that could lead to detection and to be as efficient as possible. The WarBerry script is a collection of scanning tools put together to provide that functionality.

https://github.com/toolswatch/blackhat-arsenal-tools/blob/master/red_team/warberrypi.md

