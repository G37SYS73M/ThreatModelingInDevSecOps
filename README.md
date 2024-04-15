# ThreatModelingInDevSecOps
Process of Threat Modeling in DevSecOps and implementing it in CI/CD

## Why Threat Modeling in DevSecOps?
Threat Modeling is a process for looking at attacks actively. The output of this process is a list of threats or probable threat scenarios also our approach should be Holistic to consider all threats not a specific part of an application. The Outputs of the Threat modelling Process are the follows:
- Diagrams (Data Flow Diagrams)
- Security requirements
- Non-requirements
- List of threats/vulnerabilities

## The Process of Threat Modeling in DevSecOps

### Select the Right Approach & Methodology

#### Asset-centric Approach:
According to the name, it turns around assets. So the producing steps are as follows:
1. Create a list of assets
2. Draw assets, components and data flows
3. For each element, check for threats
By repeating these steps for all assets, a list of threats will be produced.

#### Attacker-centric Approach:
Staring threat modelling from an attacker perspective. So the producing steps are as follows:
1. Create a list of threat actors
- Motive
- Means
- Opportunity
2. Create a list of threats

#### Application-centric Approach: 
This one starts with visualizing the application instead of thinking about the risks or attacks first. So the producing steps are as follows:
1. Draw a diagram of the application
2. List threats for each element
- STRIDE
- OWASP TOP 10
3. Rank threats using a classification model

The main motive of Threat Modeling during DevSecOps is to figure out the process of identifying/mitigating threats during the CI/CD. Since the earlier you find vulnerabilities in software, the easier and cheaper it is to fix them, Threat Modeling should be as early as possible in the software design process. If you are working in an agile environment, ideally the threat modelling should be done during each sprint.

In DevOps, we can create a continuous process that we can follow to mitigate risks/threats.

**Before Scans:**
1. Selecting an Approach.
2. Identifying Potential Threats.
3. Security Measures that are already present.
4. Creating a triaging process.

**After Scans:**
1. Assessing the Threat's Likelihood and Impact.
2. Prioritizing Threats (Creating a threshold).
3. Mitigation (Documenting the patches that were applied to software)
4. Documenting the current results and using it as a baseline for creating a threshold.


### Example
Let's take the example mentioned in https://owasp.org/www-community/Threat_Modeling_Process#stride-threat--mitigation-techniques.
**Step 1:**

