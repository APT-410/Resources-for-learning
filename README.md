# Learning resources & frequent tools for programming, security and general IT

Hi this is just a simple set of learning paths and tricks I found to help me, this is a quick list and is broken out into some sub paths. As there is so much content I will update when I can. If you have suggestions feel free to comment or create an issue or pull request. This can be openly shared and modified.

[Click here to check this out in the website](https://apt-0.github.io/Resources-for-learning/)

## Programming

  ### Python
  #### Websites
  - [Offical python site for getting started and tutorials: www.python.org](https://www.python.org/about/gettingstarted/) <-- You should read this first. This is a great place to get started, goes over different text editors, has a link to python libraries, tutorials etc.
  #### Books
  - [(Free)(General python - Great for beginning through some experienced) "Automate the boring stuff"](https://automatetheboringstuff.com/) <-- Great for some practical challenges and beginning to write some code
  - [Violent Python](https://www.amazon.com/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579) <-- Good for IT security
  - [Black Hat Python](https://nostarch.com/blackhatpython) <-- Good for pentest and red team
  #### Cheat sheets
  - [Python cheat sheet](https://github.com/APT-0/python-cheatsheet)

  ### C++
  (To be added)
  
  ### Javascript
  -[Hacking javascript - "untrusted"](https://alexnisnevich.github.io/untrusted/)
  
  ### Machine Learning / Deep learning / Neural networks
  -[Fast.ai (pyTorch Deep learning)](https://www.fast.ai/) <-- Machine/Deep learning course
  -[Deeplizard](https://deeplizard.com/) <-- Machine/Deep learning course
  
  ### Other
  - [Regular Expressions - testing: regex101](https://regex101.com/)
  - [Decode / Encode: Cyberchef.io](https://gchq.github.io/CyberChef/) 
  - [Development enviroment - IDE/Text editor (VScode)](https://code.visualstudio.com/) <-- Theres other text editors and IDEs like Atom, sublime, eclipse. VScode is my favorite as extensions make adding new programming languages easy and add on almost anything else you can imagine to help from running a live server, debugging, dev containers, live share "peer" program, docker to build and ship your apps.
  - [Visual Studio Dev Essentials](https://visualstudio.microsoft.com/dev-essentials/) <-- This has free azure credits, trial subscriptions like M365 E5, downloads for Windows 10, Windows server, and SQL server, certifications and more (check out too if your company already has a paid subscription you get more cool stuff like Visual studio enterprise, more monthly credits etc)

## Red Team / Pen Test
### General
- [Hands on learning game style - Tryhackme.com](https://tryhackme.com/) <-- This is personally one of my favorite websites there are complete virtual machines on here that can get you started with learning basic linux commands, python, hacking, networking, and some blue team functions.

### General Pentest
#### Authentication attacks
- [Attacking active directory 0 - 0.9](https://zer1t0.gitlab.io/posts/attacking_ad/)

#### Command and Control
- [Understanding C2 Frameworks](https://nasbench.medium.com/understanding-detecting-c2-frameworks-ares-8c96aa47e50d)
- [The C2 matrix](https://www.thec2matrix.com/matrix) <-- List of some of the most popular C2 Frameworks, with links to the frameworks
  - [SANS Slingshot C2 Matrix](https://howto.thec2matrix.com/slingshot-c2-matrix-edition) <-- VM of several C2 frameworks   

### Web Application Testing
I defintely recommend first before using the tools section learn the techniques in the owasp top 10 and manually exploit first, tools can help but many times you may not be able to use them in rule of engagement with bug bounties.
- [Making Burp Suite Macros](https://akshita-infosec.medium.com/burp-macros-what-why-how-151df8901641)

#### Books
- [Tangled Web](https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)

#### Tools (Many come with Kali)
- [Vulnerable Enviroment: Web Goat](https://owasp.org/www-project-webgoat/)
- OWASP ZAP
- Burpsuite
- Nmap
- SQLmap 
- Foca
- Fiddler (Windows only)
- Nikto
- Shodan.io


### General
- [Hands on learning game style - Tryhackme.com](https://tryhackme.com/) <-- This is personally one of my favorite websites there are complete virtual machines on here that can get you started with learning basic linux commands, python, hacking, networking, and some blue team functions.


## Blue Team

  ### Forensics
  #### Reverse Engineering
  - [Malware.re](https://class.malware.re/) <-- Reverse engineering class and content
  #### Host 
  #### Network
  ### Security Engineering
  ### Detection Engineering
  
## Purple Team

  ### Lab Builds
  Check this out to understand alittle more on chosing your lab build -> https://medium.com/@darkcaracal/building-a-free-threat-hunting-lab-for-testing-detections-and-ttps-in-5-minutes-1d216cc9d419
  - [Defensive Origins](https://github.com/DefensiveOrigins/APT-Lab-Terraform)
  - [Detection Lab](https://detectionlab.network/) <-- One of the easiest labs to setup on host, actual steps you need to take are less than 5 minutes
  - [Azure Sentinel2GO](https://github.com/OTRF/Azure-Sentinel2Go) <-- Awesome newer lab released in last year with logging setup, VMs and SIEM without limits, oh and "one click deploy"
    - [SimuLand](https://github.com/Azure/SimuLand) <-- Building off Azure Sentinel2GO, Simuland requires alittle more setup but is geared toward giving scenarios of attacks, this is cool and will be even better with more releases

## General IT
  ### Linux

## Learning Tips 
These are just a few cool things that helped me learn, and search for answers quickly.
1. Start a library of all your code or projects, Github is the easiest way to share all your cool projects once you have a few.
2. Get google drive and store PDFs from sites like humble bundle, every 3ish weeks they will come out with a new bundle of about 12ish books on topics from Python, to web application hacking or focused on linux only for $5-$15, just pick the ones you want to learn now or a later date. You can search the contents of all your books for keywords to quickly search hundreds of books in google drive at only $2 a month for 100GB.
3. Make a plan of what your goal is and layout what you want to learn, in small blocks of time each day maybe an hour or two focus on a book, website or another source to learn. Personally I think its difficult to learn if you arent doing what you want to learn hands on.
4. Join peer groups for your learning interest, I really like the app Discord and will have tons of people willing to mentor you. Just search for a group and join. Learning these topics is often a very solo activity however, some good friends can help guide you alittle more and help when you're stuck.



