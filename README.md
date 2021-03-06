# Security Research
A collection of files related to my personal security research. Additional content will be posted on my blog https://blog.mirch.io.


### Exploits
* CVE-2019-6724 - Barracuda VPN Client Privilege Escalation on Linux and macOS. PoC: [CVE-2019-6724](vulnerabilities/CVE-2019-6724.sh). Detailed write-up: [CVE-2019-6724: Barracuda VPN Client Privilege Escalation on Linux and macOS](https://blog.mirch.io/2019/02/14/cve-2019-6724-barracuda-vpn-client-privilege-escalation-on-linux-and-macos/). Barracuda VPN Client [Release Notes](http://campus.barracuda.com/product/networkaccessclient/doc/78154149/release-notes-barracuda-vpn-client-for-linux/)

* CVE-2018-18629 - Privilege Escalation on Linux via keybase-redirector . PoC: [CVE-2018-18629](vulnerabilities/CVE-2018-18629.sh). Detailed write-up: [CVE-2018-18629: Keybase Linux privilege escalation](https://blog.mirch.io/2018/12/21/cve-2018-18629-keybase-linux-privilege-escalation/). Keybase Advisory: [Local Privilege Escalation on Linux via keybase-redirector (KB002)](https://keybase.io/docs/secadv/kb002)

* CVE-2018-19788 - PolicyKit (aka polkit) 0.115 that allows a user with a uid greater than INT_MAX to successfully execute any systemctl command. PoC: [CVE-2018-19788.sh](vulnerabilities/CVE-2018-19788.sh). Detailed write-up: [CVE-2018-19788 PoC – polkit: Improper handling of user with uid > INT_MAX leading to authentication bypass](https://blog.mirch.io/2018/12/09/cve-2018-19788-poc-polkit-improper-handling-of-user-with-uid-int_max-leading-to-authentication-bypass/). The Hacker News article: [Warning! Unprivileged Linux Users With UID > INT_MAX Can Execute Any Command](https://thehackernews.com/2018/12/linux-user-privilege-policykit.html)
* CVE-2018-18556 - VyOS Privilege escalation via sudo pppd for operator users. PoC: [CVE-2018-18556.sh](vulnerabilities/VyOS/CVE-2018-18556.sh). Detailed write-up: [CVE-2018-18556 – VyOS Privilege escalation via sudo pppd for operator users](https://blog.mirch.io/2018/11/05/cve-2018-18556-vyos-privilege-escalation-via-sudo-pppd-for-operator-users). Advisory: [The "operator" level is proved insecure and will be removed in the next releases](https://blog.vyos.net/the-operator-level-is-proved-insecure-and-will-be-removed-in-the-next-releases)


