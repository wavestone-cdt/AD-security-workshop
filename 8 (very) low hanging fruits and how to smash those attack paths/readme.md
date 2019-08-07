# 8 (very) low hanging fruits and how to smash those attack paths
 
Pentesters or attackers often exploit the same obvious vulnerabilities in Active directory. Come learn how to exploit and mitigate them.
 
## Workshop
 
### Abstract
(Spoiler alert) During a cyber-attack, the Active Directory is one of favourite target in every firm. Very, very (very) often, to not say always, the active directory is compromised ... Sadly, pentesters or attackers often exploit the same obvious vulnerabilities to bounce and perform a privilege escalation. Come learn how to exploit and mitigate them. With something a little different, we are convinced that most common attacks against Active Directory could be prevent.
 
 
###  Storyline 
Welcome in the PacMan Firm, the most insecure network ever, we have a very large Active Directory environment and we do no security at all. For now, no ghost has ever hacked our corporate network (at least we hope) but our new CISO requires us to perform a security assessment.
 
**Your mission, should you choose to accept it, is to evaluate our security level and fix the issues.**
 
### Detailed content 
 
In this fully hands-on workshop, we’ll guide you through 8 of the lowest hanging fruits weaknesses that we witnessed during numerous penetration tests. You’ll learn how to:
 
- Spot passwords inside user descriptions
- Find passwords on shared folders
- Spray passwords over accounts
- Quickly detect obsolete workstations and servers
- Get free password hashes by kerberoasting
- Pivot from machine to machine by reusing local credentials
- Spot machines where Domain Admins are connected
- Retrieve Domain Admins credentials in memory
- Do it faster, do it stronger
 
Crackmapexec, Powerview, Rubeus, Mimikatz, BloodHound will be your best friends during this workshop.
 
### Video
 
Video of each fruits could be found inside Video directory.
 
## References / Tools inside
####  User Object Attributes
 
* Tool - Microsoft: [Adexplorer](https://docs.microsoft.com/en-us/sysinternals/downloads/adexplorer)
* Ref - @ropnop: [Fun with LDAP, Kerberos (and MSRPC) in AD Environments](https://troopers.de/downloads/troopers19/TROOPERS19_AD_Fun_With_LDAP.pdf)
 
#### Network share
 
* Tool - @HarmJ0y: [PowerView_dev](https://github.com/PowerShellMafia/PowerSploit/tree/dev/Recon)
* Tool - @tevora : [SharpView](https://github.com/tevora-threat/SharpView)
* Ref - @exploit-db: [Google dorks](https://www.exploit-db.com/google-hacking-database)
 
### Password Spraying
 
* Tool - @flelievre: [CleverSpary](https://github.com/wavestone-cdt/Invoke-CleverSpray)
* Ref - @trimarcsecurity: [Detect Password Spraying](https://www.trimarcsecurity.com/single-post/2018/05/06/Trimarc-Research-Detecting-Password-Spraying-with-Security-Event-Auditing)
* Ref - @jephthai: [OpenPasswordFilter](https://github.com/jephthai/OpenPasswordFilter)
* Ref - Microsoft: [Password ban on premises](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-password-ban-bad-on-premises)
 
### Pass the hash with local account
 
* Tool - @maaz: [CrackMapExecWin](https://github.com/maaaaz/CrackMapExecWin)
* Tool - @byt3bl33d3r: [CrackMapExecWin](onsole.aws.amazon.com/iam/home?region=eu-west-3#/home)
* Ref - @Microsoft: [LAPS](https://technet.microsoft.com/en-us/mt227395.aspx)
* Ref - @flamingkeys: [Deploying LAPS](https://flamingkeys.com//deploying-the-local-administrator-password-solution-part-1/)
* Ref - @jformacek: [AdmPwd.E](http://admpwd.com/)
 
### Spot Domain Admins
 
* Ref - @Microsoft: [Securing Privilege Access](https://docs.microsoft.com/en-us/windows-server/identity/securing-privileged-access/securing-privileged-access-reference-material)
 
### Targeted Kerberoasting
* Tool - @HarmJ0y: [Rubeus](https://github.com/GhostPack/Rubeus)
* Ref - @Mitre: [Kerberoasting](https://attack.mitre.org/techniques/T1208/)
* Ref - @Harmj0y: [Targeted Kerberoasting](https://www.harmj0y.net/blog/activedirectory/targeted-kerberoasting/)
* Tool - @oger: [wavecrack](https://github.com/wavestone-cdt/wavecrack)
 
 
### Mimikatz
* Tool - @gentilkiwi: [Mimikatz](https://github.com/gentilkiwi/mimikatz)
* Ref - @mysmartlogon: [You « try » to detect mimikatz](https://www.youtube.com/watch?v=F1oq9mEPk6I)
 
 
### BloodHound
* Tool - @_wald0, @CptJesus & @harmj0y: [BloodHound](https://github.com/BloodHoundAD/BloodHound)
* Ref - @_wald0, @leechristensen & @harmj0y: [An ACE Up the Sleeve](https://specterops.io/assets/resources/an_ace_up_the_sleeve.pdf)
* Ref - @CptJesus: [BloodHound](https://blog.cptjesus.com/)
* Ref - @gentilkiwi & @mysmartlogon: [DCSync](https://www.youtube.com/watch?v=KILnU4FhQbc)
* Ref - @_wald0: [BloodHound and Admin rights](https://twitter.com/_wald0/status/1103756044986171394)
* Ref - @SadProcessor: [The Dog Whisperer’s Handbook](https://insinuator.net/2018/11/the-dog-whisperers-handbook/)
* Ref - @_wald0: [BloodHound Gang Slack](https://bloodhoundgang.herokuapp.com/)
 
### Going Further
* Tool - @fireeye: [CommandoVM](https://www.fireeye.com/blog/threat-research/2019/03/commando-vm-windows-offensive-distribution.html)
* Tool - @raandree & @nyanhp: [AutomatedLab](https://github.com/AutomatedLab/AutomatedLab)
* Ref - @PyroTek3 : [Adsecurity](https://adsecurity.org/)
* Tool - @mikeloss: [Grouper2](https://github.com/l0ss/Grouper2)
* Tool - @mysmartlogon: [PingCastle](https://www.pingcastle.com/)
* Ref - @JPCERTCC: [ToolAnalysisResultSheet](https://jpcertcc.github.io/ToolAnalysisResultSheet/)
 
We are sorry if we miss some great references :(
 
## Versioning
 
* First version - 2 hours: [BSides Lisbon 2018](https://bsideslisbon.org/2018/speakers/#r%C3%A9miescourrouandnicolasdaubresseWorkshop)
* Second version - 3 hours: [Le Hack 2019](https://lehack.org/en/planning/workshop-fr-active-directory-security-8-very-low-hanging-fruits-and-how-to-smash-those-attack-paths)
* Third version - 4 hours: [BSides Las Vegas 2019](https://www.bsideslv.org/schedule-2/)

## Authors
 
* **Nicolas DAUBRESSE** - [Twitter](https://twitter.com/nicolas_dbresse)
* **Rémi ESCOURROU** - [Twitter](https://twitter.com/remiescourrou)
 
Feel free to say Hi if you want to talk about it !
 
## License
 
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
 
## Acknowledgments
 
* Everyone referenced just before
* A special thanks to @_wald0, @harmj0y & @gentilkiwi for their amazing works
