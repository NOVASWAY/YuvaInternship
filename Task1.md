											The CIA triad
-The CIA triad is a model for the three things security is trying to protect (Confidentiality, Integrity and Availability). 
-Any security control,attack or incident can be described in terms of which of the three it affects.

		The Three Principles
1. Confidentiality.
Confidentiality means only authrized people can see the information.
Controls:encryption(at rest and in transit), access control and least priviledge, `MFA(Multi Factor Authentication), data classification.
Broken by: a leaked database, a phished password, an exposed s3 bucket, shoulder surfing.

2. Integrity.
Integrity means data stays accurate and unaltered, except by authorized changes.
Controls:hashing, checksums, digital signatures, input validation, audit logs, verison control, change management.
Broken by: SQL injection that can be used to edit records, malware that modifies files, an insider changing a payment amount.

3. Availability.
Availability means systems and data are accessible when authorized users need them.
Controls: Backups, redundancy and fallover, DDoS protection, patching, disaster recovery plans.
Broken by: Ransomware, DDoS(Distributed Denial of Service attacks), hardware failure, a misconfigured deployment taking the service down.`


                                              Risk Management.
Risk management  is how an organization decides what to protect, how much to spend patching it and what to accept.
No one can eliminate every risk, so the goal is to spend linited time and money on the risks that matter the most.


         Key Terms.
Asset: Anything if value e.g data, systems, people.
Threat: Something that could cause harm e.g insider threats.
Vulnerability: A weakness a threat can exploit e.g unpatched server, weak passwords.
Risk:  The chance a threat exploits a vulnerability, and the damage that results.

	Risk = Likellihood x Impact.

	Threat Management Cycle.
Identify: List assets, threats, and vulnerabilities. Sources include assets inventories, vulnerability scans, pst incidents, and threat intelligence.
Assess: Rate each risk's likelihood and impact.
	.Qualitative: low/medium/high ratings.
	.Qantitative: Dollar values. Single Loss Expectancy(SLE) = asset value(AV) x Exposure Factor. Annualized Loss Expectancy(ALE) = SLE x Annual Rate of Occurrence(ARO).
Prioritize: Rank risks by score so the highest get attention first.
Treat: Choose to either mitigate, transfer, Avoid or accept risk.
Monitor and review: Risks can change as systems and threats change so the cycle repeats. Anything left after treatment is residual risk.
