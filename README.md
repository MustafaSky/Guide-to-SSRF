# Guide to SSRF 🌐

## The Basics

- [Server Side Request Forgery (OWASP)](https://owasp.org/www-community/attacks/Server_Side_Request_Forgery)
- [SSRF: Web App Security Basics](https://infosecwriteups.com/ssrf-web-app-security-basics-b88da872c9c8)
- [SSRF-Server Side Request Forgery](https://medium.com/@briskinfosec/ssrf-server-side-request-forgery-ae44ec737cb8)
- [What is Server-Side Request Forgery (SSRF)?](https://www.acunetix.com/blog/articles/server-side-request-forgery-vulnerability/)
- [SSRF: What is Server Side Request Forgery?](https://hdivsecurity.com/bornsecure/ssrf-what-is-server-side-request-forgery/)
- [Understanding the Web Vulnerability Server-Side Request Forgery (1/2)](https://www.vaadata.com/blog/understanding-web-vulnerability-server-side-request-forgery-1/)
- [Exploiting the SSRF vulnerability (2/2)](https://www.vaadata.com/blog/exploiting-the-ssrf-vulnerability/)
- [3 Types of SSRF Attacks and How to Prevent Them](https://www.neuralegion.com/blog/ssrf-server-side-request-forgery/)
- [SSRF](https://0x221b.github.io/SSRF)

## Server Side Request Forgery Prevention 🚫

- [Server-Side Request Forgery Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.html#case-1-application-can-send-request-only-to-identified-and-trusted-applications%2034)

## A powerful tool: SSRFmap, SSRF bug with automation 🛠️

- [SSRFmap](https://github.com/swisskyrepo/SSRFmap)
- [tomnomnom/gf](https://github.com/tomnomnom/gf)
- [tomnomnom/qsreplace](https://github.com/tomnomnom/qsreplace)
- [ffuf](https://github.com/ffuf/ffuf)
- [gau](https://github.com/lc/gau)
- [waybackurls](https://github.com/tomnomnom/waybackurls)
- [quickpress](https://github.com/pownx/quickpress)
- [automate SSRF wordpress and XMLRPC finder](https://github.com/pownx/quickpress)
- [Finding SSRF by Full Automation](https://notifybugme.medium.com/finding-ssrf-by-full-automation-7d2680091d68)
- [Bug Bounty tip Automating SSRF](https://dant0x65.medium.com/bug-bounty-tip-automating-ssrf-ea344ec59962)
- [ssrf-sheriffhggi](https://github.com/teknogeek/ssrf-sheriff)

## SSRF Techniques 🛡️

- [SSRF Techniques](https://www.xmind.net/m/eJm7bd/)

## Writeups ✍️

* [An unknown Linux secret that turned SSRF to OS Command injection](https://secureitmania.medium.com/an-unknown-linux-secret-that-turned-ssrf-to-os-command-injection-6fe2f4edc202)

* [Story Behind Sweet SSRF](https://rohit-soni.medium.com/story-behind-sweet-ssrf-40c705f13053)

* [GITLAB — Just another SSRF issue.](https://ltsirkov.medium.com/gitlab-just-another-ssrf-issue-483bc040392b)

* [Blind SSRF Chains](https://blog.assetnote.io/2021/01/13/blind-ssrf-chains/)

* [A New Era of SSRF Trending Programming Languages! - BlackHat 2017](https://www.blackhat.com/docs/us-17/thursday/us-17-Tsai-A-New-Era-Of-SSRF-Exploiting-URL-Parser-In-Trending-Programming-Languages.pdf)

* [Blind SSRF Chains](https://github.com/assetnote/blind-ssrf-chains)

* [$10000 Facebook SSRF (Bug Bounty)](https://amineaboud.medium.com/10000-facebook-ssrf-bug-bounty-402bd21e58e5)

* [31k$ SSRF in Google Cloud Monitoring led to metadata exposure](https://nechudav.blogspot.com/2020/11/31k-ssrf-in-google-cloud-monitoring.html?m=1)

* [SSRF (Server Side Request Forgery) worth $4,913 | My Highest Bounty Ever !](https://medium.com/techfenix/ssrf-server-side-request-forgery-worth-4913-my-highest-bounty-ever-7d733bb368cb)

* [Blind SSRF - The Hide & Seek Game](https://shahjerry33.medium.com/blind-ssrf-the-hide-seek-game-da9d0ecef2fb)

* [How i found 3 SSRF in one day on different bug bounty targets](https://medium.com/@Mr.Daman.Singh/how-i-found-3-ssrf-in-one-day-on-different-bug-bounty-targets-62e91b4268f8)

* [Exploiting: SSRF For Admin Access](https://infosecwriteups.com/exploiting-ssrf-for-admin-access-31c30457cc44)

* [Unauthenticated Full-Read SSRF in Grafana CVE-2020-13379](https://rhynorater.github.io/CVE-2020-13379-Write-Up)

* [My First Bug: Blind SSRF Through Profile Picture Upload](https://infosecwriteups.com/my-first-bug-blind-ssrf-through-profile-picture-upload-72f00fd27bc6)

* [A tale of my first ever full SSRF bug](https://infosecwriteups.com/a-tale-of-my-first-ever-full-ssrf-bug-4fe71a76e9c4)

* [How I Chained 4 vulnerabilities on GitHub Enterprise, From SSRF Execution Chain to RCE!](https://blog.orange.tw/2017/07/how-i-chained-4-vulnerabilities-on.html)

* [Story of a 2.5k Bounty — SSRF on Zimbra Led to Dump All Credentials in Clear Text](https://infosecwriteups.com/story-of-a-2-5k-bounty-ssrf-on-zimbra-led-to-dump-all-credentials-in-clear-text-6fe826005ccc)

* [From . in regex to SSRF — part 1](https://xvnpw.medium.com/from-in-regex-to-ssrf-part-1-31d5706854ef)

* [From . in regex to SSRF — part 2](https://xvnpw.medium.com/from-in-regex-to-ssrf-part-2-7e4ff261de85)

* [ (SSRF) ON LYFT](https://nahamsec.com/posts/my-expense-report-resulted-in-a-server-side-request-forgery-ssrf-on-lyft)

* [How I made $31500 by submitting a bug to Facebook](https://medium.com/@win3zz/how-i-made-31500-by-submitting-a-bug-to-facebook-d31bb046e204)

* [The road from sandboxed SSTI to SSRF and XXE](https://www.reddit.com/r/Slackers/comments/g6pt8t/the_road_from_sandboxed_ssti_to_ssrf_and_xxe/)

* [Exploiting SSRF in RethinkDB](https://medium.com/@d3fl4t3/exploiting-ssrf-in-rethinkdb-38a5a5438fb7)

* [Blind SSRF - Sentry Misconfiguration](https://shahjerry33.medium.com/blind-ssrf-sentry-misconfiguration-a68edc789db2)

* [Exploiting an SSRF: Trials and Tribulations](https://medium.com/a-bugz-life/exploiting-an-ssrf-trials-and-tribulations-14c5d8dbd69a)

* [Blind SSRF exploitation](https://lab.wallarm.com/blind-ssrf-exploitation/)

* [31k$ SSRF in Google Cloud Monitoring](https://nechudav.blogspot.com/2020/11/31k-ssrf-in-google-cloud-monitoring.html?m=1)

* [Tale of 3 vulnerabilities to account takeover!](https://logicbomb.medium.com/tale-of-3-vulnerabilities-to-account-takeover-44ba631a0304)

* [An unknown Linux secret that turned SSRF to OS Command injection](https://secureitmania.medium.com/an-unknown-linux-secret-that-turned-ssrf-to-os-command-injection-6fe2f4edc202)

* [SSRF inside Google production network](https://opnsec.com/2018/07/into-the-borg-ssrf-inside-google-production-network/)

* [Pivoting from blind SSRF to RCE with HashiCorp Consul](https://www.kernelpicnic.net/2017/05/29/Pivoting-from-blind-SSRF-to-RCE-with-Hashicorp-Consul.html)

* [Hunting Headers for SSRF](https://speakerdeck.com/aditya45/hunting-headers-for-ssrf?slide=16)

* [WRITE UP – GOOGLE VRP N/A: SSRF BYPASS WITH QUADZERO IN GOOGLE CLOUD MONITORING](https://omespino.com/write-up-google-vrp-n-a-ssrf-bypass-with-quadzero-in-google-cloud-monitoring/)

* [Escalating SSRF to RCE](https://sanderwind.medium.com/escalating-ssrf-to-rce-7c0147371c40)

* [GITLAB — Server Side Request Forgery in “Project Import” page.](https://ltsirkov.medium.com/gitlab-server-side-request-forgery-in-project-import-page-6fdb9ef423e4)

* [SSRF’s up! Real World Server-Side Request Forgery (SSRF)](https://www.shorebreaksecurity.com/blog/ssrfs-up-real-world-server-side-request-forgery-ssrf/)

* [SSRF - Server Side Request Forgery (Types and ways to exploit it) Part-1](https://medium.com/@madrobot/ssrf-server-side-request-forgery-types-and-ways-to-exploit-it-part-1-29d034c27978)

* [Weaponizing BURP to work as an evil SSRF Confluence Server.](https://medium.com/@Master_SEC/weaponizing-burp-to-work-as-an-evil-ssrf-confluence-server-e077d71b4ef2)

* [Google VRP SSRF in Google Cloud Platform StackDriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/)

* [Vimeo upload function SSRF](https://medium.com/@dPhoeniixx/vimeo-upload-function-ssrf-7466d8630437)

* [SSRF via FFmpeg HLS processing](https://medium.com/@pflash0x0punk/ssrf-via-ffmpeg-hls-processing-a04e0288a8c5)

* [My First SSRF Using DNS Rebinding](https://geleta.eu/2019/my-first-ssrf-using-dns-rebinfing/)

* [BugBounty | A Simple SSRF](https://jinone.github.io/bugbounty-a-simple-ssrf/)

* [ssrf reading local files](https://www.openbugbounty.org/blog/leonmugen/ssrf-reading-local-files-from-downnotifier-server/)

* [An Accidental SSRF Honeypot in Google Calendar](https://www.komodosec.com/post/an-accidental-ssrf-honeypot-in-google-calendar)

* [Gain adfly SMTP access with SSRF via Gopher Protocol](https://medium.com/@androgaming1912/gain-adfly-smtp-access-with-ssrf-via-gopher-protocol-26a26d0ec2cb)

* [SVG XLink SSRF fingerprinting libraries version](https://medium.com/@arbazhussain/svg-xlink-ssrf-fingerprinting-libraries-version-450ebecc2f3c)

* [Server Side Request Forgery(SSRF){port issue hidden approch }](https://medium.com/@w_hat_boy/server-side-request-forgery-ssrf-port-issue-hidden-approch-f4e67bd8cc86)

* [The journey of Web Cache + Firewall Bypass to SSRF to AWS credentials compromise!](https://logicbomb.medium.com/the-journey-of-web-cache-firewall-bypass-to-ssrf-to-aws-credentials-compromise-b250fb40af82)

* [Ssrf to Read Local Files and Abusing the AWS metadata](https://medium.com/@pratiky054/ssrf-to-read-local-files-and-abusing-the-aws-metadata-8621a4bf382)

* [From SSRF To RCE in PDFReacter](https://medium.com/@armaanpathan/pdfreacter-ssrf-to-root-level-local-file-read-which-led-to-rce-eb460ffb3129)

* [SSRF vulnerability via FFmpeg HLS processing](https://medium.com/@valeriyshevchenko/ssrf-vulnerability-via-ffmpeg-hls-processing-f3823c16f3c7)
 
* [Escalating SSRF to RCE](https://generaleg0x01.com/2019/03/10/escalating-ssrf-to-rce/)

* [Vimeo SSRF with code execution potential.](https://infosecwriteups.com/vimeo-ssrf-with-code-execution-potential-68c774ba7c1e)

* [Unauthenticated Blind SSRF in Oracle EBS](https://medium.com/@x41x41x41/unauthenticated-ssrf-in-oracle-ebs-765bd789a145)

* [$1.000 SSRF in Slack](https://elbs.medium.com/1-000-ssrf-in-slack-7737935d3884)

* [Exploiting SSRF in AWS Elastic Beanstalk](https://notsosecure.com/exploiting-ssrf-in-aws-elastic-beanstalk/)




## HackerOne Reports 💻

* [SSRF in imgur video GIF conversion](https://hackerone.com/reports/247680)

* [Full Read SSRF on Gitlab's Internal Grafana](https://hackerone.com/reports/878779)

* [SSRF protection bypass](https://hackerone.com/reports/736867)

* [SSRF on project import via the remote_attachment_url on a Note](https://hackerone.com/reports/826361)

* [Blind SSRF on debug.nordvpn.com due to misconfigured sentry instance](https://hackerone.com/reports/756149)

* [Blind SSRF on errors.hackerone.net due to Sentry misconfiguration](https://hackerone.com/reports/374737)

* [SSRF PDF documentconverterws](https://hackerone.com/reports/361793)

* [Blind SSRF on https://labs.data.gov/dashboard/Campaign/json_status/ Endpoint](https://hackerone.com/reports/895696)

* [SSRF In Get Video Contents](https://hackerone.com/reports/643622)

* [SSRF in webhooks leads to AWS private keys disclosure](https://hackerone.com/reports/508459)

* [SSRF - RSS feed, blacklist bypass (IP Formatting)](https://hackerone.com/reports/299130)

* [SSRF](https://hackerone.com/reports/296045)

* [SSRF in CI after first run](https://hackerone.com/reports/369451)

* [SSRF in Exchange leads to ROOT access in all instances](https://hackerone.com/reports/341876)

* [SSRF in api.slack.com, using slash commands and bypassing the protections.](https://hackerone.com/reports/381129)

## PayloadsAllTheThings / Server Side Request Forgery / 🚀

- [PayloadsAllTheThings / Server Side Request Forgery](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Request%20Forgery)
