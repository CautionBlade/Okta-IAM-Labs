
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

---

## Module 5: Define a Secure Policy Structure
**What I learned:** Built a secure policy framework using assurance technology and Okta's comprehensive security policies, balancing security with user experience.  
**Why it matters:** Policy structure determines how authentication and authorization decisions are made inside an organization.

---

## Module 6: Implement Security Policies
**What I learned:** Strengthened security posture by configuring and leveraging Okta's full security policy framework.  
**Why it matters:** Knowing how to implement not just understand security policies is what separates practitioners.

---

## Module 7: Implement Passwordless Authentication
**What I learned:** Configured phishing resistant MFA including Okta FastPass for passwordless authentication flows.  
**Why it matters:** Passwordless is the direction enterprise auth is heading towards. this reduces credential based attacks while improving UX.

---

## Module 8: Create App Integrations
**What I learned:** Integrated applications with Okta to provide SSO access. covering SAML, OIDC, and the Okta Integration Network.  
**Why it matters:** App integration is one of the most hands on in demand IAM skills. Every enterprise has dozens of apps to federate.





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

## Module 9: Automate User Provisioning
**What I learned:** Configured automated user provisioning and deprovisioning for full lifecycle management between Okta and connected applications.  
**Why it matters:** Manual provisioning doesn't scale and creates orphaned accounts. Automation is how IAM teams enforce joiner/mover/leaver policies.



---

## Module 10: Monitor Your Okta Org
**What I learned:** Used Okta's monitoring tools to identify tasks, errors, and informational issues requiring attention in the org.  
**Why it matters:** IAM isn't just configuration but ongoing monitoring is how you catch misconfigurations, suspicious activity, and policy drift.

---

## Certifications Targeted
- Okta Certified Professional

