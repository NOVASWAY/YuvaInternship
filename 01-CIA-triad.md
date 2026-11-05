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
