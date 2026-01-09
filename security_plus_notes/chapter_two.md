# Classifying Cybersecurity Threats
## Characteristics of threat actors
- Internal vs external: threat actors can exist outside or inside our environments
- Level of sophistication/capability: threat actors vary greatly in their level of their sophistication and capability
- Resources/funding: threat actors vary in the resources available to them (ex: hobbyist vs organized crime)
- Intent/motivation: threat actors vary in their intent (ex: financial gain vs political objectives)

## Types of threat actors
- Unskilled attackers: attackers who rely almost entirly on automated tools, no clear target of their attacks, motivation revolves around trying to prove their skill, lack skills and resources (time and money)
- Hacktivists: use hacking techniques to accomplish some activist goal, skill levels vary widely, resources vary somewhat, tend to be external attackers
- Organized crime: appears in any case where money is to be made, tends to have attackers who have moderate to highly skilled, have more resources, involved in these cybercrime categories: cyber-dependent crime, child sexual abuse material, online fraud, dark web activity, cross-cutting crime factors
- Nation-state attackers: state-sponsored attackers that attack foreign governments or coporations, attackers are highly skilled, significant resources, motive can be political or economic, often uses advanced persistant threats (APT)*
- Insider threat: occur when an employee, contractor, vendor, etc with authorization to info and systems uses that access to wage an attack against that organization, often aimed at disclosure of sensitive info, could be of any skill level, could have activist or financial motivations, usually working alone and has limited financial resources and time
- Competitors: engage in corporate espionage to steal sensitive info from your organization and use it to their own business advantage
- * Side note: zero day attacks are when APT attackers discover an unknown vulnerability and exploit it, giving security teams zero days to fix it before the attack
- Side note: shadow IT is when any technology used by employees for work purposes without the knowledge or approval of the organization, often to boost productivity and this creates a significant security risk for the company

## Attacker Motivations
- Data exfiltration attacks: motivated to obtain sensitive info
- Espionage attacks: motivated by organizations seeking to steal secret info from other organizations
- Service disruption attacks: seek to take down or interrupt critical systems or networks
- Blackmail attacks: seek to extort money or other concessions from victims by threating to release sensitive info or launch other attacks
- Financial gain attacks: motivated to make money through theft or fraud
- Philosophical/political belief attacks: motivated by ideological or political reasons
- Ethical attacks: motivated to expose vulnerabilities and improve security
- Revenge attacks: motivated to get even with an individual or organization by embarrassing them or extracting some other form of retribution
- Disruption/chaos attacks: motivated to cause chaos and disrupt normal operations
- War: hacking in an attempt to disrupt military operations and change the outcome of an armed conflict

## Threat vectors and attack surfaces
- Attack surface: system, application, or service that contains a vulnerability threat actors might exploit
- Threat vector: the means that threat actors use to obtain access
## Type of threat vectors and attack surfaces
- Message-based: phishing messages, spam messages, email, text, voice calls, social media, as long as the threat actor gets the login credentials of a single user they can attack
- Wired networks: gain access to an organizations wired network by physically entering the organizations facilities
- Wireless networks: gain access to an organizations wireless network
- Systems: individual systems serve as threat vectors such as an OS system or legacy applications or systems
- Files and images: files or images could be embedded with malicious code
- Removable devices: the use of removable media to spread malware
- Cloud: attackers scan cloud services for files with security flaws
- Supply chain: attacks attempt to interfere with an organizations IT supply chain including hardware providers, software providers, and service providers

## Threat data and intelligence
- Threat intelligence: set of activities and resources available to cybersecurity professionals seeking to learn about changes in the threat environment
- Threat maps: provide a geographic view of threat intelligence
- Indicators of compromise (IoCs): telltale signs an attack has taken place, threat intelligence sources may proivde IoCs

## Open source intelligence
- Open source threat intelligence: threat intelligence acquired from publicly available sources
- Dark web: network run over standard internet connections but uses multiple layers of encryption to provide anonymous communication

## Propreitary and closed-source intelligence
- Closed source intelligence: threat intelligence that is not publicly available and typically requires a fee, subscription, or special clearance to access

## Assessing threat intelligence
- Is it timely?
- Is the info accurate?
- Is the info relevant?
- Confidence score: tell an organzation how much trust they can give a piece of threat intelligence

## Threat indicator management and exchange
- Structured Threat Information eXpression (STIX): an XML language (a markup language that is readable by both humans and machines) used for describing and sharing threat intelligence, newer versions use JSON
- Trusted Automated eXchange of Intelligence Information (TAXII): allow cyber-threat info to be communicated at the application layer via HTTPS

Information sharing organizations
- Information Sharing and Analysis Centers (ISACs): help infrastructure owners and operators share threat info and provide tools and assistance to their members
