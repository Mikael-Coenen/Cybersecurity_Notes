## Cybersecurity Objectives
- Three objectives of cybersecurity programs are: confidentiality, integrity, and availability (CIA)
    - confidentiality: unathorized individuals arent able to access sensitive information
    - Integrity: no unathorized modifications to info or systems
    - Availability: legitimate users can access info and systems when they request them
- Nonrepudiation: the assurance that something cannot be denied by someone

## Data Breach Risks
- Security incidents occur when there is a breach of the CIA triad of info or systems
- Three key threats to cybersecurity efforts: disclosure, alteration, denial (DAD)
    - Disclosure: exposure of sensitive info to unauthorized individuals, violates confidentiality
    - Alteration: unauthorized modification of information, violates integrity
    - Denial: disruption of a legitimate users access to info, violates availability

## Breach Impact Categories
- Financial risk: risk of monetary damage to an organization as the result of a data breach
- Reputational risk: when negative publicity around a security breach causes loss of goodwill among customers, employees, etc
- Strategic risk: an organization will become less effective in meeting its major goals as result of a breach
- Operational risk: risk to an organizations ability to carry out its day-to-day functions
- Compliance risk: when a security breach causes an organization to run afoul of legal or regulatory requirements
----------------------------------------------------------------------------------------------------------------------------------
## Implementing Security Controls
- Control objectives: statement that details the desired result from implementing security controls
- Security controls: specific measures that fufill the security objectives of an organization

## Gap Analysis
- Examination of the effectiveness of security controls at meeting security objectives
- If any case where controls dont meet the objective, thats a gap which should be treated as a potential risk and remediated at some point

## Security Control Categories
Security control categories are based on their mechanism of action:
- Technical controls: enforce CIA in the digital space, ex: encryption
- Operational controls: the processes that are put into place to manage tech in a secure manner, ex: user access reviews
- Managerial controls: mechanics of the risk management process, ex: periodic risk assessments
- Physical controls: security controls that impact the physical world, ex: fences

## Security Control Types
Security control types are based on their desired effect:
- Preventive controls: intend to stop a security issue before it occurs, ex: firewalls
- Deterrent controls: seek to prevent an attacked from attempting to violate security policies, ex: barbed wire fences
- Detective controls: identify security events that have already occured, ex: intrusion detection systems
- Corrective controls: remediate security issues that have already occured
- Compensating controls: controls designed to mitigate the risk associated with exceptions made to a security policy
- Directive controls: inform employees and others what they should do to achieve security objectives
----------------------------------------------------------------------------------------------------------------------------------
## States where data exists
- Data at rest: stored data that resides on storage media
- Data in transit: data in motion over a network
- Data in use: data that is actively in use by a computer system

## Data Encryption
- Encryption tech uses mathematical algorithms to protect info
- Encrypted data is unintelligible to anyone without the right decryption key

## Data Loss Prevention (DLP)
- DLP systems help organizations enforce info handling policies and procedures to prevent data loss and theft
- DLP systems work in two different environments: ggent based and agentless (network-based)
- Agent-based DLP: uses software agents installed on systems to search for sensitive info which allows security teams to secure that info
- Agentless (network-based) DLP: dedicated devices that sit on the network and monitor outbound traffic

## DLP System mechanisms of action
- Pattern matching: watch for telltale signs of sensitive info
- Watermarking: where systems or administrators apply electronic tags to sensitive documents

## Data Minimization
- Data minimizations techniques seek to reduce risk by reducing amount of sensitive info that is maintained on a regular basis
- Best way to achieve this is to destroy data that is no longer needed
- Deidentification process: if data cant be destroyed then remove ability to link data to an individual
- Data obfuscation: transform data into format where the original info cannot be retrieved
    - Hashing: use a hash function to transform data into a hash value*
    - Tokenization: replaces sensitive values with a unique identifier using a lookup table
    - Masking: partially redacts sensitive info by replacing some or all sensitive fields with blank characters
    - *Note attackers can use rainbow table attack: when an attacker computes hashes of selected values to see if those hashes exist in our data
## Access Restrictions
- Access restrictions are security measures that limit the ability of individuals to access sensitive info
    - Geographic restrictions: limit access to resources based on the physical location of a user or system
    - Permission restrictions: limit access to resources based on the users role or level of authorization
## Segmentation and Isolation
- Segmentation: places sensitive systems on seperate networks where they can communicate with each other but have strict rules on communicating with systems on other networks
- Isolation: completely cuts a system off from access to or from outside networks
