**Description:**


No rate limit on the api /login of Defectdojo version 2.37.3 ([https://github.com/DefectDojo/django-DefectDojo](https://github.com/DefectDojo/django-DefectDojo)) allow remote attackers to Brute Force hijacking user accounts in the system.

**Proof of Concept:**
1. Send a login request.
2. Capture the login request
3. Replay the login request with different password value.
(Here I use intruder to the attack)
HTTP request
![image](https://github.com/user-attachments/assets/6c71b543-e431-4eea-bac5-e57923e0794a)
Success
![image](https://github.com/user-attachments/assets/3f3b007c-f46e-4840-bd5b-fc119553e160)
![image](https://github.com/user-attachments/assets/c4064478-cedb-4a5f-b59c-4217ed326c05)

**Impact:**


Hijacking user accounts in the system.
