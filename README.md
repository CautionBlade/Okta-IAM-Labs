
# Okta-IAM-Labs
Documenting my entire Okta Workforce Identity journey completed through Okta's What's Next Learning Grant (April 2026).

All modules completed via Okta's official learning platform as part of my 90-day sprint toward the Okta Certified Professional and Okta Certified Administrator certifications.

---

## Module 1: Customize Your Okta Org
**What I learned:** Applied customization to control how Okta communicates with end users. This includes branding, email templates, and user facing settings.  
**Why it matters:** Enterprise orgs require consistent branding and communication standards across identity workflows.

<img width="1889" height="981" alt="Screenshot 2026-05-12 082205" src="https://github.com/user-attachments/assets/e816cbc5-b4b8-45a9-aaa0-7cf6f12e7ee5" />


---

## Module 2: Define Your Users in Okta
**What I learned:** Managed user accounts in Universal Directory, configured user profiles, and handled data accuracy during provisioning as part of lifecycle management.  
**Why it matters:** Clean, accurate user data is the foundation of any IAM program.


<img width="830" height="1060" alt="Screenshot 2026-05-12 083313" src="https://github.com/user-attachments/assets/f5e83707-9a5e-4998-bc35-4d3429b427a9" />

<img width="1063" height="831" alt="Screenshot 2026-05-12 083822" src="https://github.com/user-attachments/assets/d7da7935-cfb3-4893-add6-48ce83b227ad" />

<img width="1063" height="390" alt="Screenshot 2026-05-12 084612" src="https://github.com/user-attachments/assets/ca9c0389-8ee4-4452-bf0a-ad2850bbe0be" />

<img width="1237" height="875" alt="Screenshot 2026-05-12 084400" src="https://github.com/user-attachments/assets/0237812b-23ec-4f72-94ee-5f634585f9bf" />


---

## Module 3: Organize Users with Groups
**What I learned:** Configured group membership to control application access, administrative privileges, and policy assignments.  
**Why it matters:** Group based access is how least privilege is enforced at scale in real enterprise environments.

<img width="1608" height="864" alt="Screenshot 2026-05-30 223826" src="https://github.com/user-attachments/assets/8c924ca9-d89a-4a78-8133-468eab3f6329" />

<img width="874" height="400" alt="Screenshot 2026-05-30 223957" src="https://github.com/user-attachments/assets/43306697-ea5d-4795-9a0f-bc56f4436d90" />

<img width="831" height="367" alt="Screenshot 2026-05-30 224030" src="https://github.com/user-attachments/assets/703359a2-60ce-4053-929b-1cb99bd6a53b" />


---

## Module 4: Define Okta Administrators
**What I learned:** Configured standard and custom administrator roles to enforce least privilege across the Okta admin console itself.  
**Why it matters:** Over privileged admins are a major attack surface. scoping admin roles is a core Zero Trust principle.

<img width="1597" height="848" alt="Screenshot 2026-05-31 094235" src="https://github.com/user-attachments/assets/cd325ac6-cee7-4d8e-8a61-8c8bb92e432f" />

<img width="1285" height="618" alt="Screenshot 2026-05-31 094303" src="https://github.com/user-attachments/assets/179fc565-b909-42f5-a4fb-cb1afe0821ab" />

---

## Module 5: Define a Secure Policy Structure
**What I learned:** Built a secure policy framework using assurance technology and Okta's comprehensive security policies, balancing security with user experience.  
**Why it matters:** Policy structure determines how authentication and authorization decisions are made inside an organization.

Okta guarntees security with their framework called 'Assurance'
Each Assurace level is Ranked as either low merdium or high. the higher one is on that assurace scale the more secure they are. 
administrators can configure various authenticators which end users can enroll and depending on the authenticator used will determine their particular level of Assurance. 


<img width="464" height="308" alt="Screenshot 2026-06-02 081557" src="https://github.com/user-attachments/assets/b8f23005-bbc1-4079-ba9b-528ed25df0e2" />

Policies 

<img width="617" height="246" alt="Screenshot 2026-06-02 081444" src="https://github.com/user-attachments/assets/41e603de-7530-400a-9476-720e06645795" />

Order of Evaluation 

<img width="708" height="288" alt="Screenshot 2026-06-02 081706" src="https://github.com/user-attachments/assets/07072acc-05b7-4b9d-914e-5feb0a0af75d" />






---

## Module 6: Implement Security Policies
**What I learned:** Strengthened security posture by configuring and leveraging Okta's full security policy framework.  
**Why it matters:** Knowing how to implement not just understand security policies is what separates practitioners.

<img width="1100" height="600" alt="Screenshot 2026-05-31 100444" src="https://github.com/user-attachments/assets/840e3392-13ed-4cec-985d-6ef5880ec9cc" />

<img width="1341" height="757" alt="Screenshot 2026-05-31 100641" src="https://github.com/user-attachments/assets/cb528779-00b5-4df7-963e-e1f53011e79e" />

<img width="1450" height="853" alt="Screenshot 2026-05-31 100543" src="https://github.com/user-attachments/assets/938a486e-9a5e-41ae-adeb-532ba289324d" />





---

## Module 7: Implement Passwordless Authentication
**What I learned:** Configured phishing resistant MFA including Okta FastPass for passwordless authentication flows.  
**Why it matters:** Passwordless is the direction enterprise auth is heading towards. this reduces credential based attacks while improving UX.

<img width="888" height="564" alt="Screenshot 2026-06-02 092037" src="https://github.com/user-attachments/assets/e0031454-bdf7-42c9-88c7-32f5048f445f" />


<img width="935" height="933" alt="image" src="https://github.com/user-attachments/assets/dc2ce98c-3c9c-45c0-8bf1-83d2702cdcf9" />


<img width="998" height="925" alt="image" src="https://github.com/user-attachments/assets/478c34a4-5aee-4ba5-a224-ed25e23586ce" />






---

## Module 8: Create App Integrations
**What I learned:** Integrated applications with Okta to provide SSO access. covering SAML, OIDC, and the Okta Integration Network.  
**Why it matters:** App integration is one of the most hands on in demand IAM skills. Every enterprise has dozens of apps to federate.

In this segment i integraded Okta with Sales force using a SAML connection along side mapping user attributes from okta to Sales force. 

<img width="1916" height="951" alt="Screenshot 2026-05-12 095542" src="https://github.com/user-attachments/assets/0dafde7d-1814-408c-a548-eb512fbc9228" />


<img width="1621" height="200" alt="Screenshot 2026-05-12 095651" src="https://github.com/user-attachments/assets/dd121790-8cd2-4319-b43e-971e18706b79" />


<img width="1503" height="597" alt="Screenshot 2026-05-12 095800" src="https://github.com/user-attachments/assets/7679c22e-e6ce-4bde-b717-56a64cb161fd" />


<img width="1916" height="938" alt="Screenshot 2026-05-12 101420" src="https://github.com/user-attachments/assets/62aa9fb0-94da-4a35-a2ad-1a38a23b6f2a" />


<img width="350" height="99" alt="Screenshot 2026-05-12 101758" src="https://github.com/user-attachments/assets/3ba9ada1-7666-4f5a-ac17-a370df1472f8" />


<img width="989" height="715" alt="Screenshot 2026-05-12 103400" src="https://github.com/user-attachments/assets/b5d0253e-ba90-451e-aceb-3f8fdbab51bb" />



---

## Module 9: Automate User Provisioning
**What I learned:** Configured automated user provisioning and deprovisioning for full lifecycle management between Okta and connected applications.  
**Why it matters:** Manual provisioning doesn't scale and creates orphaned accounts. Automation is how IAM teams enforce joiner/mover/leaver policies.

<img width="1371" height="906" alt="Screenshot 2026-05-17 093533" src="https://github.com/user-attachments/assets/b1c4a602-d672-4864-8e40-b7d9986e08d6" />

<img width="814" height="540" alt="Screenshot 2026-05-17 093553" src="https://github.com/user-attachments/assets/7e5514ce-e9d1-4a9c-ab74-cff43c8319d5" />

<img width="725" height="850" alt="image" src="https://github.com/user-attachments/assets/e11c95a2-6dc9-4aeb-b444-6693b7f20548" />


---

## Module 10: Monitor Your Okta Org
**What I learned:** Used Okta's monitoring tools to identify tasks, errors, and informational issues requiring attention in the org.  
**Why it matters:** IAM isn't just configuration but ongoing monitoring is how you catch misconfigurations, suspicious activity, and policy drift.

<img width="1598" height="852" alt="image" src="https://github.com/user-attachments/assets/4a3ebd5e-74a7-4dee-b3f8-15dda2673da1" />



## Troubleshooting Log

### Issue: Could not complete provisioning for Salesforce
**What I thought:** Provisioning was part of the SSO configuration process
**What was actually happening:** SSO and Provisioning are separate functions. 
I had successfully completed SSO but was stuck on provisioning because I 
didn't have a Salesforce developer account for Okta to connect to.
**What I learned:** SSO controls authentication. Provisioning controls 
lifecycle management. You can complete one without the other. Full lifecycle 
management requires both  and requires valid API credentials on the 
application side.
**Fix:** Sign up for a Salesforce Developer account (free) to complete 
the provisioning integration end to end.






---

## Certifications Targeted
- Okta Certified Professional Aquired 5/30/2026
<img width="1024" height="791" alt="Okta Certified Professional Badge" src="https://github.com/user-attachments/assets/d2f52345-422f-4053-a535-d1ae76b79709" />



- Okta Certified Administrator Aquiried 6/26/26
<img width="884" height="665" alt="Screenshot_29-6-2026_92630_" src="https://github.com/user-attachments/assets/6fa5f798-a816-4c16-a3e2-7ddafe5749d1" />













