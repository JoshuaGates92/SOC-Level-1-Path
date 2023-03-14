
==Cyber Threat Intelligence (CTI)== is evidence-based knowledge about adversaries, including their indicators, tactics, motivations, and actionable advice against them. These can be utilised to protect critical assets and inform cybersecurity teams and management business decisions.

### Some key terms
These are often used interchangably but need to be clarified for our purposes here:
==**Data==:** Discrete indicators associated with an adversary such as IP addresses, URLs or hashes.

==**Information==:** A combination of multiple data points that answer questions such as “How many times have employees accessed tryhackme.com within the month?”

==**Intelligence==:** The correlation of data and information to extract patterns of actions based on contextual analysis.

### Questions to consider while gathering CTI
-   Who’s attacking you?
-   What are their motivations?
-   What are their capabilities?
-   What artefacts and indicators of compromise (IOCs) should you look out for?

## Categorising sources of CTI:
-   **Internal:**
    -   Corporate security events such as vulnerability assessments and incident response reports.
    -   Cyber awareness training reports.
    -   System logs and events.

-   **Community:**
    -   Open web forums.
    -   Dark web communities for cybercriminals.

-   **External**
    -   Threat intel feeds (Commercial & Open-source)
    -   Online marketplaces.
    -   Public sources include government data, publications, social media, financial and industrial assessments.

## Threat Intelligence Classification

-   **Strategic Intel:** High-level intel that looks into the organisation’s threat landscape and maps out the risk areas based on trends, patterns and emerging threats that may impact business decisions.
    
-   **Technical Intel:** Looks into evidence and artefacts of attack used by an adversary. Incident Response teams can use this intel to create a baseline attack surface to analyse and develop defence mechanisms.
    
-   **Tactical Intel:** Assesses adversaries’ tactics, techniques, and procedures (TTPs). This intel can strengthen security controls and address vulnerabilities through real-time investigations.
    
-   **Operational Intel:** Looks into an adversary’s specific motives and intent to perform an attack. Security teams may use this intel to understand the critical assets available in the organisation (people, processes and technologies) that may be targeted.

## CTI Lifecycle

Data churning has a six-step process:
### 1. Direction
Defined goals and objectives are a requirement with the following parameters identified:
-  Information assets and business processes that require defending.
-   Potential impact to be experienced on losing the assets or through process interruptions.
-   Sources of data and intel to be used towards protection.
-   Tools and resources that are required to defend the assets.

### 2. Collection
Data collection is usually automated where possible to allow for time for triaging other more pressing incidents

### 3. Processing
Data is extracted, sorted, organised, correlated with appropriate tags and presented visually in a usable and understandable format to the analysts. SIEMs(Security Information Event Management) are valuable tools for achieving this and allow quick parsing of data.

### 4. Analysis
Deriving insights may involve:
-   Investigating a potential threat through uncovering indicators and attack patterns.
-   Defining an action plan to avert an attack and defend the infrastructure.
-   Strengthening security controls or justifying investment for additional resources.

### 5. Dissemination
Who gets more detailed info etc.

### 6. Feedback
Response from stakeholders to inform next steps
