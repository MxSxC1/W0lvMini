Project Wolverine / W0lv3r1n3

Never, Ever, Run Any Powershell Or Batch Files Or Exes Without Checking And Understanding
Trust Nobody. Including Us!
https://github.com/MxSxC1/MxSxC1Warning



WolvMini is a cut down basic version of Project Wolverine requiring no install.
Project Wolverine is a 8 year (so far) unreleased project, initially attempting to lock down and secure users privacy and security.
So what's new, there are firewalls, ad blockers, anti-virus, spyware detection apps aplenty, why bother?

Quite simply, none of them work, or they work to an extent, but they don't detect, block, or stop the real evil out there...

No doubting the stop malicious hackers/spyware/bad guys out there, but the real evil is the guys who control WHAT they block. 

Who decides what is right and what's wrong? WHo decides what is spyware, and what is not? Who decides who it's ok to share your data with, and who it's not? Very scary corporates/governments/peeople like Donald Trump maybe?

We have been blocked, stopped, dozens of our techniques to detect the real spyware and malicious goings on. It's getting worse and more difficult, and we simply can't compete with corporates who have so much power, funding, and when it's being further obsfucated and hidden from the users.

Our task now, is to continue fighting the losing battle, but to educate, and show people a taste of what is happening.

To allow the user to see what's going on, detect vulnerabilities, and leaks of their personal information, and to have at least a little power over what's going on.

We will not tell you who the bad guys are, who is right and who's wrong, who is evil, and who is not. We will give you the tools to see what and who your data is being shared with, and let you decide for yourself. And what we show you is only the tip of the Iceberg.

This project contains elements from the below:
Wolverine/W0lv3r1n3 - Overall Management Engine, The Initial Project, Later Split Up To Sheer Complexity & Size Into:

Adamantium/Adamant1um - Security Management - Continous Monitoring & Checking Of Your Device, Software, HardWare, And Control

FirstRecon/F1rstR3c0n - Device Scanner & Reports, Shows You What Is Going On, And Highlights Any Issues. This Has Not Been Released As It Can Be USed Maliciously But Elements Are Being Released.

GreyArea/Gr3yar3a/Smoke & Mirrors/Int3rf3r3nc3 - Just For Fun, Let's Screw These Guys Spying On Us Over, ANd Let's See What, Who, Why Is Targetting us based on it. I am a Baseball Player Who Likes Crochet, Who Are You? This Is Several Years Out Of Date, And It's Methods/Efectiveness Severely Limited, And Have To An Extent Been Blocked. Shelved For Now...

FirewallX - Hook INto Windows Firewall which is cr@p. Allows YOU to block what you don't like (and does it properly), then it checks it constantly, and when Windows/Program/WHoever, overriodes your settings and allows a blocked firewall rule, or creates a new one...it detects it, and locks it down again. You'd be amazed how often this happens, we have turned off alerting and just let it do it's stuff. Working on hooking in to pfsense.

Netw0rkX - Split out from the above, constantly monitors your network activity, hooks into API's to see who you are communicating with, looks up the database for any keyword matches - for example anything with "telemetry" in the name, and alerts, notifies, produces reports. Auto-update of the hosts file is possible, and feeds into DNS blocking/firewall/pfsense, being looked at.

WolvCrypto - All crypto is being taken out of Wolverinem migrated to a new project and database...and being kept completely separate. It is currently low priority, but still being worked on - hooks into API's and scans prices, x-referneces, highlights and fake data/news, and does it without spying on the user! Many plans but unliekly to have time...

---
Migration/Sync/Build
As WolvMini is a separate stand alone package, it does not follow W0lv3r1ne file structure.
Any libraries, batch files, code changes, etc from the following shared directories code need to be tested and copied to WolvMini (working on automation).
WolvMini is designed to require no installation, and therefore has no real database.

There is an alternative to use the same top level code and structure, which might be simpler solution.

Instead data is stored in arrays currently, but they wil be moved to .csv files or similar as part of migration.
Any fundamental changes to WolvDB need to be exported to these .csv files, but remember Mini version cannot handle the sheer volume of data in WolvDB.
WolvDB will be amended to flag entries which need to be exported, and it will be automated extract in future.
TODO: TableList will have 1 if table to be exported.
TODO: Where conditional cut down extract of a table is required will be done by SQL, or if required the field "MiniExport" will be added and the field set to 1 if to be exported. 
TODO: A hard limit needs to be set here, Wolverine Database is simply too big, expect limit to be a few hundred given the amount of processing - to be reviewed.
TODO: Automated SQL Extracts
TODO: Automated Build

